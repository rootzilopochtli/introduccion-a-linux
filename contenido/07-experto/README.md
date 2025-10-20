# 🚀 Módulo Experto: Desafíos Prácticos del Administrador Linux

## Descripción General

¡Bienvenido al **Módulo Experto: Desafíos Prácticos del Administrador Linux**!

Este repositorio es un módulo de práctica **extra** diseñado para complementar los conocimientos teóricos adquiridos en los posts de nuestro blog y servir como **refuerzo intensivo** en tu preparación para las certificaciones más importantes de Linux:

* **LPIC-1 (Linux Professional Institute Certification Level 1)**
* **LFCS (Linux Foundation Certified System Administrator)**
* **RHCSA (Red Hat Certified System Administrator)**

Si ya dominas los comandos básicos y buscas ejercicios que simulen tareas reales de administración y escenarios de examen, este es tu lugar. Aquí, la teoría de los posts se convierte en experiencia práctica.

---

## 💡 ¿Por Qué un Módulo Experto?

Los exámenes de certificación de Linux, especialmente el RHCSA y el LFCS, son laboratorios prácticos. No basta con saber *qué* hace un comando; debes saber *cómo* encadenarlo y aplicarlo para resolver un problema de administración en un tiempo limitado.

Este módulo te ofrece:

1.  **20 Reactivos Prácticos:** Ejercicios detallados con instrucciones paso a paso.
2.  **Enfoque de Certificación:** Énfasis en temas críticos de RHCSA/LFCS como ACLs, gestión de `sudo`, LVM y persistencia de montaje (`/etc/fstab`).
3.  **Ambiente de Laboratorio:** Diseñados para ser replicados y resueltos en una máquina virtual propia (CentOS, RHEL, Ubuntu, Debian).
4.  **Soluciones Detalladas:** Cada desafío incluye la solución con el comando preciso para verificar tu trabajo.

---

## 🛠️ Temas Clave Cubiertos

Los desafíos se organizan en las siguientes áreas de conocimiento, cruciales para las certificaciones:

| Categoría | Conceptos de Énfasis |
| :--- | :--- |
| **CLI y Navegación** | FHS, Comodines, `cp`, `mv`, `info`. |
| **Permisos y Propiedad** | `chmod` (Octal), `chown`, **ACLs** (`setfacl`, `getfacl`), Sticky Bit. |
| **Usuarios y Grupos** | `useradd`, `usermod`, Configuración de **`visudo`** y `NOPASSWD`. |
| **Texto y Redirección** | Tuberías (`|`), `grep` (Contexto), `sed` (Sustitución), Enlaces Duros y Blandos. |
| **Almacenamiento (Montaje)** | `lsblk`, Montaje temporal (`mount`), Persistencia (`/etc/fstab`) usando UUIDs. |
| **Gestión de Volumen Lógico (LVM)** | Creación completa (PV/VG/LV), **Ampliación de Volúmenes Lógicos** (`lvextend`, `xfs_growfs`/`resize2fs`). |

---

## ⚙️ Cómo Usar Este Repositorio

1.  **Clonar el Repositorio:**
    ```bash
    git clone [https://github.com/rootzilopochtli/introduccion-a-linux.git](https://github.com/rootzilopochtli/introduccion-a-linux.git)
    cd introduccion-a-linux
    ```

2.  **Preparar tu VM:** Asegúrate de tener una máquina virtual limpia con permisos de `sudo` y, si vas a practicar LVM, dos o más discos virtuales sin particionar.

3.  **Acceder a los Ejercicios:** El archivo principal con todos los reactivos y soluciones es:
    * [**`DESAFIOS.adoc`**](DESAFIOS.adoc) (Formato Asciidoc)

4.  **¡Practicar!** Intenta resolver los desafíos en tu terminal *antes* de revisar la sección de "Solución" en el documento.

---

## 🤝 Contribución

¿Encontraste un error en una solución o tienes una forma más eficiente de resolver un desafío? ¡Excelente!

Este módulo está hecho para la comunidad. Agradecemos tus contribuciones:

1.  Haz un *fork* del repositorio.
2.  Crea una rama de característica (`git checkout -b mi-gran-solucion`).
3.  Realiza tus cambios y haz *commit* (`git commit -m 'feat: Mejorar la solución del Reactivo 15'`).
4.  Empuja tus cambios (`git push origin mi-gran-solucion`).
5.  Abre un **Pull Request (PR)**.

### [🔗 Regresa](../README.md)