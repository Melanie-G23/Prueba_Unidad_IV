# Prueba Unidad IV - Sistema de Gestión de Pedidos

## 📌 Datos de Identificación

| Campo | Información |
|-------|-------------|
| **Asignatura** | Ingeniería de Requisitos (ISR-401) |
| **Unidad** | Unidad IV - Validación, Gestión, Herramientas y Estándares de Requisitos |
| **Docente** | Ing. Gleiston Guerrero, Mg. |
| **Estudiante** | [Thais Melanie Herrera Ramos] |
| **Fecha** | [11/08/2026] |
| **Modalidad** | Individual, en clase |
| **Duración** | 120 minutos |

---

## 🎯 Resultado de Aprendizaje Evaluado

El estudiante construye y valida los modelos de análisis (datos, función y comportamiento) de un sistema, especifica y gestiona sus requisitos aplicando estándares (ISO/IEC/IEEE 29148:2018 e ISO/IEC 25010:2023) y demuestra trazabilidad, control de cambios y gestión de configuración sobre un repositorio reproducible.

---

## 📋 Descripción del Caso Práctico

### Sistema de Gestión de Pedidos - Tienda en Línea

Una tienda en línea requiere un módulo para gestionar los pedidos de sus clientes. El sistema debe permitir:

- **Clientes** (identificados por cédula/RUC, nombre y correo) que pueden realizar **cero o más Pedidos**.
- Cada **Pedido** (identificador, fecha y total) contiene **una o más Líneas de pedido**.
- Cada línea referencia un **Producto** (código, descripción, precio, stock).
- Al registrar un pedido, el sistema **verifica disponibilidad de stock**:
  - ✅ Si hay existencias → **confirma el pedido**
  - ❌ Si no hay → **notifica el faltante**
- Un pedido confirmado puede:
  - 📦 **Despacharse**
  - 🚚 **Entregarse**
  - ❌ **Anularse** (mientras no haya sido entregado)
- El sistema debe registrar pedidos con **rapidez** y **proteger los datos personales** del cliente.

---

## 📁 Estructura del Repositorio
