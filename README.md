# 🏦 Sistema Bancário em Python (CLI)

Um sistema bancário simples desenvolvido em **Python**, executado via terminal (CLI), com funcionalidades de:

- 💰 Depósito  
- 💸 Saque  
- 📄 Extrato  
- 🚪 Encerramento do sistema  

Projeto criado com foco em **boas práticas de programação**, organização e modularização de código.

---

## 🎯 Objetivo do Projeto

Aplicar conceitos fundamentais da programação estruturada:

- Separação de responsabilidades
- Modularização com funções
- Evitar variáveis globais
- Implementação de regras de negócio
- Organização com função principal `main()`

---

## 🧠 Estrutura do Sistema

O sistema foi dividido nas seguintes funções:

| Função | Responsabilidade |
|--------|------------------|
| `menu()` | Exibir o menu e capturar a opção do usuário |
| `depositar()` | Realizar depósitos |
| `sacar()` | Realizar saques com validações |
| `exibir_extrato()` | Mostrar histórico e saldo |
| `main()` | Controlar o fluxo principal do sistema |

---

## ⚙️ Regras de Negócio

- ✅ Apenas valores positivos podem ser depositados  
- ✅ Limite máximo por saque: **R$ 500,00**  
- ✅ Máximo de **3 saques por sessão**  
- ✅ Não permite saque maior que o saldo disponível  

---

## 🛠 Tecnologias Utilizadas

- 🐍 Python 3  
- Terminal (CLI)

---

## 📌 Como Executar o Projeto

### 1️⃣ Clonar o repositório

```bash
git clone https://github.com/samuellsouza/desafio_sistema_bancario_2.0_python.git