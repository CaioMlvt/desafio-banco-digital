# 🏦 Sistema Bancário Orientado a Objetos  
**Porque conta bancária é fácil. Quero ver modelar comportamento.**

---

![Java](https://img.shields.io/badge/Java-Collections-orange)
![POO](https://img.shields.io/badge/Paradigma-Orientação%20a%20Objetos-blue)
![Status](https://img.shields.io/badge/Status-Em%20Evolução-success)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📌 Sobre o Projeto
Este projeto simula o funcionamento básico de um sistema bancário utilizando **Java** com foco nos pilares de **Orientação a Objetos** e uso do **Java Collections Framework** para gerenciar objetos de forma eficiente.

Não se trata apenas de criar contas.  
Trata-se de entender **como modelar responsabilidades**.

---

## 🎯 Objetivos Técnicos

- Aplicar **Encapsulamento, Herança e Polimorfismo**
- Utilizar **interfaces** para padronizar serviços bancários
- Gerenciar clientes e contas usando **Collections**
- Separar responsabilidades de forma clara (**baixo acoplamento, alta coesão**)

---

## 🧱 Estrutura de Classes
├── Banco
│ ├── gerencia lista de contas (List<Conta>)
│
├── Conta (abstrata)
│ ├── atributos comuns (agência, número, saldo, titular)
│ ├── métodos base (sacar, depositar, transferir)
│
├── ContaCorrente (extends Conta)
│ └── pode ter taxas ou lógica adicional
│
├── ContaPoupanca (extends Conta)
│ └── pode ter rendimento no futuro (scalável)
│
└── Cliente
└── dados do titular

## 🚀 Funcionalidades Implementadas

| Função | Descrição |
|-------|-----------|
| Criar conta | Clientes podem ter conta corrente e/ou poupança |
| Sacar | Validação de saldo + saída de valor |
| Depositar | Entrada de valor direta no saldo |
| Transferir | Transferência entre contas com validação |
| Listar contas do banco | `Collections` para gerenciamento |

---

## 📦 Tecnologias Utilizadas
- **Java**
- **Java Collections (`List`, `Map`, etc.)**
- **Conceitos sólidos de POO**

---
