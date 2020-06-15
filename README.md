# ES2Grupo4
Complemento ao projeto ES2 iscte

Complemento 1
A realizaçao do topico1, site gerido atraves do wordpress juntamente com a sua base de dados,o seu contentor encontra-se disponivel no seguite link do wetransfer: https://we.tl/t-NviwMqziCx  

Complemento 2
.é preciso ter instalado 3 imagens do docker
1)selenium/hub
2)selenium/node-chrome-debug
3)selenium/node-firefox-debug

.Depois pode visualizar o processo instalando VNC Viewer


.Ao executar o jar runnable é preciso defenir 3 argumentos:
1) ip para selenium console iniciado pelo docker
2) caminho para o ficheiro auxiliar
3) nome do ficheiro auxiliar
ex: http://192.168.99.100:4546/wd/hub C:\\Users\\Eduardo\\Desktop\\ES_Selenium Links.txt

NOTA: verificar os portos

.Se Eduardo78390T2_V3 nao resultar existe a Eduardo78390T2_V2

.exemplo do ficheiro auxiliar:

"(
1 *+*+*+* Verificar se consegue fazer uma pesquisa no google e se tem a palavra que esta no conteudo
http://www.google.com
Engenharia Software 2 Iscte
2 *+*+*+* verificar se o livro que está na lista de compras
https://www.wook.pt/Listacompras
es2.selenium@gmail.com
iscte1234
Bloco de Jogos e Atividades - 4/5 Anos
3 *+*+*+* verificar o login
...
)"
