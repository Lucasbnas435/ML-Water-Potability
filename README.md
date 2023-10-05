# Water Potability - Machine Learning
### [Autor: Lucas Barbosa Nascimento](https://github.com/Lucasbnas435)

O modelo de Machine Learning realiza classificação binária (binary classification), prevendo se determinada amostra de água é potável (1) ou não (0) com base em seus atributos.

## Dataset
Cada linha desse conjunto de dados representa uma amostra de água com propriedades específicas, contendo métricas de qualidade da água e uma avaliação relacionada à sua potabilidade, ou seja, sua adequeção para consumo humano.

Colunas:

- pH: O nível de pH da água
- Hardness: Dureza da água, uma medida do seu teor mineral
- Solids: Sólidos totais dissolvidos na amostra
- Chloramines: Concentração de cloraminas na água
- Sulfate: Concentração de sulfato na amostra
- Conductivity: Condutividade elétrica da amostra
- Organic_carbon: Teor de carbono orgânico na água
- Trihalomethanes: Concentração de trihalometanos na água
- Turbidity: Nível de turbidez, uma medida da clareza da água
- Potability: Indica a potabilidade da água com valores 1 (potável) e 0 (não potável)

## Desenvolvimento do Projeto
A aplicação foi desenvolvida em Python 3.10, utilizando [Jupyter Notebooks](https://jupyter.org/) hospedados e executados na plataforma [Google Colaboratory](https://colab.research.google.com/). O notebook data_visualization.ipynb apresenta um trabalho completo de visualização dos dados, expondo estatísticas e gráficos diversos, aspectos essenciais para a realização da Análise Exploratória inicial.

No notebook model_training.ipynb, é realizado o tratamento dos dados, preenchendo as entradas vazias, além da divisão do dataset entre parte de treinamento e parte de testes. Logo após, é feito o treinamento dos modelos com os algoritmos XGBoost e RandomForest. Por fim, tais modelos são exportados, permitindo seu compartilhamento e uso em outros locais.

## Fonte dos Dados
https://www.kaggle.com/datasets/uom190346a/water-quality-and-potability

## Contato
Muito obrigado por acessar esse projeto!
Vamos nos conectar?

GitHub: https://github.com/Lucasbnas435
LinkedIn:  https://linkedin.com/in/lucasbnas
E-mail: lucasbnas435@gmail.com
