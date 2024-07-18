# CatsDogs LinearRegression

## Preguntas
### Ejercicio 7 - Modelo
#### 1. ¿Qué se podría hacer para mejorar el rendimiento de esta red?
Parte del procedimiento que se podría realizar es utilizar un mayor tamaño de imágen para permitir una mejor captura de detalles.
También, podríamos modificar el learning rate y la cantidad de iteraciones para el proceso de entrenamiento en el algoritmo de gradiente descendiente.

#### 2. Interprete la gráfica de arriba
El "pico" que se genera al comienzo es el incremento del costo por los ajustes iniciales. También se puede apreciar cómo la tendencia de la gráfica es a disminuir, lo que indica que el modelo está aprendiendo y su desempeño está mejorando. Pareciera que puede llegar a converger en un punto donde el costo sea mínimo.

### Parte 2 - Red Neuronal Simpple con PyTorch
#### 1. ¿En qué consiste ```optim.SGD```?
La clase optim.SGD de PyTorch es una implementación del algoritmo de optimización por medio de descenso de gradiente estocástico para el entrenamiento de redes neuronales. 
Este algoritmo consiste en actualizar los parámetros de forma iterativa y opuesta al gradiente de la función de pérdida, utilizando un gradiente obtenido aleatoriamente de un subconjunto de datos. Este enfoque estocástico permite realizar las actualizaciones de los parámetros con mayor frecuencia que en el descenso de gradiente no estocástico, el cual utiliza el conjunto completo de datos para calcular el gradiente en cada paso.

#### 2. ¿En qué consiste ```nn.NLLLoss```?
La clase nn.NLLLoss de PyTorch es una función de pérdida que utiliza la medida de Negative Log Likelihood (NLL), útil para la clasificación cuando se tiene múltiples clases. 
La medida de NLL evalúa el rendimiento de un modelo calculando el negativo del logaritmo de las probabilidades predichas para las clases verdaderas, según se indican en las etiquetas.

#### 3. ¿Qué podría hacer para mejorar la red neuronal, y si no hay mejoras, por qué?
La principal mejor que se le puede dar a esta red neuronal es agregar más capas para que esta pueda aprender caracteristicas más especificas y poder captar mayores detalles que puedan ser utiles para la clasificación de los individuos.
