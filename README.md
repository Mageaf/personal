# Personal Portfolio Website

A modern, responsive personal portfolio website built with Next.js, TypeScript, and Tailwind CSS.

## Features

- 🎨 Modern and clean design
- 🌓 Dark/Light mode support
- 📱 Fully responsive
- ⚡ Fast performance with Next.js
- 🎭 Smooth animations with Framer Motion
- 📝 Easy to customize and extend

## Getting Started

### Prerequisites

- Node.js 18.x or later
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/portfolio.git
cd portfolio
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Customization

### Personal Information

1. Update your name in the following files:
   - `src/app/layout.tsx` - Update the title and description
   - `src/app/page.tsx` - Update the hero section with your name and title
   - `src/components/Footer.tsx` - Update the copyright text

2. Update your social links in `src/components/Footer.tsx`

### Projects

1. Edit the `projects` array in `src/app/page.tsx` to add your own projects
2. Add project images to the `public` directory
3. Update the project links with your GitHub repositories and live demos

### Styling

The website uses Tailwind CSS for styling. You can customize the colors, spacing, and other design elements by modifying the Tailwind classes in the components.

## Deployment

The website can be deployed to any platform that supports Next.js applications. Some popular options include:

- Vercel (recommended)
- Netlify
- GitHub Pages

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.