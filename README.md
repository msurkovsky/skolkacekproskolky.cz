# Školkáček Landing Page

A modern, responsive landing page for Školkáček - a preschool management tool.

## 🌐 Languages

The landing page is available in two languages:
- **Czech** (default): `index.html`
- **English**: `index-en.html`

Language switcher is available in the header.

## 🚀 Deployment to GitHub Pages

This landing page is designed to be deployed as a static site on GitHub Pages.

### Setup Instructions

1. **Enable GitHub Pages** in your repository settings:
   - Go to Settings → Pages
   - Set Source to "Deploy from a branch"
   - Select the branch containing the `landing-page` folder
   - Set the folder to `/landing-page` (if using root, skip this)
   - Save the settings

2. **Configure Custom Domain** (optional):
   - Add a `CNAME` file with your domain name
   - Update your DNS settings to point to GitHub Pages

3. **Access your site**:
   - Default: `https://<username>.github.io/<repository-name>/`
   - With custom domain: `https://skolkacekproskolky.cz/`

## 📁 Structure

```
landing-page/
├── index.html         # Czech version (default)
├── index-en.html      # English version
├── style.css          # All styles and design system
├── assets/            # Images and icons
│   ├── bear_mascot_logo_*.png
│   ├── icon_time_saving_*.png
│   ├── icon_development_tracking_*.png
│   ├── icon_overview_*.png
│   ├── step_record_icon_*.png
│   ├── step_track_icon_*.png
│   └── step_report_icon_*.png
└── README.md          # This file
```

## 🎨 Design System

The page uses a soft, friendly color palette:
- **Primary Teal**: `#4DB8A8` - Main CTAs and accents
- **Accent Peach**: `#FFB88C` - Warm highlights
- **Accent Yellow**: `#FFD966` - Important CTAs
- **Accent Green**: `#7FC7AF` - Secondary elements
- **Accent Purple**: `#A393EB` - Charts and data

### Typography
- **Display Font**: Outfit (headings)
- **Body Font**: Inter (paragraphs)

## 📱 Responsive Design

The landing page is fully responsive and tested on:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

## 🔗 Links

All CTAs currently point to `https://skolkacek.app`. Update these in the HTML files if needed.

## 📧 Contact

- Email: martin.surkovsky@gmail.com
- LinkedIn: [linkedin.com/in/msurkovsky](https://linkedin.com/in/msurkovsky)

## 📝 License

Open source solution for preschools.

---

© 2024 Školkáček pro školky
