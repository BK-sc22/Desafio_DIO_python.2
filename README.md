
# Desafio_DIO_python
    🛣️  Trilha Python

## Desafio: Otimizando o Sistema Bancário com Funções Python

## 🎯Objetivo:

    • Separar as funções existentes de saque, depósito e extrato em funções.
    • Criar duas funções: cadastrar usuário (cliente) e cadastrar conta bancária.
    
### - Desafio:
#### • Deixar o código mais modularizado
#### • criar funções para as operações: sacar, depositar e visualizar histórico
#### • criar duas funções: 
#### *usuário (cliente do banco) — deve ser armazenado em uma lista e ser composto por: nome, data de nascimento, cpf (somente os números do CPF e somente um usuário por CPF) e endereço (é uma string com o formato: logradouro, nro - bairro - cidade/sigla estado).
#### *conta corrente (vincular com usuário) — o programa deve armazenar contas em uma lista, uma conta é composta por: agência, número da conta e usuário. O número da conta é sequencial, iniciando em 1. O número da agência é fixo: "0001". O usuário pode ter mais de uma conta, mas uma conta pertence a somente um usuário.
## *Deve ser criada funções para todas as operações do sistema.

### SAQUE
#### A função saque deve receber os argumentos apenas por nome (keyword only). 
#### Sugestão de argumentos: saldo, valor, extrato, limite, numero_saques, limite_saques. 
#### Sugestão de retorno: saldo e extrato.
### DEPÓSITO
#### A função depósito deve receber os argumentos por posição (positional only)
#### Sugestão de argumentos: saldo, valor, extrato
#### Sugestão de retorno: saldo e extrato
### EXTRATO
#### A função extrato deve receber os argumentos por posição e nome (positional only       e keyword only)
#### Argumentos posicionais: daldo, argumentos nomeados: extrato
