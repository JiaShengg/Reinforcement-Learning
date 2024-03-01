2. By the linearity of expectation,

\begin{align*}
\mathbb{E}_{S\sim\mathcal{D}^m}[L_S(h)] &= \mathbb{E}_{S\sim\mathcal{D}^m}\left[\frac{1}{m} \sum_{i=1}^{m} \mathbf{1}_{h(x_i) \neq f(x_i)}\right] \\
&= \frac{1}{m} \sum_{i=1}^{m} \mathbb{E}_{x_i\sim\mathcal{D}}[\mathbf{1}_{h(x_i) \neq f(x_i)}] \\
&= \frac{1}{m} \sum_{i=1}^{m} \mathbb{P}_{x_i\sim\mathcal{D}}(h(x_i) \neq f(x_i)) \\
&= \frac{1}{m} \cdot m \cdot L_{\mathcal{D},f}(h) \\
&= L_{\mathcal{D},f}(h) .
\end{align*}

\end{document}
