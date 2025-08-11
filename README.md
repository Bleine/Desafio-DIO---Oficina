# Desafio DIO - Oficina
Desafio proposto pelo bootcamp Randstad - Analise de Dados - DIO no módulo sistemas Relacionais em Bancos de Dados.


## Objetivo
Desenvolver um esquema conceitual para banco de dados para gerenciar ordens de serviço em uma oficina mecânica, cobrindo clientes, mecânicos, peças e mão de obra

## Tecnologias e Ferramentas Utilizadas
MySQL Workbench

## Modelagem e Arquitetura
Entidades:
 - Ordem de Serviço
 - Clientes
 - Mecânicos
 - Peças
 - Mão de Obra

As entidades Peças e Mão de Obra possuem relacionamento N:M com a entidade Ordem de Serviço;
A entidade Mecânicos possui relacionamento N:M com a entidade Ordem de Serviço.

## Diagrama

[Diagrama Oficina no Github](https://github.com/Bleine/Desafio-DIO---Oficina/blob/main/oficina.png)

<img width="827" height="735" alt="oficina" src="https://github.com/user-attachments/assets/8f8d6e00-125e-4fbb-af29-dd192939f0b2" />

## Implementação
O modelo, as entidades e os relacionamentos foram desenvilvidos com base em uma narrativa oferecida pelo curso.

## Aprendizados
Criação de diagramas.
Solução de junção.
Decisão de uso dos relacionamentos.
Usar a ferramenta Workbench.
Visualização de diagramas.

