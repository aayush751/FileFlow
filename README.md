# File Explorer

## Overview
**File Explorer** is a web-based application that allows users to easily manage and explore text files stored on the server. Built using Express.js and EJS templating, the app provides a simple and intuitive interface for viewing, creating, and organizing text files.

## Features
- **Browse Files:** List all available text files stored in the server's directory.
- **View File Content:** Open and read the contents of any selected text file directly in the browser.
- **Create New Files:** Use the built-in form to create new text files by entering a title and content, which are then saved to the server.

## Technologies Used
- **Backend:** Node.js, Express.js
- **Templating Engine:** EJS
- **File Management:** Node.js `fs` module
- **Styling:** Tailwind CSS

## How It Works
The application serves an interface where users can see all the text files in the server's `files` directory. Users can click on any file to view its contents, or use the form to create a new file by specifying a title and details. The newly created file is instantly added to the list.

## Use Cases
- Simple document management system.
- Personal note-taking or journaling tool.
- Educational tool for learning basic file handling and web development concepts.

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/aayush751/FileFlow.git
2. Install dependencies:
   ```bash
    npm install
3. Start the server.
   ```bash
   npm start
4. Open your browser and go to `http://localhost:3000` to use the application.

## License
Licensed under the MIT License.
