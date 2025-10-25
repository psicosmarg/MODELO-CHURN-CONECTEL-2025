# Modelo Predictivo de Fuga de Clientes (Churn) para el Sector Telecomunicaciones

Un proyecto de Gutierrez Fernandez, Jesus Osmar y Marcelo Porcayo, Tonancy Lizahaya \| Especialistas del Comportamiento

## 1. Contexto del Problema de Negocio

"ConnecTel", una empresa líder en telecomunicaciones, enfrentaba una costosa "hemorragia" de clientes (churn) que afectaba su rentabilidad. Las estrategias de retención masivas resultaban ineficientes. El objetivo de este análisis fue pasar de la intuición a la evidencia, utilizando Machine Learning para identificar los perfiles de clientes con mayor riesgo de fuga y diseñar una estrategia de retención proactiva y quirúrgica.

## 2. Pregunta de Análisis

> ¿Qué características de servicio y de cliente (contrato, antigüedad, etc.) son los predictores más fuertes de la probabilidad de que un cliente abandone el servicio?

## 3. Metodología y Datos

Se utilizó un modelo de **Árbol de Decisión (CART)**, una técnica de "caja blanca" que revela las reglas de negocio detrás de sus predicciones. El modelo fue entrenado y validado con el dataset estándar de la industria "Telco Customer Churn", logrando una precisión del **79%** en la identificación del comportamiento de fuga en datos no vistos.

## 4. Hallazgo Clave: El Perfil del Cliente en Riesgo

El análisis reveló que el riesgo de churn no es aleatorio, sino que está altamente concentrado en un perfil muy específico. El modelo nos proporcionó la "receta" exacta del cliente con mayor probabilidad de irse.

## 5. Visualización Principal: El Mapa de Decisión

El Árbol de Decisión nos muestra el camino exacto hacia la fuga. La decisión más importante que toma el modelo se basa en el tipo de contrato, seguido por la antigüedad del cliente.

![Árbol de Decisión para la Fuga de Clientes](visualizaciones/arbol_decision_churn_publico.png)

El perfil de riesgo máximo es claro: **Un cliente nuevo (baja antigüedad), con un contrato mes a mes y que tiene contratado el servicio de Fibra Óptica.**

## 6. Conclusión y Estrategia Propuesta (ROI)

El descubrimiento de este perfil nos permite aplicar una "destrucción creativa" (Schumpeter) a las estrategias de retención masivas. Proponemos un enfoque focalizado y de alto ROI:

1.  **Intervención Temprana:** Implementar un programa de onboarding especializado para el segmento de alto riesgo.
2.  **Incentivar el Compromiso:** Crear campañas para migrar a los clientes "mes a mes" a contratos anuales.

Este enfoque permite a "ConnecTel" dirigir sus recursos de manera eficiente, actuando únicamente sobre el segmento que más lo necesita y en el momento más crítico.
