# Next.js SEO Blog Starter

A clean blog starter built with Next.js 14 and TypeScript. Ready to deploy and easy to customize.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/GanLiuuuu/nextjs-seo-blog-starter)

## Preview

![Home Page](public/images/home.png)
*Home page with featured posts and tag filtering*

![Post Page](public/images/post.png)
*Individual post page with responsive typography*

![404 Page](public/images/404.png)
*Custom 404 page with a clean design*

## Features

- Next.js 14 with App Router
- SEO metadata and OpenGraph tags
- Responsive design with Tailwind CSS
- Write posts in Markdown
- Tag system for organizing content
- Analytics support
- Custom 404 page
- Mobile-friendly

## Quick Start

### Deploy on Vercel

1. Click the "Deploy with Vercel" button above
2. Follow the setup steps
3. Done!

### Local Development

```bash
# Clone the repository
git clone https://github.com/GanLiuuuu/nextjs-seo-blog-starter.git my-blog

# Navigate to the directory
cd my-blog

# Install dependencies
npm install

# Start the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
nextjs-seo-blog-starter/
├── app/                   # Next.js 14 app directory
│   ├── page.tsx          # Home page
│   ├── posts/            # Post pages
│   └── not-found.tsx     # Custom 404 page
├── components/           # Reusable React components
├── content/             # Blog posts in markdown
├── lib/                 # Utility functions and data fetching
├── public/              # Static assets
│   └── images/          # Images including previews
└── styles/              # Global styles and Tailwind config
```

## Writing Content

Create new blog posts by adding markdown files to the `content/posts` directory:

```markdown
---
title: "My First Blog Post"
date: "2024-01-01"
tags: ["nextjs", "react"]
excerpt: "A brief description of your post"
coverImage: "/images/posts/my-first-post.jpg"  # Optional cover image
---

Your content here...
```

## Customization

### Styling

Uses Tailwind CSS. Customize by editing:

- `tailwind.config.js` - Colors, fonts, etc.
- `styles/globals.css` - Global styles
- Component files for specific styling

### Metadata

Update site metadata in `app/layout.tsx`:

```typescript
export const metadata = {
  title: 'Your Blog Name',
  description: 'Your blog description',
  // ... other metadata
}
```

## Dependencies

- [Next.js 14](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [React](https://reactjs.org/)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

MIT License

## Support

If you find this template helpful, please consider giving it a ⭐️ on GitHub!
