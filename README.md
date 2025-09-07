# Bootcamp realizado em parceria com o Santander, AWS e Dio
Este laboratório tem como objetivo consolidar meus conhecimentos em gerenciamento de instâncias EC2 na AWS. 

# Fundamentos da AWS ☁️

Este repositório tem como objetivo apresentar os principais fundamentos da **Amazon Web Services (AWS)**, a compreender os conceitos básicos e os principais serviços oferecidos pela nuvem da AWS.

---

## 📌 O que é a AWS?

A **Amazon Web Services (AWS)** é a maior provedora de computação em nuvem do mundo, oferecendo serviços sob demanda como:
- **Computação** (servidores virtuais, containers, serverless)
- **Armazenamento** (blobs, arquivos, bancos de dados)
- **Redes e entrega de conteúdo**
- **Segurança, monitoramento e ferramentas de gestão**

O modelo de cobrança: **você paga apenas pelo que utilizar.**

---

## 🏗️ Conceitos Fundamentais

### ☁️ Regiões e Zonas de Disponibilidade
- **Regiões**: Áreas geográficas (ex: `us-east-1`, `sa-east-1`).
- **Zonas de Disponibilidade (AZs)**: Datacenters isolados dentro de uma região.


### 🔐 Responsabilidade Compartilhada
- **AWS**: Responsável pela segurança da nuvem (infraestrutura, hardware, rede).
- **Cliente**: Responsável pela segurança **na nuvem** (configuração, dados, permissões).

### 💰 Modelo de Preços
- **On-Demand**: paga pelo uso (sem contrato).
- **Reserved Instances**: reserva de longo prazo com desconto.
- **Spot Instances**: uso de capacidade ociosa com desconto maior.

---

## 🚀 Principais Serviços

### 🔹 Computação
- **EC2**: Máquinas virtuais escaláveis.
- **Lambda**: Funções serverless.
- **ECS / EKS**: Containers gerenciados.

### 🔹 Armazenamento
- **S3**: Armazenamento de objetos.
- **EBS**: Volumes de armazenamento para EC2.
- **Glacier**: Arquivamento de longo prazo.

### 🔹 Banco de Dados
- **RDS**: Banco de dados relacional gerenciado.
- **DynamoDB**: Banco de dados NoSQL totalmente gerenciado.
- **Aurora**: Banco de dados compatível com MySQL/PostgreSQL, otimizado para nuvem.

### 🔹 Redes
- **VPC**: Rede virtual privada.
- **Route 53**: DNS e roteamento.
- **CloudFront**: CDN para entrega de conteúdo.

### 🔹 Segurança e Identidade
- **IAM**: Gerenciamento de usuários e permissões.
- **KMS**: Gerenciamento de chaves de criptografia.
- **WAF**: Firewall de aplicações web.

### 🔹 Monitoramento e Gestão
- **CloudWatch**: Monitoramento de métricas e logs.
- **CloudTrail**: Registro de auditoria das ações na conta.
- **Config**: Conformidade e governança.

---

## 📚 Melhores Práticas
- Organizar permissões com **IAM** (princípio do menor privilégio).
- Usar **MFA (Multi-Factor Authentication)** na conta root.
- Configurar **tags** para organizar recursos.
- Monitorar gastos com **AWS Cost Explorer**.
- Sempre pensar em **alta disponibilidade** e **escalabilidade**.

---

## 📖 Referências
- [Documentação Oficial da AWS](https://docs.aws.amazon.com/)
- [AWS Training and Certification](https://aws.amazon.com/training/)
- [Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/)

---

Feito com ☁️ para quem quer começar sua jornada na nuvem com a AWS.

