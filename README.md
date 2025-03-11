# Jornades JEDAI Taller d'Impressió 3D


## Processos subtractius vs additius

![Processos subtractius vs additius](./IMG/subsvsadd.png)

<div style="display: flex; gap: 10px;">
  <img src="IMG/VIDEO_CNC.gif" width="49%" />
  <img src="IMG/ROBOT.gif" width="49%" />
</div>

# Impressió 3D. Per qué mola??

  - Accessibilitat

<div style="display: flex; gap: 10px;">
  <img src="IMG/reprap.gif" width="100%" />
</div>

![](IMG/father-child.png)

[RepRap selfreplicating](http://fab.cba.mit.edu/classes/865.18/replication/Jones.pdf)
[reprap wiki](https://reprap.org/wiki/About)
  - Sostenibilitat

<div style="display: flex; gap: 10px;">
  <img src="IMG/Nike.png" height=470px />
  <img src="IMG/Nikeprinting.gif" height=470px />
</div>

[Zellerfeld](https://www.zellerfeld.com/)
[Zellerfeld + Nike](https://about.nike.com/en/newsroom/releases/nike-sneaker-culture-complexcon)
  - Personalitazació (Empoderament dels usuaris)

[![IMAGE ALT TEXT HERE](IMG/action_figures.png)](https://www.youtube.com/watch?v=b0eHpUR6F5I&t)
[3D Printing Your Favorite Heroes: Hasbro Does Mass Customization](https://formlabs.com/blog/formlabs-hasbro-3d-printing-mass-customization/)

[![IMAGE ALT TEXT HERE](IMG/3dfilm.png)](https://www.youtube.com/watch?v=RLS_jA9s8J4&t)
[Chase Me: A 3D printed film created on the Form 1+](https://formlabs.com/blog/chase-me-3d-printed-film/)

<div style="display: flex; gap: 10px;">
  <img src="IMG/hotels_1.png" width="49%" />
  <img src="IMG/hotels_2.png" width="49%" />
</div>

[Hotels per insectes](https://www.3dwasp.com/en/3d-printed-ceramic-sculptures-to-house-insects/)

## Sobre la Impressió 3D

![esquema]()
   restriccions
      fallada
      resolució
      temps
      cost
      materials materials
         polímer:
            PLA
               polímer renovable d'origen vegetal
               baixos volàtils, partícules fines
               més fàcil d'imprimir
               transició vítria ~60C
               més fràgil
            PETG
               polímer reciclable d'origen petrolier
               baixos volàtils, partícules fines
               transició vítria ~80C
               més resistent, millor resistència UV
            PMMA, ABS, HIPS, TPU, PVA, ...
         compost: metall, fusta
         emmagatzematge: higroscòpic
         configuracions
         cicle de vida
      certificació de ventilació
      regles de disseny
         tipus de suports
            voladís FCStd jpg stl
            separació FCStd jpg stl
         sense suport
            angle FCStd jpg stl
            voladís FCStd jpg stl
            pont FCStd jpg stl
         gruix de paret FCStd jpg stl
         dimensions FCStd jpg stl
         anisotropia FCStd jpg stl
         acabat superficial FCStd jpg stl
         farciment FCStd jpg stl
         conicitat, cantonada
      desplaçament z, anivellament, mesurament
      adhesió, deformació, bases, vores
      post-processament galvanoplàstia
   processos
      estereolitografia làser DLP
      modelat per deposició fosa (FDM)/fabricació de filament fos (FFF)
         extrusora extrusió contornejat
      DED, WAAM
      injecció d'aglutinant
      PolyJet
      sinterització selectiva per làser
      nano de dos fotons
      bio
      digital
   màquines
      RepRap autoreplicació
      Ultimaker Z-Unlimited
      Prusa peces XL color AFS 
      Sainsmart
      Bambu AMS peces color
      Mosaic Palette
      Elegoo
      Formlabs
         SLA peces Print the Legend Chase Me personalització massiva 
         SLS peces
      Stratasys J55 color
      MTM InMachines Hangprinter eixos
      E3D
      Precious Plastic
      Filastruder
   materials
      Proto-pasta
      MatterHackers
      NinjaTek
      MachineableWax
      The Virtual Foundry
      teixit teixit
      seguretat alimentària seguretat alimentària seguretat alimentària
   oficines de serveis
      granges d'impressió
      Shapeways
      JLCPCB
      Ponoko
      Additively

formats d'arxiu
   STL
      ASCII
         solid nom_objecte
            facet normal n1 n2 n3
               outer loop
                  vertex v11 v12 v13
                  vertex v21 v22 v23
                  vertex v31 v32 v33
               endloop
            endfacet
            ...
         endsolid nom_objecte
      binari
         capçalera ASCII de 80 bytes
         enter de 32 bits nombre de facetes
         registres de facetes de 50 bytes
            floats IEEE de 32 bits
            normal
            vèrtexs 1,2,3
            atribut de 2 bytes
      regla de la mà dreta
      normal (opcional)
      (falta de) unitats
      mida de l'arxiu
   PLY
   AMF 3MF
   STEP
   FAV
   OBJ, 3ds, DXF
   VRML, X3D
   glTF
   Alembic
   FREP
      camps de distància mostrejats adaptativament
   vòxels
      .vol, .gif, pila d'imatges
      marxant cubs
      impressió de vòxels
   G-codes
      imatges camins no planars arc voladissos capes de maons

programari
   mallat
      MeshLab netfabb meshmixer Geomagic
   seccionament
      ReplicatorG Skeinforge Slic3r PrusaSlicer Cura IceSL Kiri:Moto t43
   impressió
      Printrun OctoPrint Repetier
   firmware
      Klipper
   compartir
      Sketchfab Thingiverse Printables modelviewer

escaneig
   núvol de punts, triangulació, estanc, textura
   il·luminació, fons, tractament de superfície
   tomografia transformada de Radon micro-CT
      Rigaku Lumafield
   sonda escanejada
   confocal
   seccions serials
   opacitat
   digitalitzador
   Fotogrametria
      AliceVision Meshroom imatge
      Luma AI Polycam KIRI Engine ReCap PhotoScan VisualSFM SCANN3D Qlone
      OpenMVG COLMAP OpenScan escàner
   speckle OpenKinect ReconstructMe
   làser FabScan
   llum estructurada codi Gray POP3
   estèreo Ferret Pro escanejos
   LIDAR Seeed TI Intel Matterport Scaniverse
   escenari de llum escaneig fotorealista
   SLAM

assignació assignació assignació assignació
   assignació de grup:
      - provar les regles de disseny per a la(es) vostra(es) impressora(es) 3D
   assignació individual:
      - dissenyar i imprimir en 3D un objecte (petit, pocs cm3, limitat pel temps d'impressió)
         que no es podria fer de manera subtractiva
      - escanejar en 3D un objecte (i opcionalment imprimir-lo)





<p align="left">
  <img alt="Light" src="./IMG/LOGOS/logoITICBCN.png" width="15%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="Dark" src="./IMG/LOGOS/logo_CEB.png" width="15%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="Dark" src="./IMG/LOGOS/footer-logos-white.svg" width="55%">
</p>