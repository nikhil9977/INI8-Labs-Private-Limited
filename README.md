# Registration System - CRUD Operations

This project demonstrates basic CRUD operations (Create, Read, Update, Delete) on a 'Registration' table using Python and SQLite. Follow the steps below to run the code on your local machine.

## Prerequisites

- Python 3.x installed on your machine.
- Ensure the `sqlite3` module is available. You can install it using:
  ```
  pip install db-sqlite3
  ```

## Steps to Run

1. **Clone the Repository:**

   ```bash
   git clone <repository-url>
   cd registration-crud
   ```

2. **Run the Python Script:**

   Execute the following command to run the Python script:

   ```bash
   python registration_crud.py
   ```

   The script will perform the following actions:
   - Create a new SQLite database file named `registration.db`.
   - Create the 'Registration' table if it doesn't exist.
   - Perform sample CRUD operations (Create, Read, Update, Delete) on the table.

3. **View Results:**

   Check the terminal for output messages confirming the success or error during each CRUD operation.

4. **Explore the Database:**

   Optionally, you can use a SQLite database viewer (e.g., DB Browser for SQLite) to inspect the `registration.db` file and verify the changes made by the script.

## Notes

- Feel free to modify the `registration_crud.py` script according to your needs.
- Ensure the database file (`registration.db`) is not being used or locked by other processes before running the script.

Now you should be able to run the provided Python script locally and interact with the 'Registration' table. If you encounter any issues, feel free to reach out for assistance.
