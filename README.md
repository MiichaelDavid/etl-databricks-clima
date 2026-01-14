# Pipeline de Engenharia de Dados - Monitoramento Climático 🌦️

Projeto de ETL desenvolvido no Databricks para monitorar o clima das capitais brasileiras em tempo real.

## 🛠️ Tecnologias Utilizadas
- **Databricks (Community Edition)**
- **Python (PySpark & Requests)**
- **Delta Lake** (Armazenamento)
- **SQL** (Visualização e Analytics)
- **OpenWeatherMap API** (Fonte de dados)

## 🚀 Como funciona
1. **Extração:** Script Python coleta dados de 27 capitais via API.
2. **Transformação:** Tratamento de JSON aninhado e conversão para Spark DataFrame.
3. **Carga:** Salvamento em tabela Delta com suporte a Schema Evolution.
4. **Visualização:** Dashboard com mapa de calor das temperaturas.

## 📈 Resultado
Os dados são atualizados diariamente e permitem análise de tendências climáticas no Brasil.