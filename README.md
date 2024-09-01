# Django CRM Record Management System

## Overview

This Django-based CRM Record Management System allows users to manage customer records with full CRUD functionality and user authentication. Users can log in, sign up, and manage records including viewing, adding, updating, and deleting.

## Features

- **User Authentication**:
  - **Signup**: Create a new user account.
  - **Login**: Authenticate users to access the CRM system.
  - **Logout**: End the user session.

- **Record Management**:
  - **View All Records**: Display a list of all customer records.
  - **View Individual Record**: View detailed information for a specific customer record.
  - **Add Record**: Create and add new customer records.
  - **Update Record**: Modify and update existing customer records.
  - **Delete Record**: Remove customer records from the system.

## Installation

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/KhalidHamdi/DJANGO-CRM.git
    ```

2. **Navigate to the Project Directory**:

    ```bash
    cd DJANGO-CRM
    ```


3. **Apply Migrations**:

    ```bash
    python manage.py migrate
    ```

4. **Start the Development Server**:

    ```bash
    python manage.py runserver
    ```

## Usage

1. **User Authentication**:
   - **Signup**: Navigate to `/register` to create a new account.
   - **Login**: Use '/` to authenticate and access the CRM system.
   - **Logout**: Click the logout button to end your session.
     
2. **Record Management**:
   - **View All Records**: After logging in, you will see a list of all records on the home page (`/`).
   - **View Individual Record**: Click on a record to view its detailed information.
   - **Add a Record**: Go to `/add-record` to fill out the form and add a new record.
   - **Update a Record**: Navigate to a specific record and use the edit button to modify details.
   - **Delete a Record**: Navigate to the record and use the delete button to remove it.

