# Library Management System

A Library Management System built using the Frappe framework. This application allows users to manage library operations such as tracking books, borrowers, and transactions efficiently.

## Features

- **Book Management:** Add, update, and remove books in the library.
- **Borrower Management:** Manage borrower details and keep track of borrowed books.
- **Transaction Management:** Record and manage book issue and return transactions.
- **Reports:** Generate reports on book availability, borrower activity, and transaction history.

## Installation

### Prerequisites

- [Frappe Framework](https://frappeframework.com/)
- [Python 3.x](https://www.python.org/downloads/)
- [Node.js](https://nodejs.org/en/download/)
- [Redis](https://redis.io/download)
- [MariaDB](https://mariadb.org/download/)

### Step-by-Step Installation

1. **Clone the Repository:**

    ```sh
    git clone --recurse-submodules https://github.com/thomas7272/Library-Management-system.git
    cd Library-Management-system
    ```

2. **Install Bench:**

    ```sh
    pip install frappe-bench
    ```

3. **Initialize Bench:**

    ```sh
    bench init library_bench
    cd library_bench
    ```

4. **Get the App:**

    ```sh
    bench get-app library_management https://github.com/thomas7272/library_management.git
    ```

5. **Create a New Site:**

    ```sh
    bench new-site library.local
    ```

6. **Install the App:**

    ```sh
    bench --site library.local install-app library_management
    ```

7. **Start Bench:**

    ```sh
    bench start
    ```

8. **Access the Application:**

    Open your browser and go to `http://library.local:8000`.

## Usage

1. **Login:**
   Use the default administrator credentials to log in:
   - Username: `Administrator`
   - Password: `admin`

2. **Configure Library Settings:**
   Set up library settings such as categories, shelves, and borrowing rules.

3. **Add Books:**
   Navigate to the "Books" section and start adding book details.

4. **Manage Borrowers:**
   Add and manage borrower details under the "Borrowers" section.

5. **Issue and Return Books:**
   Record transactions for book issues and returns in the "Transactions" section.

6. **Generate Reports:**
   Use the reporting feature to generate and view various library reports.

## Contributing

We welcome contributions to improve the Library Management System. To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push your branch to GitHub.
4. Open a pull request with a description of your changes.
