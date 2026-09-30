# 📊 Projeto 1: Mapeamento de Mercado (Market Mapping)
## Escopo: Engenharia de Dados (Pleno a Sênior) – Brasil

Este projeto demonstra a aplicação de inteligência de mercado e sourcing estratégico para mapear profissionais de dados, identificando tendências de contratação, preferências contratuais e distribuição geográfica sem violar as diretrizes da LGPD.

### 🔍 1. Engenharia de Busca (X-Ray Search)
Sintaxe avançada utilizada no Google para mapear perfis públicos do LinkedIn, contornando limitações comerciais de filtros da plataforma:

```text
site:://linkedin.com ("Engenheiro de Dados" OR "Data Engineer") "Python" ("AWS" OR "S3") -Junior -Júnior -Estagiario -Estagiário -Intern -Trainee
```

### 📈 2. Indicadores Estratégicos Extraídos (Amostragem: 15 Profissionais Reais)

* **Distribuição Geográfica:** 
  * São Paulo: 33% | Curitiba/Paraná: 20% | Manaus: 13% | Outras Regiões (RJ, BSB, Recife, TO, Pará): 34%.
  * *Insight de Negócio:* O mercado é altamente descentralizado. Restringir buscas geograficamente estrangula o funil de contratação.

* **Cultura e Modelo de Trabalho Dominante:**
  * 100% Remoto: 63% | Híbrido Flexível: 27% | Presencial Rígido: 10%.
  * *Insight de Negócio:* Profissionais seniores priorizam regimes remotos. Ofertas presenciais exigem orçamentos salariais acima da média de mercado para compensar o deslocamento.

* **Tempo Médio de Casa (Tenure):**
  * A média de permanência identificada na empresa atual é de **29 meses** (~2,4 anos).
  * *Insight de Negócio:* Profissionais que ultrapassam a barreira dos 24 meses entram na "janela ideal de abordagem", demonstrando maior propensão a avaliar propostas de Headhunting.

* **Ecossistema Técnico Satélite:**
  * Além de Python e AWS, as ferramentas mais citadas nos perfis foram: **SQL, Apache Spark (PySpark), Databricks, Airflow e Snowflake**.
