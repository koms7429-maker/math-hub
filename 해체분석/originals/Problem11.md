# Problem11. (Unknown Source) - Logarithm and Geometry

## Problem

두 상수 $a(a>1)$, $b(0<b<1)$에 대하여 함수

$$f(x)=\left|\log_a(x+b)\right|$$

의 그래프가 $x$축, $y$축과 만나는 점을 각각 P, Q라 하자. 점 Q를 지나고 $x$축과 평행한 직선이 곡선 $y=f(x)$와 만나는 점 중 Q가 아닌 점을 R이라 할 때, 삼각형 PQR의 외접원이 점 (3, 0)을 지나고 $y$축과 점 Q에서만 만난다. $a \times b$의 값은?

## Choices
① $2^{-\frac{2}{3}}$  ② $2^{-\frac{1}{3}}$  ③ $1$  ④ $2^{\frac{1}{3}}$  ⑤ $2^{\frac{2}{3}}$

**Answer**: ① $2^{-\frac{2}{3}}$
**Difficulty**: unknown
**Score**: 14점
**Type**: multiple choice

---

## Solution

문제의 조건에 의해

$$f(x)=0 \Rightarrow \log_a(x+b)=0 \Rightarrow x=1-b \Rightarrow P(1-b, 0)$$

이고,

$$f(x)=f(0) \Rightarrow \left|\log_a(x+b)\right|=\left|\log_a b\right|$$
$$\Rightarrow x=0, \quad x=\frac{1}{b}-b$$
$$\Rightarrow Q(0, -\log_a b), \quad R\left(\frac{1}{b}-b, -\log_a b\right)$$

이다. 이때, 삼각형 PQR의 외접원을 $C$라 하면

원 $C$가 $y$축과 $\left\{\begin{array}{l}\text{점 Q에서 접함}\end{array}\right\} \Rightarrow$ 선분 QR은 원 $C$의 지름 $\cdots$ ①

임을 알 수 있고,

$$0<b<1 \Rightarrow 0<(\text{점 P의 } x\text{좌표})<1$$
$$\Rightarrow \text{원 } C\text{는 } x\text{축과 두 점 P, (3, 0)에서 만난다}$$

를 알 수 있다.

점 (3, 0)을 S라 하고 점 S에서 선분 QR에 내린 수선의 발을 H라 하자.

위 그림에서 원의 대칭성에 의해

$$(\text{선분 PS의 중점의 } x\text{좌표})=(\text{선분 QR의 중점의 } x\text{좌표})$$
$$\Rightarrow (1-b)+3=\frac{1}{b}-b$$
$$\Rightarrow b=\frac{1}{4}$$

이므로

$$\begin{cases}
Q(0, 2\log_a 2), & R\left(\frac{15}{4}, 2\log_a 2\right) \\
\overline{SH}^2=\overline{QH}\times\overline{RH} \quad (\because \text{ ①} \Rightarrow \angle QSR=\frac{\pi}{2})
\end{cases}$$

$$\Rightarrow (2\log_a 2)^2=3\times\frac{3}{4}$$

$$\Rightarrow \log_a 2=\frac{3}{4} \quad (\because a>1)$$

$$\Rightarrow a=2^{\frac{4}{3}}$$

을 얻는다.

$$\therefore a\times b=2^{\frac{4}{3}}\times\frac{1}{4}=2^{-\frac{2}{3}}$$

---