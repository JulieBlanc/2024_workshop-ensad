# Documentation / Print a web page for group workshop

Un template pour une version de groupe de "print a web page" (https://gitlab.com/pagedjs-templates/print-a-webpage).
Utile pour les workshops étudiants avec plusieurs groupe travaillant sur une même publication: chaque groupe s'occupe d'une partie de la publication. 

## Installation et lancement

La première fois que vous ouvrez Visual Studio Code, si ce n'est pas déjà fait: 
- Installer l'extention « live server » sur Visual Studio.
- Redémarrer Visual Studio.

À chaque fois que vous voulez travailler: 
- Fichier > Ouvrir le dossier
- Sélectionner tout le dossier du projet sur votre ordinateur.
- Appuyer en bas à droite sur "Go Live".
- Si le lien s'ouvre dans un autre navigateur que Chrome, copier/coller le lien dans Chrome.

## Ajouter du contenu et des styles

Dans le dossier `css`, tout ce qui est ajouté s'applique à l'ensemble du document.

Chaque groupe a un dossier dédié à sa partie dans le dossier `src`.

- `content.html` → ajouter le contenu HTML de votre partie.
- `fonts.css` → ajouter les liens vers vos polices de caractères.
- `both.css` → style qui s'applique à la version écran et à la version imprimée.
- `print.css` → style qui s'applique à la version imprimée.
- `screen.css` → style qui s'applique à la version écran.

### Images

- Ajouter les images dans le dossier `images` du dossier de votre groupes.
- Le nom des iamges ne doit pas comporter d'espaces ni de caractères speciaux (sauf des tirets).
- Pour ajouter l'image dans votre dossier HTML, copiez le code ci-dessous, où `group0` est à remplacer par le nom du dossier de votre groupe et `image-name.jpg` par le nom de votre image.

```
<img src="src/group0/images/image-name.png">
```


Attention, vérifier bien l'extention de votre image: `.jpg`, `.png`, `.jpeg`, etc. 


## Licence and version

Julie Blanc – 2022,
MIT License https://opensource.org/licenses/MIT

V0.1 – 13/09/2002, Master Innovation Design et Créativité, Sciences Po (Cours Design & Enquête, 2022, invitation par Pauline Gourlet)