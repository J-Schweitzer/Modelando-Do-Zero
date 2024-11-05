Oficina:

Este banco de dados é para um sistema de controle e gerenciamento de ordens de serviço em uma oficina mecânica. Ele é composto pelas principais entidades:

Cliente: Armazena dados dos clientes, como nome, endereço e telefone.

Veículo: Guarda informações dos veículos, como placa e modelo, e está associado a um cliente.

Equipe: Representa as equipes de trabalho, que são compostas por mecânicos e são atribuídas às ordens de serviço.

Mecânico: Contém dados dos mecânicos, como nome, endereço e especialidade, e a equipe à qual pertencem.

Ordem Serviço: Registra cada ordem de serviço, incluindo data de emissão, data de conclusão, valor total e status. É associada a um veículo e a uma equipe específica.

Serviço: Define os tipos de serviços oferecidos, com descrição e valor de mão de obra.

Peça: Contém informações sobre peças utilizadas nos serviços, como nome, preço e preço de aluguel.

As tabelas de relacionamento Ordem Serviço_has_Serviço e Ordem Serviço_has_Peça vinculam cada ordem de serviço aos serviços realizados e peças utilizadas, permitindo o cálculo do valor total da OS. Este modelo permite gerenciar o processo desde o cadastro do cliente até a conclusão e faturamento dos serviços executados.
