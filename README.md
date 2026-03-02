# 🚀 Pesquisa: Bancos de Dados Não-Relacionais (NoSQL)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![NoSQL](https://img.shields.io/badge/NoSQL-Data-green?style=for-the-badge&logo=mongodb)

---

## 📌 Sobre o Projeto

Este projeto apresenta uma análise teórica e prática sobre o ecossistema de bancos de dados não-relacionais (NoSQL). 

O objetivo é explorar as características que definem essa tecnologia, como a liberdade de esquema e a alta escalabilidade, comparando-a com o modelo relacional tradicional.

---

## 🛠️ Conceitos Explorados

- **Definição:** Diferenças entre esquemas rígidos (SQL) e flexíveis (NoSQL).
- **Vantagens:** Alta velocidade de leitura/escrita e escalabilidade horizontal].
- **Tipos de Bancos:** Documentos, Chave-Valor, Colunas Amplas e Grafos.
- **Casos de Uso:** Aplicações reais em redes sociais e plataformas de streaming (Netflix).

---

## 📂 Estrutura de Tipos e Ferramentas

| Tipo | Característica Principal | Ferramentas Populares |
| :--- | :--- | :--- |
| **Documentos** | Dados salvos como JSON; intuitivo para devs. | MongoDB, CouchDB  |
| **Chave-Valor** | Dicionário simples e extremamente rápido. | Redis, DynamoDB  |
| **Colunas Amplas** | Foco em colunas para análise de Big Data. | Cassandra, HBase  |
| **Grafos** | Focado em nós e conexões (relacionamentos). | Neo4j, ArangoDB  |

---

## ⚙️ Comparação e Prática

### 1️⃣ Modelo de Grafos vs Relacional
Enquanto o relacional exige tabelas intermediárias, o modelo de Grafos trata o vínculo como parte essencial do dado. É a diferença entre uma lista estática e um mapa de conexões.

### 2️⃣ Escalabilidade Horizontal
Em vez de um servidor gigante, o NoSQL permite adicionar vários servidores pequenos para distribuir os dados.

### 3️⃣ Flexibilidade de Schema
Permite alterar a estrutura dos dados (como adicionar um campo "LinkedIn") sem precisar interromper o sistema ou alterar toda a tabela.

---

## 🎬 Estudo de Caso: Netflix

A Netflix utiliza o **Cassandra** (Colunas Amplas) para garantir disponibilidade total.
- **Uso:** Histórico de visualização e notas em tempo real para milhões de usuários.
- **Benefício:** Replicação de dados que evita erros de sistema fora do ar ao dar o "play".

---

## 📚 Objetivo Acadêmico

Este material demonstra conhecimentos em:
- Arquitetura de dados moderna.
- Diferenciação entre modelos de persistência.
- Análise de escalabilidade para grandes volumes de dados.
- Pesquisa técnica e estruturação de documentação.

---

## 👨‍💻 Autor

**Felipe Mendonça** Inteligência Artificial / Banco de Dados Não Relacional  
**FATESG / SENAI**   
2026
