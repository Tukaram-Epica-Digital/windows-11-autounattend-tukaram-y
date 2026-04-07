Windows 11 AutoUnattend

Archivo autounattend.xml para crear una instalación desatendida de Windows 10 y Windows 11, más limpia, rápida y personalizada.

Este proyecto está pensado para usuarios que quieren controlar su instalación desde cero, evitar el bloatware innecesario y aplicar ajustes básicos de privacidad, rendimiento y personalización sin depender de scripts raros ni ISOs modificadas.
Requisitos

    Windows 10 o Windows 11.

    Probado en Windows 10 22H2 y Windows 11 23H2, 24H2 y 25H2.

    Compatible con arquitecturas de 32 bits, 64 bits y ARM64.

¿Qué hace este archivo?

El archivo de respuesta autounattend.xml permite automatizar gran parte del proceso de instalación de Windows.
Incluye descripciones detalladas de casi todas las configuraciones y ajustes del registro, para que puedas revisar y modificar todo con total transparencia.

Para personalizarlo, descarga el archivo y ábrelo con editores como Cursor o VS Code.
Funciones principales

    Permite elegir la edición de Windows, salvo que el instalador detecte una clave en la BIOS/UEFI.

    Evita los requisitos de hardware de Windows 11.

    Omite la creación obligatoria de una cuenta Microsoft durante la instalación.

    Elimina la mayoría del bloatware preinstalado, excepto Bloc de notas, Calculadora, Paint y Recortes.

    Elimina Copilot, OneDrive y Edge, junto con otras apps UWP.

    Desactiva Recall.

Optimización aplicada

    Privacidad y seguridad: desactiva la telemetría y la publicidad.

    Energía: importa y aplica el plan de energía Winhance para mejorar el rendimiento.

    Juegos y rendimiento: ajusta opciones visuales, pone en manual servicios innecesarios y desactiva tareas programadas innecesarias.

    Windows Update: desactiva las actualizaciones automáticas y deja solo avisos de actualizaciones de seguridad disponibles.

    Notificaciones: desactiva todas, excepto las relacionadas con privacidad y seguridad.

    Sonido: desactiva el sonido de inicio y configura el ducking de audio en “No hacer nada”.

Personalizaciones aplicadas

    Tema de Windows: activa el modo oscuro por defecto y desactiva la transparencia.

    Barra de tareas: oculta búsqueda, vista de tareas y widgets, y la alinea a la izquierda en Windows 11.

    Menú Inicio: desancla todos los elementos y desactiva los resultados de Bing.

    Explorador de archivos: activa el menú contextual clásico, abre el Explorador en “Este equipo”, muestra las extensiones de archivo, oculta las carpetas Inicio y Galería en el panel de navegación, y más.

Cómo usarlo

    Descarga autounattend.xml.

    Copia el archivo en la raíz del USB de instalación de Windows.

    Arranca el equipo desde ese USB.

    Sigue el proceso de instalación automática.

Recomendación importante

Antes de instalar, haz siempre una copia de seguridad de todos tus archivos.
También es recomendable probar primero en una máquina virtual antes de usarlo en tu PC principal.
Aviso

Este proyecto está pensado para aprendizaje, personalización y uso personal.
Revisa siempre el contenido antes de aplicarlo, especialmente si quieres adaptar la instalación a tu propio equipo o entorno.
Vídeo relacionado

Este archivo acompaña al vídeo:

WINDOWS 11 DEBLOAT TU MISMO
