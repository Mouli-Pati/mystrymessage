# Mystry Message

An anonymous messaging platform built with **Next.js** where users can receive honest feedback and messages through a shareable profile. It also uses OpenAI to suggest engaging conversation starters.


# Mystry Message

An anonymous messaging platform built with **Next.js** where users can receive honest feedback and messages through a shareable profile. It also uses OpenAI to suggest engaging conversation starters.

## Overview

Mystry Message gives users a simple way to receive anonymous messages. Users can create an account, manage their messages from a dashboard, and share their profile link so other people can send messages without revealing their identity.

The project was built with Next.js and TypeScript, with MongoDB for data persistence and NextAuth.js for authentication.

## Features

- **User authentication** — sign-in and sign-up flows with protected dashboard routes.
- **Anonymous messaging** — share a profile link to receive messages from others.
- **Message management** — access messages through a user dashboard.
- **AI-generated suggestions** — generate conversation starters using OpenAI.
- **Input validation** — validate form data with Zod and React Hook Form.
- **Email support** — email-related functionality using Resend and React Email.
- **Responsive UI** — interface components styled with Tailwind CSS and Radix UI primitives.

> Feature availability may depend on the current deployment and environment configuration.

## Tech Stack

| Category | Technologies |
| --- | --- |
| Framework | Next.js 14 |
| Language | TypeScript |
| UI | React 18, Tailwind CSS, Radix UI |
| Database | MongoDB, Mongoose |
| Authentication | NextAuth.js |
| Forms and validation | React Hook Form, Zod |
| AI integration | OpenAI API, Vercel AI SDK |
| Email | Resend, React Email |
| HTTP requests | Axios |
| Icons | Lucide React |

## Getting Started

### Prerequisites

Make sure you have the following installed or available:

- [Node.js](https://nodejs.org/) — use a version compatible with Next.js 14.
- npm (included with Node.js)
- A MongoDB database, either local or hosted.
- An OpenAI API key for AI-generated message suggestions.
- Email service credentials if you want to use the email features.

### 1. Clone the repository

```bash
git clone https://github.com/Mouli-Pati/mystrymessage.git
cd Mystry_Message_NextJs
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env.local` file in the project root.

```env
# MongoDB connection string
MONGODB_URI="your_mongodb_connection_string"

# NextAuth configuration
NEXTAUTH_SECRET="your_long_random_secret"
NEXTAUTH_URL="http://localhost:3000"

# OpenAI API key used for message suggestions
OPENAI="your_openai_api_key"

# Email provider (configure if used by the application)
RESEND_API_KEY="your_resend_api_key"
```

Use the exact environment variable names expected by the code in your checked-out version. If an email or authentication variable differs in the source, update the example accordingly.

**Keep secrets private.** Do not commit `.env.local` or expose API keys in client-side code. Use your hosting provider's environment-variable settings for deployment.

### 4. Run the development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Available Scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the local development server |
| `npm run build` | Build the application for production |
| `npm run start` | Start the production server after building |
| `npm run lint` | Run the configured lint command |

## How It Works

1. A user creates an account and signs in.
2. The authenticated user accesses the dashboard.
3. The user shares their profile or message link.
4. Visitors submit anonymous messages through that link.
5. The user can view received messages from their dashboard.
6. The AI suggestion endpoint can generate conversation starters to help users invite messages.

## Deployment

The project is configured as a Next.js application and has a live deployment on Vercel.

For a new deployment:

1. Import the repository into [Vercel](https://vercel.com/).
2. Configure the required environment variables in the project settings.
3. Confirm that the MongoDB database is reachable from the deployment.
4. Deploy the application and test authentication, message submission, dashboard access, and AI suggestions.

See the [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for additional details.

## Security Notes

- Keep database credentials, authentication secrets, and API keys out of source control.
- Use a strong, unique `NEXTAUTH_SECRET` in production.
- Restrict database access to trusted application environments.
- Validate incoming data on the server, even when client-side validation is present.
- Review authentication and authorization checks before deploying changes.

## Contributing

Contributions and suggestions are welcome.

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -m "Add your feature"`.
4. Push the branch and open a pull request.

For larger changes, open an issue first to discuss the proposed approach.

## License

No license information was confirmed while preparing this README. Add a `LICENSE` file and update this section if you intend to distribute the project under a specific open-source license.

## Author

## Author

**Mouli Pati**

- GitHub: [@Mouli-Pati](https://github.com/Mouli-Pati)

---

If you find this project useful, consider giving the repository a ⭐.



## Overview

Mystry Message gives users a simple way to receive anonymous messages. Users can create an account, manage their messages from a dashboard, and share their profile link so other people can send messages without revealing their identity.

The project was built with Next.js and TypeScript, with MongoDB for data persistence and NextAuth.js for authentication.

## Features

- **User authentication** — sign-in and sign-up flows with protected dashboard routes.
- **Anonymous messaging** — share a profile link to receive messages from others.
- **Message management** — access messages through a user dashboard.
- **AI-generated suggestions** — generate conversation starters using OpenAI.
- **Input validation** — validate form data with Zod and React Hook Form.
- **Email support** — email-related functionality using Resend and React Email.
- **Responsive UI** — interface components styled with Tailwind CSS and Radix UI primitives.

> Feature availability may depend on the current deployment and environment configuration.

## Tech Stack

| Category | Technologies |
| --- | --- |
| Framework | Next.js 14 |
| Language | TypeScript |
| UI | React 18, Tailwind CSS, Radix UI |
| Database | MongoDB, Mongoose |
| Authentication | NextAuth.js |
| Forms and validation | React Hook Form, Zod |
| AI integration | OpenAI API, Vercel AI SDK |
| Email | Resend, React Email |
| HTTP requests | Axios |
| Icons | Lucide React |

## Getting Started

### Prerequisites

Make sure you have the following installed or available:

- [Node.js](https://nodejs.org/) — use a version compatible with Next.js 14.
- npm (included with Node.js)
- A MongoDB database, either local or hosted.
- An OpenAI API key for AI-generated message suggestions.
- Email service credentials if you want to use the email features.

### 1. Clone the repository

```bash
git clone https://github.com/Mr-R-e-X/Mystry_Message_NextJs.git
cd Mystry_Message_NextJs
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env.local` file in the project root.

```env
# MongoDB connection string
MONGODB_URI="your_mongodb_connection_string"

# NextAuth configuration
NEXTAUTH_SECRET="your_long_random_secret"
NEXTAUTH_URL="http://localhost:3000"

# OpenAI API key used for message suggestions
OPENAI="your_openai_api_key"

# Email provider (configure if used by the application)
RESEND_API_KEY="your_resend_api_key"
```

Use the exact environment variable names expected by the code in your checked-out version. If an email or authentication variable differs in the source, update the example accordingly.

**Keep secrets private.** Do not commit `.env.local` or expose API keys in client-side code. Use your hosting provider's environment-variable settings for deployment.

### 4. Run the development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Available Scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the local development server |
| `npm run build` | Build the application for production |
| `npm run start` | Start the production server after building |
| `npm run lint` | Run the configured lint command |

## How It Works

1. A user creates an account and signs in.
2. The authenticated user accesses the dashboard.
3. The user shares their profile or message link.
4. Visitors submit anonymous messages through that link.
5. The user can view received messages from their dashboard.
6. The AI suggestion endpoint can generate conversation starters to help users invite messages.

## Deployment

The project is configured as a Next.js application and has a live deployment on Vercel.

For a new deployment:

1. Import the repository into [Vercel](https://vercel.com/).
2. Configure the required environment variables in the project settings.
3. Confirm that the MongoDB database is reachable from the deployment.
4. Deploy the application and test authentication, message submission, dashboard access, and AI suggestions.

See the [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for additional details.

## Security Notes

- Keep database credentials, authentication secrets, and API keys out of source control.
- Use a strong, unique `NEXTAUTH_SECRET` in production.
- Restrict database access to trusted application environments.
- Validate incoming data on the server, even when client-side validation is present.
- Review authentication and authorization checks before deploying changes.

## Contributing

Contributions and suggestions are welcome.

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -m "Add your feature"`.
4. Push the branch and open a pull request.

For larger changes, open an issue first to discuss the proposed approach.

## License

No license information was confirmed while preparing this README. Add a `LICENSE` file and update this section if you intend to distribute the project under a specific open-source license.

## Author

## Author

**Mouli Pati**

- GitHub: [@Mouli-Pati](https://github.com/Mouli-Pati)

---

If you find this project useful, consider giving the repository a ⭐.