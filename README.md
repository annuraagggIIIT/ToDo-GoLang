


# ToDo GoLang Application

This is a simple ToDo application written in GoLang using the Chi router and MongoDB.

 ## Table of Contents
- [Introduction](#introduction)
- [Setup](#setup)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Dependencies](#dependencies)
- [License](#license)

## Introduction

This application provides a basic CRUD (Create, Read, Update, Delete) functionality for managing ToDo items. It uses the Chi router for handling HTTP requests and MongoDB for data storage.

## Setup

1. Install Dependencies:
   Make sure you have GoLang and MongoDB installed on your system.

2. Clone the Repository:
   ```bash
   git clone https://github.com/annuraagggIIIT/ToDo-GoLang.git
   cd ToDo-GoLang
   ```

3. Install Packages:
   ```bash
   go get ./...
   ```

4. Run the Application:
   ```bash
   go run main.go
   ```

## Usage

Once the application is running, you can access the ToDo API using the specified endpoints.

## API Endpoints

- `GET /todo`: Fetch all ToDo items
- `POST /todo`: Create a new ToDo item
- `PUT /todo/{id}`: Update a ToDo item
- `DELETE /todo/{id}`: Delete a ToDo item

## Dependencies

- [Chi](https://github.com/go-chi/chi): Lightweight, idiomatic Go router
- [MongoDB](https://www.mongodb.com/): NoSQL database for data storage

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

Feel free to customize it according to your project's specific details. Add more information as needed, such as environment variables, configuration, or deployment instructions.
