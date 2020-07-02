# tutorial-microservices-archetype

<strong>Create Archetype from maven project </strong>
1. Install java <br>
> sudo apt install openjdk-11-jdk <br>
> java -version <br>
2. Install maven <br>
> sudo apt install maven <br>
> mvn -version <br>

create custom maven project name <striong>custom-archetype</strong> <br>

> cd custom-archetype <br>
> mvn archetype:create-from-project <br>
> cd target/generated-sources/archetype <br>
> mvn clean install

go to eclipse or any ide<br>
new maven project -> select archetype from default local if not exist -> add archetype -> provide groupID, artifactId and version and search
select custom archetype from local and give your project details and finish
