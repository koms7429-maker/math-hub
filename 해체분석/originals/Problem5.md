# Problem5. (Unknown Source) - 로그부등식

## Problem

자연수 $n(n \geq 2)$에 대하여

$$\log_n x > 6\log_n\left|x - \frac{11}{2}\right|$$

을 만족시키는 자연수 $x$의 개수가 4가 되도록 하는 모든 $n$의 값의 합은 [4점]

## Choices
① 12    ② 13    ③ 15    ④ 18    ⑤ 22

**Answer**: ③ 15
**Difficulty**: unknown
**Score**: 4점
**Type**: multiple choice

---

## Solution

$f(x) = \log_n x$, $g(x) = 6\log_n\left|x - \frac{11}{2}\right|$

이라 하면 문제의 부등식은

$$f(x) > g(x) \cdots ①$$

이고, 이때

• $g(5) = g(6) < 0$이고 $g(4) = g(7)$
• $y = f(x)$는 $f(1) = 0$이고 증가함수

이므로

• $x = 5$, $x = 6$은 항상 ①을 만족시킴
• $x = 4$가 ①을 만족시키면 $x = 7$도 ①을 만족시킴

을 알 수 있다.

따라서

①인 자연수 $x$의 개수가 $4 \Rightarrow \begin{cases} (i) & x = 4, 5, 6, 7 \\ (ii) & x = 5, 6, 7, 8 \end{cases}$

의 경우만 가능하다.

**(i)의 경우:**

위 그림을 참고하면

$$g(3) = g(8) \Rightarrow \begin{cases} x = 8\text{이 ①을 만족시키지 않으면} \\ x = 3\text{도 ①을 만족시키지 않음} \end{cases}$$

을 알 수 있으므로

• $f(4) > g(4) \Rightarrow \log_4 4 > 6\log_n \frac{3}{2} \Rightarrow n > \left(\frac{3}{2}\right)^3 = 3.xx$

• $f(8) < g(8) \Rightarrow \log_8 8 \leq 6\log_n \frac{5}{2} \Rightarrow n \leq \left(\frac{5}{2}\right)^2 = 6.xx$

$\Rightarrow n = 4, 5, 6$ ($\because$ $n$은 자연수)

이다.

**(ii)의 경우:**

(i)의 과정을 참고하면

$$\begin{cases} • f(4) \leq g(4) \Rightarrow n \leq \left(\frac{3}{2}\right)^3 = 3.xx \\ • f(8) > g(8) \Rightarrow n > \left(\frac{5}{2}\right)^2 = 6.xx \end{cases}$$

인 $n$이 존재하지 않음

을 알 수 있다.

따라서 (i), (ii)에 의해

(모든 $n$의 값의 합) = $4 + 5 + 6 = 15$

임을 알 수 있다.