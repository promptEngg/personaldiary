# Portfolio Website

A modern, responsive portfolio website built with Next.js, Tailwind CSS, and Framer Motion.

## Features

- Clean and modern design
- Responsive layout
- Smooth animations
- Dark mode support
- Project showcase
- Resume integration

## Getting Started

1. Clone the repository:
```bash
git clone <your-repo-url>
cd portfolio
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Customization

1. Update personal information:
   - Edit `app/page.tsx` to update your name, title, and links
   - Replace project information in the `projects` array
   - Add your resume PDF to the `public` folder

2. Update project images:
   - Add your project screenshots to the `public` folder
   - Update image paths in the `projects` array

3. Customize styling:
   - Modify colors in `tailwind.config.js`
   - Update global styles in `app/globals.css`

## Deployment

The easiest way to deploy your portfolio is using Vercel:

1. Push your code to GitHub
2. Import your repository to Vercel
3. Vercel will automatically deploy your site

## Technologies Used

- Next.js 14
- React 18
- Tailwind CSS
- Framer Motion
- TypeScript 