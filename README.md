# MaintXperts

A maintenance management system prototype.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

* **Node.js**: Ensure you have Node.js installed.
* **Git**: Ensure Git is installed.
* **PostgreSQL**: You will need a local Postgres installation or a cloud provider (like Neon, Supabase, or AWS).

### 1. Clone the Repository

Open your terminal and run:

```bash
git clone [https://github.com/sowrish12/MaintXperts.git](https://github.com/sowrish12/MaintXperts.git)
cd MaintXperts
```

### 2. Install Dependencies
```bash
npm install
# or if using yarn
yarn install
```

### 3. Environment Variables (Critical Step)
#### --- DATABASE CONFIGURATION ---
#### Replace the URL below with your actual PostgreSQL connection string.
#### Format: postgresql://USER:PASSWORD@HOST:PORT/DATABASE_NAME
#### DATABASE_URL="postgresql://johndoe:randompassword@localhost:5432/maintxperts"

#### --- AUTHENTICATION (Example: Clerk/NextAuth) ---
#### Add your auth keys here if applicable
#### NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_...
#### CLERK_SECRET_KEY=sk_test_...

### 4. Database Generation
```bash
npx prisma generate
npx prisma db push
```
### 5. Run the Application
```bash
npm run dev
```
