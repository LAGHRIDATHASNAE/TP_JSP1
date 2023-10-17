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
![s1](https://github.com/LAGHRIDATHASNAE/TP_JSP/assets/148015530/974e1f44-27ba-45ba-a37b-ad77f7ca36a4)

2)Produit.jsp: on peut ici ajouter un produit tout en précisant la catégorie aussi.
![Capture d’écran (875)](https://github.com/LAGHRIDATHASNAE/TP_JSP/assets/148015530/461a8b01-c77f-4761-8cfe-18b23e308902)

3)LigneCommande.jsp: on peut ajouter une ligne de commande par produit et par commande.
![Capture d’écran (876)](https://github.com/LAGHRIDATHASNAE/TP_JSP/assets/148015530/d012b2c5-062d-4814-a139-9ab361054629)

4)EditLigne.jsp: Ce formulaire nous permet de modifier une ligne de commande.
![Capture d’écran (877)](https://github.com/LAGHRIDATHASNAE/TP_JSP/assets/148015530/a373bfdc-d201-413f-8e85-d44a4210e6b3)

5)EditCategorie.jsp: Ce formulaire nous permet de modifier une catégorie en cliquant sur le bouton "Modifier" de l'interface "Categorie.jsp".
![Capture d’écran (869)](https://github.com/LAGHRIDATHASNAE/TP_JSP/assets/148015530/0e3a5e3e-d5bb-4b83-9985-79734ecb64b2)

En plus, la fonctionnalité de suppression est bien établie. Il suffit de cliquer sur le bouton "Supprimer".

