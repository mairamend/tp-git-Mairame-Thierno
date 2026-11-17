Q1: L'option globale enregistre la configuration dans le fichier ~/.gitconfig.La differences c'est que les configurations ne concernerons que le depot ou on l'a enregistrer 
Q2: Si l'email ne correspond à celui de github , gthub ne compte pas ta contribution 
Q3: Le dossier .git contient tout l'historique et la configuration du depot 
Q4: git diff donne les modifications non indexés alors que git diff --staged donne qui seront déjà indexés et qui seront dans le prochain commit
Q5: La suite de caractère represente  l'identifiant de chaque commit  
Q6: Par ce que c'est des fichier generer , .gitignore s'implifie git add . car on ne soucie plus d'ajouter des fichier qui ne doit pas être ajouter
Q7: git revert crée un nouveau commit qui annule les changement d'un commit précédent , l'hitorique n'est pas modifié 
git reset deplace la branche vers un commit antérieur donc réecrit l'historique 
Sur une branche partagé on prefere revert 
HEAD~1 Designe le commit avant le dernier commit de la branche  , « detached HEAD » signifie HEAD ne pointe sur une branche mais sur un commit précis 
