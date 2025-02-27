# DALL E Clone

# DALL-E Clone

This project is a clone of OpenAI's DALL-E application, enabling users to generate images from textual descriptions. Built with a modern tech stack, it offers a seamless experience for AI-driven image creation and management.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- Generate images from textual descriptions using OpenAI's API.
- Store and manage images with Cloudinary.
- Responsive frontend built with Vite and React.
- Robust backend using Express and Node.js.
- Database management with MongoDB.

## Tech Stack

- **Frontend:** Vite, React, Tailwind CSS
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Cloud Storage:** Cloudinary
- **AI Integration:** OpenAI API

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (v14 or later)
- npm or yarn
- MongoDB (local or remote)
- Cloudinary account
- OpenAI API key

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/tarakrishna/DALL-E-clone.git
   cd DALL-E-clone
   ```

2. **Install dependencies:**

   - **Backend:**

     ```bash
     cd server
     npm install
     ```

   - **Frontend:**

     ```bash
     cd client
     npm install
     ```

## Configuration

1. **Backend:**

   Create a `.env` file in the `server` directory with the following variables:

   ```env
   MONGO_URI=your_mongo_connection_string
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   OPENAI_API_KEY=your_openai_api_key
   PORT=5000
   ```

2. **Frontend:**

   Create a `.env` file in the `client` directory with:

   ```env
   VITE_API_URL=http://localhost:5000
   ```

## Usage

1. **Start the backend server:**

   ```bash
   cd server
   npm start
   ```

2. **Start the frontend development server:**

   ```bash
   cd client
   npm run dev
   ```

## Folder Structure

```plaintext
DALL-E-clone/
├── client/      # Frontend code
└── server/      # Backend code
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.


