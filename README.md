# CipherGuard => Encrypt-Decrypt-Password using C++ and MySQL

## Introduction

This project demonstrates an implementation of password encryption and decryption in C++ using MySQL database for storage. It employs Object-Oriented Programming (OOP) principles to manage user login credentials securely.

## Features

- **Sign up**: Users can create an account by providing a unique ID and a strong password.
- **Login**: Registered users can log in with their ID and password.
- **Password Encryption**: Passwords are encrypted using a simple substitution cipher to enhance security.
- **MySQL Integration**: Utilizes MySQL database to store encrypted passwords securely.

## Requirements

- C++ Compiler (e.g., GCC)
- MySQL Database
- MySQL Connector/C++
- Windows OS (for Sleep function usage)

## Installation and Setup

1. Install a C++ compiler and MySQL database on your system.
2. Set up MySQL Connector/C++ library.
3. Clone the repository to your local machine.
4. Modify the `HOST`, `USER`, `PW`, and `DB` constants in the source code with your MySQL server credentials.
5. Compile the source code using your C++ compiler.
6. Run the executable file.

## Usage

1. Run the executable.
2. Choose an option: Sign up, Login, or Exit.
3. If signing up, enter a unique ID and a strong password.
4. If logging in, enter your ID and password.
5. Follow the on-screen instructions.
