# 🏎️ WebXR AR Car Viewer

Una experiencia de **Realidad Aumentada (AR)** basada en web que permite proyectar y explorar un modelo 3D detallado de un automóvil en el mundo real. Desarrollado con **A-Frame** y la API de **WebXR**, este proyecto elimina la necesidad de instalar aplicaciones nativas, funcionando directamente desde el navegador móvil.

## 🚀 Características

* **Detección de Suelo (Hit-Test):** Utiliza sensores avanzados para anclar el modelo 3D a superficies del mundo real.
* **Visualización 360°:** El usuario puede caminar físicamente alrededor del objeto para inspeccionar detalles.
* **Iluminación Realista:** Configuración de luces ambientales y direccionales para resaltar materiales metálicos y texturas GLB.
* **Zero-Install:** Accesible mediante una URL simple en navegadores compatibles con WebXR (Chrome en Android).

## 🛠️ Tecnologías utilizadas

* [A-Frame](https://aframe.io/) - Framework web para construir experiencias de VR/AR.
* [WebXR Device API](https://www.w3.org/TR/webxr/) - Estándar para el acceso a dispositivos de realidad inmersiva.
* **HTML5 / JavaScript** - Lógica de la aplicación.
* **GLTF/GLB** - Formato de transmisión eficiente para modelos 3D.

## 📋 Requisitos para el funcionamiento

Para que la detección de AR funcione correctamente, el proyecto debe cumplir con:
1.  **Protocolo HTTPS:** Los navegadores bloquean las funciones de AR en sitios que no son seguros.
2.  **Compatibilidad:** Dispositivo Android con **Google Play Services para RA** (ARCore) instalado.
3.  **Navegador:** Google Chrome actualizado.

## 🔧 Instalación y Despliegue

1. Clona este repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/nombre-del-repo.git](https://github.com/tu-usuario/nombre-del-repo.git)
   git clone [https://github.com/tu-usuario/nombre-del-repo.git](https://github.com/tu-usuario/nombre-del-repo.git)
