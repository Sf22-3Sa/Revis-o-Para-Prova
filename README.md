algoritmo "desconto_promocional"                                                                   

var
   valorOriginal, desconto, precoFinal: real

inicio
   escreva("Digite o valor original do produto: ")
   leia(valorOriginal)

   desconto <- valorOriginal * 15 / 100
   precoFinal <- valorOriginal - desconto

   escreval("Valor original: R$ ", valorOriginal)
   escreval("Valor do desconto: R$ ", desconto)
   escreval("Preço final: R$ ", precoFinal)

fimalgoritmo

