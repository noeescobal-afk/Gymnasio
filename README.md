 Sistema de Gestión de Gimnasio
Sistema completo de gestión para gimnasios desarrollado con Python y SQLite. Permite administrar socios, instructores, clases e inscripciones de manera eficiente.
 Características

Gestión de Socios: Alta, baja, modificación y consulta de miembros Gestión de Instructores: Administración de personal y especialidades
Gestión de Clases: Registro de clases con horarios y capacidades
Sistema de Inscripciones: Inscripción de socios a clases con validaciones
 Triggers Automáticos: Auditoría y validaciones en la base de datos
 Vistas SQL: Consultas optimizadas para reportes
 Transacciones Seguras: Garantía de integridad de datos

 Estructura del Proyecto
proyecto-gimnasio/
├── database/           # Base de datos SQLite
│   └── gimnasio.db
├── src/               # Código fuente Python
│   ├── crear_base_datos.py    # Inicialización de BD
│   ├── crud_consultas.py      # Operaciones CRUD
│   ├── avanzado.py            # Triggers y vistas
│   └── app_principal.py       # Aplicación principal
├── docs/              # Documentación
│   ├── informe_tecnico.pdf
│   └── capturas/
├── README.md
└── requirements.txt
🚀 Instalación
Requisitos Previos

Python 3.8 o superior
pip (gestor de paquetes de Python)

Pasos de Instalación

Clonar el repositorio

bashgit clone https://github.com/TU_USUARIO/sistema-gestion-gimnasio.git
cd sistema-gestion-gimnasio

Instalar dependencias

bashpip install -r requirements.txt

Crear la base de datos

bashpython src/crear_base_datos.py
💡 Uso
Crear la Base de Datos Inicial
bashpython src/crear_base_datos.py
Ejecutar Operaciones CRUD
bashpython src/crud_consultas.py
Consultas Avanzadas (Triggers y Vistas)
bashpython src/avanzado.py
Aplicación Principal
bashpython src/app_principal.py
📊 Modelo de Datos
El sistema cuenta con las siguientes tablas principales:

socios: Información de miembros del gimnasio
instructores: Datos del personal instructor
clases: Catálogo de clases disponibles
inscripciones: Relación socios-clases
classes_instructores: Relación clases-instructores

🔧 Funcionalidades Técnicas
Triggers Implementados

Auditoría automática de inscripciones
Validación de duplicados
Registro de cambios en log

Vistas Creadas

v_resumen_clases: Resumen de clases con número de inscritos
Consultas optimizadas con JOINs múltiples

Transacciones

Rollback automático en caso de errores
Garantía de consistencia de datos

Nikolai Suarez - Desarrollo Backend y Base de Datos
Escobal Noe oswaldo- Desarrollo de Lógica de Negocio Documentación y Pruebas


GitHub Issues
Email: noe.escobal@tecsup.edu.pe
