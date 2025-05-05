# 🧾 Request Header Parser Microservice

My solution for the [Request Header Parser Microservice project on freeCodeCamp](https://www.freecodecamp.org/learn/back-end-development-and-apis/back-end-development-and-apis-projects/request-header-parser-microservice).

## 📌 Overview

This microservice extracts key information from the request headers of an HTTP client and returns it in a structured JSON format.  
It provides a simple and clear demonstration of how to read HTTP headers using Node.js and Express.

## 🔍 Features

- Extracts IP address of the client
- Retrieves client's language preferences
- Parses the user-agent to determine software and OS

## 📡 API Endpoint

### `GET /api/whoami`

Returns a JSON object like the following:

```json
{
  "ipaddress": "127.0.0.1",
  "language": "en-US,en;q=0.9",
  "software": "Mozilla/5.0 (X11; Linux x86_64)..."
}
```

## ⚙️ Technologies

- Node.js
- Express.js
- JavaScript (ES6)

## 💻 Source Code

🔗 [GitHub Repository](https://github.com/giannis07/fcc-request-header-parser-microservice)

## 🛠️ Getting Started Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/giannis07/fcc-request-header-parser-microservice.git
   cd fcc-request-header-parser-microservice
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the server:
   ```bash
   npm start
   ```

4. Open your browser and visit:
   ```
   http://localhost:3000/api/whoami
   ```
