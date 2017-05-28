**_Regador automático_**

Criaremos um sistema automatizado que irá regar plantas todos os dias pela manhã, que também possuirá um sensor de umidade que verificará a umidade do solo
e irá regar as plantas caso a umidade seja muito baixa.

1. Requisitos
	1. Arduino
	1. Sensor de umidade (hidrômetro)
	1. Bomba de aquário
	1. Vaso de planta
    1. Sensor wifi (no arduino)

_Instalação_
 O hidrômetro será fixado na terra do vaso de planta e conectado ao arduino para fazer as    leituras, e a bomba de aquário será ligado ao arduino por um 'jumper' que, dependendo da umidade do solo, será ativado e irá mandar energia para a bomba. A bomba precisará de um recipiente com água da qual retirará a água. O arduino será conectado à internet para se comunicar com o usuário.

Obs.:
-> *Os valores de umidade serão armazenados em um banco de dados e ao final do dia será calculado uma média que também vai ser salva no banco de dados*
-> *Caso os valores de umidade sejam muito baixos ou muito altos, o usuário irá receber um email de aviso*
-> *O usuário poderá verificar a umidade do dia em um site que mostra a hora da leitura e o valor registrado*
-> *O sistema irá controlar uma bomba de aquário para regar as plantas*