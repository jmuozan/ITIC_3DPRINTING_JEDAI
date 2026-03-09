# Consideracions

<details>
<summary><h2>Mesh</h2></summary>

<details>
<summary><h3>Formats</h3></summary>

```.stl``` ```.obj``` ```.fbx``` ```.gltf``` ```.3mf```

</details>

<details>
<summary><h3>Subdivisions</h3></summary>

![](./IMG/CONSIDERATIONS/cilindre.png)
![](./IMG/CONSIDERATIONS/cilindresub.png)
![](./IMG/CONSIDERATIONS/cilindresubtop.png)

</details>

</details>

<details>
<summary><h2>Gcode</h2></summary>

CODI màquina de bits a àtoms. Moviments finits

- [Info stl ASCII](../FORMES_BÀSIQUES/STL.md)

<details>
<summary><h3>G0 G1 G2 G3...</h3></summary>

```
G0 X10 Y10; moviment ràpid (sense extrusió)
G1 X20 Y20 E5; moviment lineal amb extrusió
G2 X30 Y10 I5 J0; arc en sentit horari
G28; home (origen)
M104 S200; temperatura hotend
M140 S60; temperatura llit
```

- `G0` — Moviment ràpid (travel), sense extrudir material
- `G1` — Moviment lineal controlat, amb extrusió opcional (`E`)
- `G2/G3` — Moviment en arc (horari / antihorari)
- `G28` — Anar a la posició d'origen
- `M104/M140` — Establir temperatures

</details>

</details>

---
<p align="left">
  <img alt="ITIC Barcelona" src="../IMG/LOGOS/logoITICBCN.png" width="15%">
  &nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="CEB" src="../IMG/LOGOS/logo_CEB.png" width="15%">
  &nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="Logos" src="../IMG/LOGOS/footer-logos-white.svg" width="55%">
</p>
