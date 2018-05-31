Corso BD2 - A.A 2017-2018 - Simone Pellegrini

Progettazione e realizzazione di un Data Warehouse sulla carriera degli studenti utilizzando dati provenienti dalla banca dati ANVUR.

Per conoscere i requisiti e le specifiche del progetto, leggere il seguente [file](https://github.com/spellegrini1995/MyFirstDWSystem/blob/master/extra/dwh_ava_requisiti_20180517.pdf).

I file [tabelle_sql_dwh](https://github.com/spellegrini1995/MyFirstDWSystem/blob/master/sql/tabelle_sql_dwh) e [tabelle_sql_ods](https://github.com/spellegrini1995/MyFirstDWSystem/blob/master/sql/tabelle_sql_dwh) servono per creare rispettivamente le tabelle del DataWarehouse (dimensioni e fact table) e le tabelle dell'ODS.

La trasformazione [csvTodb.ktr](https://github.com/spellegrini1995/MyFirstDWSystem/blob/master/etl/csvTodb.ktr) serve per popolare le tabelle dell'Operational Data Store (ODS) a partire da file CSV forniti dal minister (ANVUR). 
I file CSV non sono presenti in questa repository per rispettare la privacy.





