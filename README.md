# How to run this browser?

1. Clone this repo

2. cd into the root directory of this project

3. Run the following command

```sh

mvn clean javafx:run

```

![BrowserView](assets/BrowserView.jpg)


> [!NOTE]
> The sample code is an extract from a lecture given by Franco Roman Meola 
> @ITBA

# Requirements

- Maven installed.

    You can install it though you favourite package manager, in case you are
    on macOS, you can do:

    ```sh
    brew install maven
    ```

# Startup

- You need to run the following command

    ```sh
    mvn archetype:generate -DgroupId=com.usrName.projectName -DartifactId=proyectFullName -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
    ```

> [!NOTE]
> This command is completely configurable, you can look for the Maven
> documentation and modify flags as you wish to do it

# Adding dependencies and configuring project

All the configurations and dependencies will be on the `pom.xml` file
you can specify any dependency available on the jdk you would like to have on 
your project and they will be automatically installed

