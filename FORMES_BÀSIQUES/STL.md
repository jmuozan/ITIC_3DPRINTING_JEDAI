# Explicació del Format STL: Anàlisi d'un Con

El format STL (Stereolithography) és un format d'arxiu utilitzat principalment en impressió 3D i disseny assistit per ordinador (CAD). Analitzarem els elements bàsics del codi STL utilitzant l'exemple d'un con.

## Estructura Bàsica

Un arxiu STL en format ASCII té l'estructura següent:

```
solid [nom_objecte]
  ... facetes ...
endsolid [nom_objecte]
```

- `solid Cone`: Indica l'inici de l'objecte i li dóna un nom (en aquest cas, "Cone").
- `endsolid Cone`: Marca el final de la definició de l'objecte.

## Descripció dels Elements

### Facetes (Triangles)

L'STL representa objectes 3D mitjançant triangles (facetes). Cada faceta es defineix així:

```
facet normal nx ny nz
  outer loop
    vertex x1 y1 z1
    vertex x2 y2 z2
    vertex x3 y3 z3
  endloop
endfacet
```
 
#### Vectors Normals

- `facet normal 0.0 0.0 -1.0`: Defineix el vector normal a la faceta.
  - El vector normal indica la direcció perpendicular a la superfície del triangle.
  - Els tres valors representen les components x, y, z del vector.
  - Per exemple, `0.0 0.0 -1.0` indica que el vector normal apunta cap a l'eix Z negatiu.

#### Vèrtexs

- `vertex 0.0 0.0 0.0`: Defineix un punt en l'espai 3D.
  - Cada vèrtex està definit per tres coordenades (x, y, z).
  - Cada faceta consta exactament de 3 vèrtexs que formen un triangle.

### Exemple analitzat

Prenguem una faceta específica del nostre con:

```
facet normal 0.0 0.0 -1.0
  outer loop
    vertex 0.0 0.0 0.0
    vertex 0.951057 -0.309017 0.0
    vertex 0.587785 -0.809017 0.0
  endloop
endfacet
```

Aquesta faceta representa:
- Un triangle a la base del con.
- El vector normal `(0.0, 0.0, -1.0)` indica que la cara del triangle apunta cap avall (eix Z negatiu).
- Els tres vèrtexs estan al pla Z=0 (la base del con).
- El primer vèrtex està al centre `(0.0, 0.0, 0.0)`.
- Els altres dos vèrtexs estan al perímetre de la base.

## Estructura del Con

El con en aquest codi STL:

1. **Base circular**: Les primeres 10 facetes (totes amb normal `0.0 0.0 -1.0`) defineixen la base del con, que és un polígon circular amb 10 costats. Totes aquestes facetes estan al pla Z=0.

2. **Superfície lateral**: Les següents 10 facetes connecten la base amb el vèrtex superior del con. Cada una d'aquestes facetes té:
   - Un costat a la vora de la base.
   - Un vèrtex al punt superior del con `(0.0, 0.0, 2.0)`.
   - Vectors normals que apunten cap enfora del con.

## Observació de Patrons

1. **Coordenades de la base**: Les coordenades de la base formen un cercle unitari al pla XY utilitzant funcions sinus i cosinus (tot i que al codi només veiem els valors numèrics resultants).

2. **Consistència dels vectors normals**: 
   - Els vectors normals de la base sempre són `(0.0, 0.0, -1.0)`.
   - Els vectors normals de la superfície lateral varien per mantenir la perpendicular a la superfície.

3. **Vèrtex superior**: Totes les facetes laterals comparteixen el vèrtex superior `(0.0, 0.0, 2.0)`.

## Conclusió

L'arxiu STL [cone.stl](./cone.stl)defineix un con amb una base circular de radi 1 centrada a l'origen, i una alçada de 2 unitats. La base està discretitzada en 10 segments, i tot l'objecte està format per 20 triangles: 10 per la base i 10 per la superfície lateral.

La representació mitjançant facetes triangulars és essencial per a la impressió 3D, ja que els algoritmes de laminació (slicing) treballen dividint l'objecte en capes horitzontals a partir d'aquesta representació poligonal.