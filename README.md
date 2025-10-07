# Validador de Senhas (Avaliação QA)

## Descrição do Projeto

O objetivo desse projeto em forma de desafio foi fortalecer e familiazriar o uso dos testes unitários  enquanto dev. Utilizando o framework pytest, foi desenvolvida uma suíte completa de testes unitários que garantem o cumprimento das regras definidas, abrangendo tanto cenários de senhas válidas quanto situações que geram erros.

## Tecnologias Utilizadas

Python + Pytest

## Regras de Negócio 

| Regra | Cenário de Teste |
| :--- | :--- |
| **R1. Comprimento Mínimo** | A senha deve ter no mínimo **8 caracteres**. |
| **R2. Caractere Maiúsculo** | A senha deve conter pelo menos **uma letra maiúscula**. |
| **R3. Caractere Minúsculo** | A senha deve conter pelo menos **uma letra minúscula**. |
| **R4. Dígito Numérico** | A senha deve conter pelo menos **um número**. |
| **R5. Espaços em Branco** | A senha **não pode** conter espaços em branco. |
| **R6. Entradas Inválidas** | A senha **não pode ser nula** ou uma **string vazia**. |


## Relatório


![cffb031b-aadf-4def-86f3-1ea0bc781222](https://github.com/user-attachments/assets/ba1accf8-b655-402c-80f5-645ac6a6c490)


## Estrutura da Branch

- `main`: Branch principal, onde todas as alterações foram implementadas e testadas.

  ## Como Clonar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/eukellyanne/validador_de_senhas.git

2. **Acesse o diretório:**
   ```bash
   cd  validador_de_senhas

   
## Estrutura do Código 

VALIDADOR_DE_SENHAS/
│
├── src/
│   ├── __init__.py
│   └── password_validator.py
│
├── tests/
│   └── test_password_validator.py
│
├── .coverage
├── .gitignore
├── pytest.ini
├── README.md
└── requirements.txt






