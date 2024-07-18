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
#### 2. ¿En qué consiste ```nn.NLLLoss```?
#### 3. ¿Qué podría hacer para mejorar la red neuronal, y si no hay mejoras, por qué?
