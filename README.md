# Code Whisper

A simple web-based code editor using the Monaco Editor, with support for executing JavaScript in the browser and Python/Java via the Piston API.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

*   Node.js and npm installed on your machine.

### Installation

1.  Clone the repository:
    ```bash
    git clone <repository_url>
    ```
2.  Navigate to the project directory:
    ```bash
    cd Code-Whisper-1.0
    ```
3.  Install dependencies (if any, based on package.json - though this project currently seems to rely mostly on client-side libraries included in `public/js`):
    ```bash
    npm install
    ```

### Running the Project

This project is a client-side application. To run it:

1.  Open the `public/index.html` file in your web browser.

The code editor should load, and you can select languages and run code.

**Note:** Running Python and Java code requires an internet connection as it uses the external Piston API (`https://emkc.org/api/v2/piston/execute`).

## Project Structure

*   `public/`: Contains the public-facing files, including `index.html` and the Monaco Editor library (`js/vs`).
*   `package.json`, `package-lock.json`: Node.js package files (currently used for project metadata, but could be used for build tools or server-side dependencies in the future).
*   `code-whisper/`: Contains project documentation and license.