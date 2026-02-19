# ☁️ AWS + Docker + PostgreSQL Lab

## 📌 Visão Geral

Este laboratório simula a criação de uma infraestrutura em nuvem utilizando AWS, com provisionamento de instância Linux, instalação do Docker e deploy de um banco de dados PostgreSQL em container.

O objetivo é demonstrar habilidades práticas em infraestrutura cloud, redes e administração de banco de dados.

---

## 🎯 Objetivos do Projeto

- Criar infraestrutura básica na AWS
- Configurar ambiente Linux
- Instalar e configurar Docker
- Subir container PostgreSQL
- Aplicar boas práticas de segurança

---

## 🏗 Arquitetura

## 📊 Cenário Simulado

Empresa fictícia necessitando de:
- Servidor de banco de dados
- Ambiente containerizado
- Controle de acesso externo
- Separação de responsabilidades de rede


Infraestrutura composta por:

- VPC personalizada
- Subnet pública
- Instância EC2 (Linux)
- Docker Engine instalado
- Container PostgreSQL
- Security Group configurado

---

## 🛠 Tecnologias Utilizadas

- AWS EC2
- Linux
- Docker
- PostgreSQL
- Bash

---

## 📂 Estrutura do Projeto


---

## ⚙️ Etapas Realizadas

1. Criação da instância EC2
2. Acesso via SSH
3. Instalação do Docker
4. Pull da imagem PostgreSQL
5. Criação e execução do container
6. Teste de conexão ao banco

---

## 🔐 Segurança Aplicada

- Acesso SSH restrito
- Porta 5432 controlada via Security Group
- Uso de variáveis de ambiente para senha do banco

---

## 🧠 Aprendizados

- Provisionamento manual de infraestrutura
- Administração de containers
- Configuração básica de rede na AWS
- Gerenciamento de banco em ambiente Linux

---

## 🚀 Próximos Passos

- Automatizar com Terraform
- Implementar monitoramento
- Criar backup automatizado
- Separar banco em subnet privada

---

## 🎓 Competências Desenvolvidas com EC2

Durante a criação e gerenciamento da instância EC2, foram aplicados os seguintes conceitos:

- Provisionamento de servidor web com proteção contra encerramento ativada
- Monitoramento da instância utilizando métricas do Amazon CloudWatch
- Configuração e modificação de Security Groups para liberação de acesso HTTP (porta 80)
- Redimensionamento (Change Instance Type) conforme necessidade de recursos
- Teste prático da funcionalidade de proteção contra encerramento
- Encerramento seguro da instância após validação do ambiente

## 🔄 Gestão do Ciclo de Vida da Instância

Neste laboratório foram aplicadas práticas reais de administração de infraestrutura, incluindo:

- Criação
- Monitoramento
- Alteração de configuração
- Escalonamento vertical
- Controle de segurança
- Encerramento controlado

Simulando um cenário corporativo de gestão de servidores em nuvem.


---

## 👨‍💻 Autor

Jacson Silva  
Infraestrutura Cloud | Linux | Docker | PostgreSQL

