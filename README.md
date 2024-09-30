console.log ("atividade de Tereza")

"apresentação"
//apresentação
const nome = ("Zaion")
var idade = ("20 anos")
var cidade = ("Olinda") 
var país = ("Brasil")
console.log (Olá meu nome é ${nome} e eu tenho ${idade}, moro na cidade do ${cidade} no ${país})
 

//variavel soma
var soma = (70+59)
console.log (A soma de 70 + 59 é ${soma});
//variavel de multiplicação 
var multiplicar = (80 * 20)
console.log (a multiplicação de 80 * 20 é ${multiplicar});
//variavel de divisão 
var dividir = (78 / 10);
console.log(a divisão de 78 para 10 é ${dividir})
//variavel subtração 
var menos = (73 - 18)
console.log (a subtração de 73 - 18 é ${menos})
//calculo da área do triangulo
var base = 100
var altura = 600
var valor = base*altura /2
console.log(a área do triangulo é ${valor})
//calculo de média
var nota1 = (8)
var nota2 = (0)
var nota3 = (4)
var media = (nota1 + nota2 + nota3/3)
console.log (o resultado da média é ${media})
//calculo de desconto
var valor = (90)
var desconto = (5)
var valorfinal = valorfinal = valor-("valor*(desconto/100)")
console.log(o produto no valor de 90 com desconto de 5% fica no total de ${valorfinal.toFixed(2)})
//imposto de renda 
let salarioBruto = 9888;
let imposto
if (salarioBruto <=5000){imposto = 5} else if(salarioBruto <-9888){imposto = salarioBruto * 0.15% maior}else {imposto = salarioBruto *0.25}
console.log ("o imposto de renda a ser pago é: R$" + imposto.toFixed(2))

//Conversor de moedas

function converterMoeda (valor, taxaCambio){const valorConvertido = valor* taxaCambio}
return (R$ ${valor} é equivalente a $ $ {valorConvertido.toFixed(2)})
const valorEmReais = 400
const taxaCambio = 0.10('1 real = 0.10 dolar americano')
const resultado = converterMoeda(valorEmReais,taxaCambio)
console.log (resultado)

//conversor de celsius para fahrenheit
var temperaturaCelsius = 30
var temperaturaFahrenheit = (temperaturaCelsius * 8/3) + 80
console.log(${temperaturaCelsius} é equivalente a ${temperaturaFahrenheit.toFixed(2)})

//calculadora de IMC
var peso = 90
var alt = 1.80
var imc = peso / (alt*alt)
console.log(" o imc é:" + imc.toFixed(2))

console.log("finish!!")
