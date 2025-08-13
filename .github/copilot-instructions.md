<!-- Use this file to provide workspace-specific custom instructions to Copilot. For more details, visit https://code.visualstudio.com/docs/copilot/copilot-customization#_use-a-githubcopilotinstructionsmd-file -->

# DevPortfolio Template - Copilot Instructions

This is a modern developer portfolio template built with Astro and Tailwind CSS v4.

## Project Structure
- Built with **Astro** - A modern static site generator
- Styled with **Tailwind CSS v4** - Utility-first CSS framework
- Uses **TypeScript** for type-safe configuration
- Icons from **Tabler Icons**

## Key Files
- `src/config.ts` - Main configuration file for personal information, skills, projects, experience, and education
- `src/pages/index.astro` - Main homepage
- `src/components/` - Reusable Astro components
- `src/layouts/` - Layout templates

## Development Guidelines
- The template is designed to be easily customizable through the `src/config.ts` file
- Changing the accent color in config will update the theme site-wide
- Sections (skills, projects, experience, education) are automatically hidden if removed from config
- All styling uses Tailwind CSS utility classes
- Components are built as Astro components (.astro files)
- Images should be placed in the `public/` directory

## Common Tasks
- **Customizing content**: Edit `src/config.ts`
- **Adding new sections**: Create new components and update the main page
- **Styling changes**: Use Tailwind CSS classes
- **Adding images**: Place in `public/` directory and reference in config

## Available Scripts
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
