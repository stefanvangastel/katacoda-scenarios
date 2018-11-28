## Opdracht (EXTRA)

Als je extra tijd hebt kun je dit nog eens proberen;

Om de versie van een Linux distributie te achterhalen kun je (onder andere) het volgende commando uitvoeren: `cat /etc/*-release`

Voer dit eens uit **in de terminal**: 

`cat /etc/*-release`{{execute}}

En voer dit eens uit **in de debian:latest container**: 

`docker container run debian:latest cat /etc/*-release`{{execute}}

Je hebt dus binnen miliseconden een compleet andere Linux (of Windows (beta)) omgeving ter beschikking...
