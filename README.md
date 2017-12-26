# R-captuda-de-dados-do-Twiiter
Tutorial para processo de Captura de dados do twitter utilizando R.

https://andrehps.blogspot.com.br/2017/12/r-captura-de-dados-no-twitter.html

Para isso você deve ter:
1) Conta no twitter
2) Conhecimento de como criar uma app do twitter - https://apps.twitter.com/
3) Alterar o código e entrar com as suas informações de autenticação:
    consumer_key <- "your consumer Key"
    consumer_secret <-"your consume secret"
    access_token <-"your access token"
    access_secret <-"your access secret"
    
Esse script finaliza com salvando os dados do twiiter em um arquivo xls no diretório local da máquina:

write.xlsx(tweets.df, file="D://Td2i//Td2i//Projetos//twitter//Tweets.xlsx")

Essa parte do código também deve ser alterada para o caminho existente da sua máquina.

Esse processo explica somente o processo de captura de dados. 
Com certeza, para uma análise completa é necessário seguir mais alguns passos para limpeza da informação e manipulação do SHAPE dos dados. Você pode encontrar mais detalhes desses passos no post https://andrehps.blogspot.com.br/2017/12/text-analytics-dados-twitter.html
