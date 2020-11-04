# PrairieGit2
Historique de mes commits:

$ git log
commit 2a5e11c8c2a83c6db2ddaf41178671b76b0bb276 (HEAD -> Dev, origin/Dev)
Author: Alicia Schouman <schoumanalicia@gmail.com>
Date:   Mon Nov 2 14:13:39 2020 +0100

    merge

commit 37fef88b72948bb85f883f38e0df56e7fc569780
Author: Alicia Schouman <schoumanalicia@gmail.com>
Date:   Mon Nov 2 13:21:49 2020 +0100

    Second change to this file

commit b67a1d4be1d13b6de36157ca7b04bd93afb71dd9
Author: Alicia Schouman <schoumanalicia@gmail.com>
Date:   Mon Nov 2 12:36:24 2020 +0100

    exo1



Exo6

J'ai modifié mon fichier texte first-push.txt dans mon dossier local.
Puis j'ai exécuté les commandes pour que ma modification soit poussée sur mon Github
                               $ git add first-push.txt
                               $ git commit -m"Second change to this file"
                               $ git push
                               
                                

Exo7

J'ai cette fois modifié mon fichier first-push.txt directement dans Github. 
Pour visulaliser que ma modification a bien été prise en compte. 
 $ git diff
diff --git a/first-push.txt b/first-push.txt
index 853b7e1..314546a 100644
--- a/first-push.txt
+++ b/first-push.txt
@@ -1,2 +1,3 @@
 bonjour
 hello
+salut
\ No newline at end of file


Puis j'ai exécuté les commandes suivantes pour que ma modif de mon fichier soit enregistré sur mon dossier local.
                               $ git pull origin main

 
                                  



