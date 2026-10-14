> [!faq] 1.2-1
> Suponha que estamos comparando implementações de ordenação por inserção e ordenação por intercalação na mesma máquina. Para entradas de tamanho $n$, a ordenação por inserção é executada em $8n^2$ passos, enquanto a ordenação por intercalação é executada em $64n \lg n$ passos. Para quais valores de $n$ a ordenação por inserção supera a ordenação por intercalação?
> > [!todo]- Resposta
> > Para a ordenação por inserção ser melhor (superar) a ordenação por interacalação, $8n^2 < 64n\lg n$. Simplificando, temos que $n < 8\lg n$. Testando para valores de n:
> > $$
> > \begin{aligned}
> > n = 1 : \qquad 1 < 8 \cdot 1 \enspace \checkmark \\
> > n = 4 : \qquad 4 < 8 \cdot 2 \enspace \checkmark \\
> > n = 8 : \qquad 8 < 8 \cdot 3 \enspace \checkmark \\
> > n = 16 : \qquad 16 < 8 \cdot 4 \enspace \checkmark \\
> > n = 32 : \qquad 32 < 8 \cdot 5 \enspace \checkmark \\
> > n = 64 : \qquad 64 < 8 \cdot 6 \enspace \times \\
> > \end{aligned}
> > $$
> > Portanto, a ordenação por inserção supera a ordenação por intercalação para $n < 64, n \in \mathbb{N}.$

