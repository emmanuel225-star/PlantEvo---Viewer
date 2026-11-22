# PlanEvo

Site statique sur l'évolution et la reproduction des grands groupes de végétaux : algues, mousses, fougères, conifères, graminées et dicotylédones. Il est réalisé en HTML et CSS à partir d'une maquette Figma, sans JavaScript ni framework.

**Auteur :** Eliakhym

## Aperçu

Le site tient en une seule page, `index.html`. Chaque lien du menu défile vers sa section :

| Section | Contenu |
|---|---|
| Accueil | 6 photos cliquables, une par groupe de végétaux |
| Algues | 3 photos et le schéma de reproduction des algues |
| Mousses | 3 photos et le schéma du cycle de vie d'une mousse |
| Fougère | 3 photos et le schéma de reproduction des fougères |
| Conifère | 3 photos et le schéma du cycle des conifères |
| Graminées | 3 photos et le schéma d'une fleur de graminée |
| Dicotylédones | 3 photos et le schéma du cycle de vie d'une plante à fleur |

Chaque section se termine par un bouton « Retour à l'accueil ».

## Structure du projet

```
planevo/
├── index.html
├── style.css
├── README.md
└── images/
    ├── fond.jpg                 (à ajouter)
    ├── graminees-schema.jpg     (à ajouter)
    └── ... photos et schémas
```

## Lancer le site

Ouvre `index.html` dans un navigateur. Aucune installation n'est nécessaire.
Garde le dossier `images/` à côté de `index.html` et de `style.css`, sinon les images ne s'affichent pas.

## Fichiers à ajouter

Deux images manquent encore. Dépose-les dans `images/` avec exactement ces noms :

- `fond.jpg` : la photo de plantules utilisée comme fond de toutes les pages. Sans elle, un dégradé vert et brun s'affiche à la place.
- `graminees-schema.jpg` : le schéma d'une fleur de graminée (stigmates, paléole, ovaire, lodicules, étamine).

## Images par section

| Section | Fichiers |
|---|---|
| Accueil | `algues.jpg`, `m.jpg`, `f.jpg`, `conifere.jpg`, `gr.jpg`, `Dico.jpg` |
| Algues | `algues1.jpg`, `algues2.jpg`, `algues3.jpg`, `reproduction_des_algues_241_orig.jpg` |
| Mousses | `m1.jpg`, `m2.jpg`, `m3.jpg`, `life-cycle.png` |
| Fougère | `f1.jpg`, `f2.jpg`, `f3.jpg`, `reproduction_de_la_fougere_420_orig.jpg` |
| Conifère | `conifere2.jpg`, `conifere3.jpg`, `conifere.jpg`, `IMG_1607-774x1024.jpeg` |
| Graminées | `gr.jpg`, `Gr3.jpg`, `Gr1.jpg`, `graminees-schema.jpg` |
| Dicotylédones | `Dico1.jpg`, `dico2.jpg`, `Lamium_album__1_.JPG`, `schema_cycle_de_vie_d_une_plante_a_fleur_35_2_orig.jpg` |

Ces fichiers sont présents dans le dossier mais ne sont pas utilisés : `Gr2.jpg` (gros plan d'herbe) et `gr4.jpg` (même photo que `gr.jpg`).

## Personnaliser

Les couleurs, le rayon des coins et la hauteur du menu sont définis au début de `style.css`, dans le bloc `:root` :

```css
:root {
  --vert-menu: #10281a;
  --texte-menu: #f3efe4;
  --gris-bouton: #dcdcdc;
  --rayon: 28px;
  --hauteur-menu: 76px;
}
```

Pour changer une image, remplace le fichier dans `images/` en gardant le même nom, ou modifie l'attribut `src` dans `index.html`.

## Choix de réalisation

- **Mise en page** : toutes les sections utilisent la même grille 2 × 2, avec le schéma en bas à droite. Elle est adaptée au mobile, où les cartes passent en une colonne.
- **Polices** : EB Garamond pour le logo et le menu, Inter pour les boutons. Elles viennent de Google Fonts, avec Garamond, Georgia et Arial comme polices de secours hors ligne.
- **Schémas** : ils s'affichent en entier, sans rognage.
- **Accessibilité** : chaque image a un texte alternatif, les liens ont un focus visible et le défilement animé est désactivé pour les personnes qui préfèrent moins de mouvement.

## Crédits des images

- Schémas de reproduction des algues, des fougères et du cycle de vie d'une plante à fleur : ProjetEcolo. Le schéma des algues porte aussi la mention © Erasmo Macaya H.
- Photo `algues.jpg` (accueil) : le filigrane © Sola Sly est visible sur l'image.
- Vérifie la source et la licence des autres photos avant toute publication en ligne.
