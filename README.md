## Création d'un nouveau projet à partir de notre archetype:


Etape 1:
  Importer l'archetype depuis git
Etape 2:
  Exécuter ces commandes:
    mvn install
    mvn install archetype:update-local-catalog
    mvn archetype:crawl
    
Etape 3:
mvn archetype:generate -DarchetypeGroupId=fr.norsys.sinaf -DarchetypeArtifactId=sinaf-archetype -DarchetypeVersion=1.0
