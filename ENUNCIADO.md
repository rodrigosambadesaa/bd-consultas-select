# Enunciado original — Práctica Consultas SELECT

Fuente: `Práctica Consultas Select.pdf` de Google Drive. La entrega recuperada en este repositorio corresponde a los ejercicios **8–43**.

8. Hallar los empleados con comisión superior a la mitad de su salario.
9. Hallar los empleados cuya comisión sea menor o igual que el 25 % del sueldo.
10. Anteponer `Nombre ` y `Puesto ` a sus valores mediante `CONCAT`.
11. Hallar salario y comisión de empleados cuyo número supere 7500.
12. Obtener nombres y puestos del grupo alfabético que comienza en J, ordenados por ambos campos.
13. Obtener salario, comisión y salario total de empleados con comisión, ordenados por número.
14. Ídem para empleados sin comisión.
15. Unificar 13 y 14 con `UNION`.
16. Obtener el mismo resultado mediante `IF` de MySQL.
17. Hallar empleados con salario > 1000 cuyo jefe sea el empleado 7698.
18. Hallar el conjunto complementario del ejercicio anterior.
19. Calcular el porcentaje de la comisión sobre el salario total, controlando nulos y ordenando por nombre.
20. Hallar empleados del departamento 10 cuyo nombre no contenga `LA`.
21. Obtener empleados no supervisados por ningún otro.
22. Obtener nombre y departamento de administrativos que no trabajen en el departamento 10 y cobren más de 800, ordenados por fecha de alta.
23. Empleados cuyo nombre tenga exactamente cinco caracteres.
24. Empleados cuyo nombre tenga al menos cinco caracteres.
25. Datos de empleados cuyo nombre empiece por A y salario > 1000, o que reciban comisión y trabajen en el departamento 30.
26. Nombre y salario total de empleados con comisión, ordenados por salario total.
27. Mostrar nombre, salario actual, salario futuro con subida del 6 % e indicar si tienen comisión.
28. Obtener los empleados con números 7844, 7900, 7521, 7782, 7934, 7678 y 7369 usando un predicado compacto.
29. Entre empleados cuyo director tenga número mayor que el suyo, obtener quienes cobren entre 1000 y 2000 o estén en el departamento 30.
30. Obtener salario máximo de la empresa, total de comisiones y número de empleados.
31. Mostrar nombres, puestos y salarios de quienes igualen o superen el salario de ALLEN.
32. Hallar el último empleado por orden alfabético usando `LIMIT`.
33. Hallar salario máximo, mínimo y diferencia entre ambos.
34. Sin reutilizar 33, indicar quiénes cobran el máximo y el mínimo y sus importes.
35. Mostrar departamento y salario medio de departamentos cuya media sea > 900, considerando salarios < 5000.
36. Empleados cuyo salario iguale o supere la media de la empresa.
37. Empleados cuyo salario supere al de sus compañeros de departamento.
38. Contar empleados con comisión.
39. Departamentos con más de tres empleados y su número de empleados.
40. Empleados del departamento 10 que tengan el mismo puesto que alguien de VENTAS.
41. Departamentos sin empleados.
42. Empleados que trabajen en Dallas o New York.
43. Departamento cuya suma de salarios sea la más alta y valor de dicha suma.

## Base de datos

Este repositorio ya conserva la base necesaria en [`database/empresa.sql`](database/empresa.sql); no se duplica en otra ubicación.
