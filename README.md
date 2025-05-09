# ADNE_imagen

- Marta Rodríguez hebles
- Maria Valvanera Gil de Biedma
- Blanca Sayas Ladaga

# Detección de Anomalías en la Piel

Este proyecto implementa un sistema de clasificación automática de tres tipos de anomalías cutáneas: **melanoma**, **nevus** y **queratosis seborreica**. Se incluye un análisis exploratorio de datos (EDA), una fase de Machine Learning clásico con extracción de características y SVM, y dos modelos de Deep Learning: un **CNN entrenado desde cero** y un **ResNet-50 preentrenado**. Además, incorpora un pequeño módulo de **Image-to-Text** que genera una breve descripción de la clase predicha.

---

## Descripción

El objetivo es clasificar imágenes dermatoscópicas en tres categorías:

- **Melanoma**  
- **Nevus**  
- **Queratosis seborreica**  

Se aplica un flujo completo que incluye:

1. **EDA**: inspección de tipos de imagen, tamaños, balance de clases, histogramas de color y distribución de píxeles.  
2. **Machine Learning clásico**: extracción de características y entrenamiento de un SVM.  
3. **Deep Learning**:  
   - Un CNN personalizado entrenado desde cero.  
   - Un modelo ResNet-50 preentrenado fine-tuneado en nuestro dataset.  
4. **Image-to-Text**: módulo que genera una descripción breve (“Este ejemplo parece un melanoma”, etc.) de la predicción.  

---
