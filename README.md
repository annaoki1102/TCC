# Protótipo para atualizar sistemas legados por meio de agentes de IA em desenvolvimento (TCC de Sistemas de Informação, UDF)

**Autora:** Anna Beatriz Resende Oki Corrêa

## Resumo

Fórmulas de planilha com várias funções `SE` aninhadas escondem a lógica da regra, e é fácil esquecer uma condição ao passá-la para outro formato. Este trabalho propõe um protótipo que lê a fórmula, organiza a lógica em uma árvore de condições e, a partir dela, gera o código Python e um fluxograma. A avaliação usa casos de teste que comparam o resultado da fórmula com o do código gerado e reúne a opinião de um profissional sobre a utilidade do fluxograma.

## Situação atual

O texto do TCC está em andamento. O protótipo ainda não foi desenvolvido.

## Onde está cada coisa

| Arquivo ou pasta | O que tem |
|------------------|-----------|
| `TCC.tex` | Versão atual do TCC: arquivo principal, que junta todos os capítulos. |
| `capitulos/cap1_introducao.tex` | Introdução: problema, objetivos e metodologia. |
| `capitulos/cap2_*.tex` | Fundamentação teórica. |
| `capitulos/proposta.tex` | Proposta do protótipo e plano de avaliação. |
| `capitulos/consideracoes_finais.tex` | Considerações finais. |
| `TCC.bib` | Referências bibliográficas (BibTeX). |
| `images/` | Figuras usadas no texto. |
| `sty/` | Pacotes e estilos (`.sty`) auxiliares. |

## Como compilar

O texto é escrito em LaTeX, com a classe [abntex2](https://www.abntex.net.br/).

**Pré-requisitos:** uma distribuição LaTeX (MiKTeX ou TeX Live), Perl e `latexmk`.

Pelo terminal, na raiz do projeto:

```
latexmk -pdf TCC.tex
```

Ou, no VS Code, com a extensão **LaTeX Workshop**: abra `TCC.tex` e compile pelo botão *Build LaTeX project* (ou salve o arquivo, se a compilação automática estiver ativa).

O PDF gerado é `TCC.pdf`, que fica versionado. Os demais arquivos de compilação (`.aux`, `.log`, `.bbl` etc.) são ignorados pelo git.

## Trabalhando em mais de uma máquina

1. Ao começar: `git pull`
2. Ao terminar:
   ```
   git add .
   git commit -m "descrição do que mudou"
   git push
   ```

## Aviso

Este repositório é **privado** e deve continuar assim até a defesa do TCC.
