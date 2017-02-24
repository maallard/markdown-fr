# Titres

Maintenant que nous avons commencé l'écriture d'un document markdown, nous devons ajouter un titre et des sous-entêtes.

Markdown supporte deux styles d'entête, Setext et atx.

Les entêtes de style Setext sont "soulignés" avec des signes égal (pour les entêtes de premier niveau) et des tirets (pour les entêtes de deuxième niveau). Par exemple :

```
Ceci est un H1
=============

Ceci est un H2
-------------
```

Un nombre quelconque de = ou de - permet de souligner.

Les entêtes de style Atx utilisent de 1 à 6 caractères dièses au début de la ligne, correspondant au niveaux d'entêtes 1-6\. Par example :

```
# Ceci est un H1

## Ceci est un H2

###### Ceci est un H6
```

Vous pouvez optionnellement "encadrer" les entêtes de style atx. Ceci est purement cosmetique ; vous pouvez utiliser cela si vous trouvez ça plus joli. Les dièses encadrants n'ont pas besoin d'être le même nombre de dièses utilisés pour ouvrir l'entête. (Le nombre de dièses ouvrant détermine le niveau d'entête) :

```
# Ceci est un H1 #

## Ceci est un H2 ##

### Ceci est un H3 ######
```

--------------------------------------------------------------------------------

Voici un quiz à propos des titres markdown

Choisissez les bon entêtes :

- [x] `# bonjour`
- [ ] `#bonjour`

> Les entêtes nécessites un espace entre le caractère dièse et le texte

Choisissez les entêtes valides :

- [ ]

  ```
  test
  ########
  ```

- [x]

  ```
  test
  =======
  ```

> Seulement '=' et '-' sont valides pour souligner un entête.
