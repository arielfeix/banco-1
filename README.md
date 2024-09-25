# Trabalho Banco De Dados

## Olá, meu nome é Ariel e este é o meu primeiro projeto envolvendo banco de dados, o qual consiste em códigos simples.


```sql
create table cliente (
id_cliente int primary key,
nome_cliente varchar(100),
email_cliente varchar(100),
data_nascimento date,
telefone_cliente varchar(15)
);
```

```sql
create table produto (
id_produto int primary key,
nome_produto varchar(100),
preco_produto decimal(8,2)
);
```

```sql
create table fatura (
id_fatura int primary key,
data_criacao date,
valor_fatura decimal(10,2)
);
```