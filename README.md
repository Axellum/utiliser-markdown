# Markdown - Memento

Voici un fichier mémo pour les principales syntaxes Markdown.
Pour voir le code source, cliquez sur l'icône d'édition de ce fichier.

---

## Mettre un mot en italique

Voici un mot *en italique*

Entourez votre mot d'astérisques ou d'underscores :

`*mon-mot*` ou `_mon-mot_`

---

## Mettre un mot en gras

Voici un mot **en gras** !

Entourez votre mot de deux astérisques ou deux underscores :

`**mon-mot**` ou `__mon-mot__`

---

## Gras et italique combinés

Voici un mot ***en gras et italique*** !

`***mon-mot***`

---

## Texte barré

Voici un mot ~~barré~~ !

`~~mon-mot~~`

---

## Les titres

# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3
#### Titre de niveau 4

Pour créer un titre, placez un ou plusieurs `#` suivi d'un **espace** devant votre texte :

`# Titre de niveau 1`

`## Titre de niveau 2`

Et ainsi de suite jusqu'au niveau 6.

---

## Aller à la ligne en fin de phrase

Pour faire un  
changement de ligne

Votre ligne doit se terminer par 2 `espaces` pour faire un retour à la ligne.

---

## Faire une liste à puces

* Une puce
* Une autre puce
* Et encore une autre puce !

`* Une puce`  
`* Une autre puce`  
`* Et encore une autre puce !`

#### Liste ordonnée :

1. Et de un
2. Et de deux
3. Et de trois

`1. Et de un`  
`2. Et de deux`  
`3. Et de trois`

#### Liste imbriquée :

* Une puce
* Une autre puce
    * Une sous-puce
    * Une autre sous-puce
* Et encore une autre puce !

---

## Liste de tâches

- [x] Tâche terminée
- [ ] Tâche à faire
- [ ] Une autre tâche

`- [x] Tâche terminée`  
`- [ ] Tâche à faire`

---

## Faire une citation

> Ceci est un texte cité. Vous pouvez répondre
> à cette citation en écrivant un paragraphe
> normal juste en-dessous !

Ajoutez un `>` devant votre citation :

`> Ceci est un texte cité.`

---

## Écrire du code

#### Bloc de code simple (indentation de 4 espaces)

    int main()
    {
        printf("Hello world!\n");
        return 0;
    }

#### Bloc de code avec coloration syntaxique

```javascript
const message = "Hello world!";
console.log(message);
```

````
```javascript
const message = "Hello world!";
console.log(message);
```
````

Remplacez `javascript` par le langage souhaité : `python`, `html`, `css`, `bash`, etc.

#### Morceau de code en ligne

Voici une balise `<h1>Titre</h1>` dans une phrase.

Entourez votre code de deux accents graves `` ` `` (AltGr + 7).

---

## Mettre un lien

Rendez-vous sur [GitHub](https://github.com) !

`[texte du lien](https://url.com)`

#### Lien avec titre au survol :

[GitHub](https://github.com "Ouvrir GitHub")

`[texte du lien](https://url.com "Titre au survol")`

#### Lien automatique :

<https://github.com>

`<https://url.com>`

---

## Intégrer une image

![Logo GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

`![texte alternatif](https://url-de-l-image.com)`

---

## Tableau

| Nom       | Prénom  | Âge |
|-----------|:-------:|----:|
| Dupont    | Alice   |  30 |
| Martin    | Bob     |  25 |

```
| Nom       | Prénom  | Âge |
|-----------|:-------:|----:|
| Dupont    | Alice   |  30 |
| Martin    | Bob     |  25 |
```

- `:-------:` = centré
- `-------:` = aligné à droite
- `-------` = aligné à gauche (défaut)

---

## Échapper un caractère spécial

Pour afficher un caractère Markdown littéralement (comme `*` ou `#`), précédez-le d'un backslash `\` :

`\*ce texte ne sera pas en italique\*`

---

## Barre de séparation

Pour créer une ligne de séparation, écrivez au moins trois tirets, astérisques ou underscores seuls sur une ligne :

`---`  ou  `***`  ou  `___`
