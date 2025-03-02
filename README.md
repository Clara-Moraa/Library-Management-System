# Library Management System

A simple book lending library application built with Ruby on Rails 8. This application allows registered users to browse available books, borrow a book, return a book, and see a list of books they currently have borrowed.

## Features

- User registration and login (using Rails 8's default authentication with Devise)
- Book listing page (showing availability status)
- Book details page (with a borrow button if available)
- User profile page listing currently borrowed books
- Ability to return books
- Model validations (e.g., title/author/isbn presence, unique ISBN)
- Error handling (e.g., preventing borrowing an already borrowed book)
- Well-structured views and CSS styling

## Requirements

- Ruby 3.2.0 or higher
- Rails 8.0.0
- SQLite3

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Clara-Moraa/library_management.git
cd library_management
bundle install
rails db:create
rails db:migrate
rails db:seed
rails server

Visit http://localhost:3000 in your browser.
