# Nuxt Landing Page

A modern, responsive landing page built with Nuxt.js 4 and Nuxt UI. This project demonstrates a production-ready landing page template with beautiful design, smooth animations, and best practices.

## Features

- 🚀 **Lightning Fast**: Built with Nuxt.js 4 for optimal performance
- 🎨 **Beautiful Design**: Modern gradient backgrounds and smooth transitions
- 📱 **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- ♿ **Accessible**: Follows web accessibility best practices
- 🎯 **SEO Optimized**: Server-side rendering for better search engine visibility
- 🛠️ **TypeScript Support**: Fully typed for better developer experience

## What's Included

The landing page includes the following sections:

- **Navigation Bar**: Responsive navigation with links to Features, About, and Contact sections
- **Hero Section**: Eye-catching introduction with call-to-action buttons
- **Features Section**: Showcase of three key features with icons and descriptions
- **About Section**: Detailed information about the technology stack
- **Call-to-Action Section**: Conversion-focused section to engage visitors
- **Footer**: Complete footer with links and copyright information

## Getting Started

### Prerequisites

- Node.js 18.x or higher
- npm, pnpm, yarn, or bun package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/DonaldHawthorne/al-test.git
cd al-test
```

2. Install dependencies:
```bash
# npm
npm install

# pnpm
pnpm install

# yarn
yarn install

# bun
bun install
```

### Development

Start the development server on `http://localhost:3000`:

```bash
# npm
npm run dev

# pnpm
pnpm dev

# yarn
yarn dev

# bun
bun run dev
```

The site will automatically reload when you make changes to the code.

## Building for Production

Build the application for production:

```bash
# npm
npm run build

# pnpm
pnpm build

# yarn
yarn build

# bun
bun run build
```

Locally preview the production build:

```bash
# npm
npm run preview

# pnpm
pnpm preview

# yarn
yarn preview

# bun
bun run preview
```

## Customization

### Styling

The project uses Tailwind CSS for styling. You can customize:

- **Colors**: Modify the color scheme in `app/app.vue` (currently uses indigo/blue theme)
- **Fonts**: Add custom fonts in `app/assets/css/main.css`
- **Layout**: Adjust spacing and layout in the Vue components

### Content

To customize the content:

1. **Navigation**: Edit the navigation links in the `<nav>` section of `app/app.vue`
2. **Hero Section**: Update the headline and description in the hero section
3. **Features**: Modify the three feature cards with your own content and icons
4. **About Section**: Replace the about content with your project information
5. **Footer**: Update footer links and company information

### Configuration

The Nuxt configuration can be modified in `nuxt.config.ts`:

```typescript
export default defineNuxtConfig({
  compatibilityDate: '2025-07-15',
  devtools: { enabled: true },
  modules: ['@nuxt/ui'],
  css: ['~/assets/css/main.css']
})
```

## Deployment

This Nuxt.js application can be deployed to various platforms:

- **Vercel**: Connect your GitHub repository for automatic deployments
- **Netlify**: Deploy with continuous deployment from Git
- **Cloudflare Pages**: Build and deploy with Cloudflare's edge network
- **Node.js Server**: Deploy to any Node.js hosting service

For more detailed deployment instructions, check out the [Nuxt deployment documentation](https://nuxt.com/docs/getting-started/deployment).

## Technology Stack

- [Nuxt.js 4](https://nuxt.com/) - The Vue.js Framework
- [Vue 3](https://vuejs.org/) - Progressive JavaScript Framework
- [Nuxt UI](https://ui.nuxt.com/) - UI component library
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [TypeScript](https://www.typescriptlang.org/) - Typed JavaScript

## Project Structure

```
al-test/
├── app/
│   ├── app.vue           # Main landing page component
│   ├── assets/           # CSS and static assets
│   │   └── css/
│   │       └── main.css  # Global styles
│   └── pages/            # Nuxt pages directory
│       └── index.vue     # Home page
├── public/               # Static files
│   ├── favicon.ico
│   └── robots.txt
├── nuxt.config.ts        # Nuxt configuration
├── package.json          # Dependencies and scripts
└── tsconfig.json         # TypeScript configuration
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Learn More

- [Nuxt Documentation](https://nuxt.com/docs) - Learn about Nuxt.js features and API
- [Nuxt UI Documentation](https://ui.nuxt.com/) - Explore the Nuxt UI component library
- [Vue.js Documentation](https://vuejs.org/) - Learn about Vue.js

## Support

For questions or issues, please open an issue in the GitHub repository.
