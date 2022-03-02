# my-super-website
MacBook-Pro-de-Mac:dv macbookpro$ git clone git@github.com:ismamama1/my-super-website.git
Clonage dans 'my-super-website'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
Réception d'objets: 100% (6/6), fait.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
MacBook-Pro-de-Mac:wild-git macbookpro$ cd my-super-website
MacBook-Pro-de-Mac:my-super-website macbookpro$ git add .
MacBook-Pro-de-Mac:my-super-website macbookpro$ git status
Sur la branche main
Votre branche est à jour avec 'origin/main'.

Modifications qui seront validées :
  (utilisez "git restore --staged <fichier>..." pour désindexer)
	modifié :         index.html

MacBook-Pro-de-Mac:my-super-website macbookpro$ git commit -m "<h1><h2>"
[main eef074b] <h1><h2>
 1 file changed, 2 insertions(+)
  
MacBook-Pro-de-Mac:my-super-website macbookpro$ git push git@github.com:ismamama1/my-super-website.git
Énumération des objets: 5, fait.
Décompte des objets: 100% (5/5), fait.
Compression par delta en utilisant jusqu'à 4 fils d'exécution
Compression des objets: 100% (3/3), fait.
Écriture des objets: 100% (3/3), 355 octets | 355.00 Kio/s, fait.
Total 3 (delta 1), réutilisés 0 (delta 0), réutilisés du pack 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:ismamama1/my-super-website.git
   43e1748..eef074b  main -> main

   43e1748..eef074b  main -> main
