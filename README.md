# 🏦 Sistema Bancário V2 (Python)

## 📘 Descrição

Este projeto é uma evolução do **Sistema Bancário em Python (Versão 1)**, com o objetivo de aplicar **conceitos de modularização**, **boas práticas de programação** e **organização de funções**.  
Agora, o sistema permite **múltiplos usuários e contas**, com funções separadas para **depósito, saque, extrato, criação de usuários e contas**, e regras de negócio bem definidas.

O projeto foi desenvolvido em **Python puro**, sem bibliotecas externas, e serve como base de aprendizado para estudantes e profissionais que desejam consolidar lógica e fundamentos de programação orientada a funções.

---

## 🧠 Conceitos Praticados

- Estruturação de código em funções
- Argumentos posicionais, nomeados e mistos
- Controle de fluxo (`if`, `while`, `for`)
- Manipulação de listas e dicionários
- Validação de dados (saldo, limites, CPF)
- Encapsulamento e reuso de código
- Modularização e organização de responsabilidades

---

## ⚙️ Funcionalidades

### 🪙 Operações bancárias
- **Depositar**: adiciona saldo à conta.
- **Sacar**: realiza saques respeitando limite e número máximo de operações.
- **Extrato**: exibe todas as movimentações e o saldo atual.

### 👤 Gestão de usuários
- **Criar usuário**: cadastra novos clientes (CPF único).
- **Listar usuários**: exibe todos os usuários cadastrados (opcional).
- **Validação automática de CPF**: evita duplicidade.

### 🏧 Gestão de contas
- **Criar conta**: vincula uma conta a um usuário existente.
- **Listar contas**: mostra todas as contas criadas.
- Cada conta contém: `agência`, `número da conta`, `usuário`.

---

## 🧩 Estrutura do Código

📁 sistema_bancario_v2/

│

├── main.py # Código principal com funções e loop do menu

├── README.md # Documentação do projeto

│

└── (opcional) data/ # Pasta para salvar dados de usuários futuramente


---
🧾 Exemplo de Uso
================ MENU ================
[d] Depositar

[s] Sacar

[e] Extrato

[nu] Novo Usuário

[nc] Nova Conta

[lc] Listar Contas

[q] Sair

=> d

Informe o valor do depósito: 200

✅ Depósito realizado com sucesso!


================ EXTRATO ================

Depósito: R$ 200.00

Saldo atual: R$ 200.00

==========================================


🧑‍💻 Autor


Josemar Joel Damião Sebastião

📍 Guarulhos, SP - Brasil

🔗 LinkedIn: https://www.linkedin.com/in/josemar-sebastiao/

💻 GitHub: https://github.com/JosemarDS
