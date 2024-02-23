
# Sistema de Controle e Gerenciamento de Execução de Ordens de Serviço em uma Oficina Mecânica

## Objetivo
Este projeto tem como objetivo criar o esquema conceitual para o contexto de uma oficina mecânica, com base na narrativa fornecida. O sistema deve ser capaz de gerenciar a execução de ordens de serviço (OS), que são solicitadas pelos clientes para consertos ou revisões periódicas de veículos.

## Narrativa
- Clientes: Levam veículos à oficina mecânica para serem consertados ou para passarem por revisões periódicas.
- Equipe de Mecânicos: Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
- Cálculo de Valor dos Serviços: A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra. O valor de cada peça também irá compor a OS.
- Autorização do Cliente: O cliente autoriza a execução dos serviços.
- Execução dos Serviços: A mesma equipe avalia e executa os serviços.
- Mecânicos: Possuem código, nome, endereço e especialidade.
- Ordens de Serviço (OS): Cada OS possui um número, data de emissão, um valor, status e uma data para conclusão dos trabalhos.


## Conclusão
Este esquema conceitual fornece uma base sólida para o desenvolvimento de um sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica. Ele permite que os clientes solicitem serviços, que os mecânicos executem esses serviços e que os valores sejam calculados de acordo com tabelas de referência. O sistema também permite o controle do status das ordens de serviço e a associação de serviços a veículos e peças.