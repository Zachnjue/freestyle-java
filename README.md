# freestyle-java
Deploying a java app to Jenkins

Steps:
1. Git clone the repo to the local workspace. Create a Java file and push the changes to the remote repo.

Configure Jenkins:
2. By creating a New item, name the Job, and select freestyle job and click Ok. 

Configure SCM
Select git and insert the git url. 

Run Java file
3. Go to Build section, select Execution Shell and enter the following code
javac HelloWorld.java
java HelloWorld
