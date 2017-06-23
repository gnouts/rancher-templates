# Deal ERP

### Infos:

Ce template permet de démarrer 4 conteneurs comprenant Apache+PHP, Tomcat, Progress et un conteneur sources.

### Configuration:

- Indiquez le nom de votre instance. (Utilisez une notation explicite avec la version et le numéro client. Par exemple : v7-635)
- Sélectionnez le numéro de votre client
- Choisissez la version de PHP. (Sélectionnez 5.3 pour une version de l'ERP antérieur à la v6)

### Accès:

Les services sont accessibles aux adresses : 

${nom_du_service}.${nom_de_l_instance}.docker.deal:8181


Exemple: Si vous avez nommé votre instance 'v7-635', vous pourrez accéder aux services aux adresses suivantes

progress.v7-635.docker.deal:8181
tomcat.v7-635.docker.deal:8181
apache.v7-635.docker.deal:8181

