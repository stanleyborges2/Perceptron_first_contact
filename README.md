# Perceptron_first_contact

## CONCEITO DO PERCEPTRON
Esse perceptron é um dos mais simples e antigos de rede neural artificial. Ele foi proposto por Frank Rosenblatt em 1958 e é considerado fundamental para redes neurais modernas.

## FUNCIONAMENTO 
Perceptron é um classificador linear, Isso quer dizer que ele separa os dados usando uma linha reta (ou plano, em mais dimensões). Porém ele possui grande limitações como: É fraco para padrões complexos ou dados muito bagunçados.

## CÓDIGO
Entrada de dados

Você passa inputs, weights e bias para a função perceptron_input.

Cálculo da soma ponderada

Multiplica cada entrada pelo peso correspondente (i * w).

Soma tudo e adiciona o bias.

Função de ativação (saída)

perceptron_output retorna 1 se o valor calculado for maior ou igual a 0, senão 0.

Isso é a decisão binária do perceptron.

## Aplicação prática:
O perceptron poderia ser ultilizado em algo simples porem efetivo como um sistema simples de diagnostico através dos sintomas como por exemplo:
Entrada: pressão arterial, nível de glicose, idade.
Saída: 1 = precisa de exame médico / 0 = saudável.

Bom para triagem rápida em sistemas simples de saúde.
