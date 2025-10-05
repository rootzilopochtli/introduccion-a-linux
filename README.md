# 🚀 Introducción Práctica a Linux: De Usuario Básico a Administrador de Sistemas

Este repositorio alberga el código, los ejemplos y los materiales de soporte para la serie de posts **"Introducción a Linux: De Usuario Básico a Administrador de Sistemas"** del blog **rootzilopochtli**.

El temario ha sido cuidadosamente sintetizado y estructurado, fusionando los temas más importantes y transversales de las certificaciones **LPIC-1**, **LFCS**, y el curso **RHCSA** (RH124 y RH134), garantizando una ruta de aprendizaje práctica y completa.

## Licencias

Este proyecto utiliza una doble estrategia de licenciamiento para distinguir entre el contenido escrito y el código:

1.  **Documentación (Posts, Imágenes, Diagramas, Archivos `.md`, Archivos `.adoc`):**
    * **Licencia:** [Creative Commons Atribución-CompartirIgual 4.0 Internacional (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/deed.es)
    * **Propósito:** Asegurar que el material educativo y sus derivados permanezcan libres y abiertos.

2.  **Código Fuente (Scripts, Ejemplos de Comandos):**
    * **Licencia:** [Licencia MIT](https://opensource.org/licenses/MIT)
    * **Propósito:** Fomentar la máxima reutilización de los ejemplos de código en cualquier proyecto, sin restricciones.

## 📖 Temario

El contenido está dividido en seis secciones clave, diseñadas para guiarte de forma progresiva desde los conceptos fundamentales hasta la administración avanzada del sistema.

### 1. Fundamentos y Arquitectura del Sistema
Esta sección introduce al entorno Linux, cubriendo la historia, la arquitectura básica (**Kernel**, **Shell**, distribuciones), el proceso de arranque (como **GRUB/GRUB2**), y los niveles de ejecución (**systemd targets**). Se explora también la **Estructura de Directorios de Linux (FHS)** y la navegación básica en la **Línea de Comandos (CLI)**.

### 2. Gestión de Archivos y Flujo de Comandos
Profundiza en la manipulación de archivos, incluyendo:
* **Permisos** (**`chmod`**, **`chown`**, **ACLs**) y **Propiedad**.
* Manejo del flujo de datos con **`stdin`**, **`stdout`**, **`stderr`**, **Redirección** y **Tuberías** (`|`).
* Procesamiento de texto con **`grep`**, **`sed`**, **`awk`** y **expresiones regulares (regex)**.
* Diferencia entre **enlaces duros y blandos (simbólicos)**.

### 3. Administración del Sistema Base
Temas esenciales para la administración diaria:
* **Gestión de Usuarios y Grupos** (**`useradd`**, **`sudo`**, archivos clave como `/etc/passwd`).
* **Gestión de Procesos** (**`ps`**, **`top`**, **`kill`**, **`cron`**, **`at`**).
* **Gestión de Software y Paquetes** (`apt` vs. `yum`/`dnf`) y manejo de **repositorios**.

### 4. Almacenamiento y Sistema de Archivos
Explora cómo Linux maneja el espacio en disco:
* **Dispositivos, Particiones** (**`fdisk`**) y sistemas de archivos (**`ext4`**, **`XFS`**).
* **Montaje** persistente y temporal (**`mount`**, `/etc/fstab`).
* **Gestión de Volumen Lógico (LVM)**, incluyendo `PV`, `VG`, y `LV` (énfasis RHCSA/RH134 y LFCS).

### 5. Redes y Seguridad Básica
Los cimientos de la conexión y protección del sistema:
* **Configuración Básica de Red** (IP, Gateway) y herramientas de diagnóstico (**`ping`**, **`ss`**, **`ip`**).
* **Conexión Remota Segura con SSH** y uso de **llaves de confianza**.
* **Introducción a la Seguridad y el Firewall** (**`firewalld`** y **`ufw`**).
* **Monitoreo y Mantenimiento** con **`journalctl`** y **`systemctl`**.

### 6. Automatización y Servicios Iniciales
Temas avanzados que preparan para la eficiencia:
* **Introducción al Shell Scripting** (estructura, variables, control).
* **SELinux y AppArmor** (Modelos de Control de Acceso Obligatorio - MAC) (Énfasis RHCSA/RH134 y LFCS).
* **El Gestor de Arranque systemd** y comandos **systemctl** avanzados.

---

## 🔗 Enlaces de Interés

| Recurso | Enlace |
| :--- | :--- |
| **Post de la Serie** | [https://www.rootzilopochtli.com/introduccion-a-linux](https://www.rootzilopochtli.com/introduccion-a-linux) |
| **Autor (X/Twitter)** | [@dark_axl](https://x.com/dark_axl) |
| **Blog (X/Twitter)** | [@rootzilopochtli](https://x.com/rootzilopochtli) |

---

## 🙏 Agradecimiento
Sus comentarios son muy valiosos. Los revisores aparecerán en los agradecimientos del libro final y recibirán un ejemplar gratuito al concluir la serie.
Agrega tus sugerencias/correcciones/revisiones mediante un PR.


---

### 📝 NOTA

Este documento ha sido redactado utilizando lenguaje [AsciiDoc](http://asciidoctor.org).
Puedes consultar una hoja de referencia rápida en http://asciidoctor.org/docs/asciidoc-syntax-quick-reference/

GitHub renderizará automáticamente los archivos AsciiDoc que terminan en `.adoc`, `.asciidoc`, or `.asc`.
Para obtener más información, consulta https://github.com/github/markup.

---

## ✍️ Créditos
**Autor:** Alex Callejas (@dark\_axl) 2025.
