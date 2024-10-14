 

 Application de Gestion de Stock  

Cette application Java gère le stock d'un magasin de produits informatiques en utilisant Hibernate et MySQL.  

 Fonctionnalités  
- CRUD sur produits, catégories, commandes, et lignes de commande.  
- Affichage des produits par catégorie.  
- Affichage des produits commandés entre deux dates.  
- Affichage des détails d'une commande (référence, prix, quantité).  
- Affichage des produits dont le prix dépasse 100 DH via une requête nommée.

 Structure du Projet  
- Couche Persistance:  
  - Entités dans `ma.projet.classes`.  
  - Configuration dans `hibernate.cfg.xml` (package `ma.projet.config`).  
  - Gestion de session avec `HibernateUtil` (`ma.projet.util`).  

- Couche Service :  
  - Interface `IDao` (`ma.projet.dao`).  
  - Services : `ProduitService`, `CategorieService`, `CommandeService`, `LigneCommandeService` (`ma.projet.service`).  

 Installation  
1. Créer la base de données `magasin` sous MySQL.  
2. Ajouter Hibernate, JPA, et le driver MySQL.  
3. Configurer `hibernate.cfg.xml` avec les paramètres de connexion.  

Exécution  
- Ajouter des produits et commandes.  
- Tester les fonctionnalités comme l'affichage par catégorie ou les produits commandés entre deux dates.  

---

te.  
