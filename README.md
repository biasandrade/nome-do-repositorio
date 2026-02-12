# Projeto de Predição de Churn

Projeto de Machine Learning para prever churn de clientes.

## Estrutura do Projeto
```
churn-ml-project/
├── data/
│   ├── raw/          # Dados originais
│   ├── processed/    # Dados limpos
│   └── final/        # Dados prontos para modelo
├── notebooks/        # Análises exploratórias
├── src/             # Código fonte
├── models/          # Modelos treinados
└── reports/         # Relatórios e visualizações
```

## Como usar

1. Clone o repositório
2. Crie ambiente virtual: `python -m venv .venv`
3. Ative: `.venv/Scripts/activate`
4. Instale dependências: `pip install -r requirements.txt`
5. Baixe os dados: `dvc pull`

## Tecnologias

- Python
- Git (versionamento de código)
- DVC (versionamento de dados)
- Pandas, Scikit-learn

