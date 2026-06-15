# Projeto 4: Álgebra Linear Numérica

## Descrição 

Repositório com as resoluções do Projeto 4 da disciplina de Álgebra Linear Numérica (2026/1) da FGV-EMAp. O trabalho investiga refletores de Householder, redução à forma de Hessenberg e exponenciais de matrizes, com ênfase em estabilidade numérica e condicionamento.

## Autores

* Luiz Antônio Alves de Lima
* Rafael Gontijo Ferreira

## Conteúdo

* **Questão 1 - Refletores de Householder**: Dedução e implementação do refletor de Householder, com análise de estabilidade numérica e testes em diferentes precisões.
* **Questão 2 - Forma de Hessenberg**: Aplicação de refletores a vetores e matrizes e implementação da redução de Hessenberg via produto de refletores.
* **Questão 3 - Exponenciais de Matrizes**: Análise espectral, decomposição SVD e derivação de fórmula fechada para a exponencial de uma família de matrizes.

## Fluxo CI/CD

![CI](https://github.com/Gontijo8199/Projeto-4-ALN-A2/actions/workflows/ci.yml/badge.svg)
![Release](https://github.com/Gontijo8199/Projeto-4-ALN-A2/actions/workflows/release.yml/badge.svg)

Este projeto utiliza um pipeline de CI/CD configurado no GitHub Actions para:

1. Integração Contínua: Validação automática da execução dos notebooks a cada push.
2. Entrega Contínua: Geração automática de relatórios em HTML via Releases (disponíveis na aba [Releases](https://github.com/Gontijo8199/Projeto-4-ALN-A2/releases)).

## Referências Consultadas

- [Numerical Linear Algebra - Trefethen & Bau](https://epubs.siam.org/doi/book/10.1137/1.9780898719574)
- [Documentação Julia: LinearAlgebra](https://docs.julialang.org/en/v1/stdlib/LinearAlgebra/)



<pre> 
 __________________________________
< eu S2 refletores de Householder! >
 ----------------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
</pre>