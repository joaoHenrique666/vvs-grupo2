#Casos de Teste

Os casos de teste para o teste funcional são derivados de casos de uso do objetivo do teste. É necessário desenvolver casos de teste para cada cenário de caso de uso. Os cenários de caso de uso são identificados através da descrição dos caminhos que percorrer o fluxo básico e os fluxos alternativos, do início ao fim, através do caso de uso.

No diagrama a seguir, por exemplo, os vários caminhos através de um caso de uso, que refletem o fluxo básico e os fluxos alternativos, são representados com as setas. O fluxo básico, representado pela linha preta e reta é o caminho mais simples através do caso de uso. Cada fluxo alternativo começa no fluxo básico e, depois, de acordo com uma condição específica, é executado. Os fluxos alternativos podem retornar ao fluxo básico (fluxos alternativos 1 e 3), podem originar-se de outro fluxo alternativo (fluxo alternativo 2), ou podem terminar o caso de uso sem retornar a um fluxo (fluxos alternativos 2 e 4).

![Casos de Uso](http://www.wthreex.com/rup/process/modguide/images/tstcs_1.gif)

##Casos de Teste

As tabelas abaixo, são o modelo de identificação de Requisitos ao longo de todo o Trabalho.

#####Engenheiro

|_ID Caso de Teste_|_Cenário_|_Carteira-Crea_|_Idade_|_CPF/Passaporte_|_Reservista_|_Caracteres-Nome_|_Resultado Esperado_|
|---|---|---|---|---|---|---|---|---|
|CTE01|Engenheiro cadastrado com sucesso!|Validada|18<= idade <=75|Validado|idade < 45|5 < carac <= 100 ||

|_ID Caso de Teste_|_Cenário_|_Carteira-Crea_|_Idade_|_CPF/Passaporte_|_Reservista_|_Caracteres-Nome_|_Resultado Esperado_|
|---|---|---|---|---|---|---|---|---|
|CTE01|Engenheiro cadastrado com sucesso!|Válidado|18<= idade <=75|Válido|idade < 45|5 < carac <= 100 ||