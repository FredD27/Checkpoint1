# Exercice 3

#### 1.

cat /etc/passwd

#### 2.

chmod 744 myfile

#### 3.

- Créer un fichier .gitignore
- L'éditer en écrivant : _.pdf ---> _ pour ignorer tous les fichiers qui finissent par .pdf

#### 4.

- La branche test*valide doit être à jour avec la commande \_git pull origin main*
- Les conflits doivent être résolus, s'il y en a, en local.
- Les fichiers doivent être stagged avec _git add ._
- Puis _git push_ pour que notre branche test_valide soit à jour en distant
- Une pull request doit être demandée de la branche test_valide vers la branche main
- Après validation et confirmation du _merge_, les branches main et test_valide seront fusionnées et toutes les deux à jour.

#### 5.

Dans un script, écrire le code suivant puis l'exécuter dans bash.

#!/bin/bash

echo 'Malgré le prix élevé de 100$, il a dit "Bonjour !" au vendeur :'

echo '- "Bonjour est-ce que ce clavier fonctionne bien ?"'

echo '- "Evidemment ! On peut tout écrire avec, que ce soit des pipe | ou bien des backslash \\ !"'

echo '- "Même des tildes ~ ?"'

echo '- "Evidemment !"'

#### 6.

jobs -l | grep "gedit"

#### 7.

Couche 2 : on peut avoir des switch qui permettent de distribuer une connexion réseau en LAN en utilisant des adresses MAC  
Couche 3 : on retrouve des routeurs qui permettent de communiquer en réseau en WAN et LAN en utilisant des adresses MAC et IP.

#### 8.

- cd ---> Set-Location
- cp ---> Copy-Item
- mkdir ---> New-Item
- ls ---> Get-ChildItem

#### 9.

Le payload représente les données réelles transportées par la trame.

#### 10.

La structuration des adresses en classes a engendré des problèmes comme une pénurie dans l'attribution des adresses. Les classes C étaient trop petites et les classes B trop peu nombreuses.  
Le CIDR a permis la possibilité de découper chaque adresse au besoin et d'attribuer des adresses IP de manière flexible et efficace sur les différents réseaux. Elle améliore donc l'efficacité du routage sur internet.
