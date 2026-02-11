# Task Command Center

A beautiful, fast daily task dashboard for Chief of Staff workflow.

## Live Demo
**[View Live →](https://task-command-center.pages.dev)** *(deploy manually)*

## Features

- ✨ **Beautiful dark UI** with gradient backgrounds and smooth animations
- 📝 **Add tasks** with P0-P3 priority levels
- ✅ **One-click complete** with confetti celebration
- 📊 **Live stats** showing total/active/completed tasks
- 📈 **Progress bar** tracking daily completion rate
- 🔍 **Filter tasks** by All/Active/Completed
- 💾 **LocalStorage persistence** — tasks survive refresh
- 📱 **Fully responsive** — works on mobile and desktop

## Screenshots

*(Add screenshots after deployment)*

## Tech Stack

- Pure HTML5, CSS3, Vanilla JavaScript
- No build step, no dependencies
- Framer Motion-style animations via CSS
- Cloudflare Pages ready

## Development

```bash
# Local development
npx serve .

# Or simply open index.html in browser
```

## Deployment

### Cloudflare Pages
```bash
# Install wrangler
npm install -g wrangler

# Login to Cloudflare
wrangler login

# Deploy
wrangler pages deploy . --project-name=task-command-center
```

### GitHub Pages
Push to `gh-pages` branch or enable Pages in repo settings.

## Changelog

### v1.0.0 (2026-02-12)
- Initial release
- Task CRUD with priorities
- Stats dashboard
- Progress tracking
- Confetti on complete

## Roadmap

- [ ] Notion API integration (sync tasks)
- [ ] Due dates and reminders
- [ ] Drag-and-drop reordering
- [ ] Keyboard shortcuts (⌘+N new task, ⌘+K command palette)
- [ ] Export to CSV/Notion

## License

MIT