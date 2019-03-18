## Annexe A: Docker
####Voici quelques commandes utiles pour utiliser docker et docker-compose.

## Créer une image avec le répertoire courant
`docker build . `

## Lister les images
`docker images`

## Lancer un container
`docker run -d IMAGE`

## Lister les containers actifs
`docker ps`

## Se connecter à un container actif
`docker run -it CONTAINER /bin/sh`

## Clean et build un stack
`docker-compose build --no-cache`

## Lancer un stack
`docker-compose up`


#### Annexe B: Photon OS

## Trouver l’adresse IP de la VM
`ifconfig eth0 | grep "inet addr" | cut -c 21-34`

