Solución de Rodrigo Perelsztein para el primer DATATON de Banco Galicia (2019)
Puesto 57/266 equipos

Competencia en Kaggle: https://www.kaggle.com/c/banco-galicia-dataton-2019/data 
datasets: https://www.kaggle.com/c/banco-galicia-dataton-2019/data

El set de entrenamiento cuenta con informaciones históricas reales y anonimizadas con el flujo de navegación web de clientes del Banco, junto con datos técnicos. Además, hay informacion sobre cuales realizaron una conversión positva para que se utilizado como variable dependiente de entrenamiento del modelo predictivo.

Luego, se busca predecir las nuevas conversiones para el primer trimestre del 2019, indicando los clientes que van a convertir y sobre los que fueron evaluados los modelos en la competencia.

Los modelos fueron evaluados por AUC ROC curve.

Luego de estructurar el dataset, busqué aplicar un modelo de clasificación CATBOOST y de tunear los hiperparámetros a partir de Randomized Search CV

Resultado:

Training auc:   0.9092990699332638
Validation auc: 0.8563117699910153
