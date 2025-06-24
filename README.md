# Projeto Bancário em Python 🏦 💵

Este é um sistema bancário simples desenvolvido em Python, com funcionalidades de cadastro de usuários, criação de contas, depósitos, saques, extratos e listagem de contas. O projeto é totalmente executado via terminal e utiliza apenas estruturas básicas da linguagem, ideal para fins didáticos.

## Funcionalidades 📌📊

- **Cadastro de Usuário:** Registre novos clientes informando nome, CPF, data de nascimento e endereço.
- **Criação de Conta:** Crie contas bancárias vinculadas a usuários já cadastrados.
- **Depósito:** Realize depósitos em contas existentes.
- **Saque:** Efetue saques respeitando limites diários e de valor.
- **Extrato:** Consulte o extrato de movimentações e dados do cliente.
- **Listagem de Contas:** Veja todas as contas cadastradas no sistema.

## Como Executar ⚙💼

1. **Clone o repositório ou baixe os arquivos.**
2. Certifique-se de ter o Python 3 instalado.
3. No terminal, navegue até a pasta do projeto e execute:

```sh
   python inicio_do_projeto.py
```


## Use o Menu interativo para acessar as funcionalidades:
```
============ MENU =============
[nu] Novo Usuário
[nc] Nova Conta
[lc] Listar Contas
[d] Depositar
[s] Sacar
[e] Extrato
[q] Sair
===============================
```

## Observações

- Os dados são armazenados apenas em memória (listas). Ao encerrar o programa, todas as informações são perdidas.
- Cada usuário é identificado de forma única pelo CPF.
- Cada conta é vinculada a um usuário já cadastrado.
- O limite de saque é de R$ 500,00 por operação e até 3 saques diários.

## Licença

Este projeto está licenciado sob a Licença MIT.