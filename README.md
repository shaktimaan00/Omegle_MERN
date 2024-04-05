# Omegle_MERN

## Introduction

This readme provides an overview of the MERN (Express.js, Next.js, Node.js) stack project and its components.

## Project Overview

The MERN stack project is a full-stack web development project that leverages the following technologies:

- **Express.js**: A backend framework for building web applications and APIs using Node.js.
- **Next.js**: A JavaScript library for building user interfaces.
- **Node.js**: A JavaScript runtime environment that executes Backend-side code.

## Project Structure

The project directory structure typically includes the following components:

- **Client**: Contains the front-end code written in Next.js.
- **Backend**: Contains the back-end code written in Node.js using Express.js.

```
mern-stack-project/
  |- Frontend/
  |  |- public/
  |  |- src/
  |  |- app/
  |  |  |- components/
  |  |  |- App.js
  |  |  |- index.js
  |- Backend/
  |  |- controllers/
  |  |- models/
  |  |- routes/
  |  |- app.js
  |  |- server.js
  |- README.md
```

## Getting Started

To run the MERN stack project locally, follow these steps:

1. **Clone the Repository**: Clone the project repository to your local machine.
   ```bash
   https://github.com/shaktimaan00/Omegle_MERN.git
   ```
2. **Install Dependencies**: Navigate to the project directory and install dependencies for both the Frontend and Backend.
   ```bash
   cd mern-stack-project
   cd frontend
   npm install
   cd ..
   cd backend
   npm install
   ```
3. **Start the Development Backend**: Run the development Backend for both the Frontend and Backend.
   ```bash
   cd frontend
   npm run dev
   ```
   ```bash
   cd backend
   npm run dev
   ```
4. **Access the Application**: Access the application in your web browser at `http://localhost:3000`.

## Contributing

Contributions to the project are welcome! If you find any bugs or have suggestions for improvement, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
