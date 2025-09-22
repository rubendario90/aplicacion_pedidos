# Sistema de Gestión de Pedidos - Automuelles

## Descripción del Proyecto

Este es un sistema integral de gestión de pedidos desarrollado en PHP para la empresa Automuelles. El sistema permite administrar todo el flujo de pedidos desde la creación hasta la entrega final, incluyendo gestión de inventario, facturación, despachos y mensajería.

## Características Principales

### 🛒 **Gestión de Pedidos**
- Creación y seguimiento de pedidos
- Estados de pedidos en tiempo real
- Asignación de servicios
- Reportes de pedidos

### 📦 **Módulo de Bodega**
- Control de inventario
- Picking de productos
- Separación de pedidos
- Reportes de novedades
- Revisión final de productos

### 🚚 **Sistema de Despachos**
- Asignación de mensajeros
- Gestión de entregas
- Modificación de domicilios
- Seguimiento de pedidos en tránsito
- Entrega en mostrador

### 📋 **Mensajería**
- Registro de viajes
- Control de entregas
- Reportes diarios
- Gestión de novedades
- Firma de recibidos

### 💰 **Facturación y Tesorería**
- Generación de facturas
- Gestión de notas contables
- Facturas de contado y crédito
- Historial de facturación

### 👥 **Gestión de Usuarios**
- Panel de administración
- Roles de usuario (Admin, Jefe de Bodega, Vendedores, Mensajeros)
- Sistema de autenticación
- Gestión de sesiones

### 🔧 **Garantías y Soporte**
- Sistema de reclamos
- Seguimiento de garantías
- Estados de solicitudes
- Historial de garantías

## Estructura del Proyecto

```
📁 Sistema de Pedidos/
├── 📁 admin/           # Panel de administración e informes
├── 📁 Bodega/          # Módulo de gestión de bodega
├── 📁 Catalogo/        # Gestión de productos
├── 📁 Chat/            # Sistema de chat interno
├── 📁 Compras/         # Módulo de compras
├── 📁 Despachos/       # Gestión de despachos y entregas
├── 📁 Facturacion/     # Sistema de facturación
├── 📁 Firma/           # Módulo de firmas digitales
├── 📁 Garantias/       # Gestión de garantías
├── 📁 JefeBodega/      # Panel específico para jefe de bodega
├── 📁 Mensajeria/      # Sistema de mensajería
├── 📁 Tesoreria/       # Módulo de tesorería
├── 📁 Vendedores/      # Panel para vendedores
├── 📁 assets/          # Recursos estáticos (CSS, JS, imágenes)
├── 📁 php/             # Archivos PHP principales
└── 📁 public/          # Archivos públicos
```

## Tecnologías Utilizadas

- **Backend**: PHP
- **Frontend**: HTML5, CSS3, JavaScript
- **Base de Datos**: MySQL
- **Librerías**: 
  - FPDF/FPDI para generación de PDFs
  - JavaScript vanilla para interactividad

## Funcionalidades por Módulo

### 🏪 **Administración**
- Informes de despachos
- Informes de mensajería
- Informes de pedidos de bodega
- Catálogo de productos
- Gestión de sesiones

### 📦 **Bodega**
- Actualización de estados
- Asignación de servicios
- Picking de facturas
- Reportes de novedades
- Revisión final

### 🚛 **Despachos**
- Asignación de facturas
- Asignación de mensajeros
- Entrega en mostrador
- Modificación de domicilios
- Gestión de pedidos pendientes

### 📱 **Mensajería**
- Registro de viajes
- Revisión diaria
- Registro de novedades
- Pedidos entregados
- Firmas de recibido

## Instalación y Configuración

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/rubendario90/aplicacion_pedidos.git
   ```

2. **Configurar base de datos**
   - Crear base de datos MySQL
   - Importar esquema de base de datos
   - Configurar credenciales en `php/db.php`

3. **Configurar servidor web**
   - Apache o Nginx con soporte PHP
   - PHP 7.4 o superior
   - Extensiones MySQL/MySQLi habilitadas

4. **Permisos de archivos**
   - Dar permisos de escritura a carpetas de upload
   - Configurar permisos para generación de PDFs

## Uso del Sistema

### Para Administradores
- Acceso completo a todos los módulos
- Generación de informes
- Gestión de usuarios
- Configuración del sistema

### Para Jefes de Bodega
- Gestión de inventario
- Asignación de servicios
- Supervisión de picking
- Reportes de bodega

### Para Vendedores
- Creación de pedidos
- Seguimiento de ventas
- Gestión de garantías
- Modificación de domicilios

### Para Mensajeros
- Visualización de pedidos asignados
- Registro de entregas
- Reportes de novedades
- Firma de recibidos

## Contribución

Para contribuir al proyecto:

1. Fork el repositorio
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## Licencia

Este proyecto es propiedad de Automuelles y está destinado para uso interno de la empresa.

## Contacto

- **Desarrollador**: Ruben Dario
- **Email**: rbayonagalvis@gmail.com
- **Empresa**: Automuelles

---

## Historial de Versiones

- **v1.0.0** - Sistema inicial con módulos básicos de gestión de pedidos
- **Próximas versiones** - Mejoras en UI/UX, optimizaciones de rendimiento
