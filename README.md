# Praticando Machine Learning
# Challenge ONE Data Science – Telecom X (parte 2)

## 📊 Análisis de Evasión de Clientes

Este proyecto analiza datos de una empresa de telecomunicaciones para identificar los factores que influyen en la evasión de clientes. Se utilizaron herramientas de ciencia de datos para visualizar, cuantificar y predecir comportamientos de abandono, con el objetivo de proponer estrategias de retención.

---

## 🧠 Objetivo del Proyecto

- Investigar los factores que inciden en la decisión de un cliente de cancelar el servicio.
- Detectar patrones de evasión según edad, método de pago, permanencia y monto pagado.
- Entregar visualizaciones claras y conclusiones accionables para el área de retención.

---

## 📑 Tabla de Contenidos

1. Cargar el archivo CSV que contiene los datos tratados anteriormente 
2. Eliminar Columnas Irrelevantes 
   - Revisar los valores de columnas codependientes 
   - Volver a los valores categóricos  
3. Transformar las variables categóricas a formato numérico 
4. Verificar la Proporción de Cancelación (Churn)  
5. Dividiendo los datos entre entrenamiento, validación y prueba  
6. Análisis Dirigido 
   - Tiempo de contrato vs Cancelación 
   - Distribución de Gasto total vs Cancelación 
   - Tiempo de contrato vs Gasto total 
7. Ajustando Modelos
   - Modelo de Referencia 
   - Árboles de Decisión
     - Decision Tree 
     - Probando el modelo Decision Tree 
     - Random Forest 
     - Probando el modelo Random Forest 
   - Modelos basados en distancia 
     - KNN (k-Nearest Neighbors)
     - Probando el modelo KNN 
8. Informes de métricas
9. Feature importances (atributos más importantes del modelo)
10. Escogiendo y serializando el mejor modelo
   - Evaluamos la tasa de acierto de los modelos
   - Serializando los modelos 
11. Conclusión
   - Modelos de Clasificación Evaluados
   - Comparación de Modelos
   - Análisis de Curvas
     - Curva Precision-Recall
     - Curva ROC
   - Principales Factores que Influyen en la Cancelación
   - Estrategias de Retención

---

## 📸 Visualizaciones

### Curva Precision-Recall
![Curva Precision-Recall](./fig1.png)

---

### Curva ROC
![Curva ROC](./fig.png)

---

Este proyecto requiere Python 3.8+ y las siguientes bibliotecas:
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- notebook (para ejecutar archivos .ipynb localmente) o un entorno virtual
  
## ⚙️ Instalación y dependencias en el entorno virtual

```bash
pip install pandas numpy matplotlib seaborn plotly


# 🧰 ¿Qué necesitas para ejecutar .ipynb localmente?
# ✅ 1. Tener Python instalado
# - Puedes descargarlo desde python.org.
# - Asegúrate de marcar “Add Python to PATH” durante la instalación.

### ✅ 2. Instalar Jupyter Notebook o JupyterLab
# - Lo más cómodo es hacerlo dentro de un entorno virtual:

# Crear entorno virtual (solo la primera vez)
python -m venv venv

# Activar el entorno
# En Windows:
venv\Scripts\activate

# En macOS/Linux:
source venv/bin/activate

# Instalar Jupyter y librerías necesarias
pip install notebook pandas matplotlib seaborn plotly

# ✅ 3. Ejecutar Jupyter Notebook
jupyter notebook

