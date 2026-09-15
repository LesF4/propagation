# STANDARD DE PUBLICATION — LES F4 PROPAGATION

Ce fichier est la référence obligatoire pour chaque édition hebdomadaire.

## 1. Données et validation

Avant toute publication, les prévisions doivent être recoupées avec plusieurs sources :

1. NOAA / SWPC ;
2. SIDC / RWC Belgium ;
3. Met Office Space Weather ;
4. une source de contrôle opérationnelle complémentaire lorsque pertinente, par exemple Australian Space Weather Forecasting Centre.

Règles :
- ne jamais construire le bulletin sur une seule source si les autres sont disponibles ;
- conserver et expliquer les divergences entre sources ;
- distinguer prévisions à 3 jours et tendances plus lointaines ;
- ne pas présenter un chiffre prévisionnel comme une mesure réelle ;
- les bandes conseillées doivent être exprimées comme tendances, jamais comme garanties d’ouverture ;
- contrôler dates, titres, liens et semaine avant publication.

## 2. Bulletin texte

Nom : `LES-F4-PROPAGATION-AAAA-MM-JJ-au-AAAA-MM-JJ.txt`

Ordre fixe :
1. titre et période ;
2. résumé express ;
3. sources recoupées ;
4. activité solaire et F10.7 ;
5. géomagnétisme jour par jour ;
6. bandes HF et conseils pratiques ;
7. bloc POTA / SOTA / portable ;
8. VHF / UHF ;
9. à retenir ;
10. sources ;
11. signature `F4MAJ pour Les F4`.

## 3. Bulletin animé

Fichier public : `index.html`

Le bulletin animé conserve le format visuel « Flux vidéo V2 » :
- plein écran sombre Les F4 ;
- animation automatique par chapitres ;
- boutons précédent / pause / suivant ;
- barre de progression ;
- ticker en bas ;
- indicateur radio pratique à droite ;
- chapitres courts, lisibles et pédagogiques ;
- même période et mêmes conclusions que le bulletin texte ;
- sources recoupées visibles dans l’animation ;
- aucune ancienne date ne doit subsister dans le titre HTML, l’en-tête ou le contenu.

## 4. Discord

Ordre fixe :
1. `📡 PROPAGATION LES F4 — DU ... AU ...` ;
2. courte introduction ;
3. flux solaire et bandes principales ;
4. tendance des jours importants avec codes couleur ;
5. conseil radio pratique ;
6. sources recoupées ;
7. lien bulletin animé ;
8. lien bulletin texte ;
9. signature `73 à tous et bon trafic sur les bandes 📻 — F4MAJ`.

Le message Discord doit être préparé avant publication et correspondre exactement à l’édition active.

## 5. X / Twitter

Format court :
- titre propagation HF + période ;
- 3 à 5 lignes maximum sur la tendance ;
- conseil bandes ;
- lien vers le bulletin animé ;
- hashtags radio pertinents.

Hashtags de base : `#Radioamateur #HamRadio #Propagation #HF #POTA #SOTA`.

## 6. YouTube Les F4

Préparer à chaque édition :
- un titre clair avec période ;
- une description résumant la tendance ;
- conseils par bandes ;
- sources recoupées ;
- lien bulletin animé ;
- lien bulletin texte ;
- signature `F4MAJ pour Les F4` ;
- hashtags de base `#Radioamateur #HamRadio #Propagation #HF #POTA #SOTA #LesF4`.

## 7. Fichier messages

Nom : `MESSAGE-A-PUBLIER-AAAA-MM-JJ.txt`

Il doit contenir dans cet ordre :
1. DISCORD ;
2. X / TWITTER ;
3. YOUTUBE LES F4.

Une seule version active doit rester dans le dépôt.

## 8. Contrôle final obligatoire

Avant partage :
- [ ] bulletin texte = bonne semaine ;
- [ ] index.html = bonne semaine ;
- [ ] README = bonne semaine ;
- [ ] message Discord = bonne semaine ;
- [ ] message X = bonne semaine ;
- [ ] titre et description YouTube = bonne semaine ;
- [ ] liens testés ;
- [ ] données recoupées ;
- [ ] divergences signalées ;
- [ ] aucun ancien fichier de message public restant ;
- [ ] validation humaine de JB avant publication définitive lorsque le processus le permet.

Ce standard ne doit pas être modifié automatiquement d’une semaine à l’autre.
