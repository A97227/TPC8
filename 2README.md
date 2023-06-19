# TPC2
# _Manifesto do TPC2_
   
## Key name:Tpc2
## Work Team: Sandra Ferreira A97227

**Titulo: Pesquisa binaria**


*Data de inicio:2021_10_15

*Data do fim: 2021_10_17

__Resumo__:

  Neste trabalho de casa o objetivo era  apartir de uma lista de 0 a 100 o jogador escolhe um numero e o computador  tem que o descobrir qual é em 7 hipoteses.
 
   Para conseguir resolver o problema em 7 tentativas utilizei a pesquisa binária, que vai ao meio da lista e pergunta se é o numero do meio ("50") ou se é maior ou menor que o mesmo, se for uma dessas hipoteses vai sempre ao meio.
 
   Para isso cria-se uma variavel que é 0, que corresponde ao inicio da lista e outra variavel len(lista)-1 que vai ao fim da mesma(posiçao), e outra que vai ser a hipote dada pelo computador("b"), que começa a 0.
   
   Eu utilizei o ciclo de "while", em que enquanto a variavel do inicio for menor que a do fim, vai correr o ciclo feito. Comecamos com o b sendo 50(" b=(a+i)//2"). Se for 50 vai returnar o b no final, se for maior vai fazer com que a variavel inicial começe no b+1, se for menor a variavel final vai ser b-1.E assim ao percorremos o ciclo ele vai sempre ir a metade dok intervalo e perguntar se é aquele numero, até achar o numero escolhido. 
   
