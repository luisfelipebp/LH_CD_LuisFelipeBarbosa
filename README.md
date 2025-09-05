# Previsão de Notas IMDB com Machine Learning

Este projeto tem como objetivo prever a nota IMDb de filmes utilizando diferentes algoritmos de regressão.  
Após testes comparativos, o modelo **XGBoost Regressor** apresentou o melhor desempenho e foi salvo em formato `.pkl`.

## Requisitos

- Python 3.9+
- Bibliotecas listadas em `requirements.txt`

## Estrutura do Repositório

```bash
LH_CD_LuisFelipeBarbosa/
│
├── data/    
├── notebooks/            
│   └── LH_CD_LuisFelipeBarbosa.ipynb
├── models/              
│   └── pipeline_treinado.pkl
├── requirements.txt
└── README.md

```
## Como executar o projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/luisfelipebp/LH_CD_LuisFelipeBarbosa.git
   cd LH_CD_LuisFelipeBarbosa
   ```
   
2. Crie um ambiente virtual (opcional, mas recomendado):
  ```bash
  python -m venv venv
  
  source venv/bin/activate   # Linux/Mac
  venv\Scripts\activate      # Windows
  ```

3. Instale as dependências:

  ```bash
  pip install -r requirements.txt
  ```

4. Abra os notebooks para explorar as análises e modelos:

  ```bash
  jupyter notebook
  ```

# Criar o requirements.txt

Se quiser gerar o requirements.txt atualizado:

  ```bash
  pip freeze > requirements.txt
  ```
