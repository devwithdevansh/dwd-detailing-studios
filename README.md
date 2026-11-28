# 🚗 DWD Detailing Studios — Orbitvale

A unified multi-brand automotive detailing showcase & design system, featuring **Kohinoor**, **Boond**, **Kavach**, and the interactive **Studio Catalog & Design Lab**.

🌐 **Live:** [car-detailing-by-dwd.onrender.com](https://car-detailing-by-dwd.onrender.com/)

---

## ✨ Included Sites & Routes

| Brand / Page | Route | Description |
| :--- | :--- | :--- |
| **Kohinoor** | `/` | Dark luxury detailing flagship with brass accents, heat-map gradient, and build configurator. |
| **Boond** | `/boond/` | Light editorial wash studio with scroll-driven squeegee interaction. |
| **Kavach** | `/kavach/` | Multi-studio ceramic & PPF network with interactive Leaflet studio locator. |
| **Catalog** | `/catalog/` | Overview of all studio design systems, palettes, and typography. |

---

## 🎨 Built-in Theme & Font Modifier

Every page includes a floating **Modify [DEV]** button in the top-right corner (shortcut: `Alt + M`):
- Switch color palettes & typography pairings in real time.
- Customize individual colors and Google Fonts.
- Export generated CSS tokens with one click.
- Append `?nomod=1` to any URL to hide the button for clean client previews.

---

## 🚀 Local Development

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build
```

---

## ☁️ Deployment (Render)

Configured via [`render.yaml`](./render.yaml) as a static site:
- **Build Command:** `npm install && npm run build`
- **Publish Directory:** `dist`
- **Root Directory:** *(leave blank)*
