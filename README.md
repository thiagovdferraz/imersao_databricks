# Imersão databricks

### Supabase
Antes de partir para o databricks, fizemos ingestão de dados no supabase. Lá tem um cron que ingere a cada minuto dados fakes nas tabelas.

### Fivetran
Faz a ingestão de dados sem usar python.
Dentro do databricks criamos uma nova ingestão Postgres e somos redirecionados para o Fivetran, conta gratuita.

### Databricks
* Criação Catalog *lakehouse*
* Criação das tabelas: *usando notebook*
* Criação das tabelas via api (bitcoin e yahoo finance): *usando notebook*
* Criação de Jobs
* Criação de Pipeline Lakeflow (tabelas para camada bronze)
