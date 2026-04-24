# 🚀 Apache Spark + Delta Lake + Iceberg

[![MkDocs](https://img.shields.io/badge/MkDocs-Documentation-blue?logo=github)](https://viniciusmilanez.github.io/trabalho-spark-engdados/)
[![Python](https://img.shields.io/badge/Python-3.11-green)](https://python.org)
[![PySpark](https://img.shields.io/badge/PySpark-3.5-orange)](https://spark.apache.org)
[![Delta](https://img.shields.io/badge/Delta-3.2-purple)](https://delta.io)

---

## 🎯 Objetivo

Este projeto tem como objetivo demonstrar, de forma prática, conceitos modernos de **engenharia de dados** utilizando tecnologias amplamente adotadas no mercado.

A proposta é simular um ambiente de **Data Lakehouse**, explorando operações fundamentais em tabelas analíticas modernas.

**Demonstração prática:** INSERT / UPDATE / DELETE / Time Travel

---

## 💻 Ambiente de Desenvolvimento
O projeto foi desenvolvido utilizando WSL (Windows Subsystem for Linux) com Ubuntu, permitindo a execução de um ambiente Linux diretamente no Windows. 

Essa configuração facilitou a instalação e execução das dependências do ecossistema de engenharia de dados.

---

## 🔥 Principais Features

- ✅ INSERT em tabelas versionadas  
- 🔄 UPDATE com controle de estado  
- ❌ DELETE com consistência ACID  
- 🕒 Time Travel (consulta histórica de dados)

---

## 🧱 Arquitetura do Projeto

- ├── data/ # Dados de entrada e testes
- ├── docs/ # Documentação com MkDocs
- ├── notebooks/ # Experimentos e análises com Spark
- ├── .gitignore
- ├── LICENSE
- ├── README.md
- ├── mkdocs.yml
- └── pyproject.toml # Gerenciamento de dependências com Poetry


---

## ⚙️ Stack Tecnológica

- 🐍 Python 3.11  
- ⚡ Apache Spark (PySpark 3.5)  
- 🧊 Delta Lake 3.2  
- 🧊 Apache Iceberg  
- 📦 Poetry  
- 📓 Jupyter Lab  
- 📚 MkDocs  

---

## 🛠️ Instalação

O primeiro passo seria clonar o repositório em seu vscode


```bash
git clone https://github.com/viniciusmilanez/trabalho-spark-engdados.git
```

Posteriormente no terminal instalar as dependências do poetry e posteriormente executar o ambiente do poetry


```bash
poetry install && poetry shell
```

E por fim rodar o jupyter para executar os comandos do delta lake e iceberg


```bash
poetry run jupyter lab
```

## 📚 Mkdocs

Caso queira analisar a documentação do projeto feita em mkdocs, basta acessar o link abaixo

[Documentação do projeto](https://viniciusmilanez.github.io/trabalho-spark-engdados/)

## 👥 Integrantes
- Joao Vitor de Oliveira
- Luiz Fillipy Vefago Binatti
- Vinicius Pedroso Milanez

Referências

https://www.youtube.com/watch?v=2ubkqLY-cbE
