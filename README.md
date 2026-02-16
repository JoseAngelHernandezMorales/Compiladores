# C Programming Laboratory Repository / Repositorio del Laboratorio de Programación en C

---

## 📘 English Version

### Overview

This repository contains the development work for the C programming laboratory sessions.  
It is structured to ensure proper code organization, version control discipline, and academic development standards throughout the semester.

---

### Project Structure

```
.
├── src/        # Source code files
├── include/    # Header files
├── docs/       # Documentation files
├── tests/      # Testing files
├── Makefile    # Build configuration
└── README.md
```

---

### Build Instructions

To compile the project:

```
make
```

To remove compiled files:

```
make clean
```

---

### Branch Strategy

This repository follows a simplified branching strategy for academic development.

#### Main Branches

- `main`
  - Contains stable and validated code.
  - Represents the official version of the project.

- `develop`
  - Used for active development during the semester.
  - All new work is first integrated here.

#### Workflow Rules

1. Development is performed in the `develop` branch.
2. No direct commits are allowed on `main`.
3. When a stable version is achieved, `develop` is merged into `main`.
4. Code must compile successfully before being merged.

This strategy ensures clarity, stability, and controlled evolution of the project during the course.

---

### Language Policy

All source code, documentation, and commits are written in technical English.  
A bilingual format (English–Spanish) is maintained as an additional academic effort.

---

### Academic Declaration

I hereby confirm that I have read, understood, and accepted the course methodology document.  
I also acknowledge and accept the laboratory evaluation rubric established for this course.

---

---

## 📙 Versión en Español

### Descripción General

Este repositorio contiene el desarrollo correspondiente a las sesiones del laboratorio de programación en C.  
Está estructurado para garantizar organización del código, disciplina en el control de versiones y estándares académicos durante el semestre.

---

### Estructura del Proyecto

```
.
├── src/        # Archivos de código fuente
├── include/    # Archivos de encabezado
├── docs/       # Documentación
├── tests/      # Archivos de pruebas
├── Makefile    # Configuración de compilación
└── README.md
```

---

### Instrucciones de Compilación

Para compilar el proyecto:

```
make
```

Para eliminar los archivos compilados:

```
make clean
```

---

### Estrategia de Ramas

Este repositorio utiliza una estrategia de ramas simplificada para el desarrollo académico.

#### Ramas Principales

- `main`
  - Contiene código estable y validado.
  - Representa la versión oficial del proyecto.

- `develop`
  - Utilizada para el desarrollo activo durante el semestre.
  - Todo el trabajo nuevo se integra primero aquí.

#### Reglas de Trabajo

1. El desarrollo se realiza en la rama `develop`.
2. No se permiten commits directos en `main`.
3. Cuando se alcanza una versión estable, `develop` se fusiona en `main`.
4. El código debe compilar correctamente antes de realizar cualquier fusión.

Esta estrategia garantiza claridad, estabilidad y evolución controlada del proyecto durante el curso.

---

### Política de Idioma

El código fuente, la documentación y los commits están redactados en inglés técnico.  
Se mantiene un formato bilingüe (inglés–español) como esfuerzo académico adicional.

---

### Declaración Académica

Por medio de este repositorio confirmo que he leído, comprendido y aceptado el documento de metodología del curso.  
Asimismo, reconozco y acepto la rúbrica de evaluación del laboratorio establecida para la materia.
