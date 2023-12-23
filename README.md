# Heart Disease Detection

## Detección de Enfermedad Cardíaca

Este proyecto de datos tiene como objetivo la detección de enfermedad cardiaca mediante el análisis de un conjunto de datos que contiene información sobremúltiples pacientes con diferentes grados de enfermedad o ausencia de la misma.

Esta tarea parece sencilla, sin embargo, debemos ser conscientes de la importancia de proporcionar una solución a este tipo de problemas y el gran avance que supone en la práctica clínica. La detección temprana de enfermedades cardiovasculares en el momento del ingreso o la consulta médica puede salvar o mejorar la calidad de vida de los pacientes, por ello, desarrollar modelos precisos y eficientes puede ayudar a los profesionales médicos en la toma de decisiones clínicas y en la personalización de los tratamientos.

Este desafío consiste en entrenar un modelo de aprendizaje automático que pueda predecir la presencia de enfermedad en el corazón basándose en las características recogidas en diferentes pruebas médicas como variables clínicas.

## Descripción del dataset

### Etiquetas

El conjunto de datos se proporciona en formato CSV y contiene información sobre 866 pacientes con diferentes grados de enfermedad (1-4) o ausencia de la misma (0). Este dato puede obtenerse de la columna 'label'

### Características

Además, el conjunto de datos está compuesto por 13 características adicionales que describen las condiciones de salud de cada uno de los pacientes. Estas características se describen a continuación:

```
1. age: edad del paciente       
  2. sex: sexo del paciente       
  3. cp: tipo de dolor de pecho:
                1: angina típica
                2: angina atípica
                3: dolor no-anginoso
                4: asintomático
  4. trestbps: presión arterial en reposo (en mm Hg al ingreso en el hospital)
  5. chol: colesterol sérico en mg/dl
  6. fbs: nivel de azúcar en ayunas > 120 mg/dl  (1 = verdadero; 0 = falso)
  7. restecg: resultados electrocardiográficos en reposo
                         0: normal
                         1: presenta anormalidad de la onda ST-T (inversiones de la onda T y/o elevación o depresión del 
                             ST elevación o depresión del ST > 0,05 mV)
                         2: presenta probable o definida hipertrofia ventricular izquierda
  8. thalach: frecuencia cardiaca máxima
  9. exang: angina inducida por el ejercicio (1 = sí; 0 = no)
  10. oldpeak: depresión del ST inducida por el ejercicio en relación con el reposo
  11. slope: la pendiente del segmento ST en ejercicio máximo
                        1: pendiente ascendente
                        2: plano
                        3: pendiente descendente
  12. ca: número de vasos mayores (0-3) coloreados por flouroscopia      
  13. thal: 3 = normal
                6 = defecto fijo 
                7 = defecto reversible

```

## Split

La columna "split" identifica si esa muestra pertenece al conjunto de entrenamiento 'train' o de validación 'val'.
