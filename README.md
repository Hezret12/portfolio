## 📂 Project Structure

```
portfolio/
├── src/
│   ├── app/
│   │   ├── globals.css         # Global styles and animations
│   │   ├── layout.tsx          # Root layout with metadata
│   │   ├── page.tsx            # Main portfolio page
│   │   ├── favicon.ico         # Site favicon
│   │   └── favicon.png         # PNG favicon
│   ├── components/
│   │   ├── portfolio/          # Portfolio-specific components
│   │   │   ├── AboutSection.tsx
│   │   │   ├── Background.tsx
│   │   │   ├── CertificationsSection.tsx
│   │   │   ├── ContactSection.tsx
│   │   │   ├── ExperienceSection.tsx
│   │   │   ├── Footer.tsx
│   │   │   ├── HeroSection.tsx
│   │   │   ├── Navigation.tsx
│   │   │   ├── OverviewSection.tsx
│   │   │   ├── ProjectsSection.tsx
│   │   │   ├── SectionHeader.tsx
│   │   │   ├── TechStackSection.tsx
│   │   │   ├── TestimonialsSection.tsx
│   │   │   ├── TypewriterRole.tsx
│   │   │   └── index.ts        # Component exports
│   │   ├── AnimatedBackground.tsx
│   │   ├── PostHogProvider.tsx # Analytics provider
│   │   ├── SocketioIcon.tsx
│   │   ├── ThemeProvider.tsx   # Theme context provider
│   │   └── ThemeToggle.tsx     # Dark/light theme toggle
├── lib/
│   ├── posthog.ts             # PostHog analytics configuration
│   └── utils.ts               # Utility functions
├── public/
│   ├── certificates/          # Certificate images
│   ├── CV.pdf                # Resume/CV file
│   ├── globe.svg             # SVG icons
│   ├── next.svg
│   ├── vercel.svg
│   ├── window.svg
│   └── file.svg
├── .env                      # Environment variables
├── .gitignore               # Git ignore rules
├── eslint.config.mjs        # ESLint configuration
├── next.config.ts           # Next.js configuration
├── next-env.d.ts           # Next.js TypeScript declarations
├── package.json            # Dependencies and scripts
├── package-lock.json       # Locked dependency versions
├── postcss.config.mjs      # PostCSS configuration
├── tailwind.config.js      # Tailwind CSS configuration
├── tsconfig.json          # TypeScript configuration
└── README.md              # This file
```

=

## 📱 Browser Support

- ✅ Chrome (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Edge (Latest)
- ✅ Mobile browsers

## 🔧 Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Framer Motion** - Amazing animation library
- **Tailwind CSS** - Utility-first CSS framework
- **Next.js Team** - Excellent React framework
- **Iconify** - Beautiful icon library

---


_This portfolio demonstrates modern web development practices and showcases the beauty of well-crafted user interfaces._
