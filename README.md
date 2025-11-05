## 🧠 Interpretador da Linguagem Lox (Estudo baseado em *Crafting Interpreters*)

Este repositório contém o desenvolvimento do **interpretador da linguagem Lox**, implementado em **Python**, seguindo a estrutura e os conceitos apresentados no livro [*Crafting Interpreters*](https://craftinginterpreters.com/) de Robert Nystrom.

O projeto é parte de um **trabalho acadêmico** da disciplina de **Construção de Compiladores / Interpretadores**, e tem como objetivo compreender e aplicar conceitos fundamentais de **análise léxica, sintática e semântica**, além da implementação de **controle de fluxo e escopo de variáveis**.

---

### 🎯 Objetivos do projeto

* Implementar um interpretador funcional da linguagem **Lox**.
* Passar com sucesso nos **testes automáticos** fornecidos pelo professor (executados via `pytest`).

---

### ⚙️ Execução

O ambiente é gerenciado com **uv**, garantindo reprodutibilidade e isolamento.

```bash
# Executar o interpretador
uv run pylox

# Executar todos os testes
uv run pytest
```

---

### 🧩 Estrutura do repositório

```
.
├── pylox/                 # Código-fonte do interpretador
├── tests/                 # Testes automáticos (Pytest)
│   ├── test_statements_and_state.py
│   ├── test_control_flow.py
│   └── ...
├── README.md              # Descrição do projeto
└── pyproject.toml         # Configuração do ambiente uv
```

---


### 📚 Referências

* Robert Nystrom — *Crafting Interpreters*
* Repositório de referência do professor [Fábio M. Mendes](https://fabiommendes.github.io/craftinginterpreters/)
* Testes automatizados fornecidos pela disciplina

---
