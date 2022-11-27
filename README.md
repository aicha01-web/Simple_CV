PREREQUIS
-Avoir docker engine, installez docker desktop:
    -Sur windows:https://docs.docker.com/desktop/install/windows-install/
    -Sur MAC: https://docs.docker.com/desktop/install/mac-install/
    -Sur Linux: https://docs.docker.com/desktop/install/linux-install/

OBJECTIFS
-Créer un cv en utilisant HTML et CSS

A FAIRE
1-Installez docker desktop
2-Clonez le projet: git clone https://github.com/aicha01-web/Simple_CV.git
3-Créer l'image à partir du dockerfile en utilisant cette commande: docker build -t "nom_image" .
4-Créer un conteneur à travers l'image que l'on a crée précédemment :
docker run -d --name "nom_conteneur" -p numero_port_externe:numero_port_interne "nom_image"
5-Il reste à tester !

AIDE
sokhnaaichasarr@gmail.com

