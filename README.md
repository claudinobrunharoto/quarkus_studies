# Quarkus
How to install quarkus on Windows


### STEP 1: Download and unzip to a known folder:

a. https://www.graalvm.org

b. https://maven.apache.org


### STEP 2: Environment Variables on Windows 11:

**Path: Settings > System > About > Advanced system settings > Environment Variables...**

**a.** JAVA_HOME: graalvm unziped folder from step 1.a

**b.** MAVEN_HOME: maven unziped folder from step 1.b

**c.** Add to Path:

   - %JAVA_HOME%\bin

   - %MAVEN_HOME%\bin

Open Windows Power Shell to check if everithing is working. Type:

> 1. java --version

> 2. mvn --version (it should recognize the Java version)


### STEP 3: Create project:

https://code.quarkus.io

Configure your application details:
![quarkus](https://github.com/claudinobrunharoto/quarkus/assets/58790242/afcfa47c-2bf2-43ad-ad3a-28d793e0b06e)

Download application "skeleton"

1. Unzip it to your <Project Folder>.

2. On Windows Power shell, navigate to your <Project Folder> and type the code:

> ./mvnw compile quarkus:dev

Open a browser and access your local host on port 8080

localhost:8080

## VS Code Extensions:

### 1. Java Extension Pack

This pack contains **Maven for Java** that can easily launch the application by clicking on:

Bellow VS Code Explorer > MAVEN > Plugins > quarkus > dev

### 2. Lombok Annotations Support for VS Code

Theme: Dracula Official (Soft)

Icons: Material Icon Theme
