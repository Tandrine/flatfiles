#Comment utiliser GIT ?
##Git Hub
 1. Lancer le terminal de commande dans le dossier flatfiles
 2. Faire git pull (pull=tirer) afin de récupérer ce qu'il y a sur le compte git auquel on est lié
 3. Faire un git status qui est sensé ne rien afficher
 4. Faire un git log si on veut voir les derniers commit
 5. Si on a effectué des modif, git status montre les fichier modifiés en rouge
 6. Faire git add --all pour ajouter les fichiers modifiés au serveur
 7. Faire git status, vérifié que les fichiers sont en vert
 8. Faire git push origin master pour pousser sur la branche principale
 9. Faire sudo git commit -a pour afficher le fichier de commit
 10. Décommenter les lignes des fichiers à commiter (le nom est le nom du commit modifiable)
 11. Faire ctrl O (oh) pour enregistrer, appuyer sur entré pour confirme, ctrl x pour quitter
 12. Les fichiers sont maintenant à jour sur le serveur
 13. Faire git status qui doit ne rien afficher puis git log pour voir les modifications effectuées et par qui
 
 ##Jekyll
  1. Pour lancer le serveur jekyll faire jekyll serve dans le terminal
  2. A chaque modification effectuée par la suite sur les fichiers, un message apparaît
  3. Aller sur 127.0.0.1:4000 pour voir le site en du serveur local
  4. Aller sur <a href="jekyll.tips">jekyll.tips</a> pour trouver des tutos
  5. Quand on a terminé, refaire les manip de git
