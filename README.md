# The Wild Oasis Website

A booking management dashboard for a set of luxury cabins.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Environment Variables](#environment-variables)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Wild Oasis Website is a web application built with Next.js that serves as a booking management dashboard for luxury cabins. It allows administrators to manage bookings, cabins, users, and settings, providing a comprehensive tool for overseeing the operations of "The Wild Oasis" cabin rentals.

## Features

- **Dashboard**: Overview of key metrics and recent activity.
- **Cabin Management**: Create, edit, and delete cabin listings.
- **Booking Management**: View, create, update, and cancel bookings.
- **User Authentication**: Secure user authentication and authorization.
- **Account Management**: User profile and settings management.
- **Settings**: Configure application settings.
- **Error Handling**: Robust error handling and user feedback.
- **Responsive Design**: Fully responsive and accessible design.

## Technologies Used

- **Next.js**: React framework for building performant web applications.
- **React**: JavaScript library for building user interfaces.
- **Supabase**: Backend-as-a-service for data storage and authentication.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **Date-fns**: Modern JavaScript date utility library.
- **NextAuth.js**: Authentication library for Next.js.
- **React Day Picker**: Date picker component for React.
- **Heroicons**: Set of free MIT-licensed high-quality SVG icons for UI development.
- **ESLint**: JavaScript linting tool.
- **PostCSS**: Tool for transforming CSS with JavaScript.

## Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/iwanehu/The-wild-oasis-website.git
    cd The-wild-oasis-website
    ```

2.  **Install dependencies:**

    ```bash
    npm install # or yarn install or pnpm install or bun install
    ```

## Usage

1.  **Set up environment variables:**

    Create a `.env.local` file in the root directory and add the necessary environment variables.  See the [Environment Variables](#environment-variables) section for more details.

2.  **Run the development server:**

    ```bash
    npm run dev # or yarn dev or pnpm dev or bun dev
    ```

3.  **Open the application in your browser:**

    Visit `http://localhost:3000` to view the application.

## Environment Variables

The following environment variables are required to run this application:

-   `NEXT_PUBLIC_SUPABASE_URL`: The URL of your Supabase project.
-   `NEXT_PUBLIC_SUPABASE_ANON_KEY`: The anonymous key for your Supabase project.
-   `NEXTAUTH_SECRET`: A secret key for NextAuth.js.
-   `NEXTAUTH_URL`: The URL of your Next.js application.

You can obtain these credentials by setting up a Supabase project and configuring NextAuth.js.

## Contributing

Contributions are welcome! Here's how to contribute:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them with clear, concise messages.
4.  Submit a pull request to the main branch.

Please follow the existing code style and conventions when contributing.

## License

This project is open-source and available under the [MIT License](LICENSE).
