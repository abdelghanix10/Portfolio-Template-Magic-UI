<div align="center">
  <h1>✨ Portfolio Template - Magic UI</h1>
  <p>A beautiful, modern portfolio template built with Next.js, Magic UI, and shadcn/ui</p>
  
  <p>
    <a href="#features"><strong>Features</strong></a> ·
    <a href="#getting-started"><strong>Getting Started</strong></a> ·
    <a href="#customization"><strong>Customization</strong></a> ·
    <a href="#deployment"><strong>Deployment</strong></a>
  </p>
</div>

---

## 🚀 Features

- ⚡ **Next.js 14** - Built on the latest Next.js with App Router
- 🎨 **Magic UI Components** - Beautiful animated components (blur fade, dock, and more)
- 🧩 **shadcn/ui** - High-quality, accessible UI components
- 📝 **MDX Blog** - Write blog posts in Markdown with React components
- 🌙 **Dark Mode** - Built-in theme switching with next-themes
- 📱 **Fully Responsive** - Looks great on all devices
- 🎭 **Framer Motion** - Smooth animations and transitions
- 💅 **Tailwind CSS** - Utility-first CSS framework
- 📊 **TypeScript** - Full type safety throughout

## 📦 Tech Stack

| Category      | Technologies                      |
| ------------- | --------------------------------- |
| Framework     | Next.js 14, React 18              |
| Styling       | Tailwind CSS, tailwindcss-animate |
| UI Components | shadcn/ui, Radix UI, Magic UI     |
| Animations    | Framer Motion                     |
| Blog          | MDX, rehype-pretty-code, Shiki    |
| Language      | TypeScript                        |

## 🛠️ Getting Started

### Prerequisites

- Node.js 18+
- pnpm (recommended) or npm/yarn

### Installation

1. **Clone the repository**

   ```bash
   git clone <your-repo-url>
   cd portfolio-template-magic-ui
   ```

2. **Install dependencies**

   ```bash
   pnpm install
   ```

3. **Start the development server**

   ```bash
   pnpm dev
   ```

4. **Open your browser**

   Navigate to [http://localhost:3000](http://localhost:3000)

## ⚙️ Customization

### Personal Information

All your personal data is centralized in a single config file:

📄 **[src/data/resume.tsx](./src/data/resume.tsx)**

Update this file to customize:

- **Basic Info**: Name, initials, location, description
- **Skills**: Your technical skills
- **Work Experience**: Job history with descriptions
- **Education**: Academic background
- **Projects**: Portfolio projects with links
- **Hackathons**: Competition achievements
- **Social Links**: GitHub, LinkedIn, Twitter, etc.

### Blog Posts

Add new blog posts by creating `.mdx` files in the `content/` directory:

```
content/
  └── my-new-post.mdx
```

Each post should include frontmatter:

```mdx
---
title: "My Blog Post"
publishedAt: "2024-01-01"
summary: "A brief description of the post"
---

Your content here...
```

### Styling

- **Global styles**: `src/app/globals.css`
- **Tailwind config**: `tailwind.config.ts`
- **Component styles**: Individual component files in `src/components/`

### Components

| Component            | Description                       |
| -------------------- | --------------------------------- |
| `blur-fade.tsx`      | Animated fade-in with blur effect |
| `blur-fade-text.tsx` | Text animation with blur fade     |
| `dock.tsx`           | macOS-style dock navigation       |
| `navbar.tsx`         | Top navigation bar                |
| `project-card.tsx`   | Project showcase cards            |
| `resume-card.tsx`    | Work experience cards             |
| `hackathon-card.tsx` | Hackathon achievement cards       |

## 📜 Available Scripts

| Command      | Description              |
| ------------ | ------------------------ |
| `pnpm dev`   | Start development server |
| `pnpm build` | Build for production     |
| `pnpm start` | Start production server  |
| `pnpm lint`  | Run ESLint               |

## 🚀 Deployment

This template can be deployed on any platform that supports Next.js:

- **Netlify**: Use the Next.js adapter
- **Railway**: Connect your GitHub repo
- **Docker**: Use the included Next.js production build

## 📁 Project Structure

```
├── content/              # MDX blog posts
├── public/               # Static assets (images, icons)
├── src/
│   ├── app/              # Next.js App Router pages
│   │   ├── blog/         # Blog pages
│   │   ├── globals.css   # Global styles
│   │   ├── layout.tsx    # Root layout
│   │   └── page.tsx      # Home page
│   ├── components/       # React components
│   │   ├── magicui/      # Magic UI components
│   │   └── ui/           # shadcn/ui components
│   ├── data/             # Data and configuration
│   │   ├── resume.tsx    # Personal info config
│   │   └── blog.ts       # Blog utilities
│   └── lib/              # Utility functions
├── tailwind.config.ts    # Tailwind configuration
└── package.json          # Dependencies and scripts
```

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

---

<div align="center">
  <p>Built with ❤️ using Next.js and Magic UI</p>
</div>
