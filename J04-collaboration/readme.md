# Jour 04 : Collaborer avec Github

Pendant cette session les élèves ont créé des **redirections** à partir de leurs pages "Citation".

**Le méthode utilisée:** une balise HTML qui offre cette possibilité.

Il s'agit de la balise `<meta>`, qui a de nombreuses fonctionnalités. Voici quelques-uns des usages les plus fréquents, consistant à spécifier des "métadonnées":

```html
<head>
  <meta charset="UTF-8">
  <meta name="description" content="Free Web tutorials">
  <meta name="keywords" content="HTML,CSS,XML,JavaScript">
  <meta name="author" content="John Doe">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
``
L'usage qui nous intéresse est le paramètre `http-equiv="refresh"`. 

Voici un exemple de code fonctionnel, qui produit une redirection après 5 secondes:

```html
<meta http-equiv="refresh" content="5; url=http://example.com/">
``` 

Il faut donc placer dans le `<head>` de votre page une balise HTML `<meta>` avec: 

- le paramètre `http-equiv` ayant la valeur "refresh"
- le paramètre `content` dans lequel il faut indiquer un chiffre (le nombre de secondes avant la redirection) et une URL.

Voici la liste des pages, qui donne l'ordre des redirections:

[https://github.com/eracom-id491/liste_site_citations#readme](https://github.com/eracom-id491/liste_site_citations#readme)

Petite info historique: le concept de "webring" est une idée qui existe depuis les années 1990. [Voici un article](https://tedium.co/2018/05/31/webring-history/) qui racconte l'histoire.