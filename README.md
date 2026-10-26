📈 Gerenciamento de Vendas
Consultas SQL e padronização de dados de vendas, pensadas para quem trabalha com documentos e precisa de informação organizada.
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
Sobre o projeto
Organizar e padronizar dados sempre foi essencial para quem trabalha com documentos. Este projeto reúne a estrutura e as consultas SQL para acompanhar [vendas, clientes, produtos — ajuste para o seu caso].

Modelo de dados
Tabela	Descrição
`[tabela_1]`	[o que armazena]
`[tabela_2]`	[o que armazena]

Exemplos de consultas
```sql
-- Exemplo: total vendido por mês
SELECT [mes], SUM([valor]) AS total
FROM [vendas]
GROUP BY [mes]
ORDER BY [mes];
```
Como usar
Abra seu SGBD ([MySQL / PostgreSQL / SQLite — ajuste]).
Execute `sql/criacao.sql` para criar as tabelas.
Execute `sql/dados.sql` para inserir dados de exemplo.
Rode as consultas de `sql/consultas.sql`.

```
👤 Autor
Arthur Ricardo — @arthurrickss (linkedin)
