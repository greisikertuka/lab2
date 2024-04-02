First step is to create a folder locally, let's say it is lab2.
Then we execute the command:

mvn archetype:generate -DgroupId=com.fti.app -DartifactId=lab2 -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false

Then we can go to this directory:
 cd lab2
And we will see the structure with the pom.xml included for dependencies.

To push it to git we use these commands: 

Initialize:
git init

Add all files:
git add -A

set up the project in git:
git remote add origin git@github.com:greisikertuka/lab2-java.git (this is the repo on git)

Commit all files with a message:
git commit -m 'First Commit'

Push all files:
git push -u -f origin master

To get the project locally, we need to use this command:
git clone https://github.com/greisikertuka/lab2-java.git
