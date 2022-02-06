# **<<< Codificando em SQL >>>**

**COMENTÁRIO**
Use o hífen duas vezes ou hashtag para fazer um comentário
**Exemplo:**
`-- Isso é um comentário`
`# Isso é um comentário`

Para comentar um intervalo de linhas use " barra/asterisco* "
**Exemplo:**
```
/*Isso
é um
comentário*/
```

### SELECT
**Selecionar todas as colunas e linhas de uma tabela** _(SELECT *)_
`SELECT * FROM Tabela_Escolhida;`

**Selecionar colunas específicas** _(SELECT FROM)_
`SELECT Col1, Col2 FROM Tabela_Escolhida;`

**Selecionar colunas específicas de _DAR NOMES_ a elas** _(AS)_
`SELECT Col1 AS "Coluna1", Col2 AS "Coluna2" FROM Tabela_Escolhida;`

**Selecionar N primeiras linhas** _(LIMIT)_
`SELECT * FROM Tabela_Escolhida LIMIT 2;`

**Ordenar uma tabela a partir de uma determinada coluna** _(ORDER BY)_
`SELECT * FROM Tabela_Escolhida ORDER BY Col1 ASC ou DESC;`
_ASC: do menor para o Maior_
_DESC: do Maior para o menor_
