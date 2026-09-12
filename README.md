# Sistema de Gestión de Inventario - TechStore

## 1. Descripción del Proyecto
El **Sistema de Gestión de Inventario** es una solución integral para automatizar el control de stock y ventas de *TechStore*. Permite **gestionar productos, usuarios y reportes** de manera eficiente e interactiva.

## 2. Requisitos del Sistema
- [x] Python 3.10 o superior instalado
- [x] Base de Datos MySQL configurada
- [x] Documentación técnica completada

## 3. Módulos del Sistema

| Módulo | Descripción | Estado |
| :----: | :-----------: | :----: |
| Autenticación | Control de acceso y roles de usuario | Completado |
| Inventario | Registro y conteo de productos | En Proceso |
| Facturación | Generación de comprobantes de pago | Pendiente |

## 4. Ejemplo de Código Fuente

```python
def verificar_stock(cantidad):
    if cantidad > 0:
        return "Producto Disponible"
    else:
        return "Sin Stock"
