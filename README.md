**_Regador autom�tico_**

Criaremos um sistema automatizado que ir� regar plantas todos os dias pela manh�, que tamb�m possuir� um sensor de umidade que verificar� a umidade do solo
e ir� regar as plantas caso a umidade seja muito baixa.

1. Requisitos
	1. Arduino
	1. Sensor de umidade (hidr�metro)
	1. Bomba de aqu�rio
	1. Vaso de planta
    1. Sensor wifi (no arduino)

_Instala��o_
 O hidr�metro ser� fixado na terra do vaso de planta e conectado ao arduino para fazer as    leituras, e a bomba de aqu�rio ser� ligado ao arduino por um 'jumper' que, dependendo da umidade do solo, ser� ativado e ir� mandar energia para a bomba. A bomba precisar� de um recipiente com �gua da qual retirar� a �gua. O arduino ser� conectado � internet para se comunicar com o usu�rio.

Obs.:
-> *Os valores de umidade ser�o armazenados em um banco de dados e ao final do dia ser� calculado uma m�dia que tamb�m vai ser salva no banco de dados*
-> *Caso os valores de umidade sejam muito baixos ou muito altos, o usu�rio ir� receber um email de aviso*
-> *O usu�rio poder� verificar a umidade do dia em um site que mostra a hora da leitura e o valor registrado*
-> *O sistema ir� controlar uma bomba de aqu�rio para regar as plantas*