# 🎮 TecniLauncher
¡Bienvenido al lanzador técnico de Minecraft! Diseñado para ser ligero, elegante y funcional.

## ✨ Características

* **Diseño Moderno:** Interfaz limpia con noticias integradas.
  ![Inicio del Launcher](Media/inicio.png)
  
* **Premium o Offline:** Puedes iniciar con tu cuenta de Microsoft o jugar de modo Offline, tú eliges.
  ![Apartado de Sesión](Media/sesion.png)

* **Gestión de Perfiles:** Crea y edita tus perfiles de Vanilla, Forge, Fabric y NeoForge fácilmente.
  ![Lista de Perfiles](Media/lista_perfiles.png)
  ![Crear Perfil](Media/crear_perfil.png)

* **Gestor de Mods:** Descarga de mods a través de la API de Modrinth.
  ![Apartado Mods](Media/mods.png)
* **Eventos:** Se añadio el sistema de sincronizacion, aun en base fase beta pero funcional para actualizaciones faciles.
  [Github de Ejemplo](https://github.com/johan12390785/EventoEjemplo)

* **Actualizaciones Automáticas:** Mantente siempre en la última versión sin mover un dedo.
* **SISTEMA DE SKIN TODAVIA NO FUNCIONAL** -- Sin avances
## SISTEMAS A IMPLEMENTAR
* Descarga de Modpacks -- Sin avances
* Implementar sincronización con los proximos eventos -- ✅
* Sistema mejorado de Versiones (ej: Fabric 0.18.4-1.21.11) -- ✅

## 🚀 Descarga e Instalación
Para comenzar a jugar, descarga el instalador oficial desde el siguiente enlace:

[📥 DESCARGAR TECNILAUNCHER INSTALADOR](https://github.com/johan12390785/TecniLauncher-Data/raw/refs/heads/main/SetupV1.1.2/TecniLauncher_Setup.exe)
[Version antigua, al descargarlo te va a pedir actualizar]

## 🔒 Seguridad y Privacidad
Entendemos que la seguridad de tu cuenta de Minecraft es lo más importante. Por eso, TecniLauncher está diseñado con una política de **Transparencia Total**:

1.  **Sin Contraseñas:** TecniLauncher **NUNCA** tiene acceso a tu contraseña. El inicio de sesión se realiza a través del protocolo oficial de Microsoft (OAuth 2.0).
2.  **Librerías Certificadas:** Utilizamos `CmlLib.Core.Auth`, la librería de código abierto estándar de la comunidad para manejar la autenticación segura.
3.  **Código Abierto:** Todo el código fuente está disponible en este repositorio. Puedes revisar exactamente qué hacemos con los datos: solo guardamos el *token* de sesión localmente en tu PC para que no tengas que loguearte cada vez.

---

# 📜 Actualizaciones - TecniLauncher

Todas las mejoras, arreglos y optimizaciones del proyecto se documentarán aquí.

# 🚀 TecniLauncher v1.2.2 - *Version Actual*

¡Nueva actualización centrada en la optimización, internacionalización y mejoras visuales!

> [!WARNING]
> **⚠️ CAMBIO CRÍTICO EN EL ALMACENAMIENTO**
> Para optimizar el espacio en disco, hemos cambiado la estructura de carpetas.
> **Por favor, revisa tus perfiles antiguos y mueve tus carpetas `saves` y `screenshots` a la nueva ubicación antes de eliminar nada.**

## ✨ Novedades Principales

### 📂 Optimización de Archivos (Global Assets)
Se ha reescrito la gestión de archivos. Ahora las versiones de Minecraft (Vanilla, Fabric, Forge) se descargan en una **carpeta global compartida**.
* **Beneficio:** Ahorro masivo de espacio. Ya no tendrás versiones duplicadas por cada perfil.
* *Nota: Los "Eventos" mantienen su aislamiento para evitar conflictos.*

### 🌍 Soporte Multi-idioma
La interfaz ahora es totalmente accesible en 3 idiomas (configurable desde Ajustes):
* 🇪🇸 Español
* 🇺🇸 English
* 🇧🇷 Português (Brasil)

### 🎨 Integración Visual con Ely.by
* **Visor de Skins:** El launcher detecta y muestra automáticamente tu skin (Prioridad: Premium > Ely.by > Mojang).
* **Gestión en la Nube:** Botón directo en ajustes para subir o cambiar tu skin en Ely.by.
* *Aclaración: En esta versión (v1.2.2), la skin es visible en el Launcher. La inyección para verla dentro del juego en modo Offline llegará en la v1.3.0.*

### 🧩 Tienda de Mods 2.0
* Búsqueda optimizada conectada a la **API de Modrinth**.
* Nuevo **Selector de Versiones**: Ahora puedes elegir específicamente qué archivo descargar (Release/Beta/Alpha).

---

## 🛠️ Mejoras y Arreglos
* **UI/UX:** Rediseño completo de la pestaña de Ajustes con un formato de tarjetas moderno.
* **Menú Principal:** Reorganizado para priorizar el nuevo sistema de Eventos.
* **Bug Fix:** Solucionado el error de renderizado en la vista previa del personaje (las piernas ya no aparecen cortadas).


# v1.2.1

* **Optimizacion:** Se mejoro la optimizacion de ram.
* **Bug:** Se arreglo un bug se sobre la versiones de fabric.
* **Visual:** Se arreglo un problema visual donde las noticias tapaban el selector de perfiles.


# v1.2.0 

Se Termino el sistema de Eventos y tambien tenemos una plantilla donde te dice como puedes configurar el evento.
[Github de Ejemplo](https://github.com/johan12390785/EventoEjemplo)

# v1.1.7 

Mejoras visuales y agregado de iconos en los perfiles
Se implemento el sistema de eventos (Proximamente)

# v1.1.6
Se arreglo un pequeño bug visual

# v1.1.5

Esta actualización trae mejoras visuales, nuevas opciones de conectividad y mayor precisión en la instalación de mods.

### ✨ Novedades Principales
* **Selección de Versión Exacta:** Ahora puedes elegir la versión específica del ModLoader (Fabric/Forge/NeoForge) manualmente en lugar de instalar siempre la última.
* **Botones de Redes:** Agregados accesos directos a **Discord** y **GitHub** en el menú principal.
* **Mejoras Visuales:** Retoques generales en la interfaz (UI) para un aspecto más moderno y limpio.
* **Detección Automática de RAM:** El launcher ahora detecta tu memoria física real y ajusta el límite del slider automáticamente para evitar configuraciones erróneas.

### 🛠️ Correcciones Técnicas
* **Conectividad:** Mejoras en la seguridad de conexión (TLS 1.2/1.3) para evitar bloqueos de descarga.

### 🐛 Errores Conocidos
* Pequeño detalle visual en el borde inferior al maximizar la ventana en ciertas resoluciones (será corregido para las siguientes versiones).
* 
---

## v1.1.4 (Hotfix)
* **Corrección Crítica:** Solucionado un error que impedía el correcto inicio de usuario Offline con el Minecraft.
* **Auto-Update:** Verificación exitosa del sistema de actualización automática en entorno real.

---

## v1.1.3 (Lanzamiento Estable)
* **Identidad:** Corrección del nombre de usuario (eliminado "tester123").
* **Interfaz:** Estabilización de la Vista de Juego y mejoras visuales en la barra de carga.

---

