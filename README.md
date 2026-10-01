# 🗄️ Programación de Bases de Datos – PL/SQL

Repositorio académico que reúne mis **prácticas, pruebas y avances** de la asignatura **Programación de Bases de Datos**, enfocado en **Oracle SQL y PL/SQL**.

El objetivo del repositorio es mostrar la evolución del aprendizaje: desde bloques PL/SQL y cursores hasta el uso de excepciones, VARRAY, triggers, funciones, procedimientos, packages y SQL dinámico.

---

## 📚 Progreso de la asignatura

| Evaluación | Contenidos principales | Estado |
|---|---|---|
| **Prueba 1** | Bloques PL/SQL, cursores, condiciones y `DBMS_OUTPUT` | ✅ Evaluada |
| **Prueba 2** | Cursores, VARRAY, variables BIND y manejo de excepciones | ✅ Evaluada |
| **Prueba 3** | Triggers, funciones, procedimientos, packages y SQL dinámico | ✅ Evaluada |

El repositorio mantiene las evaluaciones como parte del historial académico, permitiendo ver la progresión desde los fundamentos hacia técnicas más avanzadas de programación en bases de datos.

---

## 📂 Estructura actual

La estructura real del repositorio conserva los nombres utilizados durante el desarrollo de las evaluaciones:

```text
Programasion-Bases-de-datos-pl-sql/
│
├── prueba-1/
│   ├── README.md
│   ├── caso-1.sql
│   └── caso-3.sql
│
├── prueba-2/
│   ├── README.md
│   └── codigo-prueba-2.sql
│
├── prueba-3/
│   ├── README.md
│   └── prueba-3-lista.sql
│
└── README.md
```

> Los archivos usan extensión `.sql` para que GitHub detecte el lenguaje y aplique resaltado de sintaxis. El contenido se conserva tal como fue desarrollado durante la asignatura.

---

# 🟦 Prueba 1 – Fundamentos de PL/SQL

La primera evaluación corresponde a los fundamentos de programación procedural dentro de Oracle.

Se trabajan conceptos como:

* Bloques PL/SQL.
* Cursores implícitos.
* Cursores explícitos.
* Variables y cálculos.
* Estructuras condicionales.
* Inserción de resultados.
* Uso de `DBMS_OUTPUT`.

Uno de los ejercicios implementa el cálculo de movilización de empleados considerando sueldo base y comuna de residencia. Otro ejercicio recorre información de camiones utilizando un cursor explícito.

El **Caso 2 quedó documentado como no resuelto**, formando parte del historial real de aprendizaje de la evaluación.

---

# 🟨 Prueba 2 – Procesos PL/SQL y manejo de excepciones

La segunda evaluación aumenta la complejidad de los procesos y las reglas de negocio.

El ejercicio principal calcula beneficios mensuales para empleados de un sistema de vacunatorios.

Entre los conceptos utilizados se encuentran:

* Cursores.
* Variables BIND.
* VARRAY.
* Excepciones predefinidas de Oracle.
* Excepciones definidas por el usuario.
* Procesamiento de reglas de negocio.
* Generación de resultados detallados y resumidos.

Los resultados se almacenan en tablas destinadas al cálculo mensual, resumen y control de errores.

---

# 🟦 Prueba 3 – Programación avanzada en PL/SQL

La tercera evaluación representa un nivel más avanzado de programación dentro de Oracle.

Se trabajó sobre un sistema de remuneraciones y automatización de cálculos.

### Tecnologías y conceptos utilizados

* **TRIGGER** para automatizar la asignación por atenciones médicas.
* **Funciones almacenadas**.
* **Procedimientos almacenados**.
* **PACKAGE**.
* **SQL dinámico** mediante `EXECUTE IMMEDIATE`.
* Reglas de negocio para cálculo de haberes.
* Manejo de errores mediante estructuras de control.

El proceso de cálculo considera elementos como cargas familiares, atenciones médicas, movilización, colación, años de servicio y otros componentes de los haberes.

---

## 🧠 Evolución técnica

El avance entre las evaluaciones puede resumirse así:

```text
Fundamentos
   │
   ├── Bloques PL/SQL
   ├── Variables
   ├── Condiciones
   └── Cursores
        │
        ▼
Procesos intermedios
   │
   ├── VARRAY
   ├── Variables BIND
   ├── Excepciones
   └── Reglas de negocio
        │
        ▼
Programación avanzada
   │
   ├── TRIGGERS
   ├── FUNCIONES
   ├── PROCEDIMIENTOS
   ├── PACKAGES
   └── SQL dinámico
```

Esta progresión representa el objetivo principal del repositorio: **mostrar el aprendizaje y no solamente almacenar código**.

---

## 🛠️ Tecnologías utilizadas

* Oracle SQL
* PL/SQL
* Oracle SQL Developer
* Cursores
* Triggers
* Funciones almacenadas
* Procedimientos almacenados
* Packages
* SQL dinámico
* Manejo de excepciones

---

## 🎯 Objetivo académico

Aplicar programación procedural y técnicas avanzadas directamente dentro de la base de datos para:

* Resolver problemas de negocio.
* Automatizar procesos.
* Trabajar con datos mediante PL/SQL.
* Controlar errores y excepciones.
* Crear lógica reutilizable mediante funciones y procedimientos.
* Comprender el funcionamiento de triggers y packages.
* Avanzar progresivamente hacia soluciones más complejas.

---

## 📌 Estado del repositorio

* ✅ Prueba 1 — Evaluada.
* ✅ Prueba 2 — Evaluada.
* ✅ Prueba 3 — Evaluada.
* 📚 Repositorio utilizado como respaldo del proceso académico.

Las futuras actividades de la asignatura pueden incorporarse manteniendo esta misma estructura de progresión.

---

## 👨‍💻 Autor

**Emilio Araya**  
Estudiante de Ingeniería en Informática 🇨🇱

Repositorio académico de la asignatura **Programación de Bases de Datos**.
