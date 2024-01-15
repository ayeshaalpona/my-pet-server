# RunMeQuick

RunMeQuick is a simple web application that allows users to execute code snippets in various programming languages. The application supports JavaScript, Python, Go, C++, and PHP.

## Features
- **Code Execution:** Execute code snippets in different programming languages.
- **Language Support:** Currently supports JavaScript, Python, Go, C++, and PHP.
- **Execution History:** View a history of code executions, including the result and timestamp.

## Technologies Used
- **Backend:** Node.js with Express
- **Database:** MongoDB
  
## Getting Started
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/riaz9191/runmequick_server

2. **Navigate to the project directory:**

   ```bash
   cd runmequick_server

3. **Install dependencies:**

   ```bash
   npm install

4. **Set Environment Variables::**
  - Create a .env file in the root directory and add the following variables:
    ```bash
    DB_USER=your_database_user
    DB_PASSWORD=your_database_password
    PORT=5000

5. **Start the development server:**

    ```bash
    npm start

6. **Run the Application::**

    ```bash
    http://localhost:5000

**Usage**
1. **Execute Code:**
- Use the /api/execute endpoint with a POST request, providing the code, runtime, and user email in the request body.
2. **View Execution History:**
- Access the /api/execute endpoint with a GET request, optionally providing a user email as a query parameter to filter by user.

**Contributions Welcome**
We welcome contributions! Feel free to fork the repository and submit pull requests.

**License**
This project is licensed under the MIT License.

<p align="center">
  <a href="https://github.com/riaz9191/gitformed_server" target="_blank">
    <img src="https://img.shields.io/badge/View%20on%20GitHub-%23000000.svg?style=for-the-badge&logo=github" alt="View on GitHub">
  </a>
</p>
