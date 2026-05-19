# Tarea 19: TF-IDF — Vectorización del Lenguaje Natural 

Hola, este es el repositorio de mi tarea sobre **Procesamiento de Lenguaje Natural**, enfocada en entender y aplicar la técnica TF-IDF usando PySpark.

## ¿Qué hay en este repo? 
- **`TareaTFIDF_Moran.ipynb`**: Es el notebook de Google Colab con todo el código ejecutado. Ahí también están mis respuestas y conclusiones sobre cómo funciona el algoritmo.
- **`corpus_noticias_es.csv`**: El dataset que usamos en el ejercicio. Tiene 600 noticias en español clasificadas en deportes, economía y tecnología.

## Sobre la tarea 
A lo largo de la práctica, vimos que para que un modelo de Machine Learning entienda texto, no basta con solo contar palabras (ya que cosas como "el", "la" o "de" harían mucho ruido). 

La técnica TF-IDF nos ayuda a encontrar un balance buenísimo: premia las palabras clave que resaltan en un texto específico y penaliza las palabras comunes que se repiten en todos los documentos. Básicamente, hace el trabajo sucio de limpiar el ruido para encontrar de qué trata realmente una noticia.

---
**Autor:** Michael Antonio Morantes Pachon
*Asignatura: Machine Learning con PySpark y Docker*
*Estadística — Universidad Santo Tomás · Semestre 2026-I*
