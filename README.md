# Implementación de Base de Datos - Consultorio Santa Gema
**Semana 6 - Módulo Base de Datos**

## Descripción
Este proyecto consiste en la creación de una base de datos relacional para la gestión de recetas médicas, pacientes y pagos del Consultorio Municipal Santa Gema.

## Requerimientos Implementados
- **DDL Completo**: Creación de tablas con tipos de datos adecuados.
- **Restricciones (Constraints)**:
  - Primary Keys y Foreign Keys para integridad referencial.
  - Checks para validación de Dígito Verificador (0-9, K).
  - Unique para teléfonos de médicos.
- **Automatización**: Uso de `IDENTITY` para `id_especialidad` e `id_comuna` (iniciando en 1101).
- **Modificaciones (Caso 2)**:
  - Uso de `ALTER TABLE` para agregar precios con rangos (1.000 a 2.000.000).
  - Restricción de métodos de pago (Efectivo, Tarjeta, Transferencia).
  - Sustitución de columna `edad` por `fecha_nacimiento`.

## Tecnologías
- Oracle SQL Developer
- Oracle Cloud (ADB)
