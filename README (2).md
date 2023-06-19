# TPC4

##__Manifesto do TPC4__
__Nome da chave: Tpc4__
Equipe de Trabalho: Sandra Ferreira A97227
** Titulo: Aplicaçao, que lê o menu e aplica uma dada funçao **

Data de inicio: 2021_11_

Data do fim: 2021_11_12

Resumo :

Neste trabalho de casa o objetivo era fazer uma aplicaçao que lê o menu e aplica uma dada funçao, ja criada, que permite a soma, subtraçao ou multiçicação de fraçoes.
Para isso utilizei a parte do criar menu que apredemos na aula, e a parte de creiar fraçao, vê-la e simplifica-la.
Depois aproveitei e parte da soma ja feita, eu apliquei o mesmo raciocinio para as funçoes de divisao, multiplicaça e subtraçao. 
Esse racicionio foi o seguinte:  primeiro para simplificar o prcesso, crei uma funçao que permite ler os dois primeiros tuplos com os elementos de 1 fraçao cada um, depois fazemos a operaçao que pretendemos, como por exemplo na subtraçaoa queremos reduzir td ao mesmo denominadr, e subtrair o nominador, por isso multiplicamos o denominador de um a uma fraçao e o demonominador de outro a outra fraçao,
assim temos uma subtraçao simples de 2 elementos.
Depois fazemos outra funçao onde chamamos a funçao anterior para percorrer a lista o que permite dividir a lista a cada 2 tuplos e calcular tudo atraves dessa divisao.
Inventamos umavariavel que chamada a funçao anterior e introduzimos os 1º 2 tuplos, lista [0] e lista[1].
de seguida criamos um ciclo for para percorrer os elem da lista, ou seja os tuplos todo, começando na posiçao 2 e indo ate ao final da lista.
para termos o resultado final, temos que utilizar a 1º funçao e dizer que a variavel inventada vai ser a 1º funcao em que os elementos sao: a variavel(ja com os 1º 2 tuplos subtraidos, pois fizemos isso no inicio) 
 e o tuplo seguinte(que é a lista[i]). como a variavel encontra-se dentro do ciclo vai ser sempre renovada, o que permite que o valor da mesma n seja o valor do inicio mas o valor que tomou dentro do ciclo, o que permite depois chamar outra vez a 1º funçao e utilizar a variavel e o lista[i+1] porque é sempre o elem a seguir!
 Exemplo:
def sub2(f1,f2):
    n1, d1=f1
    n2, d2=f2
    return simplificafraçao(int(n1*d2 - n2*d1),int(d1*d2))

listafrac2=[(1,4), (1,7), (5,3), (8,12)]
def subtra(listafrac2):
    sub=sub2(listafrac2[0],listafrac2[1])
    
    for i in range(2, len(listafrac2)):
        
        sub=sub2(sub, listafrac2[i])
    print(verfraçao(sub))
    
    Professor: José Carlos Ramalho- http://www.di.uminho.pt/~jcr/
