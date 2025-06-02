# Repositório de Diagramas UML - Diocese de Santos

## Sobre o Projeto

Este repositório contém os diagramas UML desenvolvidos para o projeto da Diocese de Santos, um aplicativo móvel e backend projetado para gerenciar informações litúrgicas, paróquias e eventos. O objetivo é representar a arquitetura do sistema por meio de diagramas de caso de uso e implantação, auxiliando na visualização das funcionalidades e da infraestrutura. O projeto utiliza uma abordagem modular com frontend em Flutter/Dart e backend em Golang, hospedado na AWS, para garantir escalabilidade, segurança e usabilidade.

## Organização dos Repositórios

O projeto é dividido em dois repositórios principais, que complementam os diagramas UML aqui apresentados:

- **Diocese-App**: Contém o código do frontend, desenvolvido em Flutter e Dart, responsável pela interface do usuário e integração com serviços como Google Calendar e Segment para análise. Este repositório inclui telas para visualização de agendas, paróquias e funcionalidades offline parciais.
- **diocese-backend**: Armazena o código do backend, escrito em Golang, que oferece uma API RESTful com autenticação JWT e interação com o banco de dados PostgreSQL no Amazon RDS. Também inclui integração com serviços AWS como SES (e-mails) e API Gateway.

Os diagramas UML neste repositório refletem a estrutura desses sistemas:
- **Diagrama de Caso de Uso**: Mostra as interações dos atores (Fiel, Visitante e Administrador) com funcionalidades como visualizar agendas, gerenciar paróquias e sincronizar eventos.
- **Diagrama de Implantação**: Representa a infraestrutura física, incluindo Cliente Móvel, Amazon Route 53, API Gateway, EC2, RDS, SES e Segment, com conexões via HTTPS, HTTP e SQL.

## Participantes do Projeto

- **Gabriel de Carvalho Barros**
- **João Victor da Silva**
- **Henrique Melo Alves Martins**
- **Leticia Silverio**
- **Rennys Rodrigues Cardoso**
- **Vitor Roggeri Cavicchiolli**
