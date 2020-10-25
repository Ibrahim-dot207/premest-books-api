# Pre-MEST Books API

Build a API for a directory of books

## Installation

Clone the repository to your local machine

```bash
git clone https://github.com/mickeymond/premest-books-api.git
```

Change directory into project

```bash
cd premest-books-api
```

Copy nodemon.example.json to nodemon.json

```bash
cp nodemon.example.json nodemon.json
```

Replace with your MONGO URI String

```json
"MONGO_URI": "YOUR_MONGO_CONNECTION_STRING"
```

Use the package manager [npm](https://www.npmjs.com/) to install dependencies.

```bash
npm install
```

## Usage

Running the application locally

```bash
npm run dev
```

Running the application in production

```bash
npm run start
```