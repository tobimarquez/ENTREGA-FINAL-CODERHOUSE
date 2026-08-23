# 🤖 Ecosistema de Automatización IA — Dark Imports

Proyecto final de Coderhouse: sistema de automatización inteligente para la gestión de consultas de clientes y disponibilidad de productos.

## 🧠 Arquitectura

- **Make:** Orquestación del flujo
- **Airtable:** Base de datos y memoria
- **OpenAI:** Procesamiento de lenguaje natural
- **Telegram:** Canal de entrada y salida

## ⚙️ Flujo

Telegram → Airtable → OpenAI → Airtable → Router → Telegram

El sistema recibe una consulta, la registra, interpreta la intención mediante IA, consulta el stock disponible y genera una respuesta automática según el resultado.

## 🛡️ Seguridad y resiliencia

- Manejo de errores y reintentos
- Validación de datos
- Control de estados
- Prevención de ejecuciones duplicadas
- Minimización de datos enviados a IA
- Human-in-the-Loop para casos críticos

## 📂 Entregables

- 📄 [Mapa de Arquitectura](./MAPA%20DE%20ARQUITECTURA.drawio.pdf)
- 📄 [Estructura de Datos](./Estructura_de_Datos_Dark_Imports_Hasta_6_FINAL.pdf)
- 📄 [Matriz de Costos](./Matriz_de_Costos_Dark_Imports.pdf)
- 📄 [Seguridad y Resiliencia](./Seguridad_y_Resiliencia_Dark_Imports.pdf)
- 📦 [Blueprint del flujo](./PROYECTO%20FINAL%20DARK%20IMPORTS.blueprint.json)
- 📸 [Screenshots](./SCREENSHOT)

## 📊 Base de datos

La información se gestiona mediante Airtable, utilizando tablas para:

- Stock de productos
- Consultas de clientes
- Estados de procesamiento
- Registro de interacciones

## 🎯 Objetivo

Construir un ecosistema de automatización IA autónomo capaz de procesar consultas comerciales de extremo a extremo, reduciendo la intervención manual y manteniendo trazabilidad, seguridad y control.

---

**Proyecto Final — Coderhouse**
