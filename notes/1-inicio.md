# Intro

Este proyecto busca aprender programacion a bajo nivel para
poder realizar un driver para un control que tengo xD pero
buen pretexto para aprender algo

## Temario

Como siempre, voy a depender de ChatGPT para aprender porque
no tengo un profesor o persona a quien sepa preguntarle

### Prompt

Quiero aprender programacion a bajo nivel, se conceptos
basicos de C pues me enseñaron los conceptos de programacion
estructurada en C, pero quiero poder desarrollar programacion
de sistemas como sistemas operativos, firmwares, drivers, etc.
Principalmente en C aunque me gustaria generalizarlo para poder
migrar mis proyectos a Rust en algun momento.

Como dije solo tengo claro programacion estructurada y orientada
a objetos, ¿puedes darme un plan de estudios que le darias a un
estudiante de informatica que pretende adentrarse a la
programacion a bajo nivel?

### Fase 1: Fundamentos de C y Conceptos de Bajo Nivel

#### 1. Profundiza en C

- Punteros y aritmética de punteros.
- Manejo dinámico de memoria (malloc, free, etc.).
- Archivos y streams en C.
- Estructuras y uniones.
- Compilación y enlaces: Uso de gcc, make, y gestión de
  bibliotecas.

#### 2. Conoce el hardware

- Aprende sobre arquitectura de computadoras (CPU, memoria,
  buses).
- Entiende cómo funciona el stack y el heap.
- Fundamentos de ensamblador (x86 o ARM).

#### 3. Introducción al Sistema Operativo

- Estudia cómo funciona un sistema operativo a nivel básico:
  - Conceptos como procesos, memoria, y sistemas de archivos.
  - Syscalls (llamadas al sistema).

#### 4. Práctica inicial

- Escribe programas pequeños para interactuar con el hardware
  (lectura de memoria, manejo de periféricos básicos).
- Usa herramientas como strace o gdb para depuración.

### Fase 2: Programación de Sistemas

#### 1. Conocimientos de Sistemas Operativos

- Libros recomendados:
  - "Operating Systems: Three Easy Pieces" de Remzi H.
    Arpaci-Dusseau.
  - "Modern Operating Systems" de Andrew S. Tanenbaum.
- Temas clave:
  - Scheduling, sincronización, comunicación entre procesos.
  - Sistemas de archivos y drivers básicos.

#### 2. Desarrollo de drivers (en C)

- Aprende cómo escribir drivers para Linux:
  - Manejo de dispositivos en modo usuario y kernel.
  - Modificación de módulos del kernel.
- Práctica con controladores básicos como GPIO, USB, o teclado.

#### 3. Proyectos de Bajo Nivel

- Implementa un pequeño gestor de memoria.
- Diseña un driver simple (por ejemplo, para un LED o periférico
  sencillo).

### Fase 3: Introducción a Rust

#### 1. Migración Conceptual de C a Rust

- Aprende Rust enfocado en la programación a bajo nivel
  - Uso de unsafe y diferencias con C.
  - Herramientas como cargo y crates relevantes (embedded-hal,
    bindgen).

#### 2. Rust para Firmware y Drivers

- Trabaja con plataformas embebidas como Raspberry Pi o
  microcontroladores.
- Escribe drivers o interactúa con periféricos en Rust.
