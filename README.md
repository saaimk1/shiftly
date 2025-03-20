# Shiftly

An automated shift management application built with TypeScript and Puppeteer.

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn

## Setup

1. Clone the repository:

```bash
git clone https://github.com/yourusername/shiftly.git
cd shiftly
```

2. Install dependencies:

```bash
npm install
```

3. Configure environment variables:
   - Copy `.env.example` to `.env`
   - Fill in your credentials and security answers in the `.env` file

## Usage

### Development Mode

```bash
npm run dev
```

### Production Mode

```bash
npm run build
npm start
```

## Project Structure

- `src/main.ts` - Application entry point
- `src/config.ts` - Configuration and environment variables
- `src/login.ts` - Login and 2FA handling
- `src/clock.ts` - Clock-in/clock-out functionality
- `src/browser.ts` - Browser session management

## Configuration

Edit the `.env` file to configure:

- Username and password
- Security answers for 2FA
- Browser settings (headless mode, timeout)

## Error Handling

The application includes comprehensive error handling for:

- Login failures
- 2FA issues
- Clock-in/clock-out errors
- Browser session problems

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
