**Como é uma Estrutura Básica de uma Tabela**

A estrutura básica de uma tabela em um banco de dados relacional é composta por **colunas** e **linhas** (ou registros), onde cada coluna define um tipo de dado e cada linha contém valores específicos para essas colunas. Aqui estão os principais componentes:

### 1. **Nome da Tabela**
Cada tabela tem um nome único no banco de dados, que a identifica.

### 2. **Colunas (Campos)**
As colunas representam os diferentes atributos ou categorias de dados que a tabela irá armazenar. Cada coluna tem:
- **Nome da Coluna**: O identificador do campo.
- **Tipo de Dado**: Define o tipo de valor que pode ser armazenado, como texto (`VARCHAR`), números (`INT`, `DECIMAL`), datas (`DATE`), etc.
- **Restrições (opcional)**: Regras aplicadas aos dados da coluna, como:
  - **NOT NULL**: Garante que o campo não possa ser vazio.
  - **UNIQUE**: Garante que todos os valores da coluna sejam únicos.
  - **PRIMARY KEY**: Define a coluna como identificador único de cada linha.

### 3. **Linhas (Registros)**
As linhas representam os dados reais na tabela. Cada linha é um registro único que armazena valores para cada coluna. 

### Exemplo Simples de Estrutura

Imagine uma tabela chamada `clientes` que armazena informações de clientes de uma loja:

| id   | nome      | email             | idade | data_cadastro |
|------|-----------|-------------------|-------|---------------|
| 1    | João      | joao@email.com     | 25    | 2023-01-15    |
| 2    | Maria     | maria@email.com    | 30    | 2023-02-10    |
| 3    | Pedro     | pedro@email.com    | 22    | 2023-03-20    |

### Componentes da Tabela:
- **id**: É a coluna de chave primária (PRIMARY KEY), que identifica cada cliente de forma única. Tipo `INT`.
- **nome**: Armazena o nome do cliente. Tipo `VARCHAR`.
- **email**: Armazena o endereço de email do cliente. Tipo `VARCHAR`.
- **idade**: Armazena a idade do cliente. Tipo `INT`.
- **data_cadastro**: Armazena a data em que o cliente foi cadastrado. Tipo `DATE`.

### Resumo
- **Colunas** definem os tipos de dados e suas regras.
- **Linhas** contêm os valores reais dos dados.
Uma tabela bem estruturada facilita o armazenamento e a recuperação eficiente das informações!
