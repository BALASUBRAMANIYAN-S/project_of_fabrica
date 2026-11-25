# Fabrica: Digital Agency Landing Page

A modern, responsive landing page for a digital agency, built with Next.js. It presents the agency's services, selected projects and client testimonials.

## Sections

- **Hero**: headline and call to action
- **Services**: Branding and Identity, Social Media Marketing, Web Design and Development, SEO Optimization, Mobile App Development
- **Projects**: project cards
- **Testimonials**: client feedback and satisfaction stats
- **Navbar and Footer**

## Tech Stack

- [Next.js 15](https://nextjs.org/) (App Router) + React 19
- Tailwind CSS 4
- PrimeReact (UI components)
- React Icons

## Getting Started

**Prerequisites:** Node.js 18.18+ and npm

```bash
git clone https://github.com/BALASUBRAMANIYAN-S/project_of_fabrica.git
cd project_of_fabrica
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

| Command | What it does |
|---|---|
| `npm run dev` | Start the dev server (Turbopack) |
| `npm run build` | Create a production build |
| `npm start` | Run the production build |
| `npm run lint` | Run ESLint |

## Project Structure

```
src/
├── app/
│   ├── Home/            # Hero, Main, Services, Projects, Testimonials
│   ├── layout.js
│   ├── page.js
│   └── globals.css
└── Components/
    ├── Common/          # HomeCard, ProjectCard
    └── Pages/           # Navbar, Footer
public/                  # Hero and project images (AVIF), logos
```

## Deploy

The easiest way is [Vercel](https://vercel.com/new): import the repo and deploy.
