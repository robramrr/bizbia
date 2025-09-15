# Orange County Web Development & AI Solutions

A modern Next.js 14 application with Tailwind CSS showcasing web development and AI solutions services.

## Features

- **Home Page**: Hero section with call-to-action buttons
- **Services Page**: Comprehensive overview of offered services
- **About Page**: Team information and company values
- **Contact Page**: Contact form and business information
- **Responsive Design**: Mobile-first approach with Tailwind CSS
- **Modern UI**: Clean, professional design with orange color scheme

## Tech Stack

- **Framework**: Next.js 14 with App Router
- **Styling**: Tailwind CSS
- **Language**: TypeScript
- **Icons**: Heroicons (SVG)
- **Font**: Inter (Google Fonts)

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Run the development server:
   ```bash
   npm run dev
   ```

3. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
orange-county-web-dev/
├── app/
│   ├── about/
│   │   └── page.tsx
│   ├── contact/
│   │   └── page.tsx
│   ├── services/
│   │   └── page.tsx
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   └── Navigation.tsx
├── package.json
├── tailwind.config.js
├── tsconfig.json
└── README.md
```

## Pages

- **Home** (`/`): Landing page with hero section and feature highlights
- **Services** (`/services`): Detailed service offerings and process overview
- **About** (`/about`): Company information, team, and values
- **Contact** (`/contact`): Contact form and business information

## Customization

The project uses a custom orange color scheme defined in `tailwind.config.js`. You can easily modify colors, fonts, and other design elements by updating the Tailwind configuration.

## Deployment

This project can be deployed to Vercel, Netlify, or any other platform that supports Next.js applications.

## License

This project is for demonstration purposes.
