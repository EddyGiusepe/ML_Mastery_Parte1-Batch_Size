# ML Mastery--Parte1 -- Batch Size


Aqui estudaremos a importância do tamanho do lote ao treinar redes neurais.

As redes neurais são treinadas usando gradiente descendente, onde a estimativa do erro usada para atualizar os pesos é calculada com base em um subconjunto do 
conjunto de dados de treinamento.

O número de exemplos do conjunto de dados de treinamento usado na estimativa do gradiente de erro é chamado de tamanho do lote e é um hiperparâmetro importante 
que influencia a dinâmica do algoritmo de aprendizagem. A escolha do tamanho do lote controla a rapidez com que o algoritmo aprende.

Temos:
* Batch Gradient Descent (Gradiente descendente em lote).

* Stochastic Gradient Descent (Gradiente descendente estocástico).

* Minibatch Gradient Descent (Gradiente descendente Minibatch).
