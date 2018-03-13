Nom de l'incendie : Thomas.
Recherche documentaire : l'humidité est un paramètre pour la propagation du feu : https://www.20minutes.fr/monde/2186891-20171213-incendies-californie-scenes-apocalypse-pres-santa-barbara-proie-incendies
Citation du lien ci-dessus :  La sécheresse extrême combinée à des températures anormalement élevées pour la saison et les vents violents ont freiné le travail des pompiers.
http://www.sudouest.fr/2017/12/17/etats-unis-la-californie-lutte-toujours-contre-l-incendie-thomas-4041717-4803.php
Citation du lien ci-dessus :  Les conditions climatiques – vents et faible humidité – continueront de favoriser la progression du feu.


Paramètres : 
-Humidité
-Température
-Vent(direction)
-Relief


Agents : 
-Arbres (sain/en feu/carbonisée)
-eau


## Données
- [incidents_details_maps](http://cdfdata.fire.ca.gov/incidents/incidents_details_maps?incident_id=1922)
https://hal.archives-ouvertes.fr/file/index/docid/287987/filename/Les_simulations_de_propagation_de_feu_en_milieu_urbain.pdf

-https://www.science-emergence.com/Articles/G%C3%A9n%C3%A9rer-un-tableau-matrice-de-nombres-al%C3%A9atoires-avec-numpy-de-python/ : Mettre un intervalle pour les valeurs de la matrice.


Remarque : -Prendre en compte le relief : Nous allons prendre en compte la carte topographique de la Californie en fonction de l'incendie.
-Choisir un sujet réel comme sujet : Nous avons pris l'incendie Thomas en Californie de Décembre 2017.

La semaine prochaine : nous comptons commencer à programmer, afin de visualiser nos resemblances et différences par rapport au sujet réel.Trouver une carte topographique de la Californie en fonction de l'incendie Thomas.
## PROJET

Thème : feu de forêt.

Sujet réel : Incendie Thomas.

Problématique : Comment se propage un feu de forêt?

Principe :Nous pensions créer une carte, dans laquelle les différentes cases auront des valeurs qui varient en fonction de différents paramètres tels que la température, l'humidité, le relief.Ces paramètres seront dans un premier temps inspirés de l'incendie Thomas puis nous les feront varier un à un pour comprendre comment ces paramètres agissent sur un incendie.

Fiche technique : Pour mettre à bien nous pensions utiliser une matrice de longueur et largeur L comme carte, puis nous selectionnerons une case comme foyer de l'incendie, cette case en interagira avec les autres de la carte en fonction du vent. Les arbres auront 3 états possibles : sain, en feu et carbonisée, ils ne pourront pas cumuler 2 états. D'autres cases seront mises en jeu telles que : les sources d'eau, les sources d'eau ne peuvent ni être en feu, ni être carbonisée.Un bilan technique sera fait à la suite de la simulation afin de tirer des conclusions.


## Notebook

[1er notebook](https://github.com/are-dynamic-2018/Projet-feu-de-foret/blob/master/Projet.ipynb)


## Objectifs
objectifs réussis : -Arbre peut être sain , en feu ou carbonisée.
                  -Le feu est guidé par le vent.
                  -Les calculs sont bons.




Ce qu'il nous manque : -Utilisation de nouveaux paramètres (température,humidité,relief).
                       -Animations.
                       -Cases neutres.
