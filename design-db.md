## Database Design Process (Top-Down)
* Que tipo de info estamos armazenando?
* Quais propriedades essa info tem? 
* Que tipo de dados cada propriedade contém? 

        Caso de Uso:
        1. Estamos armazenando uma lista de cidades
        2. Cada cidade tem um nome, país, população e area
        3. string, string, number, number

        Portanto teremos:
        1. Uma tabela que representa as cidades
        2. Uma coluna para cada propriedade (nome, país, população e area)
        3. Cada coluna terá um tipo de dado específico (string, string,     number, number)

