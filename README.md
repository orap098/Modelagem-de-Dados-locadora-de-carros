# Projeto: Banco de dados para locadora de carros

Data: 2024-01-24

## LINKS
Link Diagrama Entidade Relacionamento (DER): https://lucid.app/lucidchart/23677785-6109-419a-a5ef-ef271e57f54a/edit?viewport_loc=309%2C47%2C4177%2C1932%2CHWEp-vi-RSFO&invitationId=inv_c1324fcf-e8b1-4338-9350-6445b48a44e2

Link tabela de Dicionário de Dados: https://1drv.ms/x/s!AtshWwj6zHcpkLdqwiCWNnC9Oq6abg?e=VbFKkv

## Descrição

Este projeto consiste no desenvolvimento de um banco de dados para uma locadora de carros. O banco de dados deve armazenar as informações de clientes, carros e agências.

## Requisitos

Os clientes devem ser capazes de alugar carros.
Um cliente pode alugar mais de um carro e um carro pode ser alugado por mais de um cliente.
Um carro pertence a uma agência e uma agência pode ter mais de um carro.
As informações de clientes que precisam ser armazenadas são: CNH, nome, cartão e telefone.
As informações de carros que precisam ser armazenadas são: placa, modelo, ano e agência.
As informações de agências que precisam ser armazenadas são: número da agência, endereço e contato.
Não pode haver nenhum dado nulo no banco de dados. Todas as informações devem ser sempre preenchidas.
Desenvolvimento

## O desenvolvimento do banco de dados foi realizado nas seguintes etapas:

Compreensão do problema / solicitação: Nesta etapa, foi feita uma análise dos requisitos do projeto para identificar as entidades, relacionamentos e atributos necessários.
Definição do relacionamento entre as entidades (MER): Nesta etapa, foi criado um diagrama de entidade relacionamento (DER) para representar os relacionamentos entre as entidades.
Diagrama de Entidade Relacionamento (DER): O DER foi criado usando o Lucidchart. O link para o diagrama está disponível no início deste README.
Definição de modelo lógico: Nesta etapa, foi criado um modelo lógico para representar as entidades e relacionamentos em tabelas.
Normalização das tabelas: Nesta etapa, as tabelas foram normalizadas para reduzir a redundância e a dependência inconsistente.
Dicionário de dados: Nesta etapa, foi criado um dicionário de dados para documentar as tabelas, colunas e relacionamentos do banco de dados.

## Modelo lógico

O modelo lógico do banco de dados é composto pelas seguintes tabelas:

![image](https://github.com/orap098/Modelagem-de-Dados-locadora-de-carros/assets/75902289/dbcd1e6b-df43-48ef-8f9e-86b6f2455272)

## NORMALIZAÇÃO DAS TABELAS

Nessa etapa foi feita uma análise das tabelas, a fim de organizar os dados dentro delas, para redução da redundância e dependencia inconsistente, para correção foi acrecido colunas no lugar da coluna Endereço (Rua, Cidade e Estado).

![image](https://github.com/orap098/Modelagem-de-Dados-locadora-de-carros/assets/75902289/e5e03f2a-e84d-4944-ba55-e5e9919f4ee4)

## DICIONÁRIO DE DADOS

Nessa etapa foi feito descrição, relações de todas tabelas do banco de dados.
![image](https://github.com/orap098/Modelagem-de-Dados-locadora-de-carros/assets/75902289/8e8ff253-cd4b-4969-b460-f44a0a9d5e75)



