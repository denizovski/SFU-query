## Six Feet Under Sparql Query


### 1. Who are the cast member of the Six Feet Under Tv Series?

`SELECT ?castMember WHERE {
   <http://dbpedia.org/resource/Six_Feet_Under_(TV_series)> <http://dbpedia.org/ontology/starring> ?castMember
}`

[Run Query](https://dbpedia.org/sparql?default-graph-uri=http%3A%2F%2Fdbpedia.org&query=SELECT+%3FcastMember+WHERE+%7B%0D%0A+++%3Chttp%3A%2F%2Fdbpedia.org%2Fresource%2FSix_Feet_Under_%28TV_series%29%3E+%3Chttp%3A%2F%2Fdbpedia.org%2Fontology%2Fstarring%3E+%3FcastMember%0D%0A%7D&format=text%2Fhtml&CXML_redir_for_subjs=121&CXML_redir_for_hrefs=&timeout=30000&debug=on&run=+Run+Query+)


### 2. When is the release date of SFU?


`SELECT ?releaseDate WHERE { <http://dbpedia.org/resource/Six_Feet_Under_(TV_series)> <http://dbpedia.org/ontology/releaseDate> ?releaseDate }`

[Run Query](https://dbpedia.org/sparql?default-graph-uri=http%3A%2F%2Fdbpedia.org&query=SELECT+%3FreleaseDate+WHERE+%7B+%3Chttp%3A%2F%2Fdbpedia.org%2Fresource%2FSix_Feet_Under_%28TV_series%29%3E+%3Chttp%3A%2F%2Fdbpedia.org%2Fontology%2FreleaseDate%3E+%3FreleaseDate+%7D&format=text%2Fhtml&timeout=30000&signal_void=on&signal_unconnected=on)



### 3. Who is creator of Six Feet Under series?

`SELECT ?creator WHERE { <http://dbpedia.org/resource/Six_Feet_Under_(TV_series)> <http://dbpedia.org/ontology/creator> ?creator }`


[Run Query](https://dbpedia.org/sparql?default-graph-uri=http%3A%2F%2Fdbpedia.org&query=SELECT+%3Fcreator+WHERE+%7B+%3Chttp%3A%2F%2Fdbpedia.org%2Fresource%2FSix_Feet_Under_%28TV_series%29%3E+%3Chttp%3A%2F%2Fdbpedia.org%2Fontology%2Fcreator%3E+%3Fcreator+%7D&format=text%2Fhtml&timeout=30000&signal_void=on&signal_unconnected=on)



### 4.  What is genre of series?

`SELECT ?genre WHERE { <http://dbpedia.org/resource/Six_Feet_Under_(TV_series)> <http://dbpedia.org/ontology/genre> ?genre }`

[Run Query](https://dbpedia.org/sparql?default-graph-uri=http%3A%2F%2Fdbpedia.org&query=SELECT+%3Fgenre+WHERE+%7B+%3Chttp%3A%2F%2Fdbpedia.org%2Fresource%2FSix_Feet_Under_%28TV_series%29%3E+%3Chttp%3A%2F%2Fdbpedia.org%2Fontology%2Fgenre%3E+%3Fgenre+%7D&format=text%2Fhtml&timeout=30000&signal_void=on&signal_unconnected=on)

### 5. Who is composer of SFU series?

`SELECT ?composer WHERE { <http://dbpedia.org/resource/Six_Feet_Under_(TV_series)> <http://dbpedia.org/ontology/composer> ?composer }`

[Run Query](https://dbpedia.org/sparql?default-graph-uri=http%3A%2F%2Fdbpedia.org&query=SELECT+%3Fcomposer+WHERE+%7B+%3Chttp%3A%2F%2Fdbpedia.org%2Fresource%2FSix_Feet_Under_%28TV_series%29%3E+%3Chttp%3A%2F%2Fdbpedia.org%2Fontology%2Fcomposer%3E+%3Fcomposer+%7D&format=text%2Fhtml&timeout=30000&signal_void=on&signal_unconnected=on)

### 6.What other series starring Peter Crause, the lead actor of the series?

`SELECT ?otherSeries 
WHERE {
?otherSeries rdf:type dbo:TelevisionShow .
?otherSeries dbo:starring dbr:Peter_Krause .
}`

[Run Query](https://dbpedia.org/sparql?default-graph-uri=http%3A%2F%2Fdbpedia.org&query=SELECT+%3FotherSeries+%0D%0AWHERE+%7B%0D%0A%3FotherSeries+rdf%3Atype+dbo%3ATelevisionShow+.%0D%0A%3FotherSeries+dbo%3Astarring+dbr%3APeter_Krause+.%0D%0A%7D&format=text%2Fhtml&timeout=30000&signal_void=on&signal_unconnected=on)

### 7.
