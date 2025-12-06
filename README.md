# Criando um Servidor de Banco de Dados com Amazon RDS e Integrando com uma Aplicação Web
O projeto consistiu na criação e configuração de um ambiente de banco de dados na AWS utilizando o Amazon RDS, com foco em segurança, disponibilidade e integração prática com uma aplicação web. A partir de uma infraestrutura inicial contendo apenas a camada web em uma subnet pública, foi estruturada toda a camada de dados em sub-redes privadas, garantindo isolamento e comunicação controlada entre os serviços. 

Durante o processo, foram configurados Security Groups específicos, um DB Subnet Group distribuído por múltiplas zonas de disponibilidade e uma instância Amazon RDS Multi-AZ baseada em MySQL. Por fim, o banco foi conectado a uma aplicação web hospedada em EC2 para validar operações de leitura e escrita, assegurando que toda a arquitetura estivesse funcional de ponta a ponta.

## Objetivo 
Compreender na prática, como provisionar um banco de dados relacional gerenciado na AWS e integrá-lo de forma segura com uma aplicação web. Além de reforçar conceitos de redes, alta disponibilidade e controle de acesso, o laboratório buscou demonstrar como serviços gerenciados como o RDS, simplificam a operação de bancos de dados ao mesmo tempo em que oferecem resiliência, escalabilidade e boas práticas recomendadas para ambientes de produção.
