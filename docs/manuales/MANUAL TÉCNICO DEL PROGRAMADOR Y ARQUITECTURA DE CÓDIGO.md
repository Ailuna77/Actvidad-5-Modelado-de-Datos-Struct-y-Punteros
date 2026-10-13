# MANUAL TÉCNICO DEL PROGRAMADOR Y ARQUITECTURA DE CÓDIGO
## Proyecto: Sistema de Modelado de Datos con Estructuras y Punteros (Actividad 5)

* **Institución:** E.E.S.T. N° 1 "Eduardo Ader" Vicente López
* **Asignatura:** Laboratorio de Programación (LPR) 5° Año
* **Docente:** Mansilla Muñoz York Elías
* **Autor / Grupo:** Gabriel Zacarías, Sofía Mojica, Leonel De Armas, Mateo Roberts (Grupo N.º 3)

---

## CONTROL DE VERSIONES Y CHANGELOG

| Versión | Fecha | Autor | Descripción de Cambios |
| :--- | :--- | :--- | :--- |
| v1.0.0 | 12/10/2026 | Grupo 3 | Versión inicial del modelo estructurado del componente de hardware (struct) mediante pasaje por referencia indirecta (->). |

---

## 1. ARQUITECTURA DEL SISTEMA Y ENTORNO DE DESARROLLO

* **Requisitos:** Compilador `g++` (MinGW-w64 GCC v16.2.0+) con soporte C++11, IDE Visual Studio Code y PowerShell 5.1+.
* **Estructura del Repositorio:** Incluye carpetas para documentación (`docs/`), código fuente (`src/main.cpp`) y capturas de evidencia, tal como se detalla en el archivo Markdown completo que puedes encontrar en el repositorio y en los documentos de referencia del Grupo 3.

---

## 2. DOCUMENTACIÓN DE MÓDULOS Y FUNCIONES (`src/main.cpp`)

* **Entidad de Datos:** Se define `struct EntidadProyecto` para encapsular atributos de hardware (id, nombre, métrica) en memoria continua.
* **Módulo principal (`cargarDatos`):** Utiliza el operador flecha (`->`) para la carga por referencia indirecta, gestionando el buffer de entrada adecuadamente con `cin.ignore()` y `cin.getline()`.

---

## 3. INSTRUCCIONES DE COMPILACIÓN Y DIAGNÓSTICO

* **Compilación:** Ejecutar `g++ src/main.cpp -o src/sistemaproyecto.exe` y su respectivo binario desde PowerShell.
* **Errores frecuentes:** Soluciones documentadas para problemas con las variables de entorno del compilador (`PATH`), simetría de llaves y limpieza del buffer de lectura.

---

## 4. REFERENCIAS
* Kernighan, B. W., & Ritchie, D. M. (1988). *El lenguaje de programación C* (2.ª ed.). Prentice Hall.
* Stroustrup, B. (2013). *The C++ programming language* (4th ed.). Addison-Wesley.
