##Automatisation d'un malaxage

#Cahier des charges du projet 

Objectif :
L'objectif du projet sera de créer un processus de malaxage à partir d'un système Habilis et d'un pupitre de commande.
Déroulement des étapes :
   
    1. Se documenter sur le système Habilis et comment faire une mise en service 

    2. Faire la mise en service hors tension du pupitre d'automate 

    3. Faire la mise en service sous tension du pupitre d'automate
        
    4. Identifier toutes les configurations de l'automate 
       
    5. Créer le processus de malaxage puis charger le programme dans l'automate 
       
    6. S'assurer que l'armoire électrique ne présente pas/plus de problème
        
    7. Tester, modifier/arranger et optimiser le programme 
       
    8. Une fois le cycle de base validé, concevoir le mode automatique/manuel et éditer l'IHM


#Cahier des charges fonctionnel
   Objectif :
   Programmer le malaxeur pour qu'il réalise une séquence de chauffage et de malaxage avec des ajouts de produit à des étapes précises.
    
    1. Chauffage initial  
       - Monter la température de la cuve à 45°C
    
    2. Ajout de produit  
       -  Ajouter le produit dans la cuve
    
    3. Début du malaxage  
       - Commencer le malaxage a une vitesse déterminée
    
    4. Montée en température 
       - Augmenter la température de la cuve à 65°C.
   
    5. Arrêt de la chauffe et poursuite du malaxage  
       - Arrêter le chauffage.
       - Maintenir le malaxage pendant 60 minutes sans chauffer.
    6. Ajout de produit
       - Ajouter le produit dans la cuve.
    7. Montée en température 
       - Monter la température de la cuve à 80°C.
    8. Malaxage final
       - Maintenir le malaxage à 80°C pendant 45 minutes.



#27/01 :
Je reste bloqué sur l'élément perturbateur de l'armoire éléctrique, malgré plusieurs tentatives pour identifier et résoudre ce dysfonctionnement. J’ai essayé de forcer les sorties et entrées qui semblaient correspondre au problème, mais sans succès. Les résultats ne montraient aucune amélioration, et les signaux attendus ne parvenaient pas aux actionneurs.

Face à cette difficulté, j’ai entrepris de :

-retracer les câblages des borniers J1, J2, et J3 accordés aux entrées et sortie de l'automate, pour pouvoir savoir quelle sortie il faut forcer. Je n'ai pas accès à l'armoire éléctrique alors je regroupe toute mes idées pour pouvoir continué à la prochaine séance.
