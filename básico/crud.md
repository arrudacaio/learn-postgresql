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

### Inserir múltiplos valores:
```sql 
    INSERT INTO cities (name, country, population, area) 
        VALUES('Sao Paulo', 'Brasil', 12000000, 6000000), ('Delphi', 'India', 25403262, 12540); 
```



### Criando colunas temporárias

No exemplo a seguir, o intuito é obter a informação da densidade populacional
de cada cidade, sem necessariamente criar uma coluna para essa informação.


```sql 
    SELECT name, population / area FROM cities; 
```

Dessa forma teremos a informação da densidade (população/area) mas não criamos uma nova coluna. 

Caso eu queira uma melhor visualização dessa informação, basta criar uma variável para o valor que estamos buscando. 

```sql 
    SELECT name, population / area AS density FROM cities; 
```

