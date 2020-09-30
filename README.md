# logica de progamação
algoritmo "semnome"
// Função :
// Autor :
// Data : 06/08/2020
// Seção de Declarações 
var
   a,b,c:inteiro
inicio
  a<- 2
  b<-3
  c<- 5
  escreva(b>c%2)
fimalgoritmoalgoritmo "semnome"
// Função :
// Autor :
// Data : 06/08/2020
// Seção de Declarações 
var
   a,b,c:inteiro
inicio
  a<- 2
  b<-3
  c<- 5
  escreva(nao(a=b)ou(c>a))
fimalgoritmo
algoritmo "semnome"
// Função :
// Autor :
// Data : 06/08/2020
// Seção de Declarações 
var
   a,b,c:inteiro
inicio
  a<- 2
  b<-3
  c<- 5
  escreva((a=b)ou(c>a))
fimalgoritmo
algoritmo "semnome"
// Função :
// Autor :
// Data : 06/08/2020
// Seção de Declarações 
var
   a,b,c:inteiro
inicio
  a<- 2
  b<-3
  c<- 5
  escreva(nao(a=b)e(c<a))
fimalgoritmo
algoritmo "semnome"
// Função :
// Autor :
// Data : 06/08/2020
// Seção de Declarações 
var
   a,b,c:inteiro
inicio
  a<- 2
  b<-3
  c<- 5
  escreva((a=b)e(c<a))
fimalgoritmo
algoritmo "triangulo"
// Função :
// Autor :
// Data : 06/08/2020
// Seção de Declarações 
var
      L1 ,L2,L3:REAL
      EQ, ES,TRI:LOGICO
inicio
ESCREVA ("DIGITE O PRIMEIRO LADO:")
LEIA (L1)
ESCREVA ("DIGITE O SEGUNDO LADO")
LEIA(L2)
ESCREVA("DIGITE O TRESEIRO LADO")
LEIA (L3)
TRI<- (L1<L2+L3)E (L2<L1+l3)E (L3<L1+L2)
EQ<- (L1=L2)E (L2=L3)
ES<-(L1<>L2)E(L2<>L3)E(L1<>L3)
ESCREVAL("PODE FORMA UM TRIANGULO")
ESCREVAL("O TRIANGULO E EQILATERO",EQ)
ESCREVAL("O TRIANGULO ESCALENO",ES)
fimalgoritmo
