# Sistema de Gestión de Inventario - TechStore

## 1. Descripción del Proyecto

Es un sistema de ventas para *TechStore* que permite gestionar **productos, inventario y ventas**.  
Su objetivo es facilitar el **control de existencias y la facturación** de manera organizada.

## 2. Requisitos del Sistema

- [x] Python 3.10 o superior instalado
- [ ] Base de Datos MySQL configurada
- [ ] Documentación Técnica completada

## 3. Módulos del Sistema

| Módulo | Descripción | Estado |
|---|---|---|
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