
# 💰 Sistema de Conta Bancária

Este projeto é uma implementação simples de um sistema de gerenciamento de contas bancárias em **TypeScript**, com foco em conceitos de **Programação Orientada a Objetos (POO)** como **encapsulamento** e **modificadores de acesso**.

## 📋 Funcionalidades


- Criar nova conta (gera número de conta automaticamente).  
- Listar todas as contas.  
- Consultar conta por **número** e/ou por **nome do titular**.  
- Atualizar dados da conta.  
- Excluir conta.  
- **Depósito** e **Saque** com validações.  
- **Transferência** entre contas.  
- (Opcional) Tipos de conta: **Corrente** (com limite) e **Poupança** (com rendimento).  
- Interface via menu no terminal (readline-sync).


## ✅ Validações

- Depósitos devem ser valores **positivos**
- Saques não podem exceder o **saldo disponível**
- O saldo é protegido por **encapsulamento** e não pode ser acessado diretamente

## 🧰 Tecnologias & Requisitos

- Node.js **>= 18**  
- TypeScript **>= 5**  
- readline-sync (entrada no terminal)  
- (Opcional) Jest/Vitest para testes


  ## 🚀 Como executar

```bash
# 1) Clonar o repositório
git clone https://github.com/JBechaire/conta_bancaria.git
cd conta_bancaria

# 2) Instalar dependências
npm install

# 3) Compilar TypeScript (se rodar em JS compilado)
npm run build

# 4) Executar
npm start
# ou, se usar ts-node:
npm run dev


# Exemplo do Menu
========================================
        BANCO DO BRAZIL COM Z
========================================
1 - Criar Conta
2 - Listar Contas
3 - Buscar Conta por Número
4 - Atualizar Conta
5 - Apagar Conta
6 - Sacar
7 - Depositar
8 - Transferir
9 - Sair
----------------------------------------
Entre com a opção desejada: _