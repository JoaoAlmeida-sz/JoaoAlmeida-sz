# Olá, eu sou o João 👋

Gosto de transformar dados brutos em bases confiáveis e fáceis de usar. Neste GitHub, reúno projetos de engenharia de dados que vão da ingestão à camada pronta para análise e BI.

## Projetos

### [Carga de energia no Brasil | ONS](https://github.com/JoaoAlmeida-sz/pipeline-carga-energia-ons)

Dados públicos de carga diária por subsistema, organizados em um **esquema estrela** no Snowflake: dimensão de data, dimensão de subsistema e fato diária. Uma tabela mensal entrega médias em MWmed para os futuros dashboards.

O código inclui ingestão com validações e controle de revisões da fonte, modelos e testes em dbt e uma DAG diária no Airflow. **Estado atual:** o CSV de 2026 foi validado localmente; a execução completa no Snowflake e no Airflow está em validação.

[Ver arquitetura e código →](https://github.com/JoaoAlmeida-sz/pipeline-carga-energia-ons)

### [Olist | Pipeline de e-commerce](https://github.com/JoaoAlmeida-sz/olist-ecommerce-pipeline)

Uma pipeline sobre dados públicos do marketplace brasileiro Olist. O projeto carrega nove arquivos no Snowflake, organiza as transformações com dbt, aplica validações com Great Expectations e entrega views para análise no Power BI.

**Uma decisão de modelagem:** a tabela de pedidos mantém uma linha por pedido. Itens e pagamentos são agregados antes da junção para evitar duplicação de receita.

**Estado atual:** ingestão, modelos e testes executados; a DAG de Airflow/Astro está versionada, com execução local ainda pendente de WSL 2.

[Explorar o projeto e os resultados →](https://github.com/JoaoAlmeida-sz/olist-ecommerce-pipeline)

## Ferramentas dos projetos

Python · SQL · Snowflake · dbt · Airflow · Great Expectations · GitHub Actions

---

Cada repositório tem um objetivo claro, decisões de modelagem explicadas e dados preparados para consumo.
