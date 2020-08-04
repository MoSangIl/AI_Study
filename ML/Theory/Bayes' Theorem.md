# Bayes' Theorem (베이즈 정리)

##  $P(B|A) = (P(A|B)\cdot P(B)) \div P(A)$ 

### proof
![equation](https://latex.codecogs.com/gif.latex?P(A|B)&space;=&space;P(A\cap&space;B)\div&space;P(B)&space;\\&space;P(A\cap&space;B)&space;=&space;P(A|B)\cdot&space;p(B)&space;\\&space;P(B\cap&space;A)&space;=&space;P(B|A)\cdot&space;p(A))
따라서, 
![equation](https://latex.codecogs.com/gif.latex?P(B|A)\cdot&space;p(A)&space;=&space;P(A|B)\cdot&space;p(B)&space;\\&space;P(B|A)&space;=&space;(P(A|B)\cdot&space;P(B))&space;\div&space;P(A))


### Example
베이즈 정리를 사용하여 필터 구현하기

P(spam) 스팸 메일 = 3 / 10  
P(free) 'free'문구가 들어간 메일 = 4 / 10   
P(free|spam) 스펨 매일 중 'free' 문구가 들어간 메일 = 2 / 3   
P(spam|free) 'free' 문구가 들어간 메일이 spam 일 확율 = P(free|spam) * P(free) / P(spam) = 0.5