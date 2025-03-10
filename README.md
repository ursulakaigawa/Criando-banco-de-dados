# Criando banco de dados

Criar um banco de dados, algumas tabelas e descrever como conectar num provedor de nuvem.

Durante o desenvolvimento, foram implementados diferentes tipos de relacionamentos: um para um (cliente e endereço), um para muitos (empresa e funcionário) e muitos para muitos (curso e estudante), visando compreender a estruturação de dados e a aplicação de chaves primárias e estrangeiras. A atividade foi fundamental para reforçar os conceitos de modelagem de banco de dados e uso de SQL em um ambiente real.
O provedor escolhido para hospedar o banco de dados foi a AWS, utilizando o serviço RDS (Relational Database Service). O RDS oferece escalabilidade automática, backups automáticos, e suporte para diversas engines de banco de dados, incluindo MySQL. O custo base do serviço depende do tipo de instância utilizada, variando de acordo com a capacidade de memória, CPU, e armazenamento selecionado. Para instâncias pequenas, o preço inicial pode ser em torno de $0.018 por hora.

