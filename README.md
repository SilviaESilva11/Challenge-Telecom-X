# Análise de Churn — Telecom X

Análise exploratória e visual de evasão de clientes (*churn*) desenvolvida em Python com foco na identificação de fatores de risco ligados a contratos, serviços adicionais e cobrança mensal.

## 🎯 Objetivo
Investigar o comportamento de cancelamento de clientes da Telecom X para apoiar decisões de retenção e preparar variáveis para modelagem preditiva.

## 🛠️ Tecnologias e Ambiente
- **Python 3.14.0** (ambiente virtual `.venv` no VS Code)
- **Bibliotecas:** `pandas`, `matplotlib`, `seaborn`, `ipykernel`, `IPython`

## 📂 Estrutura do Projeto
- `Challenge_2_Telecom_X.ipynb`: pipeline completo de limpeza, exploração, visualização e relatórios automatizados em Markdown.
- `TelecomX_Data.json`: base de dados utilizada na análise.
- `TelecomX_dicionario.md`: dicionário com a descrição das variáveis do conjunto de dados.
- `requirements.txt`: dependências do projeto.
- `.gitignore`: regras para ignorar ambientes virtuais, caches e ficheiros temporários no Git.

## 🔍 Principais Frentes Analisadas
- **Proporção geral de Churn:** distribuição de clientes ativos e cancelados.
- **Contratos:** comparação da taxa de evasão por modalidade contratual (`Month-to-month`, `One year`, `Two year`).
- **Serviços de suporte e segurança:** adesão a serviços adicionais entre clientes que permaneceram e cancelaram.
- **Cobrança mensal e encargos:** comparação de valores médios e distribuição por *boxplot*.

## ▶️ Como Executar Localmente

1. Clone o repositório e abra a pasta no VS Code.
2. Crie e ative o ambiente virtual (`.venv`):
   ```powershell
   python -m venv .venv
   .\.venv\Scripts\Activate.ps1
   
   ## 👩‍💻 Autora
**Silvia Galvão**