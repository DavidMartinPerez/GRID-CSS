# GRID-CSS

## Conceptos esenciales:

## Grid Line:
Lineas del grid pueden ser horizontales o verticales

## Grid Track:
Nombre genérico para un GRID row o GRID column, Espacio vertical u horizontal entre dos grid lines consecutivas.
Define la altura de un GRID column o la anchura de un GRID row.

## GRID cell:
La intersección de un GRID row y un GRID column forma un GRID Cell

## GRID area:
Cualquier porción del GRID contenida entre 4 GRID lines.

Puede contener N numeros de Grid cells

------

# Utilización:

## Inicializar:

* display: grid
* grid-gap: tamaño de separación entre cell

## GRID TEMPLATES:

* grid-template-columns: El tamaño de las columnas
* grid-template-rows: El tamaño de las filas
* grid-template-rows: columnas / filas
* grid-area-templates: Ordenar las areas por sus nombres
* grid-area: Definir el nombre de un area

## Alineación

* justify-items: Grid eje de filas
* align-items: Grid eje de columnas
* justify-self: alineacion del hijo - eje de filas
* align-self: alineacion del hijo - eje de columnas