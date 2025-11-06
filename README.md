⚡ Lightweight & 2G-Friendly Portfolio
Fast, even on 2G.
This portfolio is engineered to deliver critical content under ~14kB so it can load in a single TCP slow start window, making it blazing fast even on slow mobile networks. Built with a modern, lightweight stack for performance, maintainability, and developer joy.

✨ Features
Blazing Fast Performance – Optimized to fit critical render under ~14kB for instant load on low-bandwidth connections, powered by Preact and Vite.

SEO Optimized – Rich metadata and JSON-LD schema for search engine visibility.

Fully Responsive – Smooth experience across all screen sizes, from desktop monitors to small smartphones.

Modern Tech Stack – Minimal yet powerful frontend tooling for a robust and maintainable codebase.

🌍 Why 2G-Friendly?
Most websites send too much data up front, causing delays on slow connections.
By keeping my critical render payload under 14kB, the entire initial page fits into the first TCP slow start burst (about 10 packets).

That means:

1 round trip to render above-the-fold content.

612ms+ faster load time on 2G compared to typical pages.

Accessible to recruiters, clients, and friends anywhere — even with limited connectivity.

🛠️ Technical Stack
Built with performance, accessibility, and developer experience in mind:

Framework: Preact — A fast, ~3kB alternative to React with the same modern API.

Build Tool: Vite — frontend tooling for instant dev server startup and lightning-fast builds.

Language: TypeScript — Strong typing for safer and more maintainable code.

Styling: Tailwind CSS — Utility-first CSS framework for rapid UI creation.

Helpers: clsx + tailwind-merge — Clean, conflict-free class name management.

Animations: tailwindcss-animate — Composable CSS animations with zero runtime overhead.

Routing: React Router DOM — Declarative SPA navigation.

Linting: ESLint — Enforces consistent coding style and catches issues early.

📦 Performance Highlights
Metric	Result
Critical payload size	~13.9kB
First render on 2G	~1s faster than typical
HTTP requests on load	1 (HTML only)
Lighthouse Performance	100/100

🔗 Live Demo
View Portfolio

📜 License
MIT License — free to use, adapt, and share.
