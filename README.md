# -Estrutura-de-decis-o-if
# Bem-vinda ao meu repositório de soluções para problemas de programação! Aqui você encontrará scripts Python que resolvem desafios diversos, ideais para praticar lógica e algoritmos. Cada script é claro e eficiente, perfeito para iniciantes ou para revisar conceitos básicos. Aproveite e contribua!




#### 1. Faça um Programa que peça dois números e imprima o maior deles.

numero1 = float(input('Informe o primeiro número: '))
numero2 = float(input('Informe o segundo número: '))

if numero1 > numero2:
    print('O maior número é', numero1)
elif numero2 > numero1:
    print('O maior número é', numero2)
else:
    print('Os números são iguais')
    
 
 
 
 
 
 
 
    
 #### 2. Faça um Programa que peça um valor e mostre na tela se o valor é positivo ou negativo.
 
 numero = float(input('Informe um número: '))

if numero > 0:
    print('O número é positivo')
elif numero < 0:
    print('O número é negativo')
else:
    print('O número é zero')
    
    






#### 3. Faça um Programa que verifique o estado civil de uma pessoa. Se a letra digitada é "C" (Casado), "S" (Solteiro), "D" (Divorciado), "V" (Viúvo) ou "O" (outros). Conforme a letra escrita pelo usuário seu programa deve escrever o estado civil, exemplo:

Usuário digita: C

Seu programa deve responder:
C - Casado

estado_civil = input('Informe o estado civil, C para Casado, S para solteiro, D para divorciado, V para viúvo ou O para outros: ')

if estado_civil == 'C':
    print('C - Casado')
elif estado_civil == 'S':
    print('S - Solteiro')
elif estado_civil == 'D':
    print('D - Divorciado')
elif estado_civil == 'V':
    print('V - Viúvo')
else:
    print('O - Outros')
    
    





 #### 4. Faça um Programa que verifique se o e-mail digitado faz parte dos e-mails de spam.
 
 emails_spam = "fulano@gmail.com,beltrano@gmail.com,ciclano@gmail.com"

email = input('Informe um email: ')

if email in emails_spam:
    print('Esse e-mail é spam')
else:
    print('Esse e-mail não é spam')
    
    
    





 #### 5. Faça um programa para a leitura de duas notas parciais de um aluno. O programa deve calcular a média alcançada por aluno e apresentar:

##### A mensagem "Aprovado", se a média alcançada for maior ou igual a sete;
##### A mensagem "Reprovado", se a média for menor do que sete;
##### A mensagem "Aprovado com Distinção", se a média for igual a dez.


nota1 = float(input('Informe a primeira nota: '))
nota2 = float(input('Informe a primeira nota: '))

media = (nota1 + nota2)/2

if media == 10:
    print('Aprovado com Distinção')
elif media > 7:
    print('Aprovado')
else:
    print('Reprovado')
    
    
    
  
  
  
  
  
    #### 6. Faça um Programa que leia o orçamento de 3 empresas e mostre o maior deles.
    
orcamento1 = float(input('Informe o primeiro orcamento: '))
orcamento2 = float(input('Informe o segundo orcamento: '))
orcamento3 = float(input('Informe o terceiro orcamento: '))

if orcamento1 > orcamento2 and orcamento1 > orcamento3:
    print('O maior orcamento é', orcamento1)
elif orcamento2 > orcamento1 and orcamento2 > orcamento3:
    print('O maior orcamento é', orcamento2)
elif orcamento3 > orcamento1 and orcamento3 > orcamento2:
    print('O maior orcamento é', orcamento3)
    
   
   
   
   
   
   
    #### 7. Faça um Programa que leia três orçamentos e mostre o maior e o menor deles.
    
orcamento1 = float(input('Informe o primeiro orcamento: '))
orcamento2 = float(input('Informe o segundo orcamento: '))
orcamento3 = float(input('Informe o terceiro orcamento: '))

if orcamento1 > orcamento2 and orcamento1 > orcamento3:
    print('O maior orcamento é', orcamento1)
elif orcamento2 > orcamento1 and orcamento2 > orcamento3:
    print('O maior orcamento é', orcamento2)
elif orcamento3 > orcamento1 and orcamento3 > orcamento2:
    print('O maior orcamento é', orcamento3)
    
if orcamento1 < orcamento2 and orcamento1 < orcamento3:
    print('O menor orcamento é', orcamento1)
elif orcamento2 < orcamento1 and orcamento2 < orcamento3:
    print('O menor orcamento é', orcamento2)
elif orcamento3 < orcamento1 and orcamento3 < orcamento2:
    print('O menor orcamento é', orcamento3)
    
    #### 8. Faça um programa que pergunte o preço de três produtos e informe qual produto você deve comprar, sabendo que a decisão é sempre pelo mais barato.
    
produto1 = float(input('Informe o preço do primeiro produto em R$: '))
produto2 = float(input('Informe o preço do segundo produto em R$: '))
produto3 = float(input('Informe o preço do terceiro produto em R$: '))

   
if produto1 < produto2 and produto1 < produto3:
    print('O produto mais barato é o primeiro produto e custa R$', produto1)
elif produto2 < produto1 and produto2 < produto3:
    print('O produto mais barato é o segundo produto e custa R$', produto2)
elif produto3 < produto1 and produto3 < produto2:
    print('O produto mais barato é o terceiro produto e custa R$', produto3)
    
    
    
    
    
    
    
 
#### 9. Faça um Programa que leia três números e mostre-os em ordem decrescente.

numero1 = float(input('Informe o primeiro número: '))
numero2 = float(input('Informe o segundo número: '))
numero3 = float(input('Informe o terceiro número: '))

if numero1 > numero2 and numero1 > numero3:
    print('O maior número é', numero1)
    if numero2 > numero3:
        print('O segundo maior número é', numero2)
        print('O terceiro maior número é', numero3)
    else:
        print('O segundo maior número é', numero3)
        print('O terceiro maior número é', numero2)
elif numero2 > numero1 and numero2 > numero3:
    print('O maior número é', numero2)
    if numero1 > numero3:
        print('O segundo maior número é', numero1)
        print('O terceiro maior número é', numero3)
    else:
        print('O segundo maior número é', numero3)
        print('O terceiro maior número é', numero1)
elif numero3 > numero1 and numero3 > numero2:
    print('O maior número é', numero3)
    if numero1 > numero2:
        print('O segundo maior número é', numero1)
        print('O terceiro maior número é', numero2)
    else:
        print('O segundo maior número é', numero2)
        print('O terceiro maior número é', numero1)
        
        
        
        
        
        
        
     #### 10. Faça um Programa que pergunte em que turno você estuda. Peça para digitar M-matutino ou V-Vespertino ou N- Noturno. Imprima a mensagem "Bom Dia!", "Boa Tarde!" ou "Boa Noite!" ou "Valor Inválido!", conforme o caso.   
    
turno = input('Informe o turno: ')

if turno == 'M':
    print('Bom Dia!')
elif turno == 'V':
    print('Boa Tarde!')
elif turno == 'N':
    print('Boa Noite!')
else:
    print('Valor Inválido!')
 
 
 
 
 
 
 
 
 
 
 #### 11. As Organizações Tabajara resolveram dar um aumento de salário aos seus colaboradores e lhe contraram para desenvolver o programa que calculará os reajustes. Faça um programa que recebe o salário de um colaborador e o reajuste segundo o seguinte critério, baseado no salário atual:

##### salários até R\\$ 280,00 (incluindo) : aumento de 20% 

##### salários entre R\\$ 280,00 e R\\$ 700,00 : aumento de 15% 

##### salários entre R\\$ 700,00 e R\\$ 1500,00 : aumento de 10% 

##### salários de R\\$ 1500,00 em diante : aumento de 5% Após o aumento ser realizado, informe na tela: 

###### o salário antes do reajuste;

###### o percentual de aumento aplicado;

###### o valor do aumento;

###### o novo salário, após o aumento.

###### Obs: Não vamos nos preocupar tanto com a formatação dos números (nº de casas decimais, por exemplo, veremos isso no próximo módulo)

salario = float(input('Informe o salário em R$: '))

if salario <= 280:
    percentual = 0.2    
elif salario <= 700:
    percentual = 0.15
elif salario <= 1500:
    percentual = 0.1
else:
    percentual = 0.05

novo_salario = salario * (1 + percentual)
aumento = novo_salario - salario

print(f'Salário antes do reajuste: R$ {salario}')
print(f'Percentual de aumento: {percentual * 100}%')
print(f'O aumento foi de R$ {aumento}')
print(f'Salário após aumento: R$ {novo_salario}')








#### 12 . Faça um programa para o cálculo de uma folha de pagamento, sabendo que os descontos são do Imposto de Renda, que depende do salário bruto (conforme tabela abaixo) e que o FGTS corresponde a 11% do Salário Bruto, mas não é descontado (é a empresa que deposita). O Salário Líquido corresponde ao Salário Bruto menos os descontos. O programa deverá pedir ao usuário o valor da sua hora e a quantidade de horas trabalhadas no mês.

Desconto do IR:<br>
Salário Bruto até 900 (inclusive) - isento<br>
Salário Bruto até 1500 (inclusive) - desconto de 5%<br>
Salário Bruto até 2500 (inclusive) - desconto de 10%<br>
Salário Bruto acima de 2500 - desconto de 20%<br>
Imprima na tela as informações, dispostas conforme o exemplo abaixo. No exemplo o valor da hora é 5 e a quantidade de hora é 220.

Salário Bruto: (5 * 220)        : R\\$ 1100,00<br>
(-) IR (5%)                     : R\\$   55,00<br>
(-) INSS ( 10%)                 : R\\$  110,00<br>
FGTS (11%)                      : R\\$  121,00<br>
Total de descontos              : R\\$  165,00<br>
Salário Liquido                 : R\\$  935,00<br>

###### Obs: Não vamos nos preocupar tanto com a formatação dos números (nº de casas decimais, por exemplo, veremos isso no próximo módulo)

valor_hora = float(input('Informe o valor da hora R$: '))
qtd_horas = int(input('Informe a quantidade de horas trabalhadas: '))
salario = valor_hora * qtd_horas
print(f'Salário Bruto: (R${valor_hora} * {qtd_horas}): R$ {salario}')

if salario <= 900:
    percentual = 0
elif salario <= 1500:
    percentual = 0.05
elif salario <= 2500:
    percentual = 0.1
else:
    percentual = 0.2

ir = percentual * salario
inss = 0.1 * salario
fgts = 0.11 * salario
total_desconto = ir + inss
salario_liquido = salario - total_desconto
print(f'(-) IR ({percentual * 100}%): R$ {ir}')
print(f'(-) INSS (10%): R$ {inss}')
print(f'FGTS (11%): R$ {fgts:.2f}')
print(f'Total de descontos: R$ {total_desconto:.2f}')
print(f'Salário Líquido: R$ {salario_liquido:.2f}')









#### 13. Faça um Programa que leia um número e exiba o dia correspondente da semana. (1-Domingo, 2- Segunda, etc.), se digitar outro valor deve aparecer valor inválido.

dia = int(input('Informe o número: '))

if dia == 1:
    dia_semana = 'Domingo'
elif dia == 2:
    dia_semana = 'Segunda-feira'
elif dia == 3:
    dia_semana = 'Terça-feira'
elif dia == 4:
    dia_semana = 'Quarta-feira'
elif dia == 5:
    dia_semana = 'Quinta-feira'
elif dia == 6:
    dia_semana = 'Sexta-feira'
elif dia == 7:
    dia_semana = 'Sábado'
else:
    dia_semana = 'Valor inválido'
    
print(dia_semana)









#### 14. Faça um programa que lê as duas notas parciais obtidas por um aluno numa disciplina ao longo de um semestre, e calcule a sua média. Em seguida, mostre qual conceito o aluno teve. A atribuição de conceitos obedece à tabela abaixo:
<pre>
Média de Aproveitamento  Conceito
Entre 9.0 e 10.0 (inclusive o 10.0, não inclui o 9.0)      A
Entre 7.5 e 9.0 (inclusive o 9.0, não inclui o 7.5)        B
Entre 6.0 e 7.5 (inclusive o 7.5, não inclui o 6.0)        C
Entre 4.0 e 6.0 (inclusive o 6.0, não inclui o 4.0)        D
Entre 4.0 e zero (inclusive o 4.0, inclui o 0.0)           E
</pre>


nota1 = float(input('Informe a primeira nota: '))
nota2 = float(input('Informe a segunda nota: '))

media = (nota1 + nota2)/2

if 9 < media <= 10:
    conceito = 'A'
elif 7.5 < media <= 9:
    conceito = 'B'
elif 6 < media <= 7.5:
    conceito = 'C'
elif 4 < media <= 6:
    conceito = 'D'
elif 0 <= media <= 4:
    conceito = 'E'
else:
    conceito = 'Conceito inválido'
    
print('O conceito é:', conceito)








#### 15. Você está construindo um calendário para controlar dias de trabalho a pedido do RH. Nessa construção, você vai precisar definir quais anos são bissextos e quais não são, para montar o calendário de forma correta. Faça um Programa que peça um número correspondente a um determinado ano e em seguida informe se este ano é ou não bissexto.
<pre>
Dica para determinar se um ano é bissexto: 
- São bissextos todos os anos múltiplos de 400, p.ex.: 1600, 2000, 2400, 2800...
- São bissextos todos os múltiplos de 4, exceto se for múltiplo de 100 mas não de 400, 
p.ex.: 1996, 2000, 2004, 2008, 2012, 2016, 2020, 2024, 2028...
- Não são bissextos todos os demais anos.<br>
ex1: 2004 é múltiplo de 4, mas não é múltiplo de 100, então é bissexto.
ex2: 2000 é múltiplo de 4, mas é múltiplo de 100, só que também é multiplo de 400, então é bissexto (porque todo ano múltiplo de 400 é bissexto, independente do resto).
ex3: 1900 é múltiplo de 4, é múltiplo de 100, mas não é múltiplo de 400, então não é bissexto

</pre>

Dica: lembre que: numero % 4 é o resto da divisão do número por 4, ex: 10 % 3 = 1 (já que 10/3 = 3 e resta 1)

ano = int(input('Informe o ano: '))

if (ano % 4 == 0 and ano % 100 != 0) or ano % 400 == 0:
    print('O ano é bissexto.')
else:
    print('Não é um ano bissexto.')







#### 16. Faça um Programa para leitura de três notas parciais de um aluno. O programa deve calcular a média alcançada por aluno e presentar:
<pre>
A mensagem "Aprovado", se a média for maior ou igual a 7, com a respectiva média alcançada;
A mensagem "Reprovado", se a média for menor do que 7, com a respectiva média alcançada;
A mensagem "Aprovado com Distinção", se a média for igual a 10.
</pre>    
    
    
 nota1 = float(input('Informe a primeira nota: '))
nota2 = float(input('Informe a segunda nota: '))
nota3 = float(input('Informe a terceira nota: '))

media = (nota1 + nota2 + nota3) / 3

if media == 10:
    print('Aprovado com Distinção')
    print('Média:', media)
elif 7 <= media < 10:
    print('Aprovado')
    print('Média:', media)
elif media < 7:
    print('Reprovado')
    print('Média:', media)
    
    
    
    
    
    
    
    
    #### 17. João Papo-de-Pescador, homem de bem, comprou um microcomputador para controlar o rendimento diário de seu trabalho. Toda vez que ele traz um peso de peixes maior que o estabelecido pelo regulamento de pesca do estado de São Paulo (50 quilos) deve pagar uma multa de R$ 4,00 por quilo excedente. João precisa que você faça um programa que leia a variável peso (peso de peixes) e calcule o excesso. Gravar na variável excesso a quantidade de quilos além do limite e na variável multa o valor da multa que João deverá pagar. Imprima os dados do programa com as mensagens adequadas.
    
    
    peso = float(input('Informe o peso dos peixes em kg: '))

if peso > 50:
    excesso = peso - 50
    multa = excesso * 4
    print(f'O excesso foi de {excesso} kg, portanto a multa será de R$ {multa}.')
else:
    print(f'O peso de {peso} kg está dentro dos limites, não há multa.')
    
    
    
    
    
    
    
#### 18. Faça um Programa para um caixa eletrônico. O programa deverá perguntar ao usuário a valor do saque e depois informar quantas notas de cada valor serão fornecidas. As notas disponíveis serão as de 1, 5, 10, 50 e 100 reais. O valor mínimo é de 10 reais e o máximo de 600 reais. O programa não deve se preocupar com a quantidade de notas existentes na máquina.
<pre>
Exemplo 1: Para sacar a quantia de 256 reais, o programa fornece duas notas de 100, uma nota de 50, uma nota de 5 e uma nota de 1;
Exemplo 2: Para sacar a quantia de 399 reais, o programa fornece três notas de 100, uma nota de 50, quatro notas de 10, uma nota de 5 e quatro notas de 1.
</pre>

Dica1: numero // 10 vai te dar como resposta a parte inteira da divisão do número por 10.<br>
Dica2: numero % 10 vai te dar o resto da divisão do número por 10.

valor = int(input('Informe o valor a ser sacado: '))

n100 = 0
n50 = 0
n10 = 0
n5 = 0
n1 = 0

if 10 <= valor <= 600:
    print('São necessárias:')
    if valor >= 100:
        n100 = valor // 100
        print(n100, 'notas de 100')
    if valor % 100 >= 50:
        n50 = (valor - 100*n100) // 50
        print(n50, 'notas de 50')
    if valor % 50 >= 10:
        n10 = (valor - 100*n100 - 50*n50) // 10
        print(n10, 'notas de 10')
    if valor % 10 >= 5:
        n5 = (valor - 100*n100 - 50*n50 - 10*n10) // 5
        print(n5, 'notas de 5')
    if valor % 5 >= 1:
        n1 = valor - 100*n100 - 50*n50 - 10*n10 - 5*n5
        print(n1, 'notas de 1')
else:
    print('Informe um valor entre 10 e 600 reais')
    
    
    
    
    
    
    
    
    #### 19. Faça um programa que faça 5 perguntas para uma pessoa sobre um crime. As perguntas são:
<pre>
"Telefonou para a vítima?"
"Esteve no local do crime?"
"Mora perto da vítima?"
"Devia para a vítima?"
"Já trabalhou com a vítima?" 
O programa deve no final emitir uma classificação sobre a participação da pessoa no crime. Se a pessoa responder positivamente a 2 questões ela deve ser classificada como "Suspeita", entre 3 e 4 como "Cúmplice" e 5 como "Assassino". Caso contrário, ele será classificado como "Inocente".
</pre>

resposta = input('Telefonou para a vítima?')

p1 = 0
p2 = 0
p3 = 0
p4 = 0
p5 = 0

if resposta == 'sim':
    p1 = 1
    
resposta = input('Esteve no local do crime?')

if resposta == 'sim':
    p2 = 1
    
resposta = input('Mora perto da vítima?')

if resposta == 'sim':
    p3 = 1
    
resposta = input('Devia para a vítima?')

if resposta == 'sim':
    p4 = 1
    
resposta = input('Já trabalhou com a vítima?')

if resposta == 'sim':
    p5 = 1

total = p1 + p2 + p3 + p4 + p5

if total == 2:
    print('Suspeita')
elif 3 <= total <= 4:
    print('Cúmplice')
elif total == 5:
    print('Assassino')
else:
    print('Inocente')
    
    
  
  
  
  
    
 #### 20. Um posto está vendendo combustíveis com a seguinte tabela de descontos:
<pre>
Álcool:
até 20 litros, desconto de 3% por litro
acima de 20 litros, desconto de 5% por litro
Gasolina:
até 20 litros, desconto de 4% por litro
acima de 20 litros, desconto de 6% por litro

Escreva um algoritmo que leia o número de litros vendidos, o tipo de combustível (codificado da seguinte forma: A-álcool, G-gasolina), calcule e imprima o valor a ser pago pelo cliente sabendo-se que o preço do litro da gasolina é R$ 2,50 o preço do litro do álcool é R$ 1,90.
</pre>

tipo = input('Informe o tipo de combustível: ')
quantidade = float(input('Informe a quantidade de combustível: '))

if tipo == 'A' and quantidade <= 20:
    total = (1.9 * quantidade) * 0.97
elif tipo == 'A' and quantidade > 20:
    total = (1.9 * quantidade) * 0.95
elif tipo == 'G' and quantidade <= 20:
    total = (2.5 * quantidade) * 0.96
elif tipo == 'G' and quantidade > 20:
    total = (2.5 * quantidade) * 0.94

print('Total a pagar: R$', total)








#### 21. Uma fruteira está vendendo frutas com a seguinte tabela de preços:
<pre>
                      Até 5 Kg           Acima de 5 Kg
Morango         R$ 2,50 por Kg          R$ 2,20 por Kg
Maçã            R$ 1,80 por Kg          R$ 1,50 por Kg
Se o cliente comprar mais de 8 Kg em frutas ou o valor total da compra ultrapassar R$ 25,00, receberá ainda um desconto de 10% sobre este total. Escreva um algoritmo para ler a quantidade (em Kg) de morangos e a quantidade (em Kg) de maças adquiridas e escreva o valor a ser pago pelo cliente.
</pre>

qtd_morango = float(input('Informe a quantidade de morango: '))
qtd_maca = float(input('Informe a quantidade de maçã: '))

if qtd_morango > 5:
    total_morango = 2.2 * qtd_morango
else:
    total_morango = 2.5 * qtd_morango
    
if qtd_maca > 5:
    total_maca = 1.5 * qtd_maca
else:
    total_maca = 1.8 * qtd_maca
    
if qtd_morango + qtd_maca > 8 or total_morango + total_maca > 25:
    total = (total_morango + total_maca) * 0.9
else:
    total = total_morango + total_maca
    
print('Total a pagar: R$', total)







#### 22. O Hipermercado Tabajara está com uma promoção de carnes que é imperdível. Confira:
<pre>
                      Até 5 Kg           Acima de 5 Kg
File Duplo      R$ 4,90 por Kg          R$ 5,80 por Kg
Alcatra         R$ 5,90 por Kg          R$ 6,80 por Kg
Picanha         R$ 6,90 por Kg          R$ 7,80 por Kg
Para atender a todos os clientes, cada cliente poderá levar apenas um dos tipos de carne da promoção, porém não há limites para a quantidade de carne por cliente. Se compra for feita no cartão Tabajara o cliente receberá ainda um desconto de 5% sobre o total da compra. Escreva um programa que peça o tipo e a quantidade de carne comprada pelo usuário e gere um cupom fiscal, contendo as informações da compra: tipo e quantidade de carne, preço total, tipo de pagamento, valor do desconto e valor a pagar.
</pre>


tipo = input('Informe o tipo da carne: ')
quantidade = float(input('Informe a quantidade de carne: '))
pagamento = input('Escolha a forma de pagamento (C - Cartão Tabajara/D - Dinheiro): ')

if tipo == 'File Duplo' and quantidade > 5:
    total = 5.8 * quantidade
elif tipo == 'File Duplo' and quantidade <= 5:
    total = 4.9 * quantidade
elif tipo == 'Alcatra' and quantidade > 5:
    total = 6.8 * quantidade
elif tipo == 'Alcatra' and quantidade <= 5:
    total = 5.9 * quantidade
elif tipo == 'Picanha' and quantidade > 5:
    total = 7.8 * quantidade
elif tipo == 'Picanha' and quantidade <= 5:
    total = 6.9 * quantidade
    
print('--- CUPOM FISCAL ---')
print('Tipo da carne:', tipo)
print('Quantidade:', quantidade, 'kg')
print('Preço total: R$', total)
print('Forma de pagamento:', pagamento)

desconto = 0.05 * total if pagamento == 'C' else 0

print('Desconto: R$', desconto)
print('Valor a pagar: R$', total - desconto)







#### 23. Faça um Programa para uma loja de tintas. O programa deverá pedir o tamanho em metros quadrados da área a ser pintada. Considere que a cobertura da tinta é de 1 litro para cada 6 metros quadrados e que a tinta é vendida em latas de 18 litros, que custam R\\$ 80,00 ou em galões de 3,6 litros, que custam R\\$ 25,00.

area = float(input('Informe o tamanho da área a ser pintada em m²: '))
litros_tinta = area / 6


##### Informe ao usuário as quantidades de tinta a serem compradas e os respectivos preços em 3 situações.

Dica: lembre dos operadores // e % mostrados em exercícios anteriores<br>
Dica1: numero // 10 vai te dar como resposta a parte inteira da divisão do número por 10.<br>
Dica2: numero % 10 vai te dar o resto da divisão do número por 10.







##### 1. Comprar apenas latas de 18 litros: (apenas latas inteiras)


if litros_tinta % 18 > 0:
    latas = litros_tinta // 18 + 1
else:
    latas = litros_tinta // 18
preco = latas * 80
print(f'Serão necessárias {latas} latas, custando R$ {preco} no total')







##### 2. Comprar apenas galões de 3,6 litros: (apenas galoes inteiros)

if litros_tinta % 3.6 > 0:
    galoes = litros_tinta // 3.6 + 1
else:
    galoes = litros_tinta // 3.6
preco = galoes * 25
print(f'Serão necessários {galoes} galões, custando R$ {preco} no total')


O custo da lata é 80/18 = 4,44 R\\$/L

O custo do galão é 25/3,6 = 6,94 R\\$/L

A lata é mais econômica, então todas as latas inteiras que pudermos usar devemos comprar em latas. Se ficar faltando alguma coisa para completar devemos avaliar se é melhor comprar latas ou galões. Exemplo:

Se queremos comprar 90 litros. 5 latas dão exatamente 90 litros. Então devemos comprar tudo em latas.

Se queremos comprar 95 litros. 5 latas dão exatamente 90 litros. Então devemos comprar pelo menos 5 latas e avaliar o que falta, se estes últimos 5 litros valem mais apenas em latas ou galões.

Para os 5 litros faltantes precisamos de 2 galões que custam 50 reais no total. Ou de uma lata que custa 80 reais no total. Portanto, neste caso vale mais a pena usar 2 galões.

Se queremos comprar 107 litros. 5 latas dão exatamente 90 litros. Então devemos comprar pelo menos 5 latas e avaliar o que falta, se estes últimos 5 litros valem mais apenas em latas ou galões.

Para os 17 litros faltantes precisamos de 5 galões que custam 125 reais no total. Ou de uma lata que custa 80 reais no total. Portanto, neste caso vale mais a pena usar uma lata.

3 galões custam 75 reais, 4 galões custam 100 reais. Então, se for possível completar com até 3 galões escolhe-se galões. Qualquer quantidade maior que 3 galões, usa-se latas.

Podemos ir ao exercício:

# acrescentamos a folga de 10%
litros_folga = litros_tinta * 1.1
galoes = 0

# só latas inteiras
latas = litros_folga // 18


# aqui vemos a tinta que faltou que não cabe em uma lata completa
tinta_faltante = litros_folga - 18 * latas

# tinta faltante em galões
if tinta_faltante > 0:
    if tinta_faltante % 3.6 > 0:
        faltante_galoes = tinta_faltante // 3.6 + 1
    else:
        faltante_galoes = tinta_faltante // 3.6
    if faltante_galoes <= 3:
        galoes = faltante_galoes
    else:
        galoes = 0
        latas = latas + 1

preco = latas * 80 + galoes * 25
print(f'São necessários {latas} latas e {galoes} galões. Custando R$ {preco} no total')




