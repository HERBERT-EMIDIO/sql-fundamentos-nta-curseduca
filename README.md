# SQL Fundamentos — Instituto NTA / Curseduca

[![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Curseduca](https://img.shields.io/badge/Curseduca-Instituto%20NTA-0EA5E9)](https://institutonta.curseduca.pro/)

Caderno de **prática** da trilha SQL (Instituto NTA / Curseduca).

> Material de referência do curso: [TrilhaSQL](https://github.com/ckoliveiraa/TrilhaSQL) — prof. **Carlos Oliveira**.  
> Neste repositório ficam **minhas notas e minhas resoluções** (não é cópia do gabarito oficial).

---

## Objetivo

Acompanhar os 15 módulos da trilha, praticar no PostgreSQL e versionar a evolução no GitHub.

---

## Trilha de aprendizado (alinhada ao professor)

| # | Módulo | Foco |
|---|--------|------|
| 01 | [Introdução](01%20-%20Introdução/) | Ambiente, PostgreSQL, Render |
| 02 | [Fundamentos - SELECT](02%20-%20Fundamentos%20-%20SELECT/) | SELECT, FROM, ORDER BY, LIMIT |
| 03 | [Filtros Avançados](03%20-%20Filtros%20Avançados/) | WHERE, AND, OR, LIKE, IN, BETWEEN |
| 04 | [Funções de String](04%20-%20Funções%20de%20String/) | CONCAT, UPPER, LOWER, TRIM… |
| 05 | [Funções de Data](05%20-%20Funções%20de%20Data/) | DATE_PART, intervalos de data |
| 06 | [Conversão de Dados](06%20-%20Conversão%20de%20Dados/) | CAST, COALESCE |
| 07 | [Condicionais](07%20-%20Condicionais/) | CASE WHEN |
| 08 | [Funções de Agregação](08%20-%20Funções%20de%20Agregação/) | COUNT, SUM, AVG, MIN, MAX |
| 09 | [Agrupamento](09%20-%20Agrupamento/) | GROUP BY, HAVING |
| 10 | [JOINs](10%20-%20JOINs/) | INNER, LEFT, RIGHT, FULL |
| 11 | [Combinando Resultados](11%20-%20Combinando%20Resultados/) | UNION, INTERSECT, EXCEPT |
| 12 | [Subconsultas](12%20-%20Subconsultas/) | Subqueries, EXISTS, IN |
| 13 | [Window Functions](13%20-%20Window%20Functions/) | ROW_NUMBER, RANK, LAG, LEAD |
| 14 | [CTEs](14%20-%20CTEs/) | WITH |
| 15 | [Manipulação de Dados](15%20-%20Manipulação%20de%20Dados/) | CREATE, INSERT, UPDATE, DELETE |

---

## Estrutura de cada módulo

```text
XX - Nome do Módulo/
├── minhas_notas.md                  # resumo nas minhas palavras
├── desafios_aulas_resolucao.sql     # minha resolução dos desafios de aula
└── desafio_final_resolucao.sql      # minha resolução do desafio final
```

Teoria e gabaritos oficiais → repo do professor.  
Prática e erros/acertos → **este** repo.

---

## Fluxo de estudo

1. Assistir a aula no Curseduca  
2. Ler a teoria no [TrilhaSQL](https://github.com/ckoliveiraa/TrilhaSQL)  
3. Resolver sozinho e salvar neste repositório  
4. Comparar com o gabarito do professor  
5. `git add` → `git commit` → `git push`  

Exemplo de mensagem de commit:

```text
feat(02): resolve desafios SELECT
```

---

## Banco de dados

Exercícios usam o modelo de **e-commerce** da trilha (categorias, produtos, clientes, pedidos, etc.).  
Anotações: [`docs/banco-ecommerce.md`](docs/banco-ecommerce.md).

---

## Créditos

- Trilha e materiais: [ckoliveiraa/TrilhaSQL](https://github.com/ckoliveiraa/TrilhaSQL) — Carlos Oliveira  
- Práticas e resoluções: Herbert Emidio  

[GitHub](https://github.com/HERBERT-EMIDIO) · [LinkedIn](https://www.linkedin.com/in/herbertemidio/)
