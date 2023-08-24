# customer-churn

## DAGSHUB + MLFLOW
Dagshub e MLflow demonstraram ser ferramentas poderosas para  gerenciar, manter e visualizar os  experimentos.  Como pode ser observado, vários  experimentos foram executados,  onde é possível visualizar cada  hiperparâmetro utilizado, bem  como a acurácia. O melhor  modelo obteve 89%.

![image](https://github.com/mtsfreitas/customer-churn/assets/21324690/764bda0c-9602-42dc-9198-83e6aacf8a73)

![image](https://github.com/mtsfreitas/customer-churn/assets/21324690/08d6950c-f602-4670-b211-dcb0c99d46fc)

Além disso, é possível visualizar outras informações de forma gráfica dos modelos.

![image](https://github.com/mtsfreitas/customer-churn/assets/21324690/470b74f9-b554-45ee-98f3-923e45dcc68f)

Também é possível utilizar o modelo para realizar previsões, basta utilizar o MLflow run ID:

![image](https://github.com/mtsfreitas/customer-churn/assets/21324690/1f59934c-263b-4a41-8151-492ab776858f)

## Resultados
Modelo de **Regressão Logística aperfeiçoado X TPOT**:

● Vale destacar que a acurácia obtida com o TPOT foi de aproximadamente **94%**, o que é superior à acurácia do modelo aperfeiçoado de **89%**. Isso sugere que o **TPOT foi capaz de encontrar um pipeline de aprendizado de máquina que produz um melhor desempenho no seu conjunto de teste.**

● Entretanto, apesar de seus pontos fortes, o TPOT pode não ser a melhor solução em todos os casos. **Ele pode demorar muito para executar, especialmente em grandes conjuntos de dados ou com um grande número de gerações.**

● Ainda assim, o **TPOT** é uma ferramenta poderosa que **pode economizar muito tempo e esforço, pois ele automatiza o que normalmente seria um processo de ajuste de parâmetros manual e trabalhoso.**
