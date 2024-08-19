# E-Commerce Store Setup Guide

Welcome to the E-Commerce Store project! This guide will help you set up the project by walking you through the necessary steps to download, extract, and run the frontend, backend, and admin sections.

## Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js**: Download and install from [Node.js official website](https://nodejs.org/).
- **Visual Studio Code (VS Code)**: Download and install from [VS Code official website](https://code.visualstudio.com/).

## Setup Instructions

### 1. Download and Extract Files

1. **Download** the `frontend`, `backend`, and `admin` zip files.
2. **Extract** each zip file into a single folder. The folder structure should look like this:

e-commerce-store/
├── frontend/
├── backend/
└── admin/


### 2. Open the Project in VS Code

1. Open **Visual Studio Code**.
2. Go to **File** > **Open Folder** and select the `e-commerce-store` folder you just created.

### 3. Setting Up the Backend

1. In VS Code, navigate to the `backend` folder.
2. Open the **Integrated Terminal** by right-clicking the `backend` folder in the file explorer and selecting `Open in Integrated Terminal`.
3. Run the following commands to install the necessary dependencies and start the backend server:

    ```bash
    npm install
    node index.js
    ```

### 4. Setting Up the Frontend

1. In VS Code, navigate to the `frontend` folder.
2. Open the **Integrated Terminal** by right-clicking the `frontend` folder and selecting `Open in Integrated Terminal`.
3. Run the following commands to install the dependencies and start the frontend development server:

    ```bash
    npm install
    npm start
    ```

### 5. Setting Up the Admin Panel

1. In VS Code, navigate to the `admin` folder.
2. Open the **Integrated Terminal** by right-clicking the `admin` folder and selecting `Open in Integrated Terminal`.
3. Run the following commands to install the dependencies and start the admin panel:

    ```bash
    npm install
    npm start
    ```

## Summary

After completing the above steps, your e-commerce store should be up and running with the following:

- **Backend**: Running on the specified port (check your `index.js` for details).
- **Frontend**: Accessible via your local machine at `http://localhost:4000`.
- **Admin Panel**: Accessible via your local machine at the specified port (check your setup for details).

Happy coding! If you encounter any issues, feel free to consult the documentation or reach out for support.
