# power_bi_analyst

Repositório relacionado a formação de Power BI Analyst
1. Tabela department:

Criou-se a tabela chamada department com três colunas: id_department,

name_department e localização e eliminei as demais.


2. Tabela manager:

Criou-se a tabela chamada manager com colunas para informações de gerentes, que são id_manager, name_manager, sex, salario, endereco, telefone e fk id_department.


3. Tabela employee:

Criou-se a tabela employee com colunas para id_employee, name_employee, sex, salario,

endereco, telefone, fks id_projeto, id_department e id_manager.


4. Tabela dependent:

Havia um erro no comando CREATE TABLE, e o campo relationship foi adicionado com um valor nulo, foi feita a mudança para não aceitar esse tipo de valor.

Essa tabela recebeu as seguintes colunas name_dependent, sex, bdate, relationship. Fks id_employee e id_dependent


5. Tabela project:

Criou-se a tabela chamada project com uma coluna hours no formato TIME.

Essa tabela recebeu as seguintes colunas name_projeto, department, hours, fks id_projeto e id_manager.