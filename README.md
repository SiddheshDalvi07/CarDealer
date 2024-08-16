# Car Dealer

Welcome to the Car Dealer project! This is a fully functional web application designed for a car dealership, allowing users to browse and search for vehicles online. The website also provides admin functionalities to manage inventory and customer inquiries.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Features
- **User Interface:**
  - Responsive design that works on all devices.
  - Search and filter cars based on make, model, price, and other criteria.
  - View detailed information about each car.
  - Contact forms for inquiries.
  - User accounts for managing personal data.

- **Admin Interface:**
  - Inventory management (add, edit, delete cars).
  - Manage customer inquiries.
  - User management (add, edit, delete users).

- **Security:**
  - User authentication and authorization.
  - Data validation and sanitization.

## Technologies Used
- **Frontend:**
  - HTML, CSS, JavaScript
  - jQuery for dynamic interactions
  - Bootstrap for responsive design

- **Backend:**
  - Python with Django
  - MySQLite for the database

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Siddheshdalvi07/cardealer.git
   cd cardealer
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add the necessary environment variables (database credentials, etc.).

4. **Run the application:**
   ```bash
   python manage.py runserver
   ```

5. **Access the application:**
   Open your browser and go to `http://127.0.0.1:8000/`.

## Usage

### User Instructions:
- **Browse Cars:** Navigate to the homepage to view the available cars. Use the search and filter options to narrow down your choices.
- **Car Details:** Click on any car to view more details, including specifications, price, and available colors.
- **Contact Sales:** Use the contact form on the car details page to inquire about purchasing or schedule a test drive.
- **User Account:** Sign up or log in to manage your profile and personal data.

### Admin Instructions:
- **Login:** Access the admin dashboard by logging in with your credentials.
- **Manage Inventory:** Use the inventory section to add, edit, or delete car listings.
- **Inquiries:** View and manage customer inquiries from the inquiries section.
- **User Management:** Add or manage users with different roles (admin, sales, etc.).

## Configuration

- **Database Configuration:**
  Set up your database credentials in the `.env` file. For example:
  ```env
  DB_HOST=localhost
  DB_USER=root
  DB_PASS=password
  DB_NAME=cardealer
  ```

## Contributing

Contributions are welcome! Please follow the steps below:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
