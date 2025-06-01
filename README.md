
# Abarrotes Wallis - Sistema de Ventas

Este proyecto es una aplicación de escritorio desarrollada en Python con Tkinter y MySQL que permite gestionar un sistema de abarrotes, incluyendo:

- Gestión de clientes, empleados, productos, proveedores, etc.
- Registro de compras y ventas.
- Interfaz gráfica con menús.
- Conexión a base de datos MySQL.

## Requisitos

- Python 3.8 o superior
- MySQL Server
- Los módulos de Python listados en `requirements.txt`

## Instalación

1. Clona el repositorio o descarga el ZIP.
2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```
3. Importa el archivo `willisdb.sql` en tu servidor MySQL (usa phpMyAdmin o consola).
4. Ejecuta `Main.py` para abrir el menú principal del sistema.

## Archivos

- `conexion_bd.py`: Conexión a la base de datos MySQL
- `Main.py`: Menú principal de navegación
- `Clientes.py`, `Proveedores.py`, etc.: Formularios de gestión CRUD
- `realizar_venta_gui.py`: Módulo de ventas con carrito
- `willisdb.sql`: Script SQL para generar la base de datos
