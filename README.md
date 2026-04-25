# 🚀 Projeto: Apache Spark com Delta Lake e Apache Iceberg

Este repositório contém o trabalho de pesquisa de Arquitetura de Dados, demonstrando a criação e manipulação de dados transacionais (Lakehouse) utilizando Apache Spark, Delta Lake e Apache Iceberg em um ambiente Python local.

## 👥 Equipe
* Tiago Palacio
* Bruno Tescke
* Gabriel Tomé

## 🛠️ Tecnologias e Bibliotecas Utilizadas
* **Gerenciador de Pacotes:** `uv`
* **Linguagem:** Python 3.11
* **Processamento:** PySpark (v3.5.1)
* **Lakehouse:** Delta-Spark (v3.2.0) e PyIceberg
* **Documentação:** MkDocs (Material Theme)
* **IDE:** Visual Studio Code (com extensões Python e Jupyter)

## ⚙️ Como reproduzir o ambiente passo a passo

**1. Pré-requisitos:**
* Ter o Python 3.11 instalado.
* Ter o Java (OpenJDK 17) instalado (Necessário para o motor do Spark).
* Ter o gerenciador de pacotes `uv` instalado.

**2. Configuração do Projeto:**
Clone este repositório em sua máquina local e abra a pasta no VS Code. No terminal, execute o comando abaixo para instalar todas as dependências isoladas no ambiente virtual:
```bash
uv sync --python 3.11