# Experimento 2: Carga de un condensador

## 📌 Descripción general
Este proyecto analiza datos experimentales de carga–voltaje obtenidos de un condensador de placas paralelas para estimar su capacitancia a dos separaciones diferentes entre placas (4 mm y 6 mm). El análisis combina fundamentos de física experimental con técnicas de análisis de datos utilizando Python.

---

## 🎯 Objetivos del experimento

### Objetivo general

Determinar la capacitancia de un condensador de placas paralelas a partir del análisis experimental de la relación carga–voltaje.

### Objetivos específicos

- Medir la carga eléctrica en función del voltaje aplicado.
- Verificar la relación lineal $Q = C V$
- Estimar la capacitancia como la pendiente del ajuste lineal.
- Comparar la capacitancia para distintas separaciones entre placas.
- Analizar la calidad del ajuste mediante residuos e incertidumbre experimental.

---

## 🧪 Conjunto de datos

El conjunto de datos consiste en mediciones experimentales de la carga eléctrica para cuatro valores diferentes de voltaje. Para cada voltaje y separación entre placas, la carga se midió tres veces para reducir errores aleatorios. Los datos fueron recolectados durante un curso universitario de física experimental..

---

##  Metodología experimental

1. Se aplicaron distintos valores de voltaje al condensador.
2. Para cada voltaje se midió la carga almacenada.
3. Cada medición fue repetida tres veces.
4. Los datos fueron registrados en Excel para su posterior análisis.

---

## 📊 Datos experimentales y análisis (en desarrollo)

Los datos experimentales fueron:
- Organizados inicialmente en Excel.
- Posteriormente importados a Python para:
- Visualización de la relación Q–V
- Ajuste lineal por mínimos cuadrados
- Cálculo de la capacitancia (pendiente)
- Análisis de residuos
- Estimación de incertidumbre experimental

> 📌 El análisis computacional se desarrolló en cuadernos Jupyter Notebook (Google Colab).

---

## 📈 Resultados esperados

- Gráficas Q–V para cada separación entre placas.
- Obtención de la capacitancia experimental en ambos casos.
- Verificación de la relación inversa entre capacitancia y distancia entre placas.
- Discusión de errores y comparación con el modelo teórico.

---

## 🧠 Herramientas utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

---

## ⚙️ Cómo ejecutar

- Subir el archivo Excel con los datos experimentales a Google Colab
- Abrir el cuaderno de Jupyter Notebook
- Ejecutar todas las celdas
- Todos los gráficos y resultados numéricos se generarán automáticamente

---

## 🎓 Contexto académico

- Curso: Física 3
- Facultad: Ciencias
- Carrera: Ingeniería Física
- Universidad: Universidad Nacional de Ingeniería (UNI)

Este proyecto forma parte de un portafolio académico orientado a fortalecer la formación en análisis experimental y programación científica, con miras a postulaciones académicas y becas internacionales.

---

## 📬 Autor

**Ángel José Ramírez Leyva**
Estudiante de Ingeniería Física – UNI
GitHub: [@MAFINPY29](https://github.com/MAFINPY29)
