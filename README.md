🚀 Spaceship Titanic - Kaggle Challenge
Este projeto é minha participação na competição Spaceship Titanic do Kaggle, cujo objetivo é prever se passageiros foram transportados para outra dimensão durante uma missão interplanetária. Utilizei técnicas de ciência de dados e machine learning para explorar, tratar e modelar os dados com foco em maximizar a acurácia do modelo.

📌 Principais etapas do projeto:
Análise exploratória (EDA) e tratamento de valores ausentes.

Engenharia de variáveis com destaque para:

Extração de informações da variável Name (como frequência do sobrenome, tamanho do nome, inicial).

Agrupamento por faixa etária (AgeBin) e criação de dummies e flags booleanas.

Criação de interações como CryoSpend = CryoSleep * log(Spend) para capturar efeitos combinados.

Codificação inteligente com uso de Target Encoding em variáveis categóricas.

Modelagem com XGBoost e ajuste fino de parâmetros.

⚙️ Ferramentas e tecnologias:
Python, Pandas, NumPy, scikit-learn, XGBoost

Jupyter Notebook

Kaggle Notebooks

🎯 Resultado:
Acurácia final: 81,00%

Foco na criação de variáveis informativas para melhoria de performance
