### String Operators

*  **||**  Junta duas strings
      *  ```SELECT name || ' , ' || country FROM cities;``` 
*  **concat()** Junta duas strings
      *  ```SELECT CONTACT(name, ', ', country) AS location FROM cities``` 
*  **lower()** Retorna uma string em lower case
   *  ```SELECT LOWER(name) AS lower_names FROM cities;``` 
*  **length()** Retorna a quantidade de caracteres em uma string
   *  ```SELECT LENGTH(name) AS quantity_name FROM cities;``` 
*  **upper()** Retorna uma string em UPPER CASE
   *  ```SELECT UPPER(name) AS upper_names FROM cities;``` 