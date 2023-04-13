# Carreras

## Listado de entidades

### carreras **(ED)**

- carrera_id **(PK)**
- nombre
- tipo_carrera **(FK)**
- fecha
- tiempo
- mejor_tiempo
- altitud
- lugar
- pais **(FK)**
- foto

### tipo_carrera **(EC)**

- tipo_carrera **(PK)**
- nombre
- distancia **(UQ)**

### paises **(EC)**

- pais_id **(PK)**
- nombre

## Relaciones

1. Una **carrera** _pertenece_ a un **tipo de carrera** (_1 a 1_)
1. Una **carrera** se _corre_ en un **pais** (_1 a 1_)

## Diagramas

### Modelo Entidad - Relacion
![Modelo Entidad - Relacion] (./CarrerasModeloE-R.png)

### Modelo Relacional de la DB
![Modelo Relacional de la DB] (./CarrerasModeloRelacionalBD.png)
