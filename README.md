# Simulador de Vehículos Autónomos 
Autores: 
- Laurie C. Hernández P.
- Emilio A. González H. @emigzzh
- Hugo E. Gamboa Sesma @hugo-edel
- E. Alejandro Corral Rdz.
---
## Descripción
Este proyecto implementa un simulador **numérico y visual** de una columna de vehículos autónomos usando un modelo básico de seguimiento, para la clase de Modelación de Sistemas con Ecuaciones Diferenciales **MA1002B**.

Incluye: 
- Integración numérica con Runge Kutta de 4to Orden
- Gráficas de posición y velocidad de los vehículos con respecto al tiempo
- **Animación 2D** del movimiento de los vehículos
- **Detección de choques** entre los vehículos
- Menú interactivo para modificar parámetros del sistema.

Este proyecto permite visualizar cómo distintos parámetros como la sensibilidad al espaciamiento, distancia inicial entre los vehículos, la cantidad de vehículos, e incluso la aceleración de los vehículos entre ellos pueden influenciar en el comportamiento del sistema. 

---
```
## Estructura del proyecto
📁 MA1002B-Vehiculos-Autonomos/
├── simulacion_vehiculos_autonomos.py # Archivo de la simulación de los vehículos
├── reporte_final.pdf # Explicación detallada de la simulación
├── media/
│ └── car_sim.gif # GIF que muestra la simulación en funcionamiento
└── README.md # Este archivo
```
--- 
## Animación 2D de la simulación
![Simulación de autos](media/car_sim.gif)

---
## Requisitos para la simulación 
- **Python ≥ 3.8**
- Librerías:
  - `matplotlib`
  - `numpy`
  - `seaborn`
---
