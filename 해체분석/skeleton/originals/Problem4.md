# Problem4. (Unknown Source) - 지수와 거듭제곱

## Problem

다음 조건을 만족시키는 100 이하의 모든 자연수 $k$의 값의 합은? [4점]

자연수 $n(n \geq 2)$에 대하여 $3^{540} \times (-2)^k$의 $n$제곱근 중 음의 정수가 존재하도록 하는 모든 $n$의 값이 12이다.

## Choices
① 301  ② 313  ③ 325  ④ 37  ⑤ 349

**Answer**: ①
**Difficulty**: unknown
**Score**: 4점
**Type**: multiple choice

---

## Solution

$k$가 홀수이면 $3^{540} \times (-2)^k < 0$, $k$가 짝수이면 
$3^{540} \times (-2)^k > 0$

이므로 $3^{540} \times (-2)^k$의 $n$제곱근 중 음의 정수가 존재하려면
(i) $k$, $n$이 모두 홀수이거나 (ii) $k$, $n$이 모두 짝수이어야 하고,

$n$의 540과 $k$의 공약수 … ⑤

이어야 한다. (i), (ii)의 경우에서
(그런 모든 $n$의 값의 합)$= 12$ … ⓒ

가 되도록 하는 $k$의 값을 구해보자.

**(i) $k$가 홀수인 경우:**

⑤ $\Rightarrow n$은 $540 = 2^2 \times 3^3 \times 5$의 약수인 홀수

이므로 $n(n \geq 2)$로 가능한 모든 값은 작은 수부터 크기순으로 차례로 나열해보면

$3, 5, 9, 15, \cdots$

이다. 따라서

ⓒ $\Rightarrow 3+9$인 경우만 가능

$\Rightarrow \begin{cases} k\text{는 9의 배수이고 27의 배수가 아님} \\ k\text{는 5의 배수가 아님} \end{cases}$

$\Rightarrow k = 9, 63, 99$ ($\because k \leq 100$)

$\Rightarrow$ (모든 홀수 $k$의 값의 합)$= 171$

이다.

**(ii) $k$가 짝수인 경우:**

⑤ $\Rightarrow n$은 $540 = 2^2 \times 3^3 \times 5$의 약수인 짝수

이므로 $n(n \geq 2)$로 가능한 모든 값은 작은 수부터 크기순으로 차례로 나열해보면

$2, 4, 6, 10, 12, \cdots$

이다. 따라서

ⓒ $\Rightarrow$ ① $2+4+6$ 또는 ② $2+10$ 또는 ③ $12$

의 경우가 가능하고, 이때

①의 경우, $k$는 $2+4+6$의 공배수이므로 $k$는 12의 배수이고,
이때 12도 $n$의 값이 되어 ⓒ에 모순이고, ③의 경우도 마찬가지로 모순임을 알 수 있다.

또한, ②의 경우,

$\begin{cases} k\text{는 2의 배수이고 4의 배수가 아님} \\ k\text{는 3의 배수가 아님} \\ k\text{는 5의 배수} \end{cases}$

$\Rightarrow k = 10, 50, 70$ ($\because k \leq 100$)

$\Rightarrow$ (모든 짝수 $k$의 값의 합)$= 130$

이다.

$\therefore$ (모든 $k$의 값의 합)$= 171+130 = 301$