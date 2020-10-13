# TP-2
***

- Le but est de lancer 4 containers avec comme image `dockercloud/hello-world` et un container avec `dockercloud/haproxy` pour faire du loadbalancing.
- La particularité des containers `dockercloud/hello-world` c'est qu'il affiche leurs le nom sur le port 80. Grace à cela si notre loadbalancing fonctionne bien, à chaque refresh de la page le nom du container devrait changer.

1. Taper la commande: docker-compose up -d
2. Taper la commande: docker-compose scale my_container=4
3. Aller sur l'adresse suivante: `127.0.0.1:8080`
