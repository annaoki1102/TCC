# Entre o Visual e o Textual: uma proposta baseada em Inteligência Artificial para a transformação de representações da lógica computacional

Trabalho de Conclusão de Curso (TCC) de Sistemas de Informação.

**Autora:** Anna Beatriz Resende Oki Corrêa

Texto escrito em LaTeX, com a classe [abntex2](https://www.abntex.net.br/).

> **Atenção:** este repositório é **privado** e deve continuar assim até o TCC ser defendido.

## Estrutura de pastas

| Item | Descrição |
|------|-----------|
| `TCC.tex` | Arquivo principal: preâmbulo e inclusão dos capítulos. |
| `TCC.bib` | Referências bibliográficas (BibTeX). |
| `capitulos/` | Um arquivo `.tex` por capítulo do trabalho. |
| `images/` | Figuras e imagens usadas no texto. |
| `sty/` | Pacotes e estilos (`.sty`) auxiliares. |

## Como compilar

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
