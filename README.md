# dsrp_Trabajo-01

##Escenario: 
Empresa de Tecnología

#Contexto: 
Una empresa de tecnología en rápido crecimiento necesita un sistema para gestionar los datos de sus empleados. La empresa tiene varias oficinas en diferentes ubicaciones y múltiples departamentos, como desarrollo de software, recursos humanos, ventas, y soporte técnico. Los empleados pueden trabajar en más de un proyecto a la vez, y cada proyecto tiene un líder de proyecto asignado.

#Requerimientos:

  #Empleados:
  Cada empleado tiene un identificador único, nombre, apellido, correo electrónico, teléfono, y dirección.
  Los empleados tienen un cargo (por ejemplo, desarrollador, gerente, etc.).
  Cada empleado pertenece a un departamento.
  Se requiere almacenar la fecha de contratación y el salario de cada empleado.

  #Departamentos:
  La empresa tiene varios departamentos. Cada departamento tiene un identificador único, nombre del departamento, y una  
  ubicación específica.
  Cada departamento está dirigido por un jefe de departamento, que es uno de los empleados.

  #Oficinas:
  La empresa tiene varias oficinas en diferentes ubicaciones. Cada oficina tiene un identificador único, dirección, y   
  capacidad máxima.
  Los empleados están asignados a una oficina específica.

#Relaciones:
Un empleado pertenece a un solo departamento.
Un empleado puede trabajar en varios proyectos.
Un proyecto puede tener varios empleados, pero solo un líder de proyecto.
Un empleado está asignado a una sola oficina.
