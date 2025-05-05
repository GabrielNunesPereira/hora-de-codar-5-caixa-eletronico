# 💳 Projeto: Caixa Eletrônico em JavaScript

Este é um projeto simples de um sistema de **caixa eletrônico (ATM)** feito com **JavaScript**, que simula operações bancárias básicas como visualização de saldo, saque, depósito, extrato e transferência.

##  Funcionalidades

- Solicita o nome do usuário ao iniciar e dá boas-vindas.
- Menu principal com as opções:
  1. Ver saldo
  2. Ver extrato
  3. Realizar saque
  4. Realizar depósito
  5. Realizar transferência
  6. Sair do sistema
- Proteção por senha (senha padrão: `3589`) para acessar operações sensíveis.
- Validação de valores:
  - Não permite saque ou transferência de valores negativos, nulos ou superiores ao saldo.
  - Não permite depósito com valor zero ou negativo.
- Mensagens de erro personalizadas e navegação de retorno em caso de senhas erradas ou opções inválidas.
- Simulação de extrato com transações fictícias.

##  Tecnologias utilizadas

- JavaScript (puro)
