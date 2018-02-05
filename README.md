## modeloLEA

Este pacote do `R` utiliza rmarkdown para criar relatórios mesclando `R` e LaTeX.

Rode o comando

    devtools::install_github("mnunes/modeloLEA")

para instalar o pacote. Se não funcionar, primeiro instale o pacote `devtools` através do comando

    install.packages("devtools")

Esta é uma versão preliminar deste modelo de relatório. É possível que hajam alguns bugs. Entre em contato pelo email marcus [arroba] marcusnunes.me para me avisar a respeito de qualquer problema.

O arquivo [modeloLEA.pdf](https://github.com/mnunes/modeloLEA/blob/master/modeloLEA.pdf) exibe o resultado esperado pelo modelo.


## Requisitos do Sistema

Para rodar os exemplos disponíveis neste repositório, é necessário instalar os seguintes programas em seu computador:

- MikTex (versão 2.9 ou superior)

- R (versão 3.4.3 ou superior)

- RStudio (versão 1.1.383 ou superior)


## Utilização do pacote

Após o pacote ser instalado, feche e abra o RStudio. Carregue o pacote `modeloLEA` na memória do `R` através do comando `library(modeloLEA)`. Desta forma, ao clicar no menu File > New File > R Markdown..., aparecerá a opção Modelo LEA (PDF) dentro da guia From Template. Acompanhe as figuras abaixo para uma explicação visual.

![alt text](fig03.png "Como criar um novo relatório - Figura 1")

![alt text](fig02.png "Como criar um novo relatório - Figura 2")

Esta sequência de comandos criará uma pasta nova em seu computador. Esta pasta terá o nome que você quiser. No exemplo acima, o nome da pasta criada é `relatorio`. Esta pasta vai conter todos os arquivos necessários para a escrita do relatório de consultoria. Basta editar os arquivos `relatorio.Rmd` e `modeloLEA.bib` para produzir seu texto. A compilação do relatório é feita através da combinação de teclas `Ctrl + Shift + K`.



<hr>

Este pacote foi fortemente inspirado pelo [pinp](https://github.com/eddelbuettel/pinp). 