# Analyse du Catalogue Netflix: Évaluation Finale du Cours Programation 2
## 1- But du projet
*Mise en situation :* Une entreprise de streaming nous a approché pour faire une étude sur le contenu du catalogue de Netflix, le plus gros joueur sur le marché. Notre mandat consiste à analyser ce catalaogue afin d'avoir une vue globale du type de contenu, de son origine, des durées et du genre dans le but d'établir une stratégie dans la conception de leur propre catalogue. pour ce faire on doit répondre aux questions suivantes:
- Quelle est la proportion de film par rapport au séries?
- Quels sont les principaux pays producteur de contenus? 
- Quelle est l'origine géographique des contenus?
- Quelles sont les années de création les plus populaires?
- Quelle est la distribution de la durée des films?
- Quels sont les genres les plus populaire?

## 2- Description du jeu de données (Dataset)
### source:  https://www.kaggle.com/datasets/shivamb/netflix-shows
### Description du dataset
Netflix est l'une des plateformes de streaming multimédia et vidéo les plus populaires. Ils ont plus de 8000 films ou émissions de télévision disponibles sur leur plate-forme, à la mi-2021, ils ont plus de 200 millions d'abonnés dans le monde. Cet ensemble de données tabulaires se compose de listes de tous les films et émissions de télévision disponibles sur Netflix, ainsi que de détails tels que la distribution, les réalisateurs, les notes, l'année de sortie, la durée, etc.
### Description des colonnes
- **show_id** : ID unique pour chaque film / émission de télévision
- **type** : Identifiant - Un film ou une émission de télévision
- **title** : Titre du film / émission de télévision
- **director** : Réalisateur du film
- **cast** : Acteurs impliqués dans le film/série
- **country** : Pays où le film/série a été produit
- **date_added** : Date à laquelle il a été ajouté sur Netflix
- **release_year** : Année de sortie réelle du film / spectacle
- **rating** : Classement TV du film / de l'émission
- **duration** : Durée totale - en minutes ou en nombre de saisons
- **listed_in** : Genres auxquels appartient le film ou la série
- **description** : La description sommaire

## 3- Analyse des résultats
### Proportion de films par rapport aux séries dans le catalogue Netflix
![image](https://user-images.githubusercontent.com/116452605/197362470-c9b0883e-e00e-4e26-bbd3-f45e807cce1a.png)

Le catalogue de Netflix est constitué principalement de films (70%) par rapport aux séries (30%). Il faut souligner que même si la proportion de films est plus élevé, les séries contiennent plusieurs épisodes et donc maintiennent les utilisateurs sur la plateforme plus longtemps.

### Les principaux pays producteur de contenus
![image](https://user-images.githubusercontent.com/116452605/197362656-b00d0e14-244f-4fb6-ab54-b18ed69536ac.png)

Étant donnée que Netflix est une entreprise américaine, il n'est pas étonnant de voir que la plupart du contenu est originaire des États-Unis. L'inde est aussi un grand producteur de films/séries, c'est donc le deuxième pays avec le plus de contenu sur Netflix. Le Canada, quant à lui, se classe à la 7ème position.

###  Les années de création les plus populaires
![image](https://user-images.githubusercontent.com/116452605/197362864-546a7465-40d8-4349-affe-a57519020f32.png)

On constate que le volume des plus récentes productions est plus élevé ce qui est normal, c'est ce qui permet à Netflix de garder sa compétitivité.

### La proportion du nombre de saisons par série
![image](https://user-images.githubusercontent.com/116452605/197362984-93501dee-7d2e-484a-b5aa-8fe37781a4cf.png)

On remarque que la grande majorité de serie (67%) ne depassent pas une saison, ceci dit 6% ont une longévité remarquable depassant les 5 saisons.

### La distribution de la durée des films
![image](https://user-images.githubusercontent.com/116452605/197362990-3d10b879-ae63-496f-88b0-90be0a1dad89.png)

On remarque que la distribution est normal avec une médiane qui se situe vers les 100 min par films.

### Les genres les plus populaire
![image](https://user-images.githubusercontent.com/116452605/197363029-6192688e-eb02-467e-b7c3-65c0bf357bb4.png)

Le genre Drama vient en première position suivi de comédie, action&aventure. Les documentaires se classent à la quatrième position.

## Conclusion
Nous avons répondu à toutes les questions soulevées afin de satisfaire le mandat de l'entreprise. Les analyses effectuées permettront de prendre des décisions éclairées quant à la stratégie appropriée pour la conception de leur propre catalogue.
