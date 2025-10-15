# 🛍️ Análisis y Limpieza de Datos – Programa de Fidelización de Clientes (Store 1)

## 📖 Descripción del Proyecto

La empresa de comercio electrónico **Store 1** está preparando el lanzamiento de un nuevo **Programa de Fidelización de Clientes**.  
Para ello, necesita analizar su base de clientes y asegurarse de que los datos estén **completos, limpios y organizados**.

El objetivo principal es **diseñar campañas personalizadas** y **optimizar acciones de marketing** mediante la segmentación de clientes según variables como la **edad**, el **historial de compras** y las **categorías de productos adquiridos**.

## 🎯 Objetivos del Proyecto

- Limpiar los perfiles de los clientes.  
- Estandarizar nombres y edades.  
- Calcular el gasto total por cliente.  
- Validar la consistencia de los datos y corregir errores.  
- Preparar los datos para generar indicadores de negocio (**KPIs**).

## 🧰 Tecnologías Utilizadas

- **Lenguaje:** Python 🐍  
- **Bibliotecas principales:**  
  - `pandas` → para manipulación y limpieza de datos  
  - `numpy` → para operaciones numéricas  
  - `re` → para expresiones regulares en limpieza de texto  
  - `matplotlib` / `seaborn` → (opcional) para visualización básica de datos  

## 🗂️ Estructura de los Datos

Los datos proporcionados por la empresa **Store 1** se presentan en una **lista de Python**, con las siguientes columnas:

| Columna | Descripción |
|----------|-------------|
| `usuario_id` | Identificador único para cada usuario. |
| `usuario_nombre` | Nombre del usuario. |
| `usuario_edad` | Edad del usuario. |
| `categorias_fav_low` | Categorías favoritas de los artículos que compró el usuario (ELECTRÓNICA, DEPORTE, LIBROS, etc.). |
| `gasto_por_categoria` | Lista de números enteros que representan el total gastado en cada categoría favorita. |
