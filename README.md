# Optimización de Horarios para Empleados de Sucursal XYZ - Dataton Bancolombia

## Descripción

Este proyecto tiene como objetivo optimizar la programación horaria de los empleados de caja de la sucursal XYZ de Bancolombia. El objetivo principal es definir el estado de cada empleado (trabajando, en pausa activa o almuerzo) en franjas horarias de 15 minutos, minimizando la diferencia entre la cantidad de empleados trabajando y la demanda requerida en cada franja horaria cuando la demanda es mayor a la capacidad.

## Integrantes

- Maikol Vergara
- Victor Peñaranda
- Juliana Castro
- Valentina Leon
- Lukas Rodriguez
- Juan Perez
- Juan Barajas

## Metodología

1. **Cargar los Datos**: Se cargan los datos de demanda y empleados desde un archivo Excel proporcionado.
2. **Definición del Algoritmo de Programación**: Se define un algoritmo para asignar los estados a los empleados en cada franja horaria, asegurando que se cumplan todas las restricciones.
3. **Asignación del Horario**: Se utiliza la función definida para asignar el horario a los empleados y verificar el número de empleados trabajando por franja horaria.
4. **Visualización y Validación**: Se grafican los resultados para validar la alineación de la demanda y la capacidad horaria.
5. **Guardado del Archivo**: Se guarda el nuevo horario en un archivo Excel.

## Restricciones

- Los empleados deben trabajar un mínimo de 1 hora antes de tomar una pausa activa o almuerzo.
- Los empleados deben trabajar un máximo de 2 horas continuas sin una pausa activa.
- El tiempo de almuerzo es de 1.5 horas y debe tomarse una única vez al día, entre las 11:30 am y 1:30 pm.
- La jornada laboral es de 8 horas diarias.
- Debe haber al menos 1 empleado trabajando en cada franja horaria.

## Resultados

- El gráfico muestra que en ningún momento hay franjas horarias sin empleados y que la capacidad se mantiene dentro del rango permitido en relación a la demanda.
- La solución asegura que todas las restricciones especificadas se cumplen.
- Se genera un nuevo horario optimizado para los empleados: `nuevo_horario_v4.xlsx`.

## Conclusión

La programación horaria optimizada desarrollada cumple con los requisitos del reto planteado en la Datatón Bancolombia, garantizando que la demanda de empleados sea satisfecha adecuadamente y que no haya excesos significativos en la capacidad de trabajo.

