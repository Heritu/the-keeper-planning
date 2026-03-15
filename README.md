# 🛡️ The Keeper - Sistema de Gestão Financeira

## 📝 Contexto e Objetivos
Este repositório documenta a fase de planejamento e estruturação do projeto **The Keeper**, um sistema web funcional para gerenciamento de saldo e controle de gastos informais. O projeto integra o currículo de TADS (Tecnologia em Análise e Desenvolvimento de Sistemas).

**Objetivos de Estudo:**
* Utilizar o NotebookLM para validar a lógica do "Simulador de Compras" (análise preditiva).
* Organizar os requisitos técnicos (React.js, Node.js, SQLite) de forma estruturada.
* Documentar o fluxo de planejamento para garantir maturidade técnica no desenvolvimento.

---

## 📚 Curadoria de Fontes
Para este estudo no NotebookLM, foram utilizadas as seguintes fontes:
1. **Documento de Requisitos (Interno):** Definição das funcionalidades (CRUD, Categorização, Agenda).
2. **Documentação Técnica:** [React.js](https://react.dev/) e [SQLite Documentation](https://www.sqlite.org/docs.html).
3. **Padrão de API:** [Swagger (OpenAPI)](https://swagger.io/specification/).

---

## 🧠 Engenharia de Prompts e "Cicatrizes"
Registro da interação com a IA durante o planejamento:

* **Prompt Estratégico:** "Com base no projeto The Keeper, como posso estruturar uma tabela no SQLite que suporte tanto gastos fixos quanto o simulador de compras sem gerar inconsistência de saldo?"
* **Cicatrizes (Troubleshooting):** Durante os testes, a IA sugeriu uma estrutura de banco de dados muito complexa. Refinei o prompt para focar em um MVP (Produto Mínimo Viável) usando apenas as tabelas essenciais para o "Guaxinim" atuar como um alerta visual de saldo.

---

## 🚀 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados do Sistema
[COLE AQUI O RESUMO QUE O NOTEBOOKLM GERAR SOBRE AS FUNÇÕES DO SEU PROJETO]

### 2. Glossário de Conceitos
* **CRUD:** Operações de Criar, Ler, Atualizar e Deletar dados no sistema.
* **MVP:** Minimum Viable Product - versão inicial focada nas funções principais.
* **SQLite:** Banco de dados relacional leve utilizado para persistência local.

### 3. Prompts Reutilizáveis para o Projeto
* "Gere uma estrutura de JSON para a rota de cadastro de despesas no Express."
* "Atue como QA e identifique possíveis erros lógicos no simulador de compras."
