# EventMasterPro

EventMasterPro is a web-based event management system built with TypeScript, Express, and Tailwind CSS. This project helps users organize and manage events efficiently.

## Features
- User authentication
- Event creation and management
- Database integration with Drizzle ORM
- Styled with Tailwind CSS

## Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v16+ recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

## Installation
Clone the repository and install dependencies:
```sh
git clone <repository-url>
cd EventMasterPro
npm install
```

## Running in Development Mode
Start the development server with:
```sh
npm run dev
```

This runs `tsx server/index.ts`, launching the project in development mode.

## Building for Production
To build and start the project in production mode:
```sh
npm run build
npm start
```

- `npm run build`: Bundles the project and outputs files to the `dist/` directory.
- `npm start`: Runs the production server using `node dist/index.js`.

## Database Setup
If using Drizzle ORM, apply database migrations with:
```sh
npm run db:push
```

## Project Structure
```
EventMasterPro/
│── server/          # Backend logic (Express, APIs)
│── src/             # Frontend components
│── public/          # Static assets
│── dist/            # Production build output
│── package.json     # Project metadata & dependencies
│── tsconfig.json    # TypeScript configuration
│── tailwind.config.ts  # Tailwind CSS setup
```

## License
This project is licensed under the MIT License.

