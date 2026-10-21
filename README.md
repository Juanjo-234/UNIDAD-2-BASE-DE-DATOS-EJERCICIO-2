# UNIDAD-2-BASE-DE-DATOS-EJERCICIO-2
Se debe diseñar un modelo entidad-relación (MER) para representar cómo funciona una aerolínea, organizando la información de sus aviones, vuelos, empleados y pasajeros.

El sistema debe permitir registrar:
- Aviones: matrícula, modelo, capacidad máxima y autonomía de vuelo.
- Vuelos: código, ciudad de origen, ciudad de destino y horarios estimados de salida y llegada.
- Empleados: número de empleado, DNI, nombre, fecha de ingreso y categoría profesional, diferenciando pilotos y auxiliares.
- Tripulación: cada vuelo debe tener varios empleados asignados, indicando el rol que cumple cada uno. Un empleado puede participar en varios vuelos.
- Pasajeros: datos de las personas que viajan en la aerolínea.
- Reservas: relacionan a cada pasajero con un vuelo y un asiento determinado.
También se deben definir las relaciones y cardinalidades entre las entidades, teniendo en cuenta que un avión puede realizar muchos vuelos, que cada vuelo en una fecha determinada utiliza un solo avión y que existe una relación muchos a muchos entre vuelos y empleados.
<img width="2492" height="1042" alt="EJERCICIO 2 drawio" src="https://github.com/user-attachments/assets/9f0002e7-0b43-4f3c-888d-f4353aefe944" />

