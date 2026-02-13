# Experimento 2: Carga de un condensador

## 📌 Descripción general
Este proyecto analiza datos experimentales de carga–voltaje obtenidos de un condensador de placas paralelas para estimar su capacitancia a dos separaciones diferentes entre placas (4 mm y 6 mm). El análisis combina fundamentos de física experimental con técnicas de análisis de datos utilizando Python.

## 🎯 Contexto físico
Para un condensador, la carga eléctrica y el voltaje aplicado se relacionan mediante:
$
Q = C \. V
$
Esta relación lineal permite determinar la capacitancia como la pendiente de un ajuste lineal de carga versus voltaje.

## 🧪 Conjunto de datos
El conjunto de datos consiste en mediciones experimentales de la carga eléctrica para cuatro valores diferentes de voltaje. Para cada voltaje y separación entre placas, la carga se midió tres veces para reducir errores aleatorios. Los datos fueron recolectados durante un curso universitario de física experimental..

## ⚙️ Metodología de análisis de datos

Se realizaron los siguientes pasos:
1. Carga y limpieza de los datos desde un archivo Excel
2. Promediado de mediciones repetidas de carga
3. Ajuste lineal mediante el método de mínimos cuadrados
4. Análisis de residuos para evaluar la calidad del ajuste
5. Estimación de la incertidumbre en la capacitancia

## 📊 Resultados
Se obtuvieron valores de capacitancia para ambas separaciones entre placas. Los resultados muestran la disminución esperada de la capacitancia al aumentar la distancia entre placas, consistente con la teoría electrostática.

## 🧠 Herramientas utilizadas
Python
Pandas
NumPy
Matplotlib
Google Colab

## ⚙️ Cómo ejecutar
Subir el archivo Excel con los datos experimentales a Google Colab
Abrir el cuaderno de Jupyter Notebook
Ejecutar todas las celdas
Todos los gráficos y resultados numéricos se generarán automáticamente

## 🎓 Contexto académico
Curso: Física Experimental Universitaria
Facultad: Ciencias
Carrera: Ingeniería Física
Universidad: Universidad Nacional de Ingeniería (UNI)

Este proyecto forma parte de un portafolio académico orientado a fortalecer la formación en análisis experimental y programación científica, con miras a postulaciones académicas y becas internacionales.

📬 Autor
Ángel José Ramírez Leyva
Estudiante de Ingeniería Física – UNI
GitHub: @MAFINPY29

