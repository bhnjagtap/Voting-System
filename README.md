# Voting System App

## Overview

The Voting System App is a web application built using the Django framework. It allows users to vote on various questions, with their votes being counted and displayed afterward. This application is designed to provide a simple yet effective platform for conducting polls and gathering user opinions.

## Features

- User-friendly interface for casting votes on given questions.
- Real-time vote counting and results display.
- Secure and reliable voting mechanism.
- Admin interface for managing questions and monitoring votes.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/bhnjagtap/VOTING SYSTEM.git
    cd VOTING SYSTEM
    ```

2. **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```

3. **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Apply migrations:**
    ```bash
    python manage.py migrate
    ```

5. **Create a superuser:**
    ```bash
    python manage.py createsuperuser
    ```

6. **Run the development server:**
    ```bash
    python manage.py runserver
    ```

7. **Open your web browser and navigate to:**
    ```
    http://127.0.0.1:8000/
    ```

## Usage

1. **Access the admin panel:**
    ```
    http://127.0.0.1:8000/admin/
    ```
    Use the superuser credentials you created to log in.

2. **Create questions and choices:**
    - In the admin panel, navigate to the "Questions" section and add new questions.
    - Add choices for each question.

3. **Vote on questions:**
    - Visit the main page to see the list of questions.
    - Select your choice for each question and submit your vote.

4. **View results:**
    - After voting, you can see the current vote counts for each choice.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
