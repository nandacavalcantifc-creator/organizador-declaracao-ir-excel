# Organizador de Declaração de Imposto de Renda (Excel)

Projeto desenvolvido no desafio da DIO para criar uma planilha que ajuda a reunir e organizar, em um só lugar, as informações necessárias para fazer a declaração do Imposto de Renda de pessoa física.

## Objetivo
Facilitar a preparação da declaração de IR, centralizando dados pessoais, saldos bancários e rendimentos em abas organizadas e fáceis de preencher, o que reduz esquecimentos e erros na hora de declarar.

## Estrutura da planilha

**1. Titular**
- Dados da pessoa física: nome, CPF, data de nascimento, título de eleitor, cônjuge, endereço, CEP, telefone, celular e e-mail
- Perguntas de controle com lista suspensa (SIM/NÃO): houve alterações em relação à entrega anterior, possui dependentes e é residente no exterior

**2. Informes**
- Registro de até 3 bancos, com o valor atual e um campo para o anexo do informe de rendimentos
- Seleção do banco por lista suspensa, com mais de 50 instituições cadastradas (código + nome)
- Mensagem de ajuda e alerta de erro quando o banco informado não é válido
- Total consolidado dos saldos calculado automaticamente

**3. Notas**
- Tabela de entradas com data, categoria e valor
- Categoria escolhida por lista suspensa: Holerite, CNPJ ou Freelance

## Ferramentas e conceitos utilizados
- Microsoft Excel
- **Validação de dados** com listas suspensas, mensagens de entrada e alertas de erro personalizados
- **Aba auxiliar oculta** com a base de bancos usada nas listas
- **Tabela formatada** do Excel para registrar as entradas
- Função **SOMA** para consolidar os saldos bancários
- Organização em abas por etapa e formatação visual para orientar o preenchimento

## Como usar
1. Baixe o arquivo `Projeto Fernanda Lins.xlsx`
2. Na aba **Titular**, preencha os dados pessoais e responda às perguntas de controle
3. Na aba **Informes**, selecione cada banco na lista, informe o valor atual e anexe o informe de rendimentos
4. Na aba **Notas**, registre as entradas do ano (holerites, recebimentos como CNPJ ou freelances)
5. Use a planilha como guia na hora de preencher o programa da Receita Federal

> Os dados que aparecem na planilha são fictícios e servem apenas como exemplo.

## Visualização
![Print da planilha](<img width="1036" height="513" alt="image" src="https://github.com/user-attachments/assets/3492df20-3a44-46ce-9565-1ad099b3a9cf" />)

## O que aprendi
Com este projeto, aprendi a estruturar uma planilha pensando na experiência de quem vai preencher, usando validação de dados para evitar erros, listas suspensas alimentadas por uma base auxiliar e tabelas para organizar os registros. Também reforcei a importância de organizar os documentos com antecedência para a declaração do Imposto de Renda.

## Autora
Fernanda Lins – [LinkedIn](https://www.linkedin.com/in/fernandacavalcantilins)
