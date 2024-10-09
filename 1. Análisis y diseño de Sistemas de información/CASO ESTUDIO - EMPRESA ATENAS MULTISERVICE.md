# Caso de estudio: Empresa Atenas Multiservice S.A.C
La Empresa ATENAS MULTISERVICE SAC es una empresa dedicada a las ventas al por mayor y menor de bebidas, alimentos y electrodomésticos; como estrategia de mercado cuenta con diversas sucursales que se encuentran distribuidos en Lima y Callao, quieren expandirse a provincias para finalmente internacionalizarse. El comité corporativo tiene previsto ampliar la cantidad de colaboradores con la que actualmente cuenta la organización, para ello como prioridad se va a repotenciar tecnológicamente el departamento de Recursos Humanos de acuerdo a sus necesidades de requerimiento y contratación de personal.

El departamento de Recursos Humanos como parte de sus requerimientos requiere el desarrollo de un sistema de información que le facilite la contratación de personal de los proyectos informáticos que actualmente está gestionando, para ello lo contrata a Ud., en su rol de Analista de Sistemas para que determine los procesos a desarrollar cuyo flujo de trabajo de las actividades que debe realizar el sistema se detallan a continuación:

Cada Jefe de proyecto se encargara de registrar las solicitudes de personal detallando internamente según perfiles el personal que formara su proyecto. El jefe de proyecto tendrá como adicional una opción para consultar el estado de la solicitud de personal, el jefe de sistemas se encarga de evaluar las solicitudes de personal, adicionalmente el jefe de sistemas podrá agregar, modificar o dar de baja los perfiles.

Todas las solicitudes aprobadas por el jefe de sistemas son atendidas por el jefe de contrataciones quien asigna un especialista de contrataciones para atender la solicitud. El especialista de contrataciones complementa la información (fecha de examen, fecha de entrevista, sueldo, tipo de contrato, etc.) de la solicitud y publica en el portal de la empresa. Las personas en general pueden ingresar al portal y proceder a su postulación registrando su ficha de inscripción a las solicitudes existentes. El asistente de contrataciones al termino de las evaluaciones de cada postulante, deberá de registrar las notas obtenidas en dichas evaluaciones (psicológica, conocimiento y entrevista). El especialista de contrataciones al final del proceso consultara los resultados obtenidos por los postulantes y genera los contratos a quienes ganaron la convocatoria.

La solución deberá de estar disponible para una intranet desarrollada en Lenguaje de Programación Java, con manejador de base de datos Sql Server y en el portal de la empresa para que puedan postular los interesados. 
## Flujo Básico de Registrar solicitud de Personal
El sistema muestra la interfaz “Registrar Solicitudes” con los siguientes datos:
- Datos del Solicitante: Nro. Registro, nombre y cargo. Cargados automáticamente. 
- Datos del evaluador Nro. Registro, nombre y cargo. Cargados automáticamente.
- Datos de los perfiles: lista desplegable de los perfiles (Ingeniero, Analista, programador, analista de calidad, analista Funcional, DBA, Diseñador software, etc.), un campo cantidad y una opción para agregar Perfil 
- Además una cuadricula con los campos: perfil y cantidad
- Además Incluye las opciones: Registrar y Cerrar
- El jefe de proyecto selecciona un perfil de la lista desplegable
- El jefe de proyecto ingresa la cantidad.
- El jefe de proyecto selecciona Agregar Perfil
- El sistema agrega los datos en la cuadricula de detalle.
- Si el jefe de proyecto desea agregar otro perfile se repiten los pasos del 3 al 6
- El jefe de proyecto selecciona el botón Registrar
- El sistema genera el Nro. de Solicitud, registra la solicitud con el detalle en estado pendiente.
- El sistema Muestra el MSG “Nro. de Solicitud “ 99999”
- El jefe de proyecto selecciona la opción Cerrar.
- El sistema cierra la interfaz “Registro de Solicitud”, retornando al menú principal del sistema y el caso de uso finaliza
## Modelo de Caso de Uso del Negocio
![Semana 3 - Modelo de caso de uso del negocio](https://youtu.be/1hsXl3twwho?si=6SDeq4YVTc1VBpC1)
## Modelo de Análisis del Negocio
![Semana 3 - Modelo de análisis del negocio](https://youtu.be/n8jfuf1iJqI?si=EaWkdYu9PGd1JPtU)