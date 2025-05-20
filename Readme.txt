-Telecharger ELK-8.11.3 :

Elasticsearch:
https://www.elastic.co/downloads/past-releases/elasticsearch-8-11-3
Logstash:
https://www.elastic.co/downloads/past-releases/logstash-8-11-3
Kibana:
https://www.elastic.co/downloads/past-releases/kibana-8-11-3

-Créez un dossier nommé 'Elk', puis extrayez-y les fichiers déjà installés.

-Suivez la vidéo 'Elk_configuration.mp4' pour la configuration.

*Ouvrir PowerShell Puis suivez ces commandes:

-elasticsearch

cd c:/elk/elasticsearch-8.11.3/bin
./elasticsearch.bat

-kibana

cd c:/elk/kibana-8.11.3/bin
./kibana.bat

-logstash
#creat file logstash.conf in config file
#then 
cd C:\elk\logstash-8.11.3\bin
./logstash -f C:\elk-2\logstash-8.11.3\config\Log.conf