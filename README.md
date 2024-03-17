# cube

## notation

TODO, only L R U F

## primo strato

mettere il giusto sotto e fare l'algoritmo NON dalla faccia bianca

```
R  U  R' U'
```

## secondo strato

<- sinistra

```
U' L' U  L  U  F  U' F'
```

-> destra

```
 U  R  U' R' U' F' U  F
```

## terzo strato

per la croce

```
F  R  U  R' U' F'
```

per gli spigoli (U gira la gialla)

```
010 010 010
000 001 101
010 000 010
```

```
R  U  R' U  R  U2  R'
```

per L'ANGOLO GIUSTO (U gira la gialla, angolo "giusto a sx, "sbagliato" a dx)

```
R  U' L' U  R' U' L  U
```

per chiudere (GIALLA SEMPRE GIU')

```
R  U  R' U'
```

## 2x2x2


+ sexy move per la faccia bianca
+ avere solo uno giusto
+ metterlo su a sx
+ algoritmo:
  + ```R U' L' U R' U' L U```
+ e ripetere finche' tutti in posizione giusta
+ faccia bianca in alto
+ sexy move sminchiando
