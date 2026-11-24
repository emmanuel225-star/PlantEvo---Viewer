# Relevés de terrain PlantEvo : répartition de groupes de végétaux selon le milieu

**Auteurs :** Emmmanuel Touré
**Relevés menés par :** Emmanuel Touré
**Date des relevés :** 21 novembre 2026
**Zone d'étude :** … (centre des relevés : 6,8927° N, 5,2254° O)

---

## 01. Introduction

### Objectif

Localiser, identifier et photographier un représentant de chacun des groupes de végétaux étudiés dans le projet PlantEvo (algues, mousses, fougères, conifères, graminées, dicotylédones), puis comparer leur répartition entre milieu sec et milieu humide.

### Zone d'étude

- **Lieu :** INPHB - NORD
- **Coordonnées approximatives du centre :** 6,8927° N, 5,2254° O
- **Emprise des relevés :** environ 660 m (nord-sud) sur 120 m (est-ouest)
- **Milieux présents :** milieu sec et milieu humide (les deux catégories utilisées dans le formulaire)

---

## 02. Matériel et méthode

### Appareil

- **Modèle :** …
- **Précision annoncée :** …
- **Précision enregistrée pendant les relevés :** de 2,6 m à 3,7 m (moyenne : 3,2 m)

### Application

- **Nom :** KoboToolbox, formulaire « Brief Projet – PlantEvo » 
- **Version et réglages :** …

### Protocole de relevé

- **Date et horaires :** 21 novembre 2026, formulaires ouverts entre 12 h 09 et 12 h 45 (heure UTC)
- **Conditions (météo, couvert) :** …
- **Parcours ou méthode d'échantillonnage :** …
- **Informations notées à chaque point :**
  - l'identifiant du relevé, le groupe et l'espèce ;
  - la position GPS (latitude, longitude, altitude, précision) ;
  - la date, le milieu (sec ou humide) et une remarque libre ;
  - trois photos : une photo de la plante, une photo de l'appareil végétatif et une photo de l'organe.
- **Règle d'attribution d'un point à un groupe :** …

### Système de coordonnées

- **Système :** WGS 84 (EPSG:4326)
- **Format :** degrés décimaux
- **Logiciel utilisé pour la carte :** Python (matplotlib), sans fond de carte

---

## 03. Résultats

### Carte des relevés

![Carte des relevés](carte-releves.png)

*Légende : un cercle indique un milieu humide, un carré un milieu sec. La couleur correspond au groupe. Les points E5-01 et E5-02 sont à environ 7 m l'un de l'autre et se chevauchent sur la carte.*

### Tableau par groupe

| Groupe | Nombre de relevés | Part du total (%) | Exemples d'espèces ou de noms | Remarques |
|---|---|---|---|---|
| Algues | 1 | 20 | *Ulva* | Aucune |
| Mousses | 1 | 20 | *Leucobryum glaucum* | Sur des murs |
| Fougères | 1 | 20 | *Nephrolepis exaltata* | Sur le tronc d'un palmier |
| Conifères | 0 | 0 | | Aucun relevé enregistré |
| Graminées | 1 | 20 | *Triticum* | Aucune |
| Dicotylédones | 1 | 20 | *Balanites aegyptiaca* | Fruits observés |
| **Total** | **5** | **100** | | |

### Détail des relevés

| Identifiant | Groupe | Espèce | Latitude | Longitude | Altitude (m) | Précision (m) | Milieu |
|---|---|---|---|---|---|---|---|
| E5-01 | Algues | *Ulva* | 6,890145 | −5,2255114 | 268,2 | 3,4 | Humide |
| E5-02 | Mousses | *Leucobryum glaucum* | 6,890193 | −5,225469 | 268,3 | 3,7 | Humide |
| E5-03 | Fougères | *Nephrolepis exaltata* | 6,8961188 | −5,2257218 | 257,1 | 2,8 | Sec |
| E5-05 | Graminées | *Triticum* | 6,89571 | −5,225615 | 265,3 | 2,6 | Sec |
| E5-06 | Dicotylédones | *Balanites aegyptiaca* | 6,8912579 | −5,2246111 | 266,4 | 3,6 | Sec |

---

## 04. Analyse

### Répartition des groupes selon les milieux

| Milieu | Algues | Mousses | Fougères | Conifères | Graminées | Dicotylédones | Total |
|---|---|---|---|---|---|---|---|
| Milieu humide | 1 | 1 | 0 | 0 | 0 | 0 | 2 |
| Milieu sec | 0 | 0 | 1 | 0 | 1 | 1 | 3 |
| **Total** | 1 | 1 | 1 | 0 | 1 | 1 | 5 |

### Observations

- Les algues et les mousses ont été relevées en milieu humide. Les fougères, les graminées et les dicotylédones ont été relevées en milieu sec.
- Les deux relevés humides sont presque au même endroit (environ 7 m d'écart), au sud de la zone. Les fougères et les graminées sont à environ 50 m l'une de l'autre, au nord, et les dicotylédones se trouvent entre les deux ensembles.
- Avec un seul relevé par groupe, cette répartition est descriptive : elle ne permet pas de conclure à une préférence de milieu.
- La fougère relevée en milieu sec poussait sur le tronc d'un palmier. Ce support peut offrir plus d'humidité que le sol environnant, et le classement en milieu sec mérite d'être discuté.

---

## 05. Limites

### Précision

La précision GPS enregistrée va de 2,6 m à 3,7 m. Les points E5-01 et E5-02 sont à 7,1 m l'un de l'autre, soit environ deux fois cette précision : leur position relative est donc peu fiable. L'altitude GPS est moins précise que la position horizontale et n'a pas été interprétée.

### Points douteux

| Identifiant du point | Problème rencontré | Décision (gardé, corrigé, supprimé) |
|---|---|---|
| E5-04 | Identifiant absent de la série E5-01 à E5-06 | … |
| E5-05 | *Triticum* est un nom de genre (le blé, une plante cultivée) : l'espèce n'est pas précisée | À vérifier avec les photos |
| E5-01 | *Ulva* est un nom de genre : l'espèce n'est pas précisée | À vérifier avec les photos |
| E5-02 | Identification de l'espèce à confirmer : mousse relevée sur des murs | À vérifier avec les photos |
| Tous | L'heure de fin enregistrée est le 22 novembre alors que les relevés datent du 21 : les fiches ont probablement été rouvertes ou modifiées ensuite | … |

### Couverture de la zone

Seuls 5 points ont été relevés, tous le 21 novembre 2026 et par une seule personne. L'emprise est d'environ 660 m sur 120 m, avec un point par groupe et aucun relevé de conifères. Le formulaire ne distingue que deux types de milieu, ce qui limite la finesse de l'analyse. Les parties de la zone non visitées sont à préciser : …

---

## 06. Annexes

### A. Fichier CSV

- **Nom du fichier :** `releves.csv` (copie de l'export KoboToolbox du 22 novembre 2026)
- **Nombre de lignes :** 5 relevés, plus une ligne d'en-tête
- **Nombre de colonnes :** 29
- **Séparateur et encodage :** point-virgule, valeurs entre guillemets, UTF-8

### B. Photos

Les photos sont hébergées sur KoboToolbox. Leurs liens figurent dans le CSV, et l'accès demande une connexion au compte du projet.

| Identifiant du point | Photo | Photo végétatif | Photo organe |
|---|---|---|---|
| E5-01 | 1795265102036.jpg | 1795265119148.jpg | 1795265134044.jpg |
| E5-02 | 1795265220220.jpg | 1795265247946.jpg | 1795265263565.jpg |
| E5-03 | 1795263541097.jpg | 1795263555100.jpg | 1795263568929.jpg |
| E5-05 | 1795263132681.jpg | 1795263154499.jpg | 1795263170599.jpg |
| E5-06 | 1795264627747.jpg | 1795264638543.jpg | 1795264657615.jpg |

### C. Dictionnaire de données

| Champ | Description | Type | Valeurs possibles ou exemple |
|---|---|---|---|
| `start`, `end` | Date et heure d'ouverture et d'enregistrement du formulaire | Date-heure | `2026-11-21T12:09:48.691+00:00` |
| `Idplant` | Identifiant du relevé | Texte | `E5-01` |
| `Groupe` | Groupe de végétaux (code) | Texte | `algues`, `mousses`, `foug_res`, `gramin_es`, `dicotyl_dones` |
| `Esp_ce` | Espèce ou genre observé | Texte | `Nephrolepis exaltata` |
| `Latitude_longitude_Précision` | Position brute : latitude, longitude, altitude, précision | Texte | `6.89571 -5.225615 265.3 2.6` |
| `_..._latitude`, `_..._longitude` | Coordonnées en degrés décimaux (WGS 84) | Nombre | `6.89571`, `-5.225615` |
| `_..._altitude` | Altitude GPS, en mètres | Nombre | `265.3` |
| `_..._precision` | Précision de la position, en mètres | Nombre | `2.6` |
| `Date_heure` | Date du relevé (la colonne ne contient pas d'heure) | Date | `2026-11-21` |
| `Observations` | Champ libre, utilisé ici pour le nom de la personne qui a mené le relevé | Texte | `Mener par Emmanuel Touré` |
| `Remarque` | Remarque libre sur le relevé | Texte | `Aucune` |
| `Mileu` | Milieu du relevé (nom de colonne avec une faute de frappe) | Texte | `Milieu sec`, `Milieu humide` |
| `Photo`, `Photo_Végétatif`, `Photo_Organe` | Nom des trois fichiers photo | Texte | `1795263132681.jpg` |
| `..._URL` | Lien KoboToolbox vers chacune des photos | Texte (URL) | `https://kf.kobotoolbox.org/...` |
| `_id`, `_uuid`, `_index`, `meta/rootUuid` | Identifiants techniques de la soumission | Texte ou nombre | `919622472` |
| `_submission_time` | Date et heure d'envoi de la fiche | Date-heure | `2026-11-21T13:40:30` |
| `_validation_status`, `_status`, `_submitted_by`, `__version__` | Statut de validation, mode d'envoi, compte utilisé et version du formulaire | Texte | `submitted_via_web` |
