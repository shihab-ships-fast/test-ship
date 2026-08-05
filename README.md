# test_project

A Node.js project for testing and experimentation.

## Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later recommended)
- npm

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/shihab-ships-fast/test-ship.git
   cd test-ship
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file in the project root (see [Environment Variables](#environment-variables)).

4. Run the application:

   ```bash
   node index.js
   ```

## Environment Variables

This project uses [dotenv](https://www.npmjs.com/package/dotenv) to load environment variables from a `.env` file.

Create a `.env` file in the project root:

```env
# Add your environment variables here
```

The `.env` file is ignored by Git and should not be committed.

## Scripts

| Command   | Description        |
| --------- | ------------------ |
| `npm test` | Run tests (not yet configured) |

## License

ISC
