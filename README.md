# Hello Docker and Java

This is a simple project that shows how to run a Java program using Docker.

## Steps

1. Write a Java program that prints a message.
2. Compile the Java file to create a `.class` file.
3. Create a Dockerfile that uses a Java image.
4. Copy the compiled `.class` file into the Docker image.
5. Set the command in Docker to run the Java program.
6. Build the Docker image using the terminal.
7. Run the image as a container to see the output.

## What Docker Did

-Docker created an image that included the compiled code
-The image was turned into a container that ran the program
-It printed the output as if it was running on any computer


## Notes

- Make sure the Dockerfile uses the correct path to your compiled class file.
- Use the correct Java version in Docker to match your compiled file (Switching the ProjectSDK to SDK 23 fixed error).
- Build and run using the terminal with `docker build` and `docker run`, where docker runs the containerized project.
