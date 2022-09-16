Fichier d'aide à l'utilisation des fichiers fournis.


Dans le dossier que nous vous remettons, vous retrouverez éléments suivants :



- Diaporama "Tuto Github/Streamlit" :

Il s'agit du tutoriel pas à pas qui explique la création d'un compte Github et d'un compte Streamlit, puis comment importer les fichiers nécessaire au fonctionnement de l'application.


C'est quoi Github ? C'est une plateforme en ligne qui permet de "stocker" du code dans des repository (une forme de dossier qui permet de gérer le code d'un projet).
Et Streamlit ? C'est un site qui fait le lien avec un repository Github et permet d'héberger et lancer le code sous forme d'application interactive utilisable sur un navigateur internet. (L'URL de l'appli est partageable).


- Le fichier "ODT_mislabelled.xlsx" :

C'est la liste des Offices de tourismes dont la catégorie est potentiellement mal référencée.
Le jeu de données ne montre que les offices de tourisme dont la catégorie est :"touristinformationcenter".



- Dossier "Streamlit" :

Il contient les fichiers qui seront à mettre dans un repository Github afin que l'application puisse être hébergée en ligne.


Le fichier "blablba.py" est le code de notre application, il fait appel aux fichiers présents dans le dossier "pages" qui contient le code des différentes pages de l'application.

"Requirements.txt" est un fichier texte qui indique quels modules Python l'application doit utiliser, rien n'est à modifier dans son contenu.

Plusieurs fichiers CSV qui sont les différentes bases de données que nous utilisons pour le rendu :
    
    - "df_matched_true.csv" Est la base de données des POI que nous avons réussi à faire matcher sur les données de DataGouv.
    - "df_datagouv_clean.csv" C'est le fichier officiel de la marque "Qualité Tourisme" issu de la DGE.
    - "df_QT_notmatched.csv"  La base des POI ayant la marque Qualité Tourisme qui n'ont pas matché.
    - "departements-france.csv" est la liste des départements Français.
    - "data_tourisme_MQ_clean.csv" C'est la base de tous les POI marque Qualité de Datatourisme.

 





