# Desafio DIO - Oficina
Desafio proposto pelo bootcamp Randstad - Analise de Dados - DIO no módulo sistemas Relacionais em Bancos de Dados.


## Objetivo
Desenvolver um esquema conceitual para banco de dados, focado no gerenciamento de ordens de serviço em uma oficina mecânica, cobrindo clientes, mecânicos, peças e mão de obra

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
O modelo, as entidades e os relacionamentos foram desenvolvidos com base em uma narrativa oferecida pelo curso.

Narrativa:
- Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
- Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
- Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
- A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
- O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
- A mesma equipe avalia e executa os serviços
- Os mecânicos possuem código, nome, endereço e especialidade
- Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.


## Aprendizados
Ao participar desse desafio, a tarefa mais difícil foi organizar a lógica de relacionamento entre as entidades.
Decidi começar pela entidade Ordem de Serviço e torná-la central. Depois, fui entidade por entidade refletindo sobre as suas relações. 
Usar o WorkBench facilitou o meu entendimento em SQL, pois permite a visualização das tabelas e seus relacionamentos.

