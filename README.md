# Atlier_Grafana_2026

Je souhaite pour mes étudiants :

Qu'ils fassent un fork de ce Reposiroty

Qu'ils ouvrent un Codepace

Qu'ils lancent 3 dockers

docker run -p 80:80 -d quay.io/ocp-edge-qe/httpd  
docker run -p 81:80 -d quay.io/ocp-edge-qe/httpd 
docker run -p 82:80 -d quay.io/ocp-edge-qe/httpd

Ils installent un collecteur pour superviser ces Dockers (cadvisor ? via un Docker)

Ils installent prometheus via docker, ne pas oublier de leur expliquer le fichier prometheus.yml

ils installent Grafana

Connecte la source prometheus dans Grafana

Charge le numéro de modèle pour voir la santé de leurs dockers
