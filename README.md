# QuickPay

This Payment Wallet application allows users to add money from a dummy bank and perform transactions between each other.

## Tech Stack

- **Frontend:**
  - [Next.js](https://nextjs.org/)
  - [Tailwind CSS](https://tailwindcss.com/)
  - [Recoil](https://github.com/pmndrs/jotai) (for state management)

- **Backend:**
  - [Express.js](https://expressjs.com/)
  - [PostgreSQL](https://www.postgresql.org/)
  - [Prisma](https://www.prisma.io/)
  - [NextAuth.js](https://next-auth.js.org/)

- **Monorepo Management:**
  - [Turborepo](https://turborepo.org/)

## Features

- Add money from a dummy bank account.
- Perform transactions between users.
- User authentication and session management.

## Getting Started

### Prerequisites

- Node.js
- PostgreSQL

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/payment-wallet.git
   cd payment-wallet
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add your environment variables. Example:
   ```env
   DATABASE_URL=postgresql://user:password@localhost:5432/mydb
   NEXTAUTH_URL=http://localhost:3000
   NEXTAUTH_SECRET=your-secret
   ```

4. **Run database migrations:**
   ```bash
   npx prisma migrate dev
   ```

### Running the Application

1. **Start the development server:**
   ```bash
   npm run dev
   ```

2. **Open your browser:**
   Navigate to `http://localhost:3000`.

## Scripts

- `dev`: Starts the development server.
- `build`: Builds the application for production.
- `start`: Starts the production server.
- `prisma`: Run Prisma commands.

## License

This project is licensed under the MIT License.
