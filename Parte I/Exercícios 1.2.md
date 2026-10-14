> [!question] 1.2-1
> Suponha que estamos comparando implementações de ordenação por inserção e ordenação por intercalação na mesma máquina. Para entradas de tamanho $n$, a ordenação por inserção é executada em $8n^2$ passos, enquanto a ordenação por intercalação é executada em $64n \lg n$ passos. Para quais valores de $n$ a ordenação por inserção supera a ordenação por intercalação?
> > [!todo]- Resposta
> > Para a ordenação por inserção ser melhor (superar) a ordenação por intercalação, precisamos que $8n^2 < 64n\lg n$. Simplificando, temos que $n < 8\lg n$. Resolvendo a inequação, temos que $n < 43.41011...$, portanto a ordenação por inserção supera a ordenação por intercalação para $n < 44, n \in \mathbb{N}$.


