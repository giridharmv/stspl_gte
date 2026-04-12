# STSPL GTE Report

This website provides an overview of the work and learning experiences completed as part of the Apprenticeship Program at STSPL (Siemens Technology and Services Private Limited).

## Project Structure

- `stspl-gte-report/`: Main Angular application with Server-Side Rendering (SSR) support.
- `package.json`: Root dependencies (includes Bootstrap for styling).
- Other configuration files for development and build.

## Technology Stack

- **Frontend**: Angular 21 with TypeScript
- **Styling**: Bootstrap 5
- **Build Tool**: Angular CLI with Vite
- **Testing**: Vitest for unit tests
- **SSR**: Angular Universal for server-side rendering

## Prerequisites

- Node.js (version 18 or higher)
- npm (comes with Node.js)

## Installation

1. Clone or download the repository.
2. Navigate to the project root directory.
3. Install dependencies for the Angular app:

   ```bash
   cd stspl-gte-report
   npm install
   ```

## Development

To start the development server:

```bash
cd stspl-gte-report
npm start
```

The application will be available at `http://localhost:4200/`. It supports hot reloading for development.

## Building

To build the project for production:

```bash
cd stspl-gte-report
npm run build
```

The build artifacts will be stored in the `dist/stspl-gte-report/` directory.

## Server-Side Rendering

To serve the application with SSR:

```bash
cd stspl-gte-report
npm run serve:ssr:stspl-gte-report
```

## Testing

Run unit tests:

```bash
cd stspl-gte-report
npm test
```

## Contributing

This is a personal project for the apprenticeship program. For any questions or feedback, please contact the developer.

## License

This project is for educational purposes as part of the STSPL Apprenticeship Program.
