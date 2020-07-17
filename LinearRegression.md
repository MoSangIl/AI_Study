# Linear Regression (선형 회귀)

## 가장 작은 에러를 내는 선형 그래프를 찾아냄

### Error 찾기

#### $Error = h(x) - y$
#### $Square Error = (h(x) - y)^2$
#### $Mean Square Error = 1/n * \sum (h(x)-y)^2$

## Find linear equation has Least Mean Square(LMS) Error Using Cost function
### Gradient Decent 개념 : Cost Fucntion = Objective Function(목표함수) 최저로 만들기

#### Gradient Decent to choose \theta in order to minimize cost function h(x) = \theta x

##### $\theta := \theta - \alpha\frac{\delta}{\delta \theta}  \alpha = Learningt Rate \\ ( Initial Value \theta = 1 , \alpha = 0.1 )$
위 식에서 \theta 값이 0이 될때까지(Converge) 계속적으로 반복한다.
