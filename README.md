# Actividad-5-Modelado-de-Datos-Struct-y-Punteros
## Proyecto Integrador Anual - LPR 2026

* **Institución:** E.E.S.T. N.º 1 "Eduardo Ader" - Vicente López
* **Curso:** 5° Año 3° (A-B)
* **Materia:** Laboratorio de Programación (LPR)
* **Profesor:** Prof. York
* **Actividad:** Actividad 5: Modelado de Datos con Estructuras (Struct) y Punteros

---

## Descripción del Proyecto
Este desarrollo implementa el modelado y la abstracción de entidades de hardware complejas utilizando estructuras de datos (`struct`) en C++. La aplicación gestiona y muta los miembros lógicos de los componentes en bloques de memoria RAM contiguos por medio de pasajes por dirección (referencia) utilizando punteros avanzados y el operador flecha (`->`). Este módulo sienta las bases arquitectónicas de software para el control de variables de hardware vinculadas al Proyecto Integrador Anual (P.I.A.) de la Expotécnica 2026.

## Integrantes (Grupo N.º 3)
* **Zacarias, Gabriel** - `[Rol: Arquitectura de Control de Versiones y Ramas Git]`
* **Mojica, Sofia** - `[Rol: Modelado Lógico de Estructuras y Pruebas en Terminal]`
* **De Armas, Leonel** - `[Rol: Documentación Técnica de Manuales e Informe APA v7]`
* **Roberts, Mateo** - `[Rol: Gestión de Buffer de Entrada y Filtros de Consistencia]`

---

## Requisitos e Instalación
1. Compilador de bajo nivel **MinGW (g++)** mapeado globalmente en las Variables de Entorno (**PATH**).
2. Entorno de desarrollo **Visual Studio Code** con el paquete de extensiones C/C++ habilitado.

###  Clonar este repositorio:
```bash
git clone https://github.com/Ailuna77/Actvidad-5-Modelado-de-Datos-Struct-y-Punteros.git
```

### Posicionarse en el directorio raíz correspondiente a la práctica:
```bash
cd sistemaproyecto
```

---

## Compilación y Ejecución (PowerShell)
Estando parados en la carpeta raíz `sistemaproyecto`, ejecute secuencialmente los comandos de enlace:

### 1. Compilación del Código
Genera el binario ejecutable optimizado en el directorio de fuentes:
```powershell
g++ src/main.cpp -o src/sistemaproyecto.exe
```

### 2. Lanzamiento del Sistema
Ejecuta la interfaz interactiva de modelado en consola:
```powershell
.\src\sistemaproyecto.exe
```

---

## Estructura del Repositorio Obligatorio

```text
sistemaproyecto/
├── .gitignore                      <-- Reglas de exclusión de Git (.exe, .vscode/)
├── LICENSE                         <-- Licencia MIT escolar de uso académico
├── README.md                       <-- Portada técnica de la actividad (Este archivo)
├── docs/                           <-- Carpeta de documentación formal
│   ├── InformeEEST1_LPR2026_ACT05_G03_v1.0.0.pdf <-- ENTREGABLE EN PDF (APA v7)
│   └── manuales/
│       ├── manual_programador_v1.0.0.pdf <-- Explicación del struct y operador -> (PDF)
│       └── manual_programador_v1.0.0.md  <-- Explicación del struct y operador -> (Markdown)
├── src/                            <-- Carpeta para los códigos fuente del proyecto
│   └── main.cpp                    <-- Programa principal modular en C++
└── capturas/                       <-- Evidencias de ejecución local
    └── ejecucion_struct.png        <-- Captura de la terminal con datos y direcciones en RAM
```
