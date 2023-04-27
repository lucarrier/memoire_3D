Bonjour et bienvenue sur le GitHub dédié à mon mémoire de recherche de 4A à Sciences Po Lille.

Mon étude porte sur les transformations numériques du cinéma. Plus particulièrement, je m'intéresse à la réception de la 3D stéréoscopique par les publics du cinéma.
J'ai choisi un terrain d'étude numérique : il s'agit de la section "critiques spectateurs" de la plateforme Allociné, pour un corpus de films sélectionnés.

Le corpus de films retenu est le suivant :
 ________________________________________________
|		 |			 |	 |
|Titre		 | Réalisateur		 | Année |
|_______________ |_______________________|_______|
|		 |			 | 	 |
|Avatar		 | James Cameron	 |2009	 |
|_______________ |_______________________|_______|
|		 |			 |	 |
|Avatar : La	 | James Cameron	 |2022	 |
|Voie de l'eau	 |			 |	 |
|_______________ |_______________________|_______|
|		 |			 |	 |
|Adieu au Langage| Jean-Luc Godard	 |2014	 |
|________________|_______________________|_______|
|		 |			 |	 |
|Gravity	 | Alfonso Cuaron	 |2013	 |
|________________|_______________________|_______|
|		 |			 |	 |
|Le Hobbit: Un 	 | Peter Jackson	 |2012	 |
|Voyage inattendu|			 |	 |
|________________|_______________________|_______|
|		 |			 |	 |
|Avengers	 | Joss Whedon		 |2012	 |
|________________|_______________________|_______|

Pour une description détaillée des choix effectués et de la méthodologie mise en oeuvre pour la collecte des données, se référer à la section méthodologie dans le document de mon mémoire de recherche, disponible sur demande.

Les données présentes dans le tableau excel sont les suivantes:

id_avis : id de l'avis retenu
film : titre du film
note : note attribuée au film par l'utilisateur
date : année du commentaire
pseudonyme : nom de l'utilisateur
total_avis : nombre total de critiques postées par l'utilisateur
nb_abo : nombre d'abonnés de l'utilisateur
derniers_films : Derniers films notés par l'utilisateur. Catégorisés en fonction du genre et du type de film.
derniers_aimes : Derniers films ayant été notés 4 étoiles (sur 5) ou plus par l'utilisateur. Catégorisés en fonction du genre et du type de film.
univore_omnivore : Posture des goûts de l'utilisateur. Déterminée lorsque c'est possible par la colonne derniers_aimes et les autres critiques postees par l'utilisateur.
CC : estimation du volume de capital culturel de l'individu, basé sur une analyse générale de son profil et sur les critiques qu'il a postées. 
3D_avis_positif : Oui/Non/Neutre pour qualifier si l'avis est positif ou négatif envers la 3D stéréoscopique (et non le film dans son ensemble).
3D_vocab : liste de mots-clés utilisés pour qualifier l'expérience de la 3D stéréoscopique.
3D_niveau_recep : Niveau de réception de la 3D stéréoscopique, fonctionnel ou iconologique selon les définitions de mon étude. 

Une dernière colonne "commentaires" a été utilisée dans le fichier original pour me permettre d'extraire des citations pour illustrer mes propos.


Une visualisation et une interprétation de ces données sont disponibles sur mon profil Tableau Public, à l'adresse : https://public.tableau.com/app/profile/lucas.carrier