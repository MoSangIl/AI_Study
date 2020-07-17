# Bayes' Theorem (베이즈 정리)

## $ P(B|A) = (P(A|B)\cdot P(B)) \div P(A) $

### proof
$ P(A|B) = P(A\cap B)\div P(B) $
$ P(A\cap B) = P(A|B)\cdot p(B) $
$ P(B\cap A) = P(B|A)\cdot p(A) $
따라서, $ P(B|A)\cdot p(A) = P(A|B)\cdot p(B) $
즉, $ P(B|A) = (P(A|B)\cdot P(B)) \div P(A) $


### Example
베이즈 정리를 사용하여 필터 구현하기

P(spam) 스팸 메일 = 3 / 10  
P(free) 'free'문구가 들어간 메일 = 4 / 10   
P(free|spam) 스펨 매일 중 'free' 문구가 들어간 메일 = 2 / 3   
P(spam|free) 'free' 문구가 들어간 메일이 spam 일 확율 = P(free|spam) \cdot P(free) \div P(spam) = 0.5  

