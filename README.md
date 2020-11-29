# TextAdventureJava

## Pre requisites
Before cloning and running this program you will need the following software:

* Java 11+
* Maven 3.5+

### On Mac
    
    # install homebrew
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    
    # install tools
    brew install git
    brew install openjdk@11    
    brew install maven@3.5
    
    # confirm tools are installed correctly
    git version
    java --version
    mvn --version
    
### On Windows

    ???

## Playing the Game From Source

    git clone https://github.com/alarson892/TextAdventureJava.git
    cd TextAdventureJava
    
    # Option 1 - with Maven
    mvn clean compile exec:java
    
    # Option 2 - with JVM
    mvn clean package
    java -classpath target/text-adventure*.jar com.alarson.text.App
   