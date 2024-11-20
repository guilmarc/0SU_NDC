# Travail Pratique #2 - Santé Plus (version 0.9)

Votre travail pratique #2 sera de reproduire le plus fidèlement possible ce site web de regroupement de professionnels de la santé.

## Règles à suivre

1. La disposition des éléments doit obligatoirement être faite en `flex` et en `grid` pour une partie du `footer`.

2. Le visuel doit être le plus identique possible lorsque vous placez le site en taille maximale HD (1920 pixels de large) et le site doit être adapté au web ainsi qu'à la taille du iPhone 14 Pro Max.

3. Vous devez utiliser les images [ICI](./_bin/images.zip). Il vous faudra cliquer sur `View raw`.

4. Vous devez obligatoirement utiliser la propriété-racourcis `background` pour fixer vos images de fond.

5. Chacune des sections du site doit être dans une balise `<section>` et contenir un ID portant le nom de la section.

6. Aucun `<br>` ne sera permis dans tout le site.

7. L'icône présent dans l'onglet doit être une version miniature du logo principal (`favicon.ico`). Une recherche sur le web sera probablement nécesaire.

## Charte graphique

### Fonts

- Montserrat
- Playwrite

### Variable

```css
:root {
  --color-primary: #e4e8ea;
  --color-secondary: #0f1108;
  --color-accent: #00f6ed;
  --color-background: #0f1108;
  --color-background-accent: #4f5058;
  --color-alpha1: rgba(255, 255, 255, 0.1);
  --color-alpha2: rgba(0, 0, 0, 0.5);
  --color-alpha3: rgba(0, 0, 0, 0.3);
  --shadow-main: 3px 3px 5px var(--color-secondary);
  --size-header-height: 5rem;
  --size-footer-height: 15rem;
}
```

### Logo central

- Le logo central devra être programmé en CSS en utilisant les `flex` ainsi que les transformation.
  - Taille de carrés: 5rem.
  - Classe responsable de tourner le carré + :
    ```css
    .rotate {
      display: flex;
      position: relative;
      top: -10px;
      left: 10px;
      transform: rotate(45deg);
    }
    ```

## Page Accueil

![IMAGE](./images/1.png)

## Sections services & équipe

![IMAGE](./images/2.png)

## Section témoignages

![IMAGE](./images/3.png)

## Footer

La partie avec les 14 liens en texte blanc doit **obligatoirement** être programmée en utilisant une disposition en `grid`.

![IMAGE](./images/4.png)

<p align="Center"><img src="./images/end.png" alt="drawing" width="150"/></p>
