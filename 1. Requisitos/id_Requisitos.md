#Documentação de Requisitos

Os requisitos serão documentados na Forma de Casos de Uso, baseado no template disponibilizado pelo Professor Gilmar, como citado anteriormente no README.md.

##Requisitos identificados

As tabelas abaixo, são o modelo de identificação de Requisitos em relação à implementação de um sistema para gerenciar o preenchimento destas vagas.

####Sistema
|_Termos_|_Conteúdo_|
|---|---|
|**Nome**|Cadastro de Usário|
|**Identificador**| RF00|
|**Importância** | Primordial|
|**Ator Primário**|Usuário/Candidato|
|**Atores Secundários**|  |
|**Pré-condições**|O site deverá estar em funcionamento|
|**Fluxo Principal**| O usuário deverá ser capaz de entrar no sistema e realisar o cadastro, com todos os dados solicitados. Durante o cadastro do candidato o sistema deve apresentar o tempo de experiência exigida e a oferta salarial do cargo. |
|**Fluxos Alternativos**| Caso o usuário não preencha um dado considerado obrigatório, o sistema deverá retornar um aviso indicando que o procedimento não foi concluído e não confirmar inscrição até o preenchimento de todos os dados. E  se o candidato não tiver o tempo de experiência ou não aceitar a oferta, o cadastro não poderá ser efetivado.|
|**Fluxos de Exceção**|Os únicos dados que poderão deixar de ser preenchidos são aqueles que não são considerados obrigatórios.
|**Pós-condições**|O sistema exibe uma mensagem confirmando inscrição do usuário.|
|**Regras de Negócio**||
|**Histórico**||
|**Notas de Implementação**||

####Gerenciador de Vagas - Requisitos Específicos para o cargo de Engenheiro

|_Termos_|_Conteúdo_|
|---|---|
|**Nome**|Carteira Crea |
|**Identificador**| REQ01|
|**Importância** |Primordial|
|**Ator Primário**|Candidato|
|**Atores Secundários**||
|**Pré-condições**||
|**Fluxo Principal**|O Candidato apresenta a carteira profissional do Crea e segue para o  próximo item de preenchimento da vaga. |
|**Fluxos Alternativos**|O Candidato não apresenta a carteira do Crea, é eliminado da seleção de prenchimento da vaga.|
|**Fluxos de Exceção**||
|**Pós-condições**||
|**Regras de Negócio**||
|**Histórico**||
|**Notas de Implementação**||

####Gerenciador de Vagas - Requisitos Específicos para o cargo de Motorista

|_Termos_|_Conteúdo_|
|---|---|
|**Nome**|CNH|
|**Identificador**| REQ02|
|**Importância** |Primordial|
|**Ator Primário**|Candidato|
|**Atores Secundários**|  |
|**Pré-condições**| |
|**Fluxo Principal**|O Candidato apresenta devida CNH e segue para o  próximo item de preenchimento da vaga.|
|**Fluxos Alternativos**|O Candidato não apresenta a CNH, é eliminado da seleção de prenchimento da vaga.|
|**Fluxos de Exceção**||
|**Pós-condições**|Segue para o  próximo item de preenchimento da vaga.|
|**Regras de Negócio**||
|**Histórico**||
|**Notas de Implementação**||

####Gerenciador de Vagas - Requisitos Específicos para o cargo de Médico

|_Termos_|_Conteúdo_|
|---|---|
|**Nome**|CRM|
|**Identificador**| REQ03|
|**Importância** |Primordial|
|**Ator Primário**|Candidato|
|**Atores Secundários**|  |
|**Pré-condições**| |
|**Fluxo Principal**|O Candidato apresenta a carteira do CRM.|
|**Fluxos Alternativos**|O Candidato não apresenta a a cartira do CRM, é eliminado da seleção de prenchimento da vaga.|
|**Fluxos de Exceção**||
|**Pós-condições**|Segue para o  próximo item de preenchimento da vaga.|
|**Regras de Negócio**||
|**Histórico**||
|**Notas de Implementação**||

####Gerenciador de Vagas - Geral

|_Termos_|_Conteúdo_|
|---|---|
|**Nome**|Idade|
|**Identificador**|REQ04|
|**Importância** |Primordial|
|**Ator Primário**|Candidato|
|**Atores Secundários**|  |
|**Pré-condições**| |
|**Fluxo Principal**|O Candidato apresenta documento(s) que comprova(m) que ele tem entre 18 e 75 anos.|
|**Fluxos Alternativos**|O Candidato não tem entre 18 e 75, é eliminado da seleção de prenchimento da vaga.|
|**Fluxos de Exceção**||
|**Pós-condições**|Segue para o  próximo item de preenchimento da vaga.|
|**Regras de Negócio**||
|**Histórico**||
|**Notas de Implementação**||

|_Termos_|_Conteúdo_|
|---|---|
|**Nome**|Nacionalidade|
|**Identificador**|REQ05|
|**Importância** |Primordial|
|**Ator Primário**|Candidato|
|**Atores Secundários**|  |
|**Pré-condições**| |
|**Fluxo Principal**|O Candidato é braileiro e apresenta o CPF válido.|
|**Fluxos Alternativos**|1) O Candidato é estrangeiro e apresenta o passaporte; 2) Não é apresentado nem o CPF, nem o passaporte, o Candidato é eliminado da seleção de prenchimento da vaga.|
|**Fluxos de Exceção**|O CPF precisa ser validado.|
|**Pós-condições**|Segue para o  próximo item de preenchimento da vaga.|
|**Regras de Negócio**||
|**Histórico**||
|**Notas de Implementação**||

|_Termos_|_Conteúdo_|
|---|---|
|**Nome**|Documento Reservista|
|**Identificador**|REQ06|
|**Importância** |Primordial|
|**Ator Primário**|Candidato|
|**Atores Secundários**|  |
|**Pré-condições**| O Candidato tem a idade inferior a 45 anos de idade.|
|**Fluxo Principal**|O Candidato é do sexo masculino e apresenta o documento de Reservista.|
|**Fluxos Alternativos**|1) O Candidato não apresenta documento reservista, é eliminado; 2) O Candidato é do sexo Feminino.|
|**Fluxos de Exceção**||
|**Pós-condições**|Segue para o  próximo item de preenchimento da vaga.|
|**Regras de Negócio**||
|**Histórico**||
|**Notas de Implementação**||

|_Termos_|_Conteúdo_|
|---|---|
|**Nome**|Nome|
|**Identificador**|REQ07|
|**Importância** |Primordial|
|**Ator Primário**|Candidato|
|**Atores Secundários**|  |
|**Pré-condições**||
|**Fluxo Principal**|O Candidato tem escreve o nome completo que tem no mínimo 5 caracteres e máximo de 100.|
|**Fluxos Alternativos**|O Candidato coloca um valor menor do que 5 caracteres ou maior do que 100 carcteres ou um valor nulo ou um sequencia de espaços em branco ou digita algum caracter especial, o sistema nega.|
|**Fluxos de Exceção**||
|**Pós-condições**|Segue para o  próximo item de preenchimento da vaga.|
|**Regras de Negócio**||
|**Histórico**||
|**Notas de Implementação**||

|_Termos_|_Conteúdo_|
|---|---|
|**Nome**|Experiência|
|**Identificador**|REQ08|
|**Importância** |Primordial|
|**Ator Primário**|Candidato|
|**Atores Secundários**|  |
|**Pré-condições**||
|**Fluxo Principal**|O Candidato apresenta comprovante de que tem no minímo 12 meses de experiência no cargo.|
|**Fluxos Alternativos**|O Candidato tem menos de 12 meses de experiência na área ou ele não tem experiência alguma.|
|**Fluxos de Exceção**||
|**Pós-condições**|Vaga preenchida com sucesso!|
|**Regras de Negócio**||
|**Histórico**||
|**Notas de Implementação**||