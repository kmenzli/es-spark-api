# How to use it 
0) Install an ES instance then run it 
1) From the root level of the project run the following CLI 
---> curl -XPUT 'http://localhost:9200/music/lyrics/1" -d @data_1.json 
---> curl -XPUT 'http://localhost:9200/music/lyrics/2" -d @data_2.json 
2) Open your browser and use http://localhost:4567/

# Note
* Port 4567 is used by spark server
* Port 9300 is the tcp listen port used by ES
* I advise you to install ESS Head Plugin to track your index by UI
# Troubleshooting
To test this sample please avoid to use «cluster.name» in your /config/elasticsearch.yml file
