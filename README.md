# 🎬 movie-prediction-project
Este repositório contém o código, modelos e análises para prever a nota do IMDb e o gênero de filmes com base em suas características.

## 📄 Descrição
Este projeto foi desenvolvido para prever a nota do IMDb e o gênero de filmes com base em dados fornecidos. O projeto inclui análises exploratórias, modelagem preditiva e uso de diversos modelos de machine learning.

## 📂 Estrutura do Projeto

- `projeto_filmes.ipynb`: Notebook Jupyter contendo todo o código para análise exploratória, modelagem e previsões.
- Modelos salvos no formato `.pkl`:
  - `log_genre_predictor.pkl`: Modelo de Regressão Logística para previsão de gênero.
  - `nb_genre_predictor.pkl`: Modelo de Naive Bayes para previsão de gênero.
  - `rf_genre_predictor.pkl`: Modelo de Random Forest para previsão de gênero.
  - `rf_imdb_rating_predictor.pkl`: Modelo de Random Forest para previsão da nota do IMDb.
  - `lr_imdb_rating_predictor.pkl`: Modelo de Regressão Linear para previsão da nota do IMDb.
  - `dt_imdb_rating_predictor.pkl`: Modelo de Árvore de Decisão para previsão da nota do IMDb.

- `requirements.txt`: Lista de bibliotecas necessárias para executar o projeto.
 - `desafio_indicium_imdb.csv`: Base de dados utilizada.

## 🛠️ Instalação

### Passo 1: Clone o repositório
```bash
git clone https://github.com/florabelas1/movie-prediction-project
cd movie-prediction-project

Passo 2: Crie e ative um ambiente virtual (opcional, mas recomendado)
python -m venv env
source env/bin/activate  # No Windows use `env\Scripts\activate`

Passo 3: Instale os requisitos
pip install -r requirements.txt


🚀 Uso
Abra o Jupyter Notebook e execute o arquivo LH_CD_FLORA.ipynb.

📊 Análises e Modelagem
O projeto inclui análise exploratória dos dados, construção e avaliação de modelos preditivos, e previsão de notas IMDb e gêneros de filmes.

🧰 Bibliotecas Utilizadas
pandas
numpy
matplotlib
seaborn
scikit-learn
wordcloud
joblib