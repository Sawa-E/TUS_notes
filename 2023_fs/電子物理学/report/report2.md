## 体積当たりの不純物原子数について
不純物原子の数を$n$とする。(今回はドナー密度だが、アクセプタでも同式)


- アボガドロ数$N_{\rm{A}}=6.02\times10^{23}\,[個/{\rm{mol}}]$
- 半導体$M\,[\rm{g}]$
- 不純物元素$m\,[\rm{g}]$
- 不純物元素のモル質量$A\,[\rm{g/mol}]$
- 半導体の比重(密度)$D\,[\rm{g/{cm}^3}]$
- 半導体の体積$V\,[\rm{{cm}^3}]$


これらの値より、体積当たりの不純物原子数(ドナー密度)は、
$$
\begin{align*}
  n &= \frac {N} {V} \\
  &= \frac {6.02 \times 10^{23} \times m / A} {M / D} \\
  &= 6.02 \times 10^{23} \cdot \frac {m D} {M A}
\end{align*}
$$

また、不純物ドーピング前後のキャリア密度の比は、$np = n_{\rm{i}}^2$より、
$$
\begin{align*}
  \frac{n_{\rm{i}_後}}{n_{\rm{i}_前}} = \frac {n + p} {n_{\rm{i}}}
\end{align*}
$$

$n \gg p$の時、
$$
\begin{align*}
  \frac {n + p} {n_{\rm{i}}} \approx \frac {n} {n_{\rm{i}}} \\
\end{align*}
$$

以上の式はアクセプタ密度にも同様に適用できる。

#ドナー #アクセプタ #キャリア密度