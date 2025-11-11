# Imersão databricks

### Supabase
Antes de partir para o databricks, fizemos ingestão de dados no supabase. Lá tem um cron que ingere a cada minuto dados fakes nas tabelas.

### Fivetran
Faz a ingestão de dados sem usar python.
Dentro do databricks criamos uma nova ingestão Postgres e somos redirecionados para o Fivetran, conta gratuita.

### Erathos
Ferramenta de ingestão de dados entre banco e databricks. A única empresa brasileira certificada pela databricks.
Substitui o papel da Fivetran.
Fazer teste posteriormente.

### Databricks
* Criação Catalog *lakehouse*
* Criação das tabelas: *usando notebook*
* Criação das tabelas via api (bitcoin e yahoo finance): *usando notebook*
* Criação de Jobs
* Criação de Pipeline Lakeflow (tabelas para camada bronze, silver e gold)
