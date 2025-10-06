# Projeto-FleetManager
Este projeto apresenta uma arquitetura serverless baseada em AWS para um sistema de gestão de frotas. Utilizamos serviços gerenciados para garantir escalabilidade, segurança e baixo custo operacional.
## 📐 Diagrama da Arquitetura

O diagrama abaixo representa o fluxo circular entre os componentes do sistema:

![Diagrama Serverless](images/arquitetura-serverless.png)

> O arquivo editável está disponível em `/drawio/arquitetura.drawio`

## 🧱 Componentes Utilizados

- **Clients**: Usuários acessam via navegador ou app mobile
- **API Gateway**: Recebe requisições HTTP e encaminha para Lambda
- **Lambda Function**: Processa lógica de negócios sem servidor
- **Amazon RDS**: Banco de dados relacional (MySQL/PostgreSQL)
- **Amazon S3**: Armazena documentos e imagens
- **IAM Roles**: Gerencia permissões entre serviços
- **CloudWatch / CloudTrail**: Monitoramento e auditoria
- **Frontend Web**: Interface administrativa e operacional

## 🚀 Como Reproduzir

1. Crie uma conta AWS
2. Configure API Gateway e Lambda
3. Implemente a função Lambda (`scripts/exemplo-lambda.js`)
4. Configure RDS e S3
5. Teste com Postman ou Insomnia

## 📂 Estrutura do Projeto

- `drawio/`: Diagrama editável
- `images/`: Capturas de tela
- `docs/`: Documentação técnica
- `scripts/`: Código de exemplo

## 📚 Referências

- [AWS Lambda](https://docs.aws.amazon.com/lambda/)
- [API Gateway](https://docs.aws.amazon.com/apigateway/)
- [Drawio Editor](https://draw.io)

