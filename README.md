# mapserver-routing-webmapping
Mise en place d'un serveur mapserver avec calcul de routing 

## Prerequis




## Création d'une carte simple




mapserver_wms.map

Pour tester les bons paramètres:

localhost:8888/cgi-bin/mapserv?map=/Applications/MAMP/htdocs/zz-sysoco/mapserver-routing-webmapping/mapserver_wms.map&SERVICE=WMS&VERSION=1.1.1&REQUEST=GetMap&LAYERS=routes&STYLES=&SRS=EPSG:4326&BBOX=4.19,42.98,7.74,45.26&WIDTH=900&HEIGHT=900&FORMAT=image/png


Test de  la requet GetCapabilities:
localhost:8888/cgi-bin/mapserv?map=/Applications/MAMP/htdocs/zz-sysoco/mapserver-routing-webmapping/mapserver_wms.map&SERVICE=WMS&VERSION=1.1.1&REQUEST=GetCapabilities



## Envoi d'un flux WMS
mapserver_wms.1.map

test du flux wms
localhost:8888/cgi-bin/mapserv?map=/Applications/MAMP/htdocs/zz-sysoco/mapserver-routing-webmapping/mapserver_wms.1.map&layer=osm_local&mode=map