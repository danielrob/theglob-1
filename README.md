# The Glob

Rural Health Checks by NZ Lions - Bringing health screening to farming communities across New Zealand.

🔗 **Live Site**: https://www.theglob.co.nz

## 🚀 Migration Strategy: Static HTML → Astro

This project migrates the original static HTML site to a modern Astro build for better maintainability, performance, and future enhancements.

### Current Status

✅ **Completed**:
- [x] Astro project scaffolded
- [x] All 8 pages migrated with content
- [x] Responsive layout with navigation
- [x] GitHub repo created and pushed
- [x] Clean, maintainable component structure

### Site Structure

```
src/
├── layouts/
│   └── Layout.astro          # Main page layout with nav/footer
└── pages/
    ├── index.astro           # Home / Rural Health Checks
    ├── the-glob.astro        # About The Glob
    ├── health-check.astro    # Health Check details
    ├── events.astro          # Events calendar (2022-2025)
    ├── sponsors.astro        # Sponsors & supporters
    ├── deanwilliamson.astro  # Dean's story
    ├── contact.astro         # Contact information
    └── confirmation.astro    # Form confirmation (placeholder)
```

### What's Been Migrated

| Original Page | Astro Page | Status |
|--------------|------------|--------|
| index.html | index.astro | ✅ Complete |
| the-glob.html | the-glob.astro | ✅ Complete |
| health-check.html | health-check.astro | ✅ Complete |
| events.html | events.astro | ✅ Complete |
| sponsors.html | sponsors.astro | ✅ Complete |
| deanwilliamson.html | deanwilliamson.astro | ✅ Complete |
| contact.html | contact.astro | ✅ Complete |
| confirmation.html | confirmation.astro | ✅ Complete |

### Next Steps

To complete the migration and deploy:

1. **Images/Assets**: 
   - Download original images from theglob.co.nz
   - Place in `public/` folder
   - Update image references in pages

2. **Styling Polish**:
   - Match original site's exact colors/fonts if needed
   - Add any missing visual elements

3. **Forms** (if applicable):
   - Contact forms may need third-party service (Netlify Forms, Formspree, etc.)

4. **Build & Deploy**:
   ```bash
   npm run build
   # Deploy dist/ folder to your hosting provider
   ```

### Development

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

### Tech Stack

- **Framework**: [Astro](https://astro.build)
- **Styling**: Scoped CSS in components + global styles
- **No JavaScript framework**: Keeping it lightweight with vanilla JS

---

Built with 💚 for rural communities by Lions District 202D Zone 1
