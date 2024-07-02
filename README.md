
# SageMaker Canvas

Escolhi um dataset sobre previsão de eletrônicos de varejo.



## Funcionalidades

A idéia era entender a demanda ao longo de 365 dias.
O modelo foi bem treinado trazendo os seguintes status:

Avg. wQL0.032

MAPE 0.052

WAPE 0.051

RMSE 100.266

MASE 0.344


## Documentação
Avg. wQL (Weighted Quantile Loss): Essa métrica é usada para avaliar a precisão de previsões quantílicas ponderadas. Um valor mais baixo indica um melhor desempenho.

MAPE (Mean Absolute Percentage Error): Representa o erro absoluto médio em termos percentuais. Um MAPE de 0.052 indica que, em média, os erros de previsão são 5.2% do valor real.

WAPE (Weighted Absolute Percentage Error): Similar ao MAPE, mas leva em consideração pesos diferentes para diferentes valores. Um WAPE de 0.051 é bastante baixo, sugerindo boas previsões relativas ao valor real.

RMSE (Root Mean Squared Error): O RMSE de 100.266 indica o erro quadrático médio da previsão. É uma métrica que penaliza mais fortemente grandes erros. Um RMSE mais baixo é melhor, mas sua interpretação depende da escala dos dados.

MASE (Mean Absolute Scaled Error): Essa métrica compara o erro absoluto médio do modelo com o erro absoluto médio de uma previsão de referência (como a previsão por inércia). Um MASE de 0.344 sugere que o modelo é consideravelmente melhor do que a previsão de referência (valores menores que 1 indicam melhoria sobre a referência).



## Conclusão

Com base nesse status, especialmente com valores baixos de MAPE, WAPE e MASE, o modelo parece estar bem treinado.




## 🔗 Links
https://www.linkedin.com/in/rodrigopresidati/

