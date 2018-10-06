# backend
Add static check for java maven project   

#### Checkstyle
we have to define the checkstyle.xml file and include it in the same path as pom.xml
#### Spotbugs
Spotbugs is a upgrade version of findbugs, with this plugin can scan the code bug before we move the code to production.
#### Code Coverage
Unit test is necessary for all the project, enough unit test case coverage can improve code quality
  
Note: if execute with -Dmaven.test.skip=true, then code coverage may not work as Jacoco is not downloaded.

#### Integration with Git
If we want to ensure all the git commit do such static check, we can add script in the git pre-commit, to ensure each time git commit will do the check.  
Just refer to pre-commit script for example and copy it to the .git folder for the project.

