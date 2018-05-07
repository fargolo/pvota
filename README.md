# povoVota

Projeto iniciado para promover engajamento politico. Em construção. Sou o único desenvolvedor do projeto atualmente. Aceito ajuda e quaisquer sugestões :)

## Roadmap
### 1 . Transparencia / Inbound marketing
Por sugestão da Edely (https://github.com/Edely), comecei fazendo um portal divulgando dados públicos processados.
Pensando na disseminação de conhecimento, comecei pela prova do Inep para educação básica.

### 2 . Portal de eleitores
Desenvolver um portal (webserver com banco de dados) com cadastros de eleitores validados pelo TSE.
Esse transmitirá informações relacionadas a quais pessoas apoiam quais causas aos políticos. O objetivo é colocar pautas populares entre as principais promessas de campanha.

### 3 . Mobile / Social Media
Meio para que os cadastrados possam divulgar suas preferências a conhecidos.

## Stack atual:
#### Webscrapping e análise 
* R Base
    * xlsx
    * knitr
    * purrr
    * dplyr
    * RCurl
#### Webserver
* Yesod

Testado em Ubuntu 16.04

## Como rodar
Instale o [Yesod](https://www.yesodweb.com/).
`$git clone https://github.com/fargolo/povoVota.git`  
`$stack build && stack exec -- yesod devel`  
O server ficará ativo em http://localhost:3000  

## To do:
( ) Aperfeiçoar análise  
