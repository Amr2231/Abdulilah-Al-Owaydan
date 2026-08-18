# Abdulilah Al-Owaydan | Workforce Solutions Website

A multi-page, bilingual (Arabic/English) corporate website for **Abdulilah Al-Owaydan Company**, a Riyadh-based workforce solutions provider serving the hotel, healthcare, and corporate sectors since 1999.

🔗 **Live site:** [ealowedan.com](https://ealowedan.com)

## About

Abdulilah Al-Owaydan Company has supplied skilled, legally compliant manpower to the Saudi hospitality, healthcare, and corporate sectors for over 25 years. This repository contains the company's official marketing website — a fast, fully responsive, RTL/LTR-aware static site built to present the company's story, services, and legal compliance standards, and to make it easy for potential clients and partners to get in touch.

## ✨ Features

- **Bilingual UI (AR/EN)** — full right-to-left (Arabic) and left-to-right (English) layout switching, powered by a lightweight custom i18n system in `js/main.js`
- **Responsive, mobile-first design** built with [Tailwind CSS](https://tailwindcss.com/)
- **Custom Arabic typography** using the "Year of Handicrafts" font family alongside Public Sans for English
- **Image/logo carousel** for client showcases (Embla-style carousel)
- **Dedicated pages** for Home, About, Services, and Contact
- **SEO-ready** — descriptive meta tags, Open Graph tags, and canonical URLs

## 🗂️ Project Structure

```
├── index.html          # Home page
├── about.html           # About Us page
├── services.html         # Services page
├── contact.html          # Contact page
├── css/
│   ├── input.css        # Tailwind source
│   ├── output.css       # Compiled Tailwind CSS
│   └── theme.css         # Brand colors & theme variables
├── js/
│   └── main.js           # i18n system, carousel logic, interactions
├── fonts/                # Custom Arabic & Latin typefaces
└── images/               # Site imagery, client logos, gallery
```

## 🛠️ Tech Stack

- HTML5
- [Tailwind CSS](https://tailwindcss.com/)
- Vanilla JavaScript (no framework — custom i18n & carousel logic)
- Google Fonts (Public Sans) + self-hosted Arabic font family

## 🚀 Getting Started

This is a static site, so there's no build step required to view it.

1. Clone the repository
   ```bash
   git clone https://github.com/Amr2231/Abdulilah-Al-Owaydan.git
   ```
2. Open `index.html` directly in your browser, **or** serve it locally:
   ```bash
   npx serve .
   ```

### Rebuilding the CSS (optional)

The compiled styles live in `css/output.css`. If you edit `css/input.css` and have the Tailwind CLI installed:

```bash
npx tailwindcss -i ./css/input.css -o ./css/output.css --watch
```

## 📄 Pages

| Page | Description |
|---|---|
| `index.html` | Landing page — hero, services overview, client carousel |
| `about.html` | Company story, experience stats, legal compliance highlights |
| `services.html` | Detailed breakdown of workforce solutions offered |
| `contact.html` | Contact information and inquiry form |

## 📬 Contact

For business inquiries, please reach out through the [contact page](https://ealowedan.com) on the live site.

---

<sub>Built with care for Abdulilah Al-Owaydan Company.</sub>
