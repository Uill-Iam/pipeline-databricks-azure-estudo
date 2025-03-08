# Desenvolvendo Pipeline com Data Factory 🚀

![Imagem do ETL construído com Data Factory Bronze, Silver e Gold](https://github.com/user-attachments/assets/7bd3d780-7f67-4784-a4be-7ebe115b622c)

## Badges
![Status](https://img.shields.io/badge/Status-Finalized-brightgreen)  
![Python](https://img.shields.io/badge/Python-3.8-blue)  
![Scala](https://img.shields.io/badge/Scala-2.12-red)  
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-3.0-orange)  
![Azure Databricks](https://img.shields.io/badge/Azure-Databricks-blue)  
![Azure Data Factory](https://img.shields.io/badge/Azure-Data%20Factory-blue)  
![Azure Data Lake](https://img.shields.io/badge/Azure-Data%20Lake-blue)  
![GitHub last commit](https://img.shields.io/github/last-commit/Uill-Iam/pipeline-databricks-azure-estudo)  
![License](https://img.shields.io/github/license/Uill-Iam/pipeline-databricks-azure-estudo)

---

## Índice
1. [Descrição do Projeto](#descrição-do-projeto)
2. [Status do Projeto](#status-do-projeto)
3. [Funcionalidades e Demonstração da Aplicação](#funcionalidades-e-demonstração-da-aplicação)
4. [Acesso ao Projeto](#acesso-ao-projeto)
5. [Tecnologias utilizadas](#tecnologias-utilizadas)
6. [Pessoas Desenvolvedoras do Projeto](#pessoas-desenvolvedoras-do-projeto)
7. [Licença](#licença)

---

## Descrição do Projeto
Este projeto tem como objetivo demonstrar a criação de um pipeline de dados utilizando a plataforma Azure, mais especificamente com o uso do **Azure Data Factory** para orquestrar os processos e **Azure Databricks** para a execução de transformações de dados. A estrutura segue o conceito de **ETL (Extract, Transform, Load)**, com três camadas de processamento de dados: **Bronze**, **Silver** e **Gold**.

Durante o curso, foram abordados os seguintes tópicos:
- Construção de um pipeline de Engenharia de Dados.
- Criação e estruturação de um Data Lake utilizando o **Azure Data Lake Storage Gen 2**.
- Configuração do **Databricks** com o serviço de Cloud da **Azure**.
- Desenvolvimento de notebooks no **Databricks** utilizando a linguagem **Scala**.
- Construção de pipelines utilizando o **Azure Data Factory**.
- Integração do projeto com o **GitHub** para versionamento.
- Definição de gatilhos de execução e colocação do pipeline em produção.

---

## Status do Projeto
✅ **Finalizado**  

O pipeline foi desenvolvido, testado e colocado em produção com sucesso.

---

## Funcionalidades e Demonstração da Aplicação
- **Extração de Dados (Bronze Layer):** Dados brutos são ingeridos do Azure Data Lake para a primeira camada de processamento.
- **Transformação (Silver Layer):** Dados são transformados e limpos usando **Databricks**.
- **Carregamento (Gold Layer):** Dados são carregados para o ambiente de produção, prontos para análise.
  
**Demonstração:**  
- A integração entre **Azure Data Factory** e **Databricks** é exemplificada com a construção de um pipeline automatizado.
- O fluxo de dados é monitorado por **Azure Data Factory**, com registros detalhados de execução.

---

## Acesso ao Projeto
Você pode acessar o repositório do projeto no GitHub [aqui](https://github.com/Uill-Iam/pipeline-databricks-azure-estudo).

---

## Tecnologias utilizadas
- **Azure Data Factory**
- **Azure Databricks**
- **Azure Data Lake Storage Gen 2**
- **Scala**
- **Apache Spark**
- **Python**

---

## Pessoas Desenvolvedoras do Projeto
- [Uiliiam Santos](https://github.com/Uill-Iam) - Desenvolvedor

---

## Licença
Este projeto está licenciado sob a **MIT License** - veja o arquivo [LICENSE](./LICENSE) para mais detalhes.
