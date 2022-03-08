########################################################################################
# Aufgabe 2:
#
# Erstellen Sie ein Dockerfile, welches Ubuntu als Quelle nutzt.
# Installieren Sie nginx mittels Paketmanager.
# Erstellen und starten Sie den docker container.
#
# Image bauen: docker build -t demo:nginx_apt .
# Image ausführen: docker run -p 8080:80 demo:nginx_apt
########################################################################################
FROM ubuntu:20.04

# Paketmanager aktualisieren und nginx installieren
########################################################################################
RUN apt update && apt install nginx -y

# Portfreigabe
# https://docs.docker.com/engine/reference/builder/#expose
########################################################################################
EXPOSE 80

# Startkommando mit Parametern
# https://docs.docker.com/engine/reference/builder/#cmd
########################################################################################
CMD ["nginx", "-g", "daemon off;"]