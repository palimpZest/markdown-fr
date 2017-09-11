# Titres

Lorsqu'on commence à écrire un document en utilisant le Markdown, on a besoin d'ajouter un titre ainsi que des sous-titres.

le Markdown possède deux styles d'en-têtes, Setext et atx.

Les en-têtes utilisant le style Setext sont "sous-lignées" par des signes d'égalité (pour les en-têtes de premier niveau) par des tirets (pour les en-têtes de deuxième niveau). Par exemple:

```
Ceci est un H1
=============

Ceci est un H2
-------------
```

N'inporte quel nombre de = ou - suffira.

Les en-têtes Atx utilisent 1 à 6 dièses au début de la ligne, correspondant aux niveaux 1-6. Par exemple:

```
# Ceci est un H1

## Ceci est un H2

###### Ceci est un H6
```


Optionally, you may “close” atx-style headers. This is purely cosmetic — you can use this if you think it looks better. The closing hashes don’t even need to match the number of hashes used to open the header. (The number of opening hashes determines the header level.) :

```
# This is an H1 #

## This is an H2 ##

### This is an H3 ######
```


---

Here's a quiz about markdown titles.

Select the valid headers:
- [x] `# hello`
- [ ] `#hello`

> Headers need space between the hash characters and the text.

Select the valid headers:
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

> Only '=' and '-' are accepted for underlining an header.

---


