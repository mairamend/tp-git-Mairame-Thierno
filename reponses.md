Q1: L'o












































ption globale enregistre la configuration dans le fichier ~/.gitconfig.La differences c'est que les configurations ne concernerons que le depot ou on l'a enregistrer 
Q2: Si l'email ne correspond à celui de github , gthub ne compte pas ta contribution 
Q3: Le dossier .git contient tout l'historique et la configuration du depot 
Q4: git diff donne les modifications non indexés alors que git diff --staged donne qui seront déjà indexés et qui seront dans le prochain commit
Q5: La suite de caractère represente  l'identifiant de chaque commit  
Q6: Par ce que c'est des fichier generer , .gitignore s'implifie git add . car on ne soucie plus d'ajouter des fichier qui ne doit pas être ajouter
Q7: git revert crée un nouveau commit qui annule les changement d'un commit précédent , l'hitorique n'est pas modifié 
git reset deplace la branche vers un commit antérieur donc réecrit l'historique 
Sur une branche partagé on prefere revert 
Q8: HEAD~1 Designe le commit avant le dernier commit de la branche  , « detached HEAD » signifie HEAD ne pointe sur une branche mais sur un commit précis 
Q9:Parce que chaque branche a sa propre version des fichiers. Quand on change de branche, Git remplace le contenu de du dossier par celui de la branche sur laquelle on arrives.
Q10: Une fusion fast-forward (« avance rapide ») se produit quand Git n’a rien à combiner : il se contente de déplacer le pointeur de la branche vers l’avant c'est à dire qu'on a pas modifié le fichier dans main  depuis qu'on a swiché 
Q11: Ce sont les marqueurs de conflit que Git insère dans un fichier quand il ne sait pas lequel des deux changements garder.
<<<<<<< HEAD : début du conflit. Ce qui suit est la version de la branche actuelle (main dans notre tp)
======= : séparateur entre les deux versions.
>>>>>>> titre : fin du conflit. Ce qui précède est la version de la branche qu'on fusionnes (titre).
Une modification

