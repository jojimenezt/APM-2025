---
title: "Insurance"
date: 2019-05-18T12:33:46+10:00
weight: 7
---

Para alcanzar un alto nivel de automatización, seguridad y eficiencia en el proceso de ensamblaje, se planteó la incorporación de celdas robóticas especializadas y equipos industriales.
# Etapa Seleccionada: Instalación de Baterías (Celda Robótica)
Esta etapa fue identificada como crítica y prioritaria debido a su complejidad operativa y su alto impacto en la seguridad del producto final. La manipulación e instalación de las baterías requiere precisión, fuerza controlada y repetibilidad, lo que la convierte en una candidata ideal para ser automatizada mediante robótica industrial, dado a que contribuye significativamente a reducir riesgos de fallos eléctricos por errores de conexión.

-	Aplicación del robot: Pick & Place + herramienta de torque
-	Estado del material de entrada: Paquete de baterías en bandeja, con cables parcialmente preparados
-	Estado del material de salida: Batería instalada y ajustada correctamente sobre el chasis del vehículo
  

# Etapa Opcional: Pruebas Eléctricas y Verificación de Cargadores (Celda Semiautomatizada)
Como posible ampliación, se propone una segunda celda orientada a realizar las pruebas eléctricas finales de cada unidad ensamblada, asegurando el correcto funcionamiento de los sistemas eléctricos.

- Aplicación del robot: Inspección y pruebas con sensores y visión artificial
- Estado del material de entrada: Motocicleta completamente ensamblada con sistema eléctrico activo
- Estado del material de salida: Vehículo validado en cuanto a encendido, luces, cargador y motor
  
Esta celda puede implementarse con un alto grado de automatización o como una estación semiautomatizada con interfaz HMI, sensores y procedimientos guiados para los operarios.

# Equipos Evaluados para Automatización
Se evaluaron múltiples robots industriales según la carga útil y el alcance necesarios en cada etapa del proceso:

- ABB IRB 6600 – Carga: 150 kg.
- KUKA KR 60-3 – Carga: 60 kg.
- ABB IRB 2600 – Carga: 20 kg.
  
Adicionalmente, se consideró la incorporación de centros de mecanizado CNC, como el Haas VF-2SS y el Mazak QT-Primos 100 SG, para la fabricación precisa de piezas como carcasas y ejes estructurales.
También se incluyó la instalación de una cinta transportadora especializada para motocicletas monoplaza, la cual permite un flujo continuo y sincronizado de las unidades entre estaciones de trabajo, reduciendo tiempos muertos y riesgos por manipulación manual.

![](TextoImagenes/manipuladores.png)
![](TextoImagenes/OtraMaq.png)

# Seguridad en Celdas Robotizadas

Dado el carácter crítico de las operaciones seleccionadas, se plantea la definición de criterios de seguridad industrial para el diseño de las celdas.

Para garantizar un entorno de trabajo seguro, se tendrá en cuenta la identificación de los elementos peligrosos en el proceso, la evaluación de riesgos conforme a las normas ISO 12100 y 14121, y la determinación del nivel de seguridad requerido (PLr) según la norma ISO 13849-1. Esto permitirá establecer medidas adecuadas de mitigación y control.

El diseño de las celdas incorporara componentes de seguridad industrial como cortinas fotoeléctricas, enclavamientos, paros de emergencia y sensores redundantes, todos integrados a través de un sistema de control confiable y validado. Además, se definieran procedimientos operativos seguros para ingreso, mantenimiento y operación de las estaciones, asegurando que las personas y los equipos estén protegidos en todo momento.
En conjunto, estas acciones permiten no solo cumplir con los estándares internacionales, sino también asegurar la continuidad del proceso productivo sin comprometer la seguridad.

