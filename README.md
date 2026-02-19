# Implementación de Base de Datos - Holding Carpenter SPA
**Semana 7 - Módulo Base de Datos**

## Descripción
Este proyecto corresponde a la actividad formativa de la semana 7, enfocada en la implementación de un sistema de gestión de personal para el Holding Carpenter SPA. El trabajo abarca desde el diseño estructural (DDL) hasta la generación de reportes estadísticos avanzados.

## Contenidos del Proyecto
El script SQL adjunto (`.sql`) está organizado en 4 casos principales:

### 1. Caso 1: Implementación del Modelo (DDL)
* Creación de tablas siguiendo la jerarquía de integridad referencial.
* Definición de **Primary Keys** y **Foreign Keys**.
* Implementación de columnas **Identity** en las tablas `REGION` (inicio 7, inc. 2) e `IDIOMA` (inicio 25, inc. 3).

### 2. Caso 2: Reglas de Negocio (ALTER TABLE)
* Configuración de restricciones de unicidad (`UNIQUE`) para correos electrónicos.
* Validación de Dígito Verificador del RUN mediante `CHECK`.
* Restricción de sueldo base mínimo ($450.000).

### 3. Caso 3: Poblamiento y Secuencias
* Creación de objetos `SEQUENCE` para las tablas `COMUNA` e `COMPANIA`.
* Inserción de datos utilizando el método `.NEXTVAL`.

### 4. Caso 4: Recuperación de Datos (Reportes)
* **Informe 1**: Simulación de renta promedio con ordenamiento descendente por renta y ascendente por nombre de empresa.
* **Informe 2**: Simulación de renta con un incremento adicional del 15% sobre el porcentaje base, utilizando operadores aritméticos y alias de columna.

## Integrantes
* Daniel Ceballos
* Catalina Hillmer

## Tecnologías Utilizadas
* **Base de Datos**: Oracle Database (Oracle Cloud)
* **IDE**: Oracle SQL Developer (24.3)
