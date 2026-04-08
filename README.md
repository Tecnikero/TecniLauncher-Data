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
