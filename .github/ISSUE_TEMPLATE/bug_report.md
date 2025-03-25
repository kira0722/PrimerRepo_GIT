name: bug report
about: crea un reporte de error para ayudarnos a mejorar
title: "[BUG] descripcion breve"
labels: bug
assignees: ''

Título: Problema con [Nombre del Flujo de Trabajo/Acción/Configuración] en .github

Descripción:

Se ha encontrado un problema con [Nombre del flujo de trabajo, acción de GitHub, configuración, etc.] ubicado en la carpeta .github del repositorio. El problema específico es [Describe el problema detalladamente. Por ejemplo: "el flujo de trabajo de CI/CD no se está ejecutando", "la acción de GitHub Actions falla con un error de permisos", "la configuración de la plantilla de pull request no se muestra correctamente", etc.].

Pasos para reproducir:

[Paso 1: Describe el primer paso para reproducir el problema.]
[Paso 2: Describe el segundo paso, y así sucesivamente.]
[Paso final: Describe el último paso que lleva al error.]
Comportamiento esperado:

[Describe el comportamiento que debería ocurrir en lugar del error.]

Comportamiento actual:

[Describe el comportamiento que ocurre actualmente, incluyendo mensajes de error, capturas de pantalla, etc.]

Información adicional:

Entorno: [Sistema operativo, versión de Git, etc.]
Versión del repositorio: [Hash del commit, rama, etc.]
Capturas de pantalla: [Adjunta capturas de pantalla si es relevante.]
Registros (logs): [Adjunta los registros de errores o logs relevantes.]
Cualquier otra información que considere de importancia.
Posibles causas:

Conflicto en los archivos YAML.
Errores de sintaxis.
Problemas de permisos dentro de las acciones de GitHub.
Problemas de compatibilidad con versiones de dependencias.
Sugerencias:

Revisar la sintaxis de los archivos YAML.
Verificar los permisos de las acciones.
Actualizar las dependencias de las acciones.
Ejemplo específico

Título: El flujo de trabajo de CI/CD no se está ejecutando después de cambios en .github/workflows/main.yml

Descripción:

Después de realizar cambios en el archivo .github/workflows/main.yml, el flujo de trabajo de integración continua (CI/CD) ya no se ejecuta automáticamente al enviar cambios a la rama principal.

Pasos para reproducir:

Realizar un cambio en el archivo .github/workflows/main.yml.
Enviar los cambios a la rama principal (main).
Observar la pestaña "Actions" en GitHub: el flujo de trabajo no se inicia.
Comportamiento esperado:

El flujo de trabajo de CI/CD debería iniciar automáticamente después de enviar cambios a la rama principal.

Comportamiento actual:

El flujo de trabajo no se inicia y no se muestra ningún error en la interfaz de GitHub Actions.

Información adicional:

Sistema operativo: Ubuntu 20.04
Versión de Git: 2.27.0
El archivo modificado está en la ruta .github/workflows/main.yml