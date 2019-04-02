## Creating a new project from the archetype:


### step 1 : 
Run the following commands:
  
    git clone https://github.com/norsys-2019/norsys-archetype.git
  
    cd norsys-archetype
  
    mvn install

### step 2 : 

Generate the project:

    mvn archetype:generate -DarchetypeGroupId=fr.norsys.sinaf -DarchetypeArtifactId=sinaf-archetype -DarchetypeVersion=1.0 -Dport=xxxx



![cap](https://user-images.githubusercontent.com/48215221/55421954-717a8b80-5572-11e9-881b-e31cb4024e69.PNG)
