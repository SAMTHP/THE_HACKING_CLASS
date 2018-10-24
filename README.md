# Création de THE HACKING PINTEREST
Contributeurs SAMTHP & HERVELEE

**Après téléchargement du repo, lancer**

```bundle install```  
```rails db:migrate```  
```rails db:seed```  

Accès à la console pour vérifier la structure de la BDD
```rails console```


## Résumé du projet
- Création d'un site de d'éducation en ligne
- Elèves qui pourront s'inscrire à un seul cours
- Un cours pourra avoir plusieurs élèves

## Structure de la BDD

### Models 
- Cour
- Student

### Colonnes de chaque table
> ```timestamps``` est présent dans chaque table sous la forme  
> ```t.datetime "created_at", null: false```  
> ```t.datetime "updated_at", null: false```   

* **table** ```students```
    * "name" (string)
    * "cour_id" **(foreign key)**

* **table** ```cours```
    * "url" (name)
