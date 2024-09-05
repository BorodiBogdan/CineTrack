
# Local Movie Database – Movie Management App

Local Movie Database is a movie management app that provides a dual-mode system for administrators and users. Administrators can manage movie data using full CRUD (Create, Read, Update, Delete) operations, while users can create personalized watchlists. The app features data visualizations and charts to enhance the user experience.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Features

- **Admin Mode**: Allows administrators to manage movie data with full CRUD functionality.
- **User Mode**: Users can create and manage personalized watchlists of movies.
- **Data Visualizations**: Visual charts and graphs are used to represent movie data for an enhanced user experience.
- **Responsive Interface**: Intuitive interface designed for easy navigation and management.

## Technologies

- **Frontend/GUI**: QT (for building the interface)
- **Programming Language**: C++
- **Database**: SQLite (for storing movie and user data)

## Installation

### Prerequisites

- QT framework installed on your system.
- C++ compiler to build the application.
- SQLite for database storage.

### Steps

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/local-movie-database.git
   cd local-movie-database
   ```

2. **Install dependencies**:

   Make sure you have QT and SQLite installed on your machine.

3. **Set up the database**:

   Use the provided SQL scripts to set up the SQLite database with the required tables for movie and user data.

4. **Build the application**:

   Compile the C++ code using a C++ compiler and QT framework.

5. **Run the application**:

   Execute the compiled binary to start the application.

## Usage

- **Admin Mode**: Log in as an administrator to add, edit, delete, and view movies.
- **User Mode**: Users can browse movies and create personalized watchlists.
- **Data Visualization**: View data visualizations, including charts and graphs of movie trends and user preferences.

## Contributing

We welcome contributions to improve Local Movie Database. If you have ideas for new features or bug fixes, feel free to fork the project and submit a pull request.

1. Fork the repository
2. Create a new branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request
