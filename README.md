# NSOA_Software
# NSOA Binario aplicado al Set Covering Problem (SCP)

Este repositorio contiene la implementación en Python del **Algoritmo de Optimización por Selección Natural (NSOA)** adaptado a un entorno discreto (binario), utilizando la técnica de binarización en dos pasos (Función Sigmoide + Regla Probabilística). El algoritmo fue puesto a prueba utilizando una instancia real del Set Covering Problem (SCP).

## 📌 Contenido del Repositorio

El proyecto se divide en dos componentes principales:

1. **Optimización Real (Test SCP):** - Script principal que resuelve la instancia `scp41.txt`. 
   - Ejecuta la metaheurística evaluando miles de dimensiones, incluyendo la Fase de Selección Natural completa (eliminación y clonación).
   - Logra evadir óptimos locales para alcanzar un costo de 19.550,0 con 100% de factibilidad.

2. **Ruteo Didáctico (Mini-SCP):** - Script diseñado exclusivamente para la demostración matemática del algoritmo.
   - Trabaja con un entorno controlado de 4 individuos y 3 dimensiones.
   - Imprime el desglose paso a paso de las ecuaciones de movimiento, el cálculo continuo ($SD$, $P_{new}$) y la transformación probabilística en la primera iteración. Ideal para entender la "caja negra" del NSOA.

## ⚙️ Parámetros Base de la Metaheurística
* **Distribución:** Normal
* **Control de Transición ($std$):** Función Sigmoide
* **MaxIter:** 100
* **Delta ($\delta$):** 30
* **Nu ($\nu$):** 0.3

## 👥 Autores
Proyecto desarrollado para la Pontificia Universidad Católica de Valparaíso:
* Joaquín Castro 
* Álvaro Del Pino 
* Sebastián Rojas
