# User Booking Hotel Oasis

This application allows users to book hotels seamlessly. It is built using Next.js, Supabase for the database, and Auth.js for authentication.

![Screenshot 2024-10-09 162313](https://github.com/user-attachments/assets/1fc1ab25-be86-4948-a541-b27197387232)
![Screenshot 2024-10-09 162248](https://github.com/user-attachments/assets/3e2721d0-8466-4389-9040-c3906838dc34)


## Table of Contents

- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Contributing](#contributing)
- [License](#license)
- [Repository](#repository)

## Technologies Used

- **Next.js**: A React framework for server-side rendering and static site generation.
- **Supabase**: An open-source Firebase alternative for the database.
- **Auth.js**: Authentication library for handling user sign-in and sign-up.

## Getting Started

### Prerequisites

- Node.js installed
- Supabase account
- Auth.js setup

### Installation

1. Clone the repository:

```bash
git clone https://github.com/raffimh/user-hotel-oasis.git
cd user-booking-hotel-oasis
```

2. Install dependencies:

```bash
npm install
```

3. Set up environment variables:
   Create a `.env.local` file in the root directory and add your environment variables:

```plaintext
NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
AUTH_SECRET=your-auth-secret
```

### Running the Application

Start the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Repository

[GitHub Repository](https://github.com/raffimh/user-hotel-oasis.git)
