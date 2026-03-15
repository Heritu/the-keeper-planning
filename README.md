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

### . Resumo Estruturado do Sistema
**O Projeto The Keeper** é um sistema web funcional focado no gerenciamento financeiro e controle de gastos informais. A seguir, apresento um resumo estruturado de suas funcionalidades principais, destacando o registro financeiro e o simulador de compras:

*   **Registro de Gastos (Gestão de Fluxo / CRUD)**: O sistema permite o **cadastro manual e simples de todas as entradas e saídas de dinheiro**. Esses registros são salvos (persistência) utilizando um banco de dados SQLite. Além do valor, o usuário pode **categorizar os gastos** com etiquetas como "Comida", "Lazer" ou "Faculdade", o que facilita a organização e o uso de filtros no sistema.
*   **Simulador de Compras (O Guaxinim / Análise Preditiva)**: O "Guaxinim" é o módulo de análise preditiva do sistema. Nele, o usuário pode simular a compra de um item para ver qual será o **impacto no seu saldo atual antes de efetivamente realizar a compra**. O simulador foi desenhado para ser uma ferramenta simples (MVP), baseada em cálculos aritméticos claros, que **projeta o estado futuro do seu dinheiro sem alterar os dados reais salvos no banco de dados**, funcionando como um importante alerta visual de impacto financeiro.
*   **Painel de Saldo (Dashboard)**: Uma tela central que soma tudo o que foi cadastrado nas entradas e saídas e exibe de forma clara o valor final que o usuário tem disponível "no bolso".
*   **Agenda de Lembretes (Vencimentos)**: Uma funcionalidade onde o usuário pode adicionar um campo de data para contas que precisam ser pagas. O sistema fornece **alertas visuais** (usando cores diferentes ou o ícone do Guaxinim) quando o vencimento da conta está se aproximando.

### . Glossário de Conceitos
* **CRUD:** Operações de Criar, Ler, Atualizar e Deletar dados no sistema.
* **MVP:** Minimum Viable Product - versão inicial focada nas funções principais.
* **SQLite:** Banco de dados relacional leve utilizado para persistência local.

### . Prompts Reutilizáveis para o Projeto
* "Gere uma estrutura de JSON para a rota de cadastro de despesas no Express."
* "Atue como QA e identifique possíveis erros lógicos no simulador de compras."
