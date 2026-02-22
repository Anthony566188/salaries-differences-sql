# 📊 Salaries Differences – StrataScratch (MySQL)

Este repositório contém a resolução do exercício **"Salaries Differences"** da plataforma StrataScratch.

🔗 Link do desafio:  
https://platform.stratascratch.com/coding/10308-salaries-differences  

---

## 🎯 Objetivo

Calcular a diferença entre os **maiores salários** dos departamentos de:

- Marketing  
- Engenharia  

### 🔎 Exercício adicional

Foi desenvolvido um exercício complementar (não presente na plataforma):

- Calcular a **média salarial** dos departamentos de:
  - Vendas  
  - Engenharia  

---

## 🗂 Estrutura das Tabelas

### `db_employee`

| Coluna         | Tipo   |
|---------------|--------|
| department_id | bigint |
| first_name    | text   |
| id            | bigint |
| last_name     | text   |
| salary        | bigint |

### `db_dept`

| Coluna     | Tipo   |
|------------|--------|
| department | text   |
| id         | bigint |

---

## 🧠 Conceitos e Recursos Utilizados

- `JOIN`
- `WHERE`
- `IN`
- `CASE WHEN`
- `MAX()`
- `AVG()`
- Funções de agregação
- Agregações condicionais
- Filtragem por departamento

---

## 📈 Resultados

- Diferença entre o maior salário de Marketing e Engenharia  
- Média salarial de Vendas e Engenharia (exercício adicional)

