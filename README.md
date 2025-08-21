# Java Quiz Application

A simple quiz application built in Java to practice creating graphical user interfaces using Swing and AWT.

## Features

- 10 multiple-choice questions on various topics.
- Each question has a time limit of 15 seconds.
- Questions are skipped if not answered within the time limit.
- Immediate feedback on correct and incorrect answers.
- Basic graphical interface using Swing and AWT.

## Getting Started

Follow these steps to run the quiz application on your local machine:

1. Navigate to the project directory: `cd Quiz-Application/Quiz-Application-Using-Java`
2. Compile the Java files: `javac -d build -cp src src\quiz\application\*.java`
3. Run the application: `java -cp "build;src" quiz.application.Login`
4. Answer the questions within the 15-second time limit.



## Project Structure

```
Quiz-Application/
├── Quiz-Application-Using-Java/
│   ├── src/
│   │   ├── icons/
│   │   │   ├── login.jpeg
│   │   │   ├── quiz.jpg
│   │   │   └── score.png
│   │   └── quiz/application/
│   │       ├── Login.java      # Main entry point
│   │       ├── Quiz.java       # Quiz logic and questions
│   │       ├── Rules.java      # Rules display
│   │       └── Score.java      # Score display
│   ├── build/                  # Compiled Java classes
│   ├── screenshots/            # Application screenshots
│   └── build.xml               # Build configuration
```

## Requirements

- Java 8 or higher
- Java Development Kit (JDK)

## How to Run

1. **Compile the application:**
   ```bash
   javac -d build -cp src src\quiz\application\*.java
   ```

2. **Run the application:**
   ```bash
   java -cp "build;src" quiz.application.Login
   ```


## About

This is a Java-based quiz application that demonstrates GUI development using Swing and AWT. It's perfect for learning Java programming concepts and building interactive applications.
