# -Estrutura-de-decis-o-if
# a estrutura de decisão if é implementada com duas condições, além dos operadores lógicos AND ( && ) e OR ( || ):
Como verificar se uma condição é falsa.


var c = -30;
var d = 50;

console.log("if com duas condições, onde ambas precisam ser verdadeiras:");
if (c > d && d > 0){
    console.log("c é maior que d E d é um número positivo");
}
if (c > d && d <= 0){
    console.log("c é maior que d E d não é um número positivo");
}
console.log("if com duas condições, onde pelo menos uma precisa ser verdadeira:");  
if (c < d || d > 0){
    console.log("c é menor que d OU d é um número positivo");
}
