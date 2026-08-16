# Modelamiento de Bases de Datos – PRY2204

## Actividad formativa Semana 1: Aplicando conceptos de modelamiento inicial

Repositorio con el modelo Entidad-Relación desarrollado para la asignatura **Modelamiento de Bases de Datos (PRY2204)**, correspondiente a la actividad formativa de la Semana 1.

## Descripción

Se desarrolla el modelo de datos inicial para la línea aérea **BT&Airways**, identificando las entidades del negocio, sus atributos y los tipos de datos (dominio) asociados, utilizando **Oracle SQL Data Modeler**.

## Contexto de negocio

BT&Airways es una línea aérea con más de 25 años en el mercado del transporte de pasajeros. Se requiere levantar el modelo de datos inicial de su negocio, identificando entidades, atributos y tipos de datos, para una futura Base de Datos.

## Entidades identificadas

| Entidad | Tipo | Descripción |
|---|---|---|
| Pasajero | Fuerte | Persona que viaja en los vuelos de la compañía |
| Empleado | Fuerte | Trabajador que atiende y gestiona las reservas |
| Vuelo | Fuerte | Vuelo ofrecido por la compañía |
| Reserva | Débil | Reserva de un pasajero para un vuelo, gestionada por un empleado |

## Relaciones

- **Pasajero** realiza **Reserva** (1:N)
- **Empleado** gestiona **Reserva** (1:N)
- **Vuelo** está asociado a **Reserva** (1:N)

## Herramienta utilizada

- [Oracle SQL Data Modeler](https://www.oracle.com/database/sqldeveloper/technologies/sql-data-modeler/download/)

## Contenido del repositorio

- `Modelo_Base.dmd` – Archivo principal del modelo generado en Oracle SQL Data Modeler.
- `Modelo_Base/` – Subcarpeta con los recursos del modelo.
- `PRY2204_Exp1_S1_Formato_respuesta.docx` – Documento de respuesta con las capturas del modelo en notación Barker y Bachman/Ingeniería de la Información.

## Notación utilizada

- **Modelo Entidad-Relación (MER):** notación Barker.
- **Modelo lógico:** notación de Bachman / Ingeniería de la Información.

## Autor(es)

- Nombre Apellido — Carrera
- Nombre Apellido — Carrera

## Asignatura

Modelamiento de Bases de Datos (PRY2204) — Duoc UC Online
