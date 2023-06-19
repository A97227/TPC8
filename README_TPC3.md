# TPC3
# _Manifesto do TPC3__

##  Nome da chave: Tpc3
##  Equipe de Trabalho: Sandra Ferreira A97227

** Titulo:  ordenar lista **


* Data de inicio: 2021_10_21

* Data do fim: 2021_10_21

__Resumo__ :

  Neste trabalho de casa o objetivo era apartir de uma lista dessordenada, ordena-la atraves que um processo chamado bubblesort em que se realiza atraves da comparaçao entre o 1º e o 2º elemento da lista, se o primeiro for maior que o segundo, o segundo passa para o lugar do primeiro e  o 1º para o lugar do segundo, comecando  outra vez o ciclo de verificacao, isto e se o  1 e maior que o segundo, como ja houve 1 troca o ciclo começa onde houve a troca.
  
  Para este fim eu construi um ciclo for que vai desde a 1 posiçao  ate ao len(lista)-1,  para percorrer a lista, quando o ciclo percorre a lista vê se o 1º é maior que o segundo, se for, ha uma troca e por isso criamos uma variavel temporal para colocar lá o L[i] e de seguida podermos fazer que o L[i]=L[i+1] ou seja haá o segundo passa para o 1º, e depois o 1 passa para o segundo atraves da igualdade L[i+1]=temp.
  Se  esta condiçao nao se verificar  temos que retomar a variavel como False. 
  
  Ao correr isto verifiquei que tinha que fazer print varias vezes para me ordenatr a lista e que nao corrigia erros como o 6 estar primeiro que o 4, entao lembrei me de criae outro ciclo para  que ao longo da lista ddepois de ordenada  maioritariamente, ele fizese o mesmo processo que fez no 1º ciclo, e que se nao fosse possivel trocar, o programa  parava pois queria dizer que a lista tava ordenada.
  
 Assim tive a lista toda ordenada e so precisei de fazer 1 print.
 
 Professor: José Carlos Ramalho- http://www.di.uminho.pt/~jcr/
 
