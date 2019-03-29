## Création d'un nouveau projet à partir de notre archetype:


Etape 1:

  Importer l'archetype depuis git avec les commandes suivantes:
  
  git clone https://github.com/norsys-2019/norsys-archetype.git
  
  cd norsys-archetype
  
  git checkout Feature/initialize project 
  
Etape 2:

 Dans le dossier norsys-archtype,on exécute les commandes suivantes:
  
    mvn install

Etape 3:

Dans le dossier où on veux créer notre projet,on execute la commande:

mvn archetype:generate -DarchetypeGroupId=fr.norsys.sinaf -DarchetypeArtifactId=sinaf-archetype -DarchetypeVersion=1.0 -Dname=xxxx -Dport=xxxx

Dans la console,on doit spécifier les propriétés comme suit:

![tableauparam](https://user-images.githubusercontent.com/48215221/55246525-aec6dc80-5245-11e9-91ee-83a500ea16d9.PNG)
