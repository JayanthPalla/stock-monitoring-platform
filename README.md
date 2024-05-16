# Django and React App README

This repository contains a Django backend integrated with a React frontend to create a full-stack web application.

## Setup

### Prerequisites

- Python 3.x installed
- Node.js and npm installed

### Backend Setup

1. Clone the repository:

    ```
    git clone <repository_url>
    ```

2. Navigate to the backend directory:

    ```
    cd backend
    ```

3. Install Python dependencies:

    ```
    pip install -r requirements.txt
    ```

4. Apply migrations:

    ```
    python manage.py migrate
    ```

5. (Optional) Load initial data (if any):

    ```
    python manage.py loaddata <fixture_file>
    ```

6. Run the Django server:

    ```
    python manage.py runserver
    ```

### Frontend Setup

1. Navigate to the frontend directory:

    ```
    cd frontend
    ```

2. Install Node.js dependencies:

    ```
    npm install
    ```

3. Start the React development server:

    ```
    npm start
    ```

## Usage

Once both the backend and frontend servers are running, you can access the web application by navigating to `http://localhost:3000` in your web browser.

## Folder Structure

- **backend**: Contains the Django backend code.
- **frontend**: Contains the React frontend code.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
