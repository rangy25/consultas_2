# consultas_2
![competitivo1](imagen/competitivo01.jpg "competitivo 1") 
![competitivo2](imagen/competitivo02.jpg "competitivo 2") 
![competitivo3](imagen/competitivo03.jpg "competitivo 3") 


# obtener apellidos 
SELECT apellidos_empleado FROM Empleado;
![competitivo4](imagen/competitivo04.jpg "competitivo 4") 

# que no se repita apellidos 

SELECT DISTINCT apellidos_empleado FROM Empleado;
![competitivo5](imagen/competitivo05.jpg "competitivo 5") 

#  apellidos  gomez 
SELECT DISTINCT apellidos_empleado 
FROM Empleado
WHERE apellidos_empleado = 'Gomez';
![competitivo6](imagen/competitivo06.jpg "competitivo 6") 


# Obtener todos los datos de los empleados que se apellidan "Diaz" y los que se apellidan "Rodriguez".  Usar OR o IN

SELECT * 
FROM Empleado
WHERE apellidos_empleado = 'Diaz' OR apellidos_empleado = 'Rodriguez';
![competitivo7](imagen/competitivo07.jpg "competitivo 7") 

# Obtener los nombres de los empleados que trabajan en el departamento 11
SELECT nombre_empleado FROM Empleado WHERE id_departamento = 11;
![competitivo8](imagen/competitivo08.jpg "competitivo 8") 

# Obtener todos los datos de los empleados cuyo apellido empiece por 'P'
SELECT * FROM Empleado WHERE apellidos_empleado LIKE 'P%';
![competitivo9](imagen/competitivo09.jpg "competitivo 9") 

# Obtener el presupuesto total de todos los departamentos.
SELECT SUM(presupuesto_departamento) AS presupuesto_total FROM Departamento;
![competitivo10](imagen/competitivo010.jpg "competitivo 10 ") 


# Obtener el número de empleados de cada departamento.

![competitivo11](imagen/competitivo011.jpg "competitivo 11 ") 



# Obtener un listado completo de empleados, incluyendo por cada empleado los datos del empleado y de su departamento.

![competitivo12](imagen/competitivo012.jpg "competitivo 12 ") 

# Obtener un listado completo de empleados, incluyendo el nombre y apellidos del empleado junto al nombre y presupuesto de su departamento.

![competitivo13](imagen/competitivo013.jpg "competitivo 13 ") 

# Obtener los nombres y apellidos de los empleados que trabajen en departamentos cuyo presupuesto sea mayor a 100000000

![competitivo14](imagen/competitivo014.2.jpg "competitivo 14 ") 
