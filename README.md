# povoVota

[Povo vota](https://povovota.herokuapp.com)

Projeto iniciado para promover engajamento politico. Em construção. Sou o único desenvolvedor do projeto atualmente. Aceito ajuda e quaisquer sugestões :)

PRECISAMOS DE PESSOAS DISPOSTAS A ESCREVER SOBRE A REDE DE EDUCAÇÃO. TEMOS RESULTADOS INTERESSANTES PARA DISCUSSÃO. JORNALISTAS SÃO BEM-VINDOS.  

## Roadmap
### 1 . Transparencia / Ideias
Por sugestão da Edely do Grupo de Dados e Mineração (https://github.com/Edely), comecei fazendo um portal divulgando dados públicos processados.  
Escolhi o tema de educação e os dados da prova do Inep para educação básica (5ª, 9ª e 12ª ano).  
Descobri que as notas de escolas Rurais são menores em média. Alguns outros achados interessantes podem ser encontrados nos relatórios.

### 2 . Portal de eleitores
Desenvolver alguma solução eficiente, portal (webserver com banco de dados) e  cadastros de eleitores validados pelo TSE.  
Fortalecer a democracia representativa deixando o fluxo de informações mais aberto.Costumamos receber poucas informações oficiais de forma confiável.
O objetivo é colocar pautas importantes (e.g. educação e saúde) em discussão e envolver políticos no processo. Gostaria de saber melhor sobre o que já se foi feito nessa área.  

### 3 . Mobile / Social Media

## Stack atual:
#### Webscrapping e análise 
* R 
    * Desenvolvido em .Rmd (RMarkdown e convertido em .html).  
    * Análises em static/reports/analysis.  
    * Outputs a serem servidos em static/reports/outputs.  
#### Webserver
* Yesod/Haskell
    * Framework seguro (type safe URLs, etca).  
    * Server leve e de alta performance.  

Testado em Ubuntu 16.04  

## Deploy
Instale o [Yesod](https://www.yesodweb.com/).  
`$git clone https://github.com/fargolo/povoVota.git`  
`$stack build && stack exec -- yesod devel`  
O app está configurado para escutar na porta 3000, mas é suprimido se a variavel$PORT estiver definida.  
A versão atual está rodando em cloud com Heroku. A ideia é talvez migrar para docker ou algo assim no futuro.  


## To do:
( ) Aplicar CSS no html gerado pelo RStudio.  
( ) Jornalistas que queiram escrever sobre edução.    
    - Temos achados interessantes (Rural vs. Urbano/ Escolas Federais).  
    - Entrevistar diretores e alunos?  
( ) Buscar paralelos em outros países (Dinamarca?).  
