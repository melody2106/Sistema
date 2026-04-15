# Laboratorio: Introducción al Control de Versiones

Este repositorio contiene la implementación práctica del flujo de trabajo esencial con **Git y GitHub**, desarrollado como parte de la especialidad de Ingeniería de Sistemas e Informática.

---

## 📝 Información General
* **Autor:** Melody Palo Bravo
* **Institución:** Laboratorio de Ingeniería de Sistemas e Informática
* **Fecha:** Abril 2026
* **Objetivo:** Conocer e implementar el flujo de trabajo esencial de Git y GitHub mediante el uso de comandos fundamentales para gestionar versiones de software de manera eficiente y colaborativa.

---

## 🚀 Fundamentos Teóricos

### 1. Historia y Evolución de los VCS
El control de versiones ha evolucionado en tres grandes generaciones:
* **Primera generación (Sistemas locales):** Como SCCS y RCS. El historial se guardaba solo en el equipo local. No permitían el trabajo colaborativo.
* **Segunda generación (Sistemas centralizados):** Como CVS y Subversion (SVN). Dependen de un servidor central. Si el servidor falla, el desarrollo se detiene.
* **Tercera generación (Sistemas distribuidos):** Como **Git**. Cada desarrollador posee una copia completa del repositorio y su historial. Es el estándar actual de la industria.

### 2. Conceptos Fundamentales
* **Repositorio:** Contenedor que almacena archivos e historial.
* **Working Directory:** Carpeta de trabajo donde editamos los archivos.
* **Staging Area:** Espacio intermedio donde seleccionamos qué cambios incluir en el siguiente commit.
* **Commit:** Fotografía del estado del proyecto en un momento dado.
* **Branch (Rama):** Línea independiente de desarrollo (ej. `main`, `desarrollo`).

---

## 🛠️ Actividades y Comandos Implementados

### 1. Configuración del Entorno
Se utilizó **Git Bash** para emular un entorno Linux y configurar las credenciales globales:
```bash
git config --global user.name "Melody Palo Bravo"
git config --global user.email "tu-email@ejemplo.com"
# Edición de configuración global
git config --global -e
# Operación en editor: :wq! (Escribir y Salir)