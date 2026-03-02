# 🚀 Pesquisa: Bancos de Dados Não-Relacionais (NoSQL)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![NoSQL](https://img.shields.io/badge/NoSQL-Data-green?style=for-the-badge&logo=mongodb)

---

## 📌 Sobre o Projeto

[cite_start]Este projeto apresenta uma análise teórica e prática sobre o ecossistema de bancos de dados não-relacionais (NoSQL)[cite: 29]. 

[cite_start]O objetivo é explorar as características que definem essa tecnologia, como a liberdade de esquema [cite: 1, 2] [cite_start]e a alta escalabilidade[cite: 4], comparando-a com o modelo relacional tradicional.

---

## 🛠️ Conceitos Explorados

- [cite_start]**Definição:** Diferenças entre esquemas rígidos (SQL) e flexíveis (NoSQL)[cite: 2].
- [cite_start]**Vantagens:** Alta velocidade de leitura/escrita e escalabilidade horizontal[cite: 4, 20].
- [cite_start]**Tipos de Bancos:** Documentos, Chave-Valor, Colunas Amplas e Grafos[cite: 9, 11, 12, 13].
- [cite_start]**Casos de Uso:** Aplicações reais em redes sociais e plataformas de streaming (Netflix)[cite: 18, 25].

---

## 📂 Estrutura de Tipos e Ferramentas

| Tipo | Característica Principal | Ferramentas Populares |
| :--- | :--- | :--- |
| **Documentos** | [cite_start]Dados salvos como JSON; intuitivo para devs[cite: 9, 10]. | [cite_start]MongoDB, CouchDB [cite: 10] |
| **Chave-Valor** | [cite_start]Dicionário simples e extremamente rápido[cite: 11]. | [cite_start]Redis, DynamoDB [cite: 12] |
| **Colunas Amplas** | [cite_start]Foco em colunas para análise de Big Data[cite: 12, 13]. | [cite_start]Cassandra, HBase [cite: 13] |
| **Grafos** | [cite_start]Focado em nós e conexões (relacionamentos)[cite: 13, 14]. | [cite_start]Neo4j, ArangoDB [cite: 14] |

---

## ⚙️ Comparação e Prática

### 1️⃣ Modelo de Grafos vs Relacional
[cite_start]Enquanto o relacional exige tabelas intermediárias, o modelo de Grafos trata o vínculo como parte essencial do dado[cite: 15, 16]. [cite_start]É a diferença entre uma lista estática e um mapa de conexões[cite: 17].

### 2️⃣ Escalabilidade Horizontal
[cite_start]Em vez de um servidor gigante, o NoSQL permite adicionar vários servidores pequenos para distribuir os dados[cite: 20, 21].

### 3️⃣ Flexibilidade de Schema
[cite_start]Permite alterar a estrutura dos dados (como adicionar um campo "LinkedIn") sem precisar interromper o sistema ou alterar toda a tabela[cite: 22, 23, 24].

---

## 🎬 Estudo de Caso: Netflix

[cite_start]A Netflix utiliza o **Cassandra** (Colunas Amplas) para garantir disponibilidade total[cite: 25, 27].
- [cite_start]**Uso:** Histórico de visualização e notas em tempo real para milhões de usuários[cite: 26].
- [cite_start]**Benefício:** Replicação de dados que evita erros de sistema fora do ar ao dar o "play"[cite: 27, 28].

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
[cite_start]**FATESG / SENAI** [cite: 50, 52]  
2026
