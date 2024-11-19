# Getting Started with the Java Dashboard Builder

Welcome to the Java Dashboard Builder! This repository is a collection of applications to help you get started with building and testing dashboards using the Java server application, alongside client applications built with HTML, Angular, and React.

## Prerequisites

- **Java Development Kit (JDK) 17+**
- **Node.js** (for Angular and React Clients)
- **Maven Wrapper** (comes with the Java Server)

## Getting Started

### Step 1: Running the Java Server
The Java Server is the backend that powers the dashboard applications.

1. **Download the server ZIP** from the repository.
2. **Unzip the file** to a desired directory.
3. Open a terminal, navigate to the unzipped directory, and run the following command:
   ```bash
   ./mvnw spring-boot:run
   ```
   *For Windows users:*  
   ```bash
   mvnw.cmd spring-boot:run
   ```

4. Once started, the server will be running at `http://localhost:5111`.

### Step 2: Using a Client Application
You can use one of the provided client applications to interact with the server.

#### HTML Client
1. Navigate to the **Html-Client** repository.
2. Clone the repository or download the source files.
3. Open the `index.html` file in any browser to interact with the Java Server.

#### Angular Client
1. Navigate to the **Angular-Client** repository.
2. Clone the repository.
3. Run the following commands:
   ```bash
   npm install
   ng serve
   ```
4. Open your browser and go to `http://localhost:4200`.

#### React Client
1. Navigate to the **React-Client** repository.
2. Clone the repository.
3. Run the following commands:
   ```bash
   npm install
   npm start
   ```
4. Open your browser and go to `http://localhost:3000`.

## Popular Repositories

| Repository | Language/Framework | Description |
|------------|--------------------|-------------|
| [Java-Server](./Java-Server) | Java | The backend server application |
| [Html-Client](./Html-Client) | HTML | A basic HTML client to test the server |
| [Angular-Client](./Angular-Client) | TypeScript | Angular-based client application |
| [React-Client](./React-Client) | TypeScript | React-based client application |

## Support
If you encounter any issues, feel free to open an issue in the corresponding repository.
