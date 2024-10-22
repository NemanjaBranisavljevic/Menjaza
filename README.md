# Menjaza App

## Overview

The Menjaza App is a web application designed to facilitate the swapping of goods between users. Built on the Django framework, Menjaza allows individuals to easily exchange items they no longer need for those they want, promoting sustainability and community engagement.

## Features

- **User Profiles**: Create and manage personal profiles to showcase items available for swapping.
- **Item Listing**: Easily list items you want to swap, complete with photos and descriptions.
- **Search and Filter**: Browse available items using search and filtering options to find what you need.
- **Swap Requests**: Send and receive swap requests to negotiate trades with other users.
- **Messaging System**: Communicate with other users to finalize details about swaps.
- **Ratings and Reviews**: Rate your swapping experience and read feedback from other users to ensure trust and safety.

## Technologies Used

- **Backend**: Django
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (or PostgreSQL, depending on configuration)

## Installation

### Prerequisites

- Python 3.x
- Django 3.x (or higher)
- pip

### Steps to Install

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/menjaza-app.git
   cd menjaza-app
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Apply migrations:
   ```bash
   python manage.py migrate
   ```

5. Create a superuser (optional):
   ```bash
   python manage.py createsuperuser
   ```

6. Run the server:
   ```bash
   python manage.py runserver
   ```

7. Access the application in your web browser at `http://127.0.0.1:8000/`.

## Usage

1. **Register/Login**: Create an account or log in to access your dashboard.
2. **List Items**: Add items you wish to swap, including descriptions and images.
3. **Browse Items**: Search for items you want to acquire and explore available swaps.
4. **Send Swap Requests**: Connect with other users to propose swaps and negotiate terms.
5. **Leave Feedback**: After completing swaps, provide ratings and reviews for fellow users.

## Contributing

We welcome contributions! If you’d like to contribute to the Menjaza App, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Support

For support or questions, please open an issue on the GitHub repository or contact us at [nbranisavljevic@yahoo.com].

---

Thank you for using the Menjaza App! Happy swapping!
