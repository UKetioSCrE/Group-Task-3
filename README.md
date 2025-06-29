# Task 3: Docker – Running a Java Program in a Container

## Overview  
This project demonstrates how to use Docker to containerize and run a simple Java program. It includes a Java class that prints a message, a Dockerfile to build the container image, and instructions to build and run the Docker container.

## Files  
- HelloWorld.java – Simple Java program that prints a message  
- Dockerfile – Instructions for building the Docker image  
- Main.class – Compiled Java class generated after building the project   

## Team Members and Responsibilities
Project Management: Wania Tajammal

Coders: Jonathan, Mitali

Support and review members: Raiyan, Madhuri Kola, Ayaan

## Expected Output  
Hello, Docker and Java!

## How We Used Docker  
In this task, we used Docker to containerize and run our Java program. A Docker container provides a lightweight and consistent environment that ensures the application runs the same regardless of the host system.

We created a Dockerfile that specifies how the image should be built: it uses an OpenJDK base image, copies the compiled Java files into the container, and defines the command to run the program. After building the image using the `docker build` command, we executed it with `docker run`.

Using Docker made the setup simple and portable. It allowed us to run the Java program without needing to configure Java manually on different machines. All dependencies were packaged within the container, making the program easy to test, deploy, and share across systems.

