# 📊 Clasificación de Planes de Clientes – Megaline  

## 📌 Descripción del Proyecto  
La compañía de telecomunicaciones **Megaline** busca migrar a sus clientes desde planes heredados hacia dos planes actuales: **Smart** y **Ultra**.  
Para apoyar este proceso, se desarrolla un **modelo de machine learning** que analiza el comportamiento de los clientes (llamadas, mensajes y consumo de internet) y recomienda el plan más adecuado.  

---

## 🎯 Objetivo  
Entrenar, comparar y seleccionar un modelo de clasificación supervisado que permita predecir con la mayor exactitud posible el plan ideal para cada cliente.  

---

## 🗂️ Dataset  
El dataset contiene información de clientes que ya se han cambiado a los nuevos planes, incluyendo:  
- Número de llamadas realizadas.  
- Minutos consumidos.  
- Mensajes enviados.  
- Megabytes de internet utilizados.  
- Plan actual del cliente (**Smart** o **Ultra**).  

---

## ⚙️ Metodología  
1. **Exploración inicial del dataset** → revisión de estructura, tipos de datos, valores nulos y duplicados.  
2. **Segmentación de datos** → división en conjuntos de entrenamiento (70%) y validación (30%) usando `train_test_split`.  
3. **Prueba de modelos** → entrenamiento y ajuste de hiperparámetros con **GridSearchCV** y validación cruzada.  
   - Logistic Regression  
   - Decision Tree Classifier  
   - Random Forest Classifier  
4. **Evaluación** → comparación de desempeño en validación y prueba.  
5. **Selección final** → elección del modelo con mejor rendimiento.  

