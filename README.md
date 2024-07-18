Proyecto Final: Aplicación de Cálculo de Planilla para Micro Empresa
Descripción
Este proyecto consiste en una aplicación para el cálculo de la planilla de una micro empresa. La aplicación permite a los usuarios gestionar empleados, usuarios y la planilla de pagos a través de una interfaz gráfica. Incluye funciones de autenticación, encriptación de contraseñas y diversas pantallas para la administración de datos.

Requisitos
Verificación de datos de entrada contra una tabla de usuarios (tbl_usuarios).
Contraseñas encriptadas en la tabla de usuarios.
Pantalla principal con menús para Empleados, Usuarios, Planilla y Salir.
Mostrar el nombre y apellido del usuario en la pantalla principal.
Funcionalidades
Pantalla de Empleados
Búsqueda de empleados: Todos los campos de texto están inhabilitados excepto la cédula de búsqueda y el botón de búsqueda.
Nuevo empleado: Habilita campos de texto para datos del empleado.
Editar empleado: Habilita campos de texto para modificar datos del empleado.
Guardar empleado: Inserta o actualiza registros en la base de datos.
Pantalla de Usuarios
Funcionalidades similares a la pantalla de empleados para la gestión de usuarios en tbl_usuarios.
Pantalla de Planilla
Crear planilla: Inserta un registro en tbl_planilla y obtiene el ID de la planilla.
Adicionar empleados a la planilla: Introducción de cédula, horas trabajadas y salario por hora. Validaciones de horas trabajadas (4-12 horas) y salario por hora (5.00-20.00).
Ver planilla: Muestra una tabla con el contenido de tbl_planilla, tbl_detalle_planilla y tbl_empleado.
Tablas de la Base de Datos
tbl_usuario: Cedula (PK), UserID, Contraseña, Nombre, Apellido, Dirección, Fecha de Ingreso.
tbl_empleado: Cedula (PK), Nombre1, Nombre2, Apellido, Apellido2, Fecha de Nacimiento, Dirección, Teléfono.
tbl_planilla: id_planilla (PK, autoincrement), fecha.
tbl_detalle_planilla: id_planilla, cedula_empleado, horas_trabajadas, salario_por_horas, salario_bruto, seguro_social, seguro_educativo, salario_neto.
Detalles Técnicos
Clases definidas para manejar datos de empleados, usuarios y planillas.
Procedimientos almacenados para la inserción y consulta de datos en la base de datos.
Requisitos de Instalación
Clonar el repositorio: git clone https://github.com/tu_usuario/proyecto-final.git
Configurar la base de datos con las tablas mencionadas.
Ejecutar la aplicación.
Uso
Iniciar sesión con credenciales válidas.
Utilizar el menú principal para navegar entre Empleados, Usuarios y Planilla.
Administrar datos según las funcionalidades descritas.
Contribuciones
Las contribuciones son bienvenidas. Por favor, enviar un pull request para revisión.
