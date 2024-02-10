
## Description

Welcome to NestJS Carnival! This project is a NestJS application, and here's a guide to help you get started.

### Setting up

1. **Download and install Node.js**
   - We recommend using `fnm` to facilitate switching between Node versions in the future.

2. **Download and install PostgreSQL**
   1. Set the root `postgres` user's password (you'll need it later).
   2. Test PostgreSQL installation by entering `psql -U postgres` and providing your password.
   3. Create a database named `carnival` using the statement `CREATE DATABASE carnival;`.
   4. If successful, exit the psql shell.

3. **Clone the project to your local machine**
   - We suggest using VSCode's built-in git tools and cloning to `C:/dev/carnival` or a similar location for easy access.

4. **Install dependencies**
   - Open the VSCode terminal at the project root and run `npm install`.

5. **Create a `.env` file**
   - Follow the example in `.env.example` to set up the necessary environment variables.

6. **Bootstrap the database**
   1. Navigate to the project root in the terminal.
   2. Run `npm run migration:run` to apply migration files.

7. **Project setup complete. Use the commands below to run the app.**

## Running the app

- **Development:**
  ```bash
  npm run start
  ```

- **Watch Mode:**
  ```bash
  npm run start:dev
  ```

- **Production:**
  ```bash
  npm run start:prod
  ```

## Testing

- **Unit Tests:**
  ```bash
  npm run test
  ```

- **End-to-End Tests:**
  ```bash
  npm run test:e2e
  ```

- **Test Coverage:**
  ```bash
  npm run test:cov
  ```

## Database Management

- **Generate Migration Files:**
  ```bash
  npm run migration:generate
  ```

- **Create a New Migration File:**
  ```bash
  npm run migration:create --name=FILE_NAME
  ```

- **Run All Migration Files:**
  ```bash
  npm run migration:run
  ```
