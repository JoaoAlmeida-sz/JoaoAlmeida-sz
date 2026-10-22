# Olá, eu sou o João 👋

Gosto de transformar dados brutos em bases confiáveis e fáceis de usar. Neste GitHub, reúno projetos de engenharia de dados que vão da ingestão à camada pronta para análise e BI.

## Projeto em destaque

### [Olist | Pipeline de e-commerce](https://github.com/JoaoAlmeida-sz/olist-ecommerce-pipeline)

Uma pipeline sobre dados públicos do marketplace brasileiro Olist. O projeto carrega nove arquivos no Snowflake, organiza as transformações com dbt, aplica validações com Great Expectations e entrega views para análise no Power BI.

**Uma decisão de modelagem:** a tabela de pedidos mantém uma linha por pedido. Itens e pagamentos são agregados antes da junção para evitar duplicação de receita.

**Estado atual:** ingestão, modelos e testes executados; a DAG de Airflow/Astro está versionada, com execução local ainda pendente de WSL 2.

[Explorar o projeto e os resultados →](https://github.com/JoaoAlmeida-sz/olist-ecommerce-pipeline)

## Ferramentas presentes no projeto

Python · SQL · Snowflake · dbt · Great Expectations · Airflow/Astro · GitHub Actions

---

Cada repositório terá um objetivo claro, decisões de modelagem explicadas e dados preparados para consumo. Conforme novos projetos forem validados, eles aparecerão aqui.
