# Previsão de Vendas — Melhores Compras Ltda.

Solução preditiva baseada em Machine Learning para estimar o faturamento semanal (`Weekly_Sales`) da empresa **Fictícia** Melhores Compras Ltda., integrando fatores sazonais e indicadores macroeconômicos para apoiar o planejamento financeiro e a tomada de decisão estratégica do conselho executivo (*board*).

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3.12
* **Análise e Manipulação de Dados:** Pandas, NumPy, SciPy, Statsmodels
* **Visualização:** Matplotlib, Seaborn, Plotly
* **Modelagem e Explicabilidade:** Scikit-Learn, XGBoost, LightGBM, SHAP

## 📁 Estrutura do Repositório

```text
Projeto_Preditivo_de_Vendas_Melhores_Compras/
├── data/         # Base de dados (sales.csv)
├── docs/         # Documentação e briefings técnicos
├── notebooks/    # Pipeline analítico e modelagem (modelo_previsao.ipynb)
├── outputs/      # Modelos compilados, gráficos e relatórios
├── src/          # Módulos e scripts auxiliares em Python
├── .gitignore    # Regras de exclusão para o Git
├── README.md     # Documentação do projeto
└── requirements.txt
```

## 🚀 Como Executar o Projeto

1. **Clonar o repositório:**
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd Projeto_Preditivo_de_Vendas_Melhores_Compras
   ```

2. **Criar e ativar o ambiente virtual:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Instalar as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Executar a análise:**
   Abra a IDE (ex: VS Code) e selecione o kernel do ambiente virtual (`venv`) para executar os arquivos em `notebooks/`.