# Résumé de la vidéo "How does the internet works in 5 mins" 

## Présentation de la vidéo 
![Screenshot vidéo](/BECODE-TRAINING-Gwendoline-Jacobs/refs/video.png)
La vidéo a été créée par **Aaron Titus** pour [Security Catalyst](https://securitycatalyst.com/) en *février 2019*.
Le lien de la vidéo est disponible [ici](https://www.youtube.com/watch?v=7_LPdttKXPc).

## Comment fonctionne internet ?
>Maintenant, nous sommes tous connectés par internet, comme des neurones dans un cerveau géant.
>*Stephen Hawking*

![Point d'interrogation nuage](https://meiklesinvestor.com/wp-content/plugins/use-your-drive/css/clouds/cloud_status_256.png)
Contrairement à l'idée préconcue avec la sortie des technologies cloud actuelle, internet **ne ressemble pas** à une bulle de cloud. C'est d'avantage un câble :electric_plug: enterré sous le sol !
Qu'il s'agisse de **fibre optique**, de **cuivre** ou d'**un rayon satellite** émis par le téléphone portable.

### Serveurs
Les machines directement connectées à internet s'appellent des **serveurs**, il en existe des milliers. Ca ressemble à ceci :

![serveurs image](https://bi.fr/wp-content/uploads/2020/12/serveur-1.jpg)

On pourrait voir les serveurs comme des ordis spéciaux connectés directement à internet. 
Les serveurs ont plusieurs caractéristiques :
1. **Une adresse IP unique** à laquelle on donne des noms pour plus de facilités
2. Des éléments connectés au **disque dur**, comme des :
    - Fichiers
    - Pages Web
3. Comme déjà mentionné, ils sont **directement** connectés à internet. 

### Les PC (Personnal Computer)
![Ordinateur personnel](https://static.javatpoint.com/computer/images/pc.jpg)
Contrairement aux serveurs, les PC sont **indirectement** connectés à internet. Ils ont besoin d'un **ISP** (*Internet Service Provider*). 
Voici un exemple de chemin qui pourrait être fait lorsque vous envoyez un mail :
Client -> ISP -> Gmail serveur -> ISP -> Client2

### Paquets
Les données sont envoyées sous forme de **paquets** c'est à dire des données fragmentées de votre message initial et qui sont réassemblées à l'arrivée. Pour que les paquets sachent sur quel PC ils sont sensés arriver, ils transportent les **adresses IP** du PC duquel ils sont envoyés auquelles s'ajoutent les adresses IP de **tous les routeurs** par lesquels ils passent. Quand ils reviennent, ils font l'inverse c'est à dire qu'ils **perdent une couche d'IP des routeurs par lesquels ils passent**. Un peu comme un bonbon qu'on emballerait et qu'on désemballerait ! 
![pile de bonbons](https://media.giphy.com/media/Jsi0pCShyVEo2xOjtJ/giphy.gif)

## About
Cette vidéo a été résumée par [Gwendoline Jacobs](https://github.com). 
Pour revenir au README, cliquez [ici](/BECODE-TRAINING-Gwendoline-Jacobs/README.md)

this theory file has been reviewed by Audrius Grebliunas :sunglasses:
