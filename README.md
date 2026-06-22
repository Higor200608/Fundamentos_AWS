# Fundamentos AWS

Este repositório tem como objetivo registrar e praticar meus conhecimentos relacionados à nuvem AWS, explorando seus fundamentos e principais serviços, tais como: **EC2, AWS Lambda, S3, RDS, EBS, IAM**, entre outros.

O cronograma de estudos e práticas está dividido nos módulos abaixo:

---

## Módulos de Estudo

### 1. Introdução à AWS e Conceitos Básicos
Nas primeiras semanas, explorei a definição de Cloud Computing e o papel das principais *Cloud Providers* do mercado (AWS, Azure e GCP). 

* **Modelos de Serviço:** Compreensão das diferenças práticas entre **IaaS** (Infraestrutura como Serviço), **PaaS** (Plataforma como Serviço) e **SaaS** (Software como Serviço), bem como a divisão de responsabilidades entre o provedor e o usuário final.
* **Segurança e IAM:** 
    * Gerenciamento de acessos, criação de usuários, grupos e políticas de permissões.
    * Entendimento das boas práticas de segurança, como o princípio do menor privilégio, a importância de **não utilizar a conta Root** no dia a dia e a obrigatoriedade da autenticação multifator (**MFA**).

### 2. Computação na Nuvem com EC2 & Armazenamento
Foco na camada de computação e persistência de dados.

* **Amazon EC2:** Entendimento do conceito de instâncias e como o EC2 entrega capacidade computacional escalável (Máquinas Virtuais) na nuvem.
* **EBS vs S3 (Estratégias de Armazenamento):**
    * **Amazon EBS:** Armazenamento em blocos, de alta performance, ideal para o sistema operacional e volumes anexados diretamente à instância EC2.
    * **Amazon S3:** Armazenamento de objetos, altamente escalável e durável, utilizado para arquivos estáticos, logs e backups.
