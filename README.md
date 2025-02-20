# DIO-Oficina-BD
Criação de um Banco de Dados baseado no funcionamento de uma Oficina com a criação de um Diagrama Esquema Relacional

## Ferramentas utilizadas

Foi utilizado o MYSQL Workbench para a criação do modelo de Entidade - Relacionamento e também para a criação do Banco de Dados através de SQL.

## Criação do Diagrama Entidade - Relacionamento.

Foi desenvolvido um "Enhanced Entity-Relationship"  (EER) ou Diagrama de Entidade Relacionamento por meio do MySQL Workbench.

Neste diagrma foi mapeado como irá funcionar toda a oficina e seus relacionamentos de dados para o serviço completo.

![Diagrama Esquema Relacional](https://github.com/user-attachments/assets/e08f39fb-07be-4a4d-802c-18dde523a7f1)


## Criação do Banco de Dados

A partir do modelo de Entidade - Relacionamento criado foi mais simples a criação do Banco de Dados.

Abaixo a criação do Banco de Dados de acordo com os relacionamentos, os atributos, as constraints e as Primary Key e Foreign Key.

- [Código Criação Banco de Dados](documentos/banco_de_dados/01_Criacao_Banco_Dados_Oficina.txt)



## Dados de Exemplo.

Dados inseridos de exemplo para o modelo de Banco de Dados.

- [Código de Inserção dos Dados](documentos/banco_de_dados/02_Insercao_Dados_Oficina.txt)

# Respostas das Queries

## 1 -  Qual o faturamento do mês de Janeiro de 2025?

Comando em SQL

- [Faturamento de Janeiro de 2025](documentos/banco_de_dados/03_Lucro_Janeiro_2025.txt)

Resultados

![image](https://github.com/user-attachments/assets/0466ed2b-e24c-4a4c-a957-a8ee3fe373e4)


## 2 - Quais serviços foram cancelados, por quem e quanto deixei de faturar?

Código SQL

- [Serviços Cancelados](documentos/banco_de_dados/04_OS_Cancelada.txt)

Resultados

![image](https://github.com/user-attachments/assets/1a586f59-8512-44ab-9644-470a3bb53312)


    
## 3 - Equipes que mais finalizaram os serviços;

Código SQL

- [Equipes que mais finalizaram serviços](documentos/banco_de_dados/05_Equipe_Mais_Finalizou.txt)

Resultados

![image](https://github.com/user-attachments/assets/7d63079a-7220-405a-91b9-569bb685034e)


## 4 - Peças mais utilizadas nos consertos dos carros;

Código SQL

- [Peças mais utilizadas](documentos/banco_de_dados/06_Pecas_Mais_Utilizadas.txt)

Resultados

![image](https://github.com/user-attachments/assets/ab1e2819-49ca-4940-8e6d-d2615999a575)



