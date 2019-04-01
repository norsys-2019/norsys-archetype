## Creating a new project from the archetype:


### step 1 : 
Run the following commands:
  
    git clone https://github.com/norsys-2019/norsys-archetype.git
  
    cd norsys-archetype
  
    mvn install

### step 2 : 

Generate the project:

    mvn archetype:generate -DarchetypeGroupId=fr.norsys.sinaf -DarchetypeArtifactId=sinaf-archetype -DarchetypeVersion=1.0 -Dname=xxxx -Dport=xxxx



![Capture2](https://user-images.githubusercontent.com/48215221/55362256-5ad02800-54d1-11e9-8c06-5e3f63b31ede.PNG)
