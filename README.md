Colegiaturas
============

************* Que es y que hace este sistema

COLEGIATURAS es un sistema hecho para el registro de pagos de colegiaturas en una institucion educativa.

Puede registrar Alumnos, grupos de alumnos y ciclos escolares. Un ciclo escolar se registra desde una
fecha inicial hasta una fecha final, lo cual indica su periodo de vigencia, por cada ciclo escolar
se han de registrar dos costos, el de inscripcion y el de mensualidad.

Aunque al registrar un ciclo puede indicar dos fechas cualquiera como inicial y final el sistema esta
hecho para ciclos de un año y al crear un ciclo siempre se consideran trece pagos que son la inscripcion
y doce mensualidades.

Para registrar alumnos solo se manejan datos basicos, nombre y apellidos, porcentaje de beca (si maneja
becas), nombre de los padres y telefono de contacto con los padres.

Para registrar grupos, cada grupo debe tener un grado y una letra denominativa, por ejemplo 1A, 1B etc.
Cada grupo debe pertenecer a un ciclo educativo registrado. En cada grupo puede haber N alumnos, al
agregar un alumno a un grupo se crearan sus registros de pagos por el concepto de inscripcion y doce
mensualidades.

Para los grupos solo se consideran grados del 1ro al grado 6to.

Teniendo grupos y alumnos registrados puede registrar un pago a traves de la vista de Registrar Pago.
Para registrar un pago debe indicar el nombre del alumno, seleccionar el alumno dando doble click sobre
su nombre y seleccionar el grupo del cual desea ver el registro de pagos (el alumno puede pertenecer a uno
o mas grupos) Al abrir la ficha de pagos vera los trece conceptos posibles debe elegir el concepto a pagar
(inscripcion o mensualidad) y dar clic sobre el concepto, la cantidad del costo del concepto
se carga previamente, en caso de ser alumno con beca el costo aparece con el descuento debido,
en cualquier caso la cantidad del costo se puede editar y se puede guardar como pago definitivo o 
abono, en caso de registrar abonos, puede registrar N abonos y el registro se marcara como abonado hasta
que registre una cantidad con el modo final.

Puede buscar deudores por concepto de pago y ciclo escolar, al buscar deudores puede imprimir un reporte
de deudores.

Puede hacer corte de caja de un periodo determinado de dias y generar un reporte de ingresos, este reporte
tambien se puede imprimir.

En la seccion sistema puede indicar el nombre de la institucion, dicho nombre aparecera en el titulo de
la ventana principal del sistema asi como en los reportes impresos.

Las restricciones de trece conceptos de pago y solo seis grados posible se deben a que el sistema esta
ideado para una escuela nivel primaria de acuerdo al modelo educativo Mexicano.

A modo de muestra al descargar el sistema contiene algunos registros guardados (* datos ficticios)

************* Algunos datos de Desarrollo

  Aplicacion de escritorio
  Desarrollado usando el JDK 6
  IDE Netbeans 7.2.1
  Interfaces usando swing
  Base de datos Derby (Modo Embedded)
  JPA a traves de la implementacion de EclipseLink2.3.2
  JasperReports 5.1.0
    Otras librerias
  coatldev_beans version 0.23
