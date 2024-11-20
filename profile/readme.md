# Welcome to the Java Dashboard Builder Organization 👋

This organization provides everything you need to get started with building and testing dashboards using our **Java Server** and multiple client applications. Follow these steps to quickly set up and explore the tools.

---

## 🚀 Quick Start Guide

### Step 1: Run the Java Server

The **Java Server** is the backend that powers the dashboard system. Follow these steps to get it up and running:

1. **Download the ZIP file** from the [Java-Server](./Java-Server) repository.
2. **Unzip the file** into your desired directory.
3. Open a terminal, navigate to the unzipped directory, and run the following command:
   ```bash
   ./mvnw spring-boot:run
   ```
   *For Windows users:*  
   ```bash
   mvnw.cmd spring-boot:run
   ```

4. The server will start at `http://localhost:5111`.

---

### Step 2: Test the Server with a Client Application

Once the server is running, you can test it using one of the client applications available in the organization.

#### **HTML Client**
- Navigate to the [Html-Client](./Html-Client) repository.
- Download the source files or clone the repository.
- Open `index.html` in any browser to interact with the server.

#### **Angular Client**
- Navigate to the [Angular-Client](./Angular-Client) repository.
- Clone the repository.
- Install dependencies and start the development server:
   ```bash
   npm install
   ng serve
   ```
- Open your browser and visit `http://localhost:4200`.

#### **React Client**
- Navigate to the [React-Client](./React-Client) repository.
- Clone the repository.
- Install dependencies and start the application:
   ```bash
   npm install
   npm start
   ```
- Open your browser and visit `http://localhost:3000`.

---

## 📂 Repositories in This Organization

Here’s a quick overview of the repositories to help you get started:

| Repository | Description | Language/Framework |
|------------|-------------|---------------------|
| [Java-Server](./Java-Server) | Backend server application | Java |
| [Html-Client](./Html-Client) | Basic HTML client for testing the server | HTML |
| [Angular-Client](./Angular-Client) | Angular-based client application | TypeScript |
| [React-Client](./React-Client) | React-based client application | TypeScript |
| [Visualization-Images](./Visualization-Images) | Visualization assets | N/A |

---

## 💡 Need Help?

If you encounter any issues or have questions, feel free to open an issue in the relevant repository or reach out to us. We're here to help!
