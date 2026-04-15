# Laboratorio: Introducción al Control de Versiones

Este repositorio contiene la implementación práctica del flujo de trabajo esencial con **Git y GitHub**, desarrollado como parte de la especialidad de Ingeniería de Sistemas e Informática.

---

## 📝 Información General
* **Autor:** Remigio Huarcaya Almeyda
* **Institución:** Laboratorio de Ingeniería de Sistemas e Informática
* **Fecha:** Abril 2026
* **Objetivo:** Implementar la gestión de versiones mediante comandos fundamentales y flujos de trabajo colaborativos.

---

## 🚀 Fundamentos Teóricos
El proyecto se basa en el uso de **Sistemas de Control de Versiones Distribuidos (DVCS)**. A diferencia de los sistemas locales o centralizados, Git permite que cada desarrollador posea una copia completa del historial, facilitando:
* Trabajo sin conexión.
* Ramificación (*branching*) rápida.
* Gestión eficiente de fusiones.

---

## 🛠️ Flujo de Trabajo Implementado
El laboratorio cubrió el ciclo de vida completo de un proyecto bajo control de versiones:

### 1. Configuración y Preparación
Se utilizó **Git Bash** para emular un entorno Linux en Windows, configurando las credenciales globales:

```bash
git config --global user.name "TuUsuario"
git config --global user.email "tu@email.com"