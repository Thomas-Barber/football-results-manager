# Football Results Manager

This was an assessed piece of work during the first semester of my first year at university. I have since re-written the program to be simpler while maintaining its previous level of functionality.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

To use Football Results Manager you must have Java JDK installed (found at: http://www.oracle.com/technetwork/java/javase/downloads/index.html) and a basic knowledge of either Windows Command Prompt or Linux Terminal, depending on the platform you are using.

To install Java JDK download the SDK from Oracle's downloads page. Once downloaded, run the program and go through the setup wizard. Remember where the JDK is saved if you want to recompile later.

### Installing
Assuming you have downloaded the project to C:\Users\[TomBabz]\Documents\GitHub where [TomBabz] is your own username:

Open Command Prompt and type "cd Documents\GitHub":
```
C:\Users\TomBabz> cd Documents\GitHub
```
Next type "cd football-results-manager":
```
C:\Users\TomBabz\Documents\GitHub> cd football-results-manager
```
Next type "cd Java Assignment":
```
C:\Users\TomBabz\Documents\GitHubs\football-results-manager> cd Java Assignment
```
Next type "cd src":
```
C:\Users\TomBabz\Documents\GitHubs\football-results-manager\Java Assignment> cd src
```
Next type "java Main":
```
C:\Users\TomBabz\Documents\GitHubs\football-results-manager\Java Assignment\> Java Main
```
You should now be greeted with the welcome screen for the Football Results Manager:
```
Welcome to Football Results Manager.
Reading from file...
The available options are the following...

stop         |  Ends the program.
help         |  Prints help text for the user.
options      |  Prints out the options that are available.
report       |  Will ask the user for team report or league report.
league       |  Produce a HTML file containing a report on the league.
team         |  Produce a HTML file containing a report on a specific team.
file         |  Will read game data from a file.
league table |  Produce a HTML file containing a league table.

Please enter a Games results.
_
```

If you want to compile the project then:

Open Command Prompt and type "cd Documents\GitHub":
```
C:\Users\TomBabz> cd Documents\GitHub
```
Next type "cd football-results-manager":
```
C:\Users\TomBabz\Documents\GitHub> cd football-results-manager
```
Next type "cd Java Assignment":
```
C:\Users\TomBabz\Documents\GitHubs\football-results-manager> cd Java Assignment
```
Next type "cd src":
```
C:\Users\TomBabz\Documents\GitHubs\football-results-manager\Java Assignment> cd src
```
check that the java files are present with "dir". You should see .java files.
```
C:\Users\TomBabz\Documents\GitHubs\football-results-manager\Java Assignment> dir
```
Next tell the system where your JDK programs are located with "set path=%path%;C:\Program Files\Java\[your JDK version]\bin
```
C:\Users\TomBabz\Documents\GitHubs\football-results-manager\Java Assignment> set path=%path%;C:\Program Files\Java\jdk1.8.0_172\bin
```
Next compile the programs with javac
```
C:\Users\Tom\Documents\GitHub\football-results-manager\Java Assignment\src> javac FootballResultsManager.java Input.java Main.java Team.java Validation.java
```
If all has gone well then you should have .java and .class files in the directory. Check with "dir":
```
C:\Users\Tom\Documents\GitHub\football-results-manager\Java Assignment\src> dir
```
Next type "java Main":
```
C:\Users\TomBabz\Documents\GitHubs\football-results-manager\Java Assignment\> Java Main
```
You should now be greeted with the welcome screen for the Football Results Manager:
```
Welcome to Football Results Manager.
Reading from file...
The available options are the following...

stop         |  Ends the program.
help         |  Prints help text for the user.
options      |  Prints out the options that are available.
report       |  Will ask the user for team report or league report.
league       |  Produce a HTML file containing a report on the league.
team         |  Produce a HTML file containing a report on a specific team.
file         |  Will read game data from a file.
league table |  Produce a HTML file containing a league table.

Please enter a Games results.
_
```

## Running the tests

//TODO: Implement tests

## Deployment

Deployment was not apart of the assessment for this program and furthermore the program does not have much practical use. It was intended for assessment purposes only.

## Authors

* **Thomas Barber**

## License

This project is unlicensed

## Acknowledgements

* Leeds Beckett University
* Stack Overflow
