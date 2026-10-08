Customer Manager

A JavaFX-based customer management application built with JDK 21 and Gradle.
Requirements

    JDK 21

    Gradle

    JavaFX dependencies configured through Gradle

Verify your Java version:

java -version

It should report Java 21.
Running the Application

Clone the repository and navigate to the project directory:

cd CustomerManager

Run the application with:

gradle run

On Windows, if the Gradle wrapper is included, you can also use:

gradlew run

Project Structure

CustomerManager/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com.example.customermanager/
│   │   │       ├── Customer.java
│   │   │       └── MainApp.java
│   │   └── resources/
│   └── test/
├── build.gradle
├── gradle/
└── README.md

Technologies

    Java 21

    JavaFX

    Gradle

    FXML (if applicable)

Development

The project uses Gradle to manage dependencies and run the JavaFX application.

Build the project:

gradle build

Run the application:

gradle run

License

This project is for educational/development purposes.


