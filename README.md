
# 💰 Sistema de Conta Bancária

Este projeto é uma implementação simples de um sistema de gerenciamento de contas bancárias em **TypeScript**, com foco em conceitos de **Programação Orientada a Objetos (POO)** como **encapsulamento** e **modificadores de acesso**.

## 📋 Funcionalidades

- Criar uma conta bancária com:
  - Nome do titular (`public`)
  - Saldo (`private`)
- Operações disponíveis:
  - Depositar valores
  - Sacar valores (com validação de saldo)
  - Exibir saldo atual
  - Mostrar resumo da conta

## ✅ Validações

- Depósitos devem ser valores **positivos**
- Saques não podem exceder o **saldo disponível**
- O saldo é protegido por **encapsulamento** e não pode ser acessado diretamente

## 🛠️ Tecnologias Utilizadas

- **TypeScript** – Linguagem principal
- **Node.js** – Para execução local (opcional)

## 🚀 Como Executar

1. Certifique-se de ter o **Node.js** instalado
2. Clone o repositório:

```bash
git clone https://github.com/JBechaire/conta_bancaria.git
cd conta_bancaria
