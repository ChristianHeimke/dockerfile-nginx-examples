# dockerfile examples

## About

Eine Übersicht über die möglichen Schritte um nginx in einem Container zu installieren:

* direkt als feriges Image
* Installation über den Paketmanager
* Installation mittels Source Code
* Installation mittels Source Code im Multistage-Verfahren

## docker hub

Die Images können in folgendem Repository gefunden werden:
https://hub.docker.com/repository/docker/christianheimke/nginx

## Vergleich

Vergleich der Image-Größe je nach Bauart:

| **Variante**                | **Image Größe** |
|-----------------------------|-----------------|
| nginx image                 | 10MB            |
| Paketmanager                | 74MB            |
| Source Code                 | 187MB           |
| Soruce Code mit Mutli-Stage | 58MB            |