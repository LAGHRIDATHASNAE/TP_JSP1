# TP_JSP1



Ce Tp sert à réaliser une manipulation complète sur les entités, tout en parlant sur les opérations CRUD(Create,Read,Update,Delete).

Ce Tp a pour architecture:

ma.projet 
1)classes(Commande,Produit,Catégorie,LigneCommandeProduit) 
2)services(CommandeService,ProduitService,CatégorieService,LigneCommandeProduitService)
3)config(hibernate.cfg.xml) 
4)util(HibernateUtil) 
5)Test(Test,TestCommande,TestFindProduitByCommande, TestLigneCommandeProduit, TestProduit --> plusieurs fichiers réparties, chaque entité a son fichier de test/ manipulation avec la base de données/ l'affichage composé des méthodes définies au niveau du couche service.
6)dao(IDao)
7)controllers(CommandeController,ProduitController,CatégorieController,LigneCommandeProduitController)

Pour base de données, veuillez créer la base de données : stock2

Concernant la couche présentation, voici une petite présentation de quelques interfaces de cette application:

1)index.jsp: cette page contient les quatres liens d'ajout des produits, lignecommandes, commandes, et catégories
![s1](https://github.com/LAGHRIDATHASNAE/TP_JSP1/assets/148015530/51eecd1a-6da7-42f2-b4e8-c07923c05454)


2)Produit.jsp: on peut ici ajouter un produit tout en précisant la catégorie aussi.
![Capture d’écran (875)](https://github.com/LAGHRIDATHASNAE/TP_JSP1/assets/148015530/a7ba5285-6741-4e84-917d-8edc731c9a88)


3)LigneCommande.jsp: on peut ajouter une ligne de commande par produit et par commande.

![Capture d’écran (876)](https://github.com/LAGHRIDATHASNAE/TP_JSP1/assets/148015530/afde4b08-581d-4dc0-92cb-21258521c2af)


4)EditLigne.jsp: Ce formulaire nous permet de modifier une ligne de commande.
![Capture d’écran (877)](https://github.com/LAGHRIDATHASNAE/TP_JSP1/assets/148015530/ec5a7f6b-cec2-4efc-a6e4-fe78389ff045)


5)EditCategorie.jsp: Ce formulaire nous permet de modifier une catégorie en cliquant sur le bouton "Modifier" de l'interface "Categorie.jsp".

![Capture d’écran (869)](https://github.com/LAGHRIDATHASNAE/TP_JSP1/assets/148015530/b3c804c9-d3c4-42cd-9dec-32848cc48045)

En plus, la fonctionnalité de suppression est bien établie. Il suffit de cliquer sur le bouton "Supprimer".

