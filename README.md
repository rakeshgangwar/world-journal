# World Journal

A minimalist blog and portfolio site built with Astro, featuring a clean design with light/dark modes and dynamic content management through TinaCMS.

## 🚀 Features

- ⚡️ Built with Astro for blazing-fast performance
- 🌗 Light/Dark mode with smooth transitions
- 📝 Markdown & MDX support for content
- 🎨 Tailwind CSS for styling
- 🔍 Search functionality
- 📱 Fully responsive design
- ✍️ TinaCMS integration for content management
- 🔄 Dynamic blog post filtering
- 🌟 Animated backgrounds (particles in light mode, stars in dark mode)

## 🛠️ Tech Stack

- [Astro](https://astro.build)
- [TinaCMS](https://tina.io)
- [Tailwind CSS](https://tailwindcss.com)
- [SolidJS](https://www.solidjs.com)
- [TypeScript](https://www.typescriptlang.org)

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/world-journal.git
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
Create a `.env.local` file with the following:
```
NEXT_PUBLIC_TINA_CLIENT_ID=your_tina_client_id
TINA_TOKEN=your_tina_token
TINA_PUBLIC_IS_LOCAL=true
GITHUB_BRANCH=your_branch_name
```

4. Start the development server:
```bash
npm run dev
```

## 🧞 Commands

| Command                   | Action                                           |
| :----------------------- | :----------------------------------------------- |
| `npm install`            | Installs dependencies                            |
| `npm run dev`            | Starts local dev server at `localhost:4321`      |
| `npm run dev:network`    | Starts dev server accessible on local network    |
| `npm run build`          | Build your production site to `./dist/`          |
| `npm run preview`        | Preview your build locally                       |
| `npm run preview:network`| Preview build on local network                   |
| `npm run lint`          | Run ESLint                                       |
| `npm run lint:fix`      | Fix ESLint issues                                |

## 📁 Project Structure

```text
/
├── public/              # Static assets
├── src/
│   ├── components/      # UI components
│   ├── content/         # Blog posts and other content
│   ├── layouts/         # Page layouts
│   ├── pages/          # Route components
│   ├── styles/         # Global styles
│   ├── lib/           # Utility functions
│   ├── consts.ts      # Site configuration
│   └── types.ts       # TypeScript types
└── package.json
```

## 📝 Content Management

Content can be managed through:
1. Direct markdown/MDX files in the `src/content` directory
2. TinaCMS admin interface at `/admin` (when configured)

## 🎨 Customization

1. Site configuration: Edit `src/consts.ts`
2. Styling: Modify `src/styles/global.css` and Tailwind config
3. Layout: Update components in `src/layouts`
4. Content: Add/edit files in `src/content`

## 📄 License

[MIT License](LICENSE)

## 👥 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.