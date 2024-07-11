# Mineria de datos
## Proyecto academico
### Descripción de las Técnicas y Modelos

#### Objetivo
Se busca determinar el color de los granos de café mediante la medición de atributos característicos.

#### Actividades

1. **Análisis del Conjunto de Datos**
   - Se descargó y se analizó el conjunto de datos "CoffeeRatings.csv" para comprender las distribuciones, detectar outliers y revisar los tipos de datos.

2. **Predicción del Atributo Color utilizando Support Vector Machines (SVM) con Kernel Lineal**
   - Se usó SVM con kernel lineal, ajustando parámetros clave y evaluando el desempeño con validación cruzada.

3. **Predicción del Atributo Color utilizando Support Vector Machines (SVM) con Kernel Gaussiano**
   - Se aplicó SVM con kernel gaussiano, optimizando parámetros relevantes y evaluando mediante validación cruzada.

4. **Predicción del Atributo Color utilizando Random Forest**
   - Se implementó Random Forest, ajustando la cantidad de estimadores y la profundidad de los árboles, y evaluando el modelo con validación cruzada.

#### Descripción de las Técnicas

**Support Vector Machines (SVM):**
- **Kernel Lineal:** Utiliza una función lineal para separar las clases.
- **Kernel Gaussiano (RBF):** Utiliza una función de base radial para manejar relaciones no lineales en los datos.

**Random Forest:**
- Conjunto de árboles de decisión que trabajan en conjunto para mejorar la precisión de la predicción.

Cada técnica se evaluó mediante validación cruzada para asegurar una medida robusta del desempeño del modelo, comparando los resultados en términos de precisión, exhaustividad y exactitud.
