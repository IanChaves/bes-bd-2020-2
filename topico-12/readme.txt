Neste diretório você deverá depositar um arquivo JPG, 
contendo a imagem de um DER que você criará:

ao depositar o arquivo, checar se as dimensões da imagem do diagrama estão ajustadas à 
area de apresentação no GitHub (não deve ser muito pequeno a ponto de tornar-se ilegível, 
nem grande demais a ponto de ser necessário rolar (to scroll) para visualizar).

Requisitos de dados:

trata-se de um banco de dados simples para um aplicativo de transporte (tipo Uber), denominado BD Transporte Simples;
basicamente, o banco de dados possui percursos, e cada percurso envolve um motorista, um cliente, data/hora de início, 
local de origem, local de destino, valor referente ao serviço prestado e data/hora do pagamento;
dois ou mais percursos podem ter a mesma data/hora de início, desde que sejam de clientes diferentes;
um cliente pode ter vários percursos;
um motorista tem um ou mais percursos;
o esquema do banco de dados deve ter pelo menos um tipo de entidade fraca;
cliente e motorista têm os mesmos atributos: RG, CPF, nome, data de nascimento, cor preferida;
algumas consultas típicas são:
	quais os percursos que ainda não foram pagos?
	qual a média diária de percursos por cliente?
	qual a média diária de percursos por motorista?
	qual o faturamento diário da empresa?