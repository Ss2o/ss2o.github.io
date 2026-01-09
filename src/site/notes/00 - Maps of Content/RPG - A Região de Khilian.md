![[Mapa de Khilian.png]]

## Cidades:
```datacards
TABLE region AS "Região", cover, religion AS "Religião", culture AS "Cultura", geography AS "Situação Geográfica", main-ethnicity AS "Etnia Principal" FROM #khilian and #cidade
SORT file.link ASC


//Settings
preset: square
columns: 4
fontSize: small
imageProperty: cover
scrollableProperties: true
contentHeight: 250px
mobilePreset: square
```

## Personagens:
```datacards
TABLE cover, status, race AS "Raça", class AS "Classe", birthplace AS "Local de Nascimento", religion AS "Religião", campanha, player FROM #khilian and #player-character 
SORT file.link ASC


//Settings
preset: square
columns: 5
fontSize: small
imageProperty: cover
scrollableProperties: true
contentHeight: 250px
mobilePreset: square
```

## NPCs:
```datacards
TABLE cover, status, race AS "Raça", class AS "Classe", birthplace AS "Local de Nascimento", religion AS "Religião" FROM #khilian and #NPC 
SORT file.link ASC


//Settings
preset: square
columns: 5
fontSize: small
imageProperty: cover
scrollableProperties: true
contentHeight: 250px
mobilePreset: square
```

## Divindades:
```datacards
TABLE cover, titles AS "Títulos" FROM #khilian and #divindade 
SORT file.link ASC

//Settings
preset: square
columns: 4
fontSize: small
imageProperty: cover
imageFit: contain
scrollableProperties: true
contentHeight: 250px
mobilePreset: square
```

## Correntes Religiosas:
```dataview
TABLE divindade-principal AS "Divindade(s) Principa(is)" FROM #khilian and #religião 
SORT file.link ASC
```

## Espécies
```datacards
TABLE cover, culture AS "Cultura", religion AS "Religião" FROM #khilian and #species
SORT file.link ASC

//Settings
preset: square
columns: 4
fontSize: small
imageProperty: cover
imageFit: contain
scrollableProperties: true
contentHeight: 250px
mobilePreset: square
```

## Documentos Históricos:
```dataview
TABLE author AS "Autor", publishing-date AS "Data de Publicação" FROM #khilian and #doc-histórico 
SORT publishing-date ASC
```

## Marcos Geográficos:
```datacards
TABLE cover, tipo, cidades FROM #khilian and #marco-geográfico
SORT file.link ASC

//Settings
preset: square
columns: 4
fontSize: small
imageProperty: cover
scrollableProperties: true
contentHeight: 250px
mobilePreset: square
```

