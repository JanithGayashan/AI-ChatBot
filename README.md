
# AI Chatbot Using MERN Stack

This repository contains an AI Chatbot application inspired by ChatGPT, built using the MERN stack and OpenAI's API. The chatbot stores each user's messages in a MongoDB database and allows for message retrieval and deletion. The application is designed with a focus on security and a smooth user experience.

## Features

- **Custom Chatbot**: Each user message is stored in a database and can be retrieved or deleted.
- **Security**: The application is secured using JWT Tokens, HTTP-Only Cookies, Signed Cookies, Password Encryption, and Middleware Chains.
- **MERN Stack**: Built with MongoDB, Express.js, React, and Node.js for a robust full-stack development experience.
- **Frontend Setup**: React + TypeScript + Vite for fast development, including support for Hot Module Replacement (HMR).

## Technologies Used

- **MongoDB**: NoSQL database to store messages and user data.
- **Express.js**: Web framework for handling backend routes and API requests.
- **React**: Frontend framework for building dynamic user interfaces.
- **Node.js**: Backend runtime environment to run the server.
- **OpenAI API**: Integration for AI-based responses.
- **JWT Tokens**: For secure user authentication.
- **Vite**: Next-generation build tool for fast development.

## Frontend Setup

This project uses React with TypeScript and is powered by Vite for fast development. It includes a minimal setup to integrate React and Vite, supporting Hot Module Replacement (HMR).

### Available Plugins

- **@vitejs/plugin-react**: Uses Babel for fast refresh and optimized React development.
- **@vitejs/plugin-react-swc**: Uses SWC for faster React development with Fast Refresh.

## ESLint Configuration

For production-quality code, expand the ESLint configuration to enable type-aware lint rules.

### ESLint Setup

```js
export default {
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}


2. Replace `plugin:@typescript-eslint/recommended` with `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`.
3. Optionally, add `plugin:@typescript-eslint/stylistic-type-checked`.
4. Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list.

---
