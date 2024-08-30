# Project Setup and Execution Guide

## Prerequisites

To run this project, ensure you have the following installed:
- Java Development Kit (JDK)
- Node.js and npm (Node Package Manager)

## Configuration

1. **Create a `dev.properties` File:**
   - At the root of the project, create a file named `dev.properties`.
   - Add the following configuration details to the file:

     ```properties
     BASE_URI=http://localhost:3000/
     JWTSecret=????
     DB_URL=????
     DB_USER=????
     DB_PASSWORD=????
     ```

   Replace the `????` with the appropriate values for your setup.

## Running the Project

2. **Run the Main Java File:**
   - Navigate to the main Java file located at `src/main/java/be/vinci/pae/main/Main.java`.
   - Run the file to start the backend server.

3. **Setting Up the Frontend:**
   - Navigate to the `webapp` directory.
   - Install the necessary dependencies by running:
     ```bash
     npm install
     ```
   - Start the frontend application by running:
     ```bash
     npm start
     ```

## Notes

- Make sure your database and backend server are properly configured and running before starting the frontend application.
- The default base URI for the project is set to `http://localhost:3000/`, but this can be adjusted in the `dev.properties` file as needed.

If you encounter any issues, please ensure that all environment variables are correctly set up in the `dev.properties` file and that all dependencies are installed properly.
