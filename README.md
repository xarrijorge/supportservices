# Support Services

## Overview

This repository contains the source code for a fullstack web application that streamlines the uploading, processing, and retrieval of various documents. The backend is built using Flask, and the frontend is developed with Svelte. Both components are organized into separate directories.

## Features

- **User Authentication**: Secure login and registration
- **File Upload**: Users can upload documents for processing
- **Document Processing**: Our team takes care of the document processing
- **Notification**: Users receive email notifications once documents are processed
- **Document Retrieval**: Processed documents can be downloaded from the platform

## Tech Stack

- Backend: Flask
- Frontend: Svelte
- Database: PostgreSQL
- Email: SMTP

## Repository Structure

- `/backend`: Contains the Flask backend code
- `/frontend`: Contains the Svelte frontend code

## Installation and Setup

### Prerequisites

- Python 3.9+
- Node.js 16+
- PostgreSQL

### Steps

1. Clone the repository
    ```bash
    git clone https://github.com/yourusername/DocumentProcessingService.git
    ```

2. Navigate to the project directory
    ```bash
    cd DocumentProcessingService
    ```

3. Install backend dependencies
    ```bash
    cd backend
    pip install -r requirements.txt
    ```

4. Install frontend dependencies using Yarn
    ```bash
    cd ../frontend
    yarn install
    ```

5. Create a `.env` file within the `/backend` directory to configure database and email settings

6. Initialize the database
    ```bash
    cd ../backend
    flask db init
    flask db migrate
    flask db upgrade
    ```

7. Run the backend
    ```bash
    flask run
    ```

8. In a new terminal window, navigate to the frontend directory and run it
    ```bash
    cd ../frontend
    yarn dev
    ```

## Usage

1. Register or login to your account
2. Upload documents that require processing
3. Wait for email notification regarding document status
4. Download processed documents via the platform

## Contributing

To contribute, please fork the repository and create a feature branch. Pull requests are welcome.

## License

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.
