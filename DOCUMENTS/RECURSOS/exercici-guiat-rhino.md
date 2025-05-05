# Exercici Guiat de Rhino

**Tasca:** Modelar la següent peça de Lego a Rhino.

## Peça de Lego

<img src="https://fablabbcn-projects.gitlab.io/learning/educational-docs/assets/lego_piece.jpg" width="80%" alt="LEGO piece">



## Interfície

### Vistes
- Rhino utilitza múltiples finestres de visualització per mostrar el model des de diferents angles (Superior, Frontal, Dreta, Perspectiva, etc.).
- Pots maximitzar una vista fent doble clic al seu títol o canviar entre vistes utilitzant les pestanyes de Visualització.

### Panell de Capes
- Les capes ajuden a organitzar el model separant diferents parts o components.
- Utilitza el panell de Capes per crear, reanomenar i gestionar capes. Assigna objectes a capes per controlar visibilitat, color i tipus de línia.

### Panell de Propietats
- El panell de Propietats mostra informació sobre els objectes seleccionats, com les seves dimensions, material i capa.
- També és on pots ajustar atributs d'objectes com el color i el tipus de línia.
- El més important per a la impressió 3D: obert/tancat.

### Filtres de Selecció
- Utilitza filtres de selecció per limitar quins tipus d'objectes es poden seleccionar (per exemple, corbes, superfícies, punts).
- Accedeix als filtres mitjançant la barra d'eines de Filtre de Selecció o escrivint Sel + el tipus d'objecte (per exemple, SelCurva).

### OSnaps (Snaps d'Objecte)
- Els OSnaps t'ajuden a col·locar punts amb precisió acoblant-se a ubicacions específiques dels objectes (per exemple, punts finals, punts mitjans, centres).
- OSnaps comuns: Final, Mig, Cen, Int, Perp, Prop. Activa/desactiva'ls a la barra d'eines OSnap o a la barra d'estat.

### Comandes i Finestra de Comandes
- Rhino funciona amb comandes. Escriu comandes a la Línia de Comandes o utilitza barres d'eines/menús.
- Prem Entrar o Clic dret per executar una comanda. Utilitza Esc per cancel·lar.
- Prémer Entrar, Clic dret o Espai quan la finestra de Comandes està buida repetirà l'última comanda.
- L'Historial de Comandes mostra comandes anteriors per a referència.

### CPlà i Coordenades Mundials
- El Pla de Construcció (CPlà) defineix el pla de treball actiu per dibuixar i editar.
- El Sistema de Coordenades Mundials és la referència global per a tots els objectes. Utilitza comandes de CPlà per ajustar el pla de treball.

## Dibuixant Formes 2D

### Rectangle
- Comanda: **Rectangle**
- Dibuixa rectangles especificant punts de cantonada o utilitzant opcions com Centre, 3Punts o Vertical.

### Cercle
- Comanda: **Circle**
- Dibuixa cercles especificant el centre i el radi o utilitzant opcions com Diàmetre, 3Punts o Tangent.

## Movent Objectes

### Amb el Gumball
- El Gumball és una eina interactiva per moure, rotar i escalar objectes.
- Fes clic i arrossega les fletxes per moure, els cercles per rotar o els quadrats per escalar.
- Mantén Alt mentre arrossegues per crear una còpia de l'objecte.

### Amb la Comanda Moure
- Comanda: **Move**
- Selecciona objectes, especifica un punt base i després un punt de destinació.
- Mantén Shift per restringir el moviment a direccions perpendiculars. Utilitza Tab per bloquejar el moviment al llarg d'un eix específic.

## Seleccionant Objectes
- Selecció d'Esquerra a Dreta: Selecciona objectes completament dins de la finestra de selecció.
- Selecció de Dreta a Esquerra: Selecciona objectes que toquen o estan dins de la finestra de selecció.

## Creant Volums

Hi ha moltes estratègies per crear volums 3D: utilitzant primitives, operacions booleanes, extrusió, revolució, etc.

### Extrusió
- Comanda: **Extrude**
- Selecciona una forma 2D (per exemple, un rectangle o cercle) i utilitza el Gumball o especifica una distància per extrudir-la en un volum 3D.

### PushPull (Nou a Rhino 8)
- Comanda: **PushPull**
- Fes clic i arrossega cares d'un objecte 3D per modificar la seva forma interactivament.

### Desfasament
- Comanda: **Offset**
- Crea una còpia paral·lela d'una corba o superfície a una distància específica.

### Operacions Booleanes
- **Unió Booleana**
  - Comanda: **BooleanUnion**
  - Combina múltiples objectes en un sol objecte.

- **Diferència Booleana**
  - Comanda: **BooleanDifference**
  - Resta un objecte d'un altre.

- **Intersecció Booleana**
  - Comanda: **BooleanIntersection**
  - Manté només la porció superposada dels objectes.

## Utilitzant OSnaps

- Construeix un Cilindre centrat en un dels pins de la cara superior.
  - Comanda: **Cylinder**
  - Utilitza OSnaps com Cen per col·locar el centre amb precisió.

- Mou el cilindre cap avall a la seva posició utilitzant la comanda Moure.
  - Comanda: **Move**
  - Utilitza OSnaps com Final o Mig per a una col·locació precisa.

- Crea 7 còpies més amb la comanda Matriu.
  - Comanda: **Array**
  - Utilitza opcions com Rectangular o Polar per crear còpies en un patró.

- Utilitza **BooleanUnion** i **BooleanDifference** per combinar o restar les polisuperfícies tancades resultants.

## Exercici

Construeix la resta de la peça de Lego utilitzant una combinació de les estratègies i comandes anteriors.

## Altres Comandes Importants o Interessants

- **Distance**: Mesura la distància entre dos punts.
- **Trim**: Talla objectes a les seves interseccions.
- **Join**: Combina múltiples objectes en un sol objecte.
- **Fillet**: Crea vores arrodonides entre corbes o superfícies.
- **Chamfer**: Crea vores bisellades entre corbes o superfícies.
- **FlowAlongSrf**: Deforma un objecte per seguir una superfície.
- **Sweep**: Crea una superfície escombrant un perfil al llarg d'un camí.
- **Loft**: Crea una superfície fusionant entre múltiples corbes.
- **Zoom Selected All Viewports**: Zoom a l'objecte seleccionat en totes les vistes.
