# Projeto 4: Álgebra Linear Numérica

Repositório com as resoluções do Projeto 4 da disciplina de Álgebra Linear Numérica (2026/1) da FGV-EMAp. O trabalho investiga refletores de Householder, redução à forma de Hessenberg e exponenciais de matrizes, com ênfase em estabilidade numérica e condicionamento.

## Autores

* Luiz Antônio Alves de Lima
* Rafael Gontijo Ferreira

## Conteúdo

* **Questão 1 - Refletores de Householder**: Dedução e implementação numericamente estável do refletor $Q_v = I - \beta v v^*$. Análise de cancelamento numérico na escolha de $\beta$, condicionamento absoluto de $v$, e testes de estabilidade em `Float32` e `Float64`.
* **Questão 2 - Forma de Hessenberg**: Aplicação de refletores a vetores e matrizes (`apply_reflector`, `rev_apply_reflector`). Implementação da redução de Hessenberg via produto de refletores de Householder, com verificação de corretude via $\|A - QHQ^*\|$ e $\|Q^*Q - I\|$.
* **Questão 3 - Exponenciais de Matrizes**: Análise espectral de $A(\omega)$, decomposição SVD e condicionamento da matriz de autovetores em função de $\omega$. Derivação da fórmula fechada para $e^{tA(\omega)}$ via série de Taylor e verificação numérica do erro relativo.

## Referências Consultadas

- [Numerical Linear Algebra - Trefethen & Bau](https://epubs.siam.org/doi/book/10.1137/1.9780898719574)

- [Documentação Julia: LinearAlgebra](https://docs.julialang.org/en/v1/stdlib/LinearAlgebra/)

