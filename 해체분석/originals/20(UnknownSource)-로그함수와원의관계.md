# 20. (Unknown Source) - 로그함수와 원의 관계

## Problem

두 양수 $a$ $(a>1)$, $b$에 대하여 두 곡선 $y=\log_a(b-1-x)$와 $y=\log_a(b-x)$의 점근선이 $x$축과 만나는 점을 각각 A, B라 하자. 두 곡선 $y=\log_a(b-1-x)$와 $y=\log_a(b-x)$의 점근선이 곡선 $y=(\sqrt{2})^x$과 만나는 점을 각각 C, D라 할 때, 점 D의 $y$좌표가 점 C의 $y$좌표의 2배이다.

네 점 A, B, C, D가 한 원 위에 있을 때, $a^b$의 값은? [4점]

## Choices

① $2^{\frac{\sqrt{2}}{2}}$ ② $2^{\sqrt{2}}$ ③ $2^{\frac{3\sqrt{2}}{2}}$ ④ $2^{2\sqrt{2}}$ ⑤ $2^{\frac{5\sqrt{2}}{2}}$

**Answer**: ③  
**Difficulty**: unknown  
**Score**: 4점  
**Type**: multiple choice

---

## Solution

[FIGURE: 좌표평면에 곡선 $y=\log_a(b-x)$, 곡선 $y=(\sqrt{2})^x$, 그리고 점 A, B, C, D와 원이 표시된 그래프]

문제의 조건에 의해

$$\text{A}(b-1, 0), \quad \text{B}(b, 0), \quad \text{D}(b, (\sqrt{2})^b),$$

이고,

점 D의 $y$좌표가 점 C의 $y$좌표의 2배

$$\Rightarrow (\text{점 C의 }y\text{좌표})=\frac{(\sqrt{2})^b}{2}=(\sqrt{2})^{b-2}$$

$$\Rightarrow \text{C}(b-2, (\sqrt{2})^{b-2}) \quad (\because \text{ 점 C는 곡선 } y=(\sqrt{2})^x \text{ 위의 점})$$

이다. 이때,

• 네 점 A, B, C, D가 한 원 위에 있음 $\Rightarrow$ AD가 원의 직경

• $\angle \text{ABD}=\frac{\pi}{2}$

이므로

$$\angle \text{ACD}=\frac{\pi}{2} \Rightarrow (\text{AC의 기울기})\times(\text{CD의 기울기})=-1$$

$$\Rightarrow \frac{(\sqrt{2})^{b-2}-0}{(b-2)-(b-1)} \times \frac{(\sqrt{2})^b-(\sqrt{2})^{b-2}}{b-(b-2)}=-1$$

$$\Rightarrow \frac{-(\sqrt{2})^{b-2}}{1} \times \frac{(\sqrt{2})^{b-2}(2-1)}{2}=-1$$

$$\Rightarrow -\frac{(\sqrt{2})^{2(b-2)}}{2}=-1$$

$$\Rightarrow 2^{b-2}=2$$

$$\Rightarrow b=3$$

을 얻고,

$$\text{C}(1, \sqrt{2})\text{가 }y=\log_a(3-x) \text{ 위의 점} \Rightarrow \sqrt{2}=\log_a(2) \Rightarrow a^{\sqrt{2}}=2 \Rightarrow a=2^{\frac{1}{\sqrt{2}}}$$

을 얻는다.

$$\therefore a^b=\left(2^{\frac{1}{\sqrt{2}}}\right)^3=2^{\frac{3}{\sqrt{2}}}=2^{\frac{3\sqrt{2}}{2}}$$

---