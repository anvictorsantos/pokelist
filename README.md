# Pokelist

## Overview

This project is a Pokémon List application built with Vue 2, ESLint for code linting, JavaScript (JS) for logic, and Docker for containerized deployment.

## Structure Overview

The project structure is organized as follows:

- **`/src`**: The main source code directory.

  - **`/assets`**: Contains static assets like images, fonts, and other resources.
  - **`/components`**: Houses Vue components used in the application.
  - **`/constants`**: Defines constants used across the project.
  - **`/services`**: Includes services for handling data or external APIs.
  - **`/utils`**: Houses utility functions and helper scripts.
  - **`App.vue`**: The root Vue component.
  - **`main.js`**: The entry point for the application.

- **`/public`**: Contains public assets and the `index.html` file.
- **`/tests`**: Holds unit and integration tests.
- **`.eslintrc.js`**: ESLint configuration for code linting.
- **`Dockerfile`**: Configuration for building the Docker image.
- **`docker-compose.yml`**: Docker Compose configuration for container orchestration.
- **`README.md`**: Project documentation.

## Usage

To run the Monster Slayer game, follow these steps:

1. Clone this repository to your local machine.
2. Ensure you have Vue 2 and npm/yarn installed.
3. Navigate to the project directory in your terminal.
4. Run the following command to install dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

### Development

- Start the development server:
  ```
  npm run serve
  # OR
  yarn serve
  ```
- Open your browser and visit http://localhost:8080 to see the application in action.

### Docker Usage

1. Build the Docker image and run the Docker container with `docker-compose up`.
2. Access the application in your browser at `http://localhost:8080`.

## Technologies Used

- **Frontend**:

  - Vue 2
  - JavaScript
  - ESLint (Code Linting)

- **Devops**:

  - Docker

## Features

- View a list of Pokémon with details.
- Utilize an intuitive and responsive user interface.
- Code linting with ESLint for maintainable code.
- Dockerized for containerized deployment.

### Contributing

If you'd like to contribute to this project or have suggestions for improvement, please feel free to open issues or submit pull requests.

### License

This project is licensed under the MIT License - see the [LICENSE](https://chat.openai.com/c/LICENSE) file for details.

### Acknowledgments

This project is designed to demonstrate proficiency in building a full-stack web application with Vue 2 and Docker, emphasizing clean code and modern development practices.

Happy coding!
