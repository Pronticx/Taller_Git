# 🧾 Sistema de Inventario en Python

Este es un sistema de gestión de inventario de productos desarrollado en Python, utilizando SQLite como base de datos local. Permite realizar operaciones CRUD (Crear, Leer, Actualizar y Eliminar), generar reportes de bajo stock y mantener registros organizados mediante una interfaz de consola intuitiva y funcional.

---

## 📁 Estructura del Proyecto

```
inventario/
├── pfi_modelo_vehiculos.py        # Punto de entrada de la aplicación
├── bd_metodos.py                  # Funciones de acceso y modificación a la base de datos
├── get_metodos.py                 # Lógica del menú e interacción con el usuario
└── inventario.db                  # Base de datos SQLite (se genera automáticamente)
```

---

## ⚙️ Requisitos

- Python 3.8 o superior  
- No se requieren librerías externas (solo la biblioteca estándar)

> **Opcional:** Para mejor experiencia visual (colores en consola):
```bash
pip install colorama
```

---

## 🚀 Cómo Ejecutar

1. Cloná el repositorio:
   ```bash
   git clone https://github.com/Pronticx/Taller_Git.git
   cd Taller_Git
   ```

2. Ejecutá el sistema:
   ```bash
   python main.py
   ```

> ⚠️ La base de datos `inventario.db` se crea automáticamente si no existe.

---

## 🧩 Funcionalidades

- ✅ Alta de productos  
- 🔍 Búsqueda por ID, nombre o categoría  
- 📝 Actualización de campos individuales  
- 🗑️ Eliminación segura de productos  
- 📉 Reporte de productos con bajo stock  
- 🧽 Normalización automática de texto y validaciones  

---

## ✨ Buenas Prácticas Aplicadas

- Uso de `with` para manejo seguro de archivos y base de datos  
- Separación de responsabilidades en módulos independientes  
- Validación robusta de entradas del usuario  
- Documentación con docstrings para cada función  
- Código limpio y mantenible, ideal para estudiantes y equipos pequeños  

---

## 📚 Licencia

Este proyecto es de uso **educativo y libre**. Podés modificarlo, extenderlo o adaptarlo para tus propios fines.

---

## 🤝 Agradecimientos

Proyecto desarrollado como ejercicio práctico de programación estructurada en Python. Ideal para clases, talleres o autoaprendizaje.
