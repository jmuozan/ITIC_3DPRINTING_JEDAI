   restriccions
      fallada
      resolució
      temps
      cost
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



