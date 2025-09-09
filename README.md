📌 Gerenciamento de Instâncias EC2 na AWS

Este repositório tem como objetivo consolidar os conhecimentos sobre o Amazon EC2 (Elastic Compute Cloud), abordando conceitos fundamentais, boas práticas e comandos úteis para administração de instâncias na AWS.

📖 Índice

Sobre

Conceitos Principais

Boas Práticas

Comandos Úteis

Exemplo de Fluxo de Trabalho

Recursos e Documentação

💡 Sobre

O Amazon EC2 fornece capacidade de computação escalável na nuvem da AWS.
Com ele, é possível:

Lançar e gerenciar servidores virtuais (“instâncias”);

Escolher sistemas operacionais, CPU, memória e armazenamento;

Aumentar ou reduzir a capacidade sob demanda;

Integrar-se a outros serviços da AWS (S3, RDS, VPC, etc.).

🗂 Conceitos Principais

AMI (Amazon Machine Image): imagem usada para iniciar instâncias.

Tipos de instância: otimizadas para computação, memória ou armazenamento.

Security Groups: firewall virtual que controla tráfego de entrada/saída.


✅ Boas Práticas

Utilizar tags para identificar instâncias e facilitar a organização.

Restringir acessos em Security Groups (permitir apenas portas necessárias).

Utilizar IAM Roles ao invés de armazenar credenciais na instância.

Criar Snapshots regulares para backup de volumes EBS.

Encerrar ou parar instâncias não utilizadas para evitar custos.

🖥️ Comandos Úteis

Gerenciar instâncias via AWS CLI:
# Listar instâncias
aws ec2 describe-instances

# Iniciar instância
aws ec2 start-instances --instance-ids i-1234567890abcdef0

# Parar instância
aws ec2 stop-instances --instance-ids i-1234567890abcdef0

# Encerrar instância
aws ec2 terminate-instances --instance-ids i-1234567890abcdef0

🚀 Exemplo de Fluxo de Trabalho

Criar uma instância EC2 usando uma AMI.

Acessar a aplicação pelo navegador utilizando o IP público.

Criar um snapshot do volume EBS para backup.

📚 Recursos e Documentação

Documentação Oficial EC2

AWS CLI Reference

Melhores práticas de segurança na AWS

👉 Esse README pode servir tanto como guia de estudo quanto documentação de um repositório de exemplos práticos.
