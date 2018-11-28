## Opdracht

Geen tutorial begint zonder een fatsoenlijke `Hello World` dus ook wij gaan dit doen. 

We beginnen maximaal eenvoudig en gaan de laatste stabiele `debian` container van `DockerHub` starten die `Hello Whale` zegt. 

Hiervoor gebruiken we het `docker run` command (of `docker container run` volluit) gevolgd door de naam van het `image` wat we willen starten; `debian:latest`. 

*Later volgt meer over informatie over image tags zoals `debian:latest`, `debian:9` of `debian:stretch`*

Daarna volgt een set argumenten die we door de container (in de container) willen laten uitvoeren; `echo "Hello Whale"`.

De container start in de `foreground` (voorgrond) en is dus gekoppeld aan onze eigen terminal, alle output (`STDOUT` en `STDERR`) van de container komt dus ook daar terecht. 

`docker container run debian:latest echo "Hello Whale"`{{execute}}
