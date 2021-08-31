le workflow utilisé aura 8 branches

1 branche main 
1 branche hotfix pour regler les problemes rapidement
1 branche develop pour integrer le plus gros du code
1 branche feature-1 pour les fonctionnalitées basiques (Ajout série)
1 branche feature-2 pour les fonctionnalitées avancées (Ajout personnage)
1 branche feature-3 pour les fonctionnalitées basiques (Ajout avec commit signé)
1 branche feature-4 pour les fonctionnalitées avancées (Ajout avec commit signé)
1 release pour la correction des derniers bugs 
ce workflow couvre l'ensemble des exigences pour un projet car il peut corriger les bugs eventuels avec une branche hotfix, puis developer des fonctionnalités avec la branche feature qui se regrouperont dans la branche develop, avant de corriger les derniers bugs et de se regrouper dans le main  

![workflow](https://user-images.githubusercontent.com/89772013/131465755-1d71e529-2ce0-4e93-bf6e-397f74e5a156.PNG)

commandes utilisées :

git checkout -b pour creer une branche et s'y accrocher directement
git checkout pour changer de branche
git merge pour fusionner les branches 
touch pour creer un fichier 
git add . pour ajouter les fichiers
git commit pour valider les modifications 
git push pour envoyer au serveur distant 
git pull pour recuperer sur le serveur distant
rm pour supprimer un fichier
mv pour renommer un fichier
gpg --gen-key pour generer une clef privé pour pouvoir signer les commit
git config --global user.signingKey pour ajouter la clef 
git commit -a -S -m 'commit signé' pour generer un commit signé  
