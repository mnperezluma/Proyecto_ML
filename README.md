# Proyecto_ML - House Price Prediction


En mi primer lugar, hice un muy breve EDA. Analizé las columnas que me parecían más influyentes para la predicción. Tenía decidido trabajar con entre 15/20
como máximo. 
A partir de esto y de hacer un breve research, supe que los modelos de regresión eran apropiados para la problemática en cuestión, es decir, predecir precios de propiedades.

Modelos que utilize para comparar valores y scores:
  * DecisionTreeRegressor
  * LinearRegression
  * Lasso
  * RandomForestRegressor
  
  Utilizé múltiples herramientas para medir mi score:
  + GridSearch
  + CrossValidation --> Promedio de 5 ejecuciones
  + Matriz de correlación entre las variables independientes elegidas
  
  Conclusión actual:
  Modelo con mejor perfomance: RandomForestRegressor 
  * Accuracy Score Promedio: 0.82
  * RMSLE: 0.02
