# Criando um Servidor de Banco de Dados com Amazon RDS e Integrando com uma Aplicação Web
Este repositório documenta um dos projetos práticos desenvolvidos durante o programa AWS re/Start na Escola da Nuvem ☁️, cujo objetivo foi criar um servidor de banco de dados e interagir com o banco de dados usando uma aplicação web.

O projeto consistiu na criação de um ambiente de banco de dados na AWS com Amazon RDS, estruturando a camada de dados em sub-redes privadas para garantir segurança e isolamento. Foram configurados Security Groups, um DB Subnet Group distribuído em múltiplas zonas de disponibilidade e uma instância RDS Multi-AZ (MySQL). Por fim, o banco foi integrado a uma aplicação web hospedada em EC2 para validar operações de leitura e escrita, assegurando o funcionamento completo de toda a arquitetura.

**Sobre o Amazon RDS:** trata-se de um serviço gerenciado que simplifica a criação, operação e escalabilidade de bancos de dados relacionais na nuvem. Ele automatiza tarefas administrativas, oferece alta disponibilidade e reduz a complexidade operacional, permitindo que o foco permaneça na aplicação e no negócio.

