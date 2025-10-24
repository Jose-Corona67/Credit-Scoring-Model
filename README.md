# Credit-Scoring-Model

## Descripciónn

Un modelo de scoring crediticio implementado en Python que predice la probabilidad de incumplimiento de clientes utilizando técnicas estadísticas avanzadas.
Este proyecto implementa un sistema de scoring crediticio que utiliza:

- **Weight of Evidence (WoE)** para transformar variables categóricas
- **Regresión Logística** para la predicción de probabilidades
- **Análisis de poder discriminativo** mediante curva ROC y estadístico KS


## Variables Utilizadas

- **Mora_Max**: Mora máxima del cliente (agrupada en categorías)
- **CURRENCY_TYPE**: Tipo de moneda del crédito
- **TYPE_OF_ECONOMY_EN**: Tipo de empleo del cliente
- **Clasificación Real**: Variable objetivo (0 = Bueno, 1 = Malo)

## Metodología
1. **Análisis exploratorio de datos**
2. **Transformación WoE** de variables categóricas
3. **Modelado con Regresión Logística**
4. **Escalado del Score** (0-1000 puntos)
5. **Validación del modelo** (KS, ROC, análisis de estabilidad)

## Resultados
- **R²**: 0.1479
- **Todas las variables significativas** (p-value < 0.05)
- **Buen poder discriminativo** entre buenos y malos pagadores
- **Score escalado** de 70-736 puntos

## Requisitos

- pandas
- numpy
- statsmodels
- scikit-learn
- matplotlib

## Autor

- José Luis Corona López
