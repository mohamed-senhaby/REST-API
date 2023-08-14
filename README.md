# REST-API Web App

This is a web application that allows users to interact with a secrets API to perform CRUD (Create, Read, Update, Delete) operations on secrets. Users can enter IDs, secrets, and scores and choose different HTTP methods to interact with the API.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [API Configuration](#api-configuration)
- [Contributing](#contributing)


## Features

- Submit requests to the secrets API using various HTTP methods (GET, POST, PUT, PATCH, DELETE).
- Display API responses and error messages in a user-friendly interface.
- Easily interact with the API by providing input through the web form.

## Prerequisites

- Node.js (>= 12.x)
- npm (Node Package Manager)

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/secrets-management-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd secrets-management-app
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

## Usage

1. Start the server:

   ```bash
   npm start
   ```

2. Open your web browser and navigate to `http://localhost:3000` to access the web application.

3. Use the provided input fields and buttons to interact with the secrets API.

## API Configuration

1. Obtain a Bearer token from the secrets API provider.
2. Replace the value of `yourBearerToken` in the `app.js` file with your actual Bearer token.

## Contributing

Contributions are welcome! Here's how you can get involved:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature-new-feature` or `git checkout -b bugfix-issue-fix`.
3. Make your changes and commit them: `git commit -m "Add new feature"` or `git commit -m "Fix issue"`
4. Push to the branch: `git push origin feature-new-feature`
5. Create a pull request.
