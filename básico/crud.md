## Para criarmos uma tabela

```sql
    CREATE TABLE IF NOT EXISTS cities (
        name VARCHAR(50), 
        country VARCHAR(50),
        population INTEGER, 
        area INTEGER
    );
``` 
*Sempre usar letras minúsculas para nomear as tabelas.*


</br>


## Para inserirmos valores na tabela:


```sql 
    INSERT INTO cities (name, country, population, area) VALUES('Sao Paulo', 'Brasil', 12000000, 6000000); 
```
*Sempre usar aspas simples (single quotes).*
