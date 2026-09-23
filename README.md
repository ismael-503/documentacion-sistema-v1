# Sistema de Gestión de Inventario - TechStore

## 1. Descripción del Proyecto
El sistema de gestión optimiza las **ventas diarias, facturación y control de inventario** de forma automatizada. Esta solución integral permite a *TechStore* gestionar sus operaciones comerciales con máxima eficiencia y precisión.

## 2. Requisitos del Sistema
- [x] Python 3.10 o superior instalado
- [x] Base de Datos MySQL configurada
- [x] Documentación técnica completada

## 3. Módulos del Sistema

| Módulo | Descripción | Estado |
| :--- | :---: | :---: |
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
 ``` 
## 5. Enlaces Útiles
- [Ver Arquitectura del Sistema](docs/arquitectura.md)
- [Ver Casos de Uso Hospitalarios](docs/arquitectura/casos-de-uso.md)
- [Ver Diagrama de Secuencia de Login](docs/arquitectura/secuencia-autenticacion.md)
- [Ver Arquitectura del Sistema](docs/arquitectura.md)
- [Ver Manual de Usuario](docs/manual_usuario.md)
- [Ver Especificación de API](docs/api_endpoints.md)
- [Repositorio Oficial en GitHub](https://github.com/gaps3600/documentacion-sistema-v1-)