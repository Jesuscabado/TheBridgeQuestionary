# TheBridgeQuestionary
Full Stack | Blooket Manager Pro 🎓

Una herramienta interna diseñada para los instructores de The Bridge - Digital Talent Accelerator. Esta aplicación permite centralizar, filtrar y generar cuestionarios personalizados para Blooket, adaptándose al ritmo de cada clase.
🚀 Características Principales

    Banco de Preguntas Centralizado: Más de 250 preguntas pre-cargadas sobre Full Stack Development (Bash, HTML/CSS, JS, Node, Mongo, React, etc.).

    Filtrado por Temática: Organiza y visualiza preguntas específicas de un solo módulo.

    Guardado Automático (Local API): Conexión directa con el archivo de base de datos para persistir cambios sin descargas manuales (en navegadores compatibles).

    Importación Inteligente: Capacidad de añadir nuevos archivos CSV de Blooket y clasificarlos automáticamente por temas.

    Generador de Cuestionarios: Selección "a la carta" de preguntas para exportar un archivo CSV listo para subir a la plataforma Blooket.

📂 Estructura del Proyecto

El proyecto se compone de dos archivos principales que deben residir en la misma carpeta:

    index.html: La interfaz de la aplicación y la lógica de gestión.

    questions_data.js: El archivo que actúa como base de datos (contiene el array JSON de preguntas).

🛠️ Instalación y Configuración Local

No requiere instalación de servidores ni dependencias de Node.js.

    Descarga index.html y questions_data.js en una misma carpeta.

    Abre index.html utilizando un navegador moderno (Google Chrome o Microsoft Edge son recomendados para las funciones de autoguardado).

📖 Guía de Uso
1. Activar el Guardado Automático

Para evitar tener que descargar el archivo de base de datos cada vez que añadas preguntas:

    Haz clic en el botón "Enlazar questions_data.js" en la parte superior.

    Selecciona el archivo questions_data.js de tu carpeta local.

    Concede permisos de edición cuando el navegador te lo solicite.

2. Importar nuevas preguntas

    Ve a la sección "Añadir Preguntas".

    Sube un archivo CSV que siga la plantilla de Blooket.

    Asigna un nombre al tema (ej: Módulo 3 - Avanzado).

    Si el archivo está enlazado, se guardará automáticamente en el disco duro.

3. Generar un Cuestionario para Clase

    Usa el filtro de temas para encontrar las preguntas deseadas.

    Marca los checkboxes de las preguntas que quieres incluir.

    Haz clic en "Descargar Cuestionario CSV".

    Sube el archivo resultante a tu panel de Blooket -> Import CSV.

🎨 Identidad Visual

La herramienta utiliza la paleta de colores oficial de The Bridge:

    Morado Principal: #4c1d95

    Morado Oscuro: #2e1065

    Fondo: #f8fafc (Light Slate)

⚠️ Notas de Seguridad

    Privacidad: Todos los datos se procesan y guardan localmente en tu ordenador. Nada se envía a servidores externos.

    Compatibilidad: La función de autoguardado directo requiere navegadores basados en Chromium (Chrome/Edge). En otros navegadores, el sistema funcionará en "Modo de Descarga Manual".
