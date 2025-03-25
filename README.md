# Basic Node.js App

A simple Node.js application using Express.

## Setup

1. Install dependencies:

```bash
npm install
```

## Running the App

Development mode (with auto-reload):

```bash
npm run dev
```

Production mode:

```bash
npm start
```

The server will start on port 3000 (or the port specified in the PORT environment variable).

## Code Formatting

This project uses Prettier for code formatting. To format all files:

```bash
npm run format
```

To check if files are properly formatted:

```bash
npm run format:check
```

## CI/CD

This project uses GitHub Actions for continuous integration. The CI pipeline:

- Runs on pull requests to alpha, beta, and prod branches
- Checks code formatting using Prettier
- (Future) Will run tests when added

## API Endpoints

- `GET /`: Returns a welcome message
