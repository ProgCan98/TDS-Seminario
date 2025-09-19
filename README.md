# Backlog

# Product Backlog Inicial para SportsCT

## Sprint 1: Fundaciones y Panel de Admin
### Historia 1: Sistema de Autenticación Base
**Prioridad:** Crítica | **SP:** 8

- **Como** desarrollador
- **Quiero** implementar el sistema de autenticación JWT
- **Para** que usuarios puedan registrarse, loguearse y mantener sesión

**Criterios de Aceptación:**

- ✅ Registro con email/password y validación
- ✅ Login con generación de JWT
- ✅ Middleware de autenticación para rutas protegidas
- ✅ Logout y manejo de tokens

##
### Historia 2: Panel de Administración Principal

**Prioridad:** Crítica | **SP:** 13

- **Como** administrador
- **Quiero** acceder a un panel completo de administración
- **Para** gestionar todos los aspectos de la plataforma

**Criterios de Aceptación:**

- ✅ Dashboard con métricas principales (usuarios, eventos, etc.)
- ✅ Navegación clara entre secciones administrativas
- ✅ Interfaz responsive y moderna
- ✅ Acceso solo para usuarios con rol admin

##
- ### Historia 3: Gestión de Usuarios por Admin

**Prioridad:** Crítica | **SP:** 10

- **Como** administrador
- **Quiero** gestionar todos los usuarios de la plataforma
- **Para** aprobar organizadores, suspender usuarios y asignar permisos

**Criterios de Aceptación:**

- ✅ Lista paginada de todos los usuarios
- ✅ Filtros por rol, estado, provincia
- ✅ Acciones: aprobar/rechazar organizadores, suspender/activar usuarios
- ✅ Cambio de roles (promover a admin)
- ✅ Vista detallada de cada usuario

##
### Historia 4: Gestión de Permisos de Administradores

**Prioridad:** Alta | **SP:** 8

- **Como** administrador principal
- **Quiero** asignar permisos específicos a otros administradores
- **Para** delegar responsabilidades sin dar acceso total

**Criterios de Aceptación:**

- ✅ Sistema de permisos granular
- ✅ Asignación de permisos por módulo
- ✅ Super admin con permisos totales
- ✅ Log de cambios de permisos

##
## Sprint 2: Sistema de Autenticación Base
