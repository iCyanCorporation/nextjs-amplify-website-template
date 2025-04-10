## AWS Amplify Next.js (App Router) Starter Template

This repository provides a starter template for creating applications using Next.js (App Router) and AWS Amplify, emphasizing easy setup for authentication, API, and database capabilities.

## Overview

This template equips you with a foundational Next.js application integrated with AWS Amplify, streamlined for scalability and performance. It is ideal for developers looking to jumpstart their project with pre-configured AWS services like Cognito, AppSync, and DynamoDB.

## Getting Started

### Creating a New Project

Copy this repo

### Adding UI Components and Styling

This template uses [shadcn/ui](https://ui.shadcn.com/) for beautifully designed components that are easily customizable:

```bash
# First, install and set up Tailwind CSS (required for shadcn)
npm install -D tailwindcss postcss autoprefixer

# update tailwind
https://tailwindcss.com/docs/installation/framework-guides/nextjs

# Create or update your tailwind.config.js to match this:
# content: [
#   './pages/**/*.{js,ts,jsx,tsx,mdx}',
#   './components/**/*.{js,ts,jsx,tsx,mdx}',
#   './app/**/*.{js,ts,jsx,tsx,mdx}',
# ],

# Add the Tailwind directives to your CSS
# Create or edit ./app/globals.css with:
# @tailwind base;
# @tailwind components;
# @tailwind utilities;

# After Tailwind is properly set up, add shadcn/ui
npx shadcn@latest init
```

For component installation:

```bash
# Add commonly used components individually
npx shadcn@latest add button
npx shadcn@latest add card
npx shadcn@latest add form
```

or

```bash
# Add all components at once
npx shadcn@latest add --all
```

### Other Recommended Packages

```bash
# Add useful packages for a modern web experience
npm install next-themes           # For dark/light mode
npm install react-icons           # Icon library
npm install @hookform/resolvers zod # Form validation
npm install date-fns             # Date formatting
npm install zustand              # State management
npm install framer-motion        # Animations
```

## Features

- **Authentication**: Setup with Amazon Cognito for secure user authentication.
- **API**: Ready-to-use GraphQL endpoint with AWS AppSync.
- **Database**: Real-time database powered by Amazon DynamoDB.
- **UI Components**: Modern, accessible components with shadcn/ui.
- **Styling**: Utility-first CSS with Tailwind CSS.
- **Theming**: Support for dark/light mode using next-themes.

## Deploying to AWS

For detailed instructions on deploying your application, refer to the [deployment section](https://docs.amplify.aws/nextjs/start/quickstart/nextjs-app-router-client-components/#deploy-a-fullstack-app-to-aws) of our documentation.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.
