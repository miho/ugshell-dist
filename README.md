# ugshell-dist

[ ![Download](https://api.bintray.com/packages/miho/UG/ugshell-dist/images/download.svg) ](https://bintray.com/miho/UG/ugshell-dist/_latestVersion)

Bintray distribution infrastructure for ug4

## How to Build ugshell-dist

### Requirements

- Java >= 1.8
- Internet connection (dependencies are downloaded automatically)
- IDE: [Gradle](http://www.gradle.org/) Plugin (not necessary for command line usage)
- local ugshell executable and lua scripts that shall be added to the distribution

### IDE

Open the `ugshell-dist` [Gradle](http://www.gradle.org/) project in your favourite IDE (tested with NetBeans 8.2) and build it
by calling the `assemble` task.

### Command Line

Navigate to the [Gradle](http://www.gradle.org/) project (e.g., `path/to/ugshell-dist`) and enter the following command

#### Bash (Linux/OS X/Cygwin/other Unix-like shell)

    sh gradlew assemble
    
#### Windows (CMD)

    gradlew assemble
    
    
