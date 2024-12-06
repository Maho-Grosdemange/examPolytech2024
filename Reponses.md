> 16. Qu'est ce que Docker ? A quoi cela sert-il ?

Docker est une plateforme open-source permettant de créer et de déployer des conteneurs.
Un conteneur est une sorte de VM légère qui se base sur l'OS du système hôte (contrairement aux VM)
Les conteneurs embarquent tout ce dont ils ont besoin pour fonctionner.
C'est un outil qui s'est imposé dans l'industrie.

> 17. Qu'est ce que la CI et la CD ? Pourquoi est-ce utile ?

CI (Continuous Integration) et CD (Continuous Delivery/Deployment)
Ce sont des techniques de développement logiciel dont le but est d'automatiser et d'accélérer le cycle de mise en prod des applications.

Grâce aux techniques de CI/CD, une application peut être testée en continue (à chaque push) pour éliminer la majorité des bugs qui pourraient arriver en prod.

> 18. Qu'avez vous pensez du cours ?

Je n'avais jamais utilisé Docker. Je pense avoir appris de nouvelles compétences qui me seront utiles dans le futur.
Le cours était très prenant, j'ai beaucoup apprécié la mise en pratique instantanée du cours.

> 19. Surprenez moi

On peut jouer à Doom sur un conteneur Docker (bon c'est pas hyper étonnant étant donné que Doom tourne à peu près partout) :
https://gamerant.com/weirdest-consoles-you-can-play-doom-on/

```docker run --rm -it --shm-size=512m -p 6901:6901 -e VNC_PW=password kasmweb/doom:1.16.0```

Puis

```https://localhost:6901```

User : kasm_user

Password: password

(source : https://hub.docker.com/r/kasmweb/doom)


> 20. Pusher votre code sur github avec votre fichier de réponse aux questions et envoyer moi les urls de vos repos github.
