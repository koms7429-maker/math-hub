# 14. (Source Unknown) - 함수의 연속성과 미분가능성

## Problem

두 상수 $a(a>1)$, $b$에 대하여 함수 $f(x)$를

$$f(x) = \begin{cases} a^{x+b} & (a^{x+b} \leq 2x+5) \\ |2x+5| & (a^{x+b} > 2x+5) \end{cases}$$

라 하자. 양수 $t$에 대하여 $x$에 대한 방정식 $f(x)=t$의 서로 다른 모든 실근의 합을 $g(t)$라 하자. $g(t) \neq k$ ($k$는 상수)를 만족시키는 모든 양수 $t$의 값의 범위가 $1<t<9$일 때,

$$f(-k)+f(0)$$

의 값을 구하시오. [4점]

## Choices
① $18$  
② [해설]

**Answer**: $18$
**Difficulty**: unknown
**Score**: 4점
**Type**: 단답형

---

## Solution

문제의 $f(x)$의 식에서

① $y=a^{x+b}$, $y=2x+5$의 교점이 개수가 1 이하인 경우,
$f(x) = |2x+5|$
($\because$ 모든 실수 $x$에 대하여 $a^{x+b} \geq 2x+5$)

② $y=a^{x+b}$, $y=2x+5$의 교점이 개수가 2인 경우,
두 교점의 $x$좌표를 $p$, $q$라 하면

$$f(x) = \begin{cases} a^{x+b} & (p \leq x \leq q) \\ |2x+5| & (x < p, \, x > q) \end{cases}$$

임을 알 수 있다.

[FIGURE: 두 개의 그래프가 제시됨]
- ①의 경우: $y=f(x)$가 $x=-\frac{5}{2}$에서 V자 형태
- ②의 경우: $y=f(x)$가 두 점 $p$, $q$에서 지수함수와 직선이 만남

한편, 양수 $t$에 대하여

$x$에 (방정식 $f(x)=t$의 모든 실근의 합) 이므로 ①의 경우,

모든 양수 $t$에 대하여 $g(t)=-5$

($\because$ $y=|2x+5|$는 $x=-\frac{5}{2}$에 대하여 대칭)

임을 알 수 있고, ②의 경우,

$$\begin{cases} t \geq f(q)\text{일 때 } g(t)=-5 \\ f(p)<t<f(q)\text{일 때 } g(t) \neq -5 \end{cases}$$

임을 알 수 있다.

따라서 문제의 조건에서

$$\begin{cases} g(t) \neq k \text{(}k\text{는 상수)}를 만족시키는 \\ \text{모든 양수 } t \text{의 값의 범위가 } 1<t<9 \end{cases}$$

를 만족시키는 경우는 ②의 경우뿐이므로, 이때

$$k=-5$$

를 얻고,

$$\begin{cases} f(p)=1 \Rightarrow 2p+5=a^{p+b}=1 \\ f(q)=9 \Rightarrow 2q+5=a^{q+b}=9 \end{cases}$$

을 얻는다. $\Rightarrow p=-2$, $q=2$, $a=\sqrt{3}$, $b=2$

$$\therefore f(x) = \begin{cases} (\sqrt{3})^{x+2} & (-2 \leq x \leq 2) \\ |2x+5| & (x < -2, \, x > 2) \end{cases}$$

$$\therefore f(-k)+f(0)=f(5)+f(0)=15+3=18$$

---