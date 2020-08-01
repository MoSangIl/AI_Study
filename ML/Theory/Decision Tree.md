# Decision Tree

## Step

### 1. Define Problem
#### Collect training Data

### 2. Extract Data
#### Build a tree
컴퓨터가 알아들을 수 있도록 데이터 분류 및 트리 생성

### 3. Deploy machine
머신을 훈련시킨다.

### 4. Test machine!


## Build a Tree
### Extract Data

어떤 속성(Property)을 먼저 나누어야 효과적일까?
- 가장 분류를 많이 해내는 속성이 효율적이다. 따라서 그런 속성을 먼저 선정한다.
#### -->Choose best feature to split

## Entropy
어질러진 상태 -> High Entropy (Messy)
깔끔한 상태 -> Low Entropy (Clean)

### 수식
Total 8 photos
1 photo Yes
7 photos No
$$
Entropy([1+, 7-])\\
= -(1/8) * log(1/8) - (7/8) * log(7/8)\\
= 0.543
$$
#### $$Entropy = - p(+)*log(p(+)) - p(-)*log(p(-))$$ { p = 확률, + = Yes, - = No )

## Information Gain 
### (base entropy - new entropy)
Tree 생성시 Information Gain 이 높은 속성을 먼저 책정 함

new entropy 를 구할 때, 조건부 확률을 사용한다.