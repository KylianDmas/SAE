#Installation SAE

##I: Préparer la clé d'installation
On commence par télécharger l'iso d'Ubuntu (version 22.04 personnellement) [ici](https://lecrabeinfo.net/installer-ubuntu-22-04-lts-en-dual-boot-avec-windows.html).
Installer Rufus et l'utiliser sur sa clé USB pour la rendre bootable (on pourra l'utiliser pour démarrer la machine).

##II: Partitionner le disque (méthode Windows 11 pour le dual boot uniquement)
Aller dans Gestion des disques, puis faire un clic droit sur le disque C: et choisir "Réduire le volume".
J'ai choisi de donner à la partition Ubuntu 25 000 Mo, soit 25Go.

##III: Lancer la machine via la clé

On branche la clé puis on redemarre l'ordinateur.
On doit ensuite rentrer dans le boot menu. Etant sous Lenovo, je reste appuyé sur la touche F12 lorsque le logo apparaît.
On chosis ensuite l'option 'Try or Install Ubuntu'

##IV: Configurer Ubuntu

Maintenant dans l'installeur Ubuntu, on est désormais moins obligé de suivre les instructions à la lettre sauf exeptions.
- On appuie sur Installer Ubuntu en choisissant la langue désirée
- On choisi le clavier désiré
- On choisi Installation normale ou minimale (normale étant fournie avec un certain nombre d'applications utiles)
- **IMPORTANT**: 
    - on choisi 'Installer ubuntu à côté de Windows Boot Manager' pour le dual boot
    - on choisi 'Effacer le disque et installer ubuntu' si on veux supprimer Windows et passer entièrement sous ubuntu
- On confirme par 2 fois
- Mettre ensuite son fuseau horaire et créer son compte

L'installation débute enfin.

Une fois chose faite, on redémmare la machine, puis on enlève la clé bootable quand demandé à l'écran et on appuie sur entrée

Ubuntu se lance et est fonctionnel, on n'a plus qu'à configurer Ubuntu de façon unique et personnelle.

