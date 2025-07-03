# KARAN'S CLI Weather Agent

![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white&style=for-the-badge)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white&style=for-the-badge)
![Axios](https://img.shields.io/badge/Axios-5A29E4?logo=axios&logoColor=white&style=for-the-badge)
![dotenv](https://img.shields.io/badge/dotenv-8DD6F9?logo=dotenv&logoColor=black&style=for-the-badge)

---

## 🚀 About

**KARAN'S CLI** is a command-line weather agent powered by OpenAI and real-time weather data from [wttr.in](https://wttr.in).  
It uses a multi-step reasoning approach to answer your weather queries for any city.

---

## 🛠️ Tech Stack & Packages

### [Node.js](https://nodejs.org/)

- JavaScript runtime for building CLI tools.

### [OpenAI Node.js SDK](https://www.npmjs.com/package/openai)

- Used for interacting with OpenAI's GPT models.

### [Axios](https://www.npmjs.com/package/axios)

- Promise-based HTTP client for making API requests.

### [dotenv](https://www.npmjs.com/package/dotenv)

- Loads environment variables from a `.env` file.

### [readline (Node.js core)](https://nodejs.org/api/readline.html)

- For interactive CLI input/output.

---

## 📦 Installation

1. **Clone the repo:**

   ```sh
   git clone https://github.com/yourusername/weatherAgent.git
   cd weatherAgent
   ```

2. **Install dependencies:**

   ```sh
   npm install
   ```

3. **Set up your `.env` file:**
   ```
   OPENAI_API_KEY=your_openai_api_key_here
   ```

---

## 🏃 Usage

```sh
node index.js
```

You'll see a banner and be prompted for a city name.  
The agent will reason step-by-step and fetch the weather for you!

---

## 📚 Packages Used

| Package      | Link                                             | Description                       |
| ------------ | ------------------------------------------------ | --------------------------------- |
| **OpenAI**   | [openai](https://www.npmjs.com/package/openai)   | OpenAI API SDK for Node.js        |
| **Axios**    | [axios](https://www.npmjs.com/package/axios)     | HTTP client for API requests      |
| **dotenv**   | [dotenv](https://www.npmjs.com/package/dotenv)   | Loads environment variables       |
| **readline** | [readline](https://nodejs.org/api/readline.html) | Node.js core module for CLI input |

---

## ✨ Features

- Interactive CLI with ASCII art banner
- Step-by-step AI reasoning (plan, action, observe, output)
- Real-time weather data from [wttr.in](https://wttr.in)
- Modular and extendable function mapping
