# Next-Project

A scalable real-time chat application built with TypeScript, Next.js, Redis, Express, Socket.io, and Upstash.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- **Node.js**: Version 16 or higher
- **npm** (Node Package Manager) or **yarn**

## Getting Started

Follow these instructions to set up and run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Next-Project.git
cd Next-Project
```

### 2. Install Dependencies

For the Client
Navigate to the client directory and install the necessary dependencies:

```bash
cd client
npm install
```

For the Server
Navigate to the server directory and install the necessary dependencies:

```bash
cd ../server
npm install
```

### 3. Set Up Environment Variables

Client
In the client directory, create a .env file based on the .env.example provided:

```bash
cp .env.example .env
```

Fill in the necessary environment variables in the .env file.

Server
In the server directory, create a .env file based on the .env.example provided:

```bash
cp .env.example .env
```

Fill in the necessary environment variables in the .env file.

### Running the Application

Start the Server
First, start the Express server:

```bash
cd ../server
npm run dev
```

This will start the server on http://localhost:3001 (or another port if configured differently in your environment variables).

Start the Client
Next, start the Next.js client:

```bash
cd ../client
npm run dev
```

This will start the Next.js development server on http://localhost:3000.

### 5. Access the Application

Open your browser and navigate to:

```bash
http://localhost:3000
```
