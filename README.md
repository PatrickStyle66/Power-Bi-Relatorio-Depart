# Power-Bi-Relatorio-Depart
Desafio de PowerBi realizado para o Bootcamp DIO em parceria com Santander. O Objetivo é, a partir de uma base de dados MySql hospedada na azure, realizar a extração e a transformação dos dados com foco na limpeza dos mesmos, realizando todas as modificações necessárias para o melhor entendimento das informações.

# Criações
- Criação da tabela "Employees and Department" a partir da mescla de consultas realizando um outer left join.
  - Eliminação de todas as colunas que não faziam referência a nome de empregado e departamento.
- Criação da tabela "Employees and Managers" a partir da mesca de consultas realizando um inner join.
  - Eliminação de todas as colunas que não faziam referência a nome de empregado e Gerente.
- Criação da tabela "Depatment Location" a partir da mescla de consultas realizando um outer left join.
  - Eliminação de todas as colunas que não faziam referência a nome de departamento e local.
# Modificações

## Tabela employee
- Mudança do tipo de dados da coluna "Salary" da tabela de decimal para decimal fixo.
- Divisão dos endereços em 4 colunas, sendo elas Address 1, Address 2, City e State.
- Mescla das colunas "Fname", "Minit" e "Lname" formando apenas a coluna "Name".

## Tabela works_on
- Mudança do tipo de dados da coluna "Hours" de decimal para decimal fixo.
- Agregação da coluna "department".

# Relatório
![Relatório departamento](https://github.com/ghastcmd/projeto-de-ecc/assets/30088774/7b357f0d-19a1-4ef7-8a28-61ede0186494)
