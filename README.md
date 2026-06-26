# S. Naganath Timber 🏠
### Premium Roofing & Building Materials — Paramakudi, Tamil Nadu

> A luxury single-page storefront with a fully featured hidden admin panel, powered by Supabase.

---

## 🖥️ Live Site

[https://sivasankar515.github.io/naganath_timber]()

---

## ✨ Features

### Storefront
- **Bilingual branding** — product names in English and Tamil (S.நாகநாத் டிம்பர்)
- **Animated ticker** — scrolling contact info, WhatsApp link, and promotions
- **Product catalog** with 6 category filter tabs:
  - Clay Tiles · White / Cool Tiles · Design / Jally Tiles
  - Sheets · Wood / Timber · Accessories
- **3D product cards** with auto-cycling multi-image slideshow and per-card share button
- **Product detail modal** — full image gallery with arrow navigation, spec table, WhatsApp enquiry & native share
- **About section** with founder photo from Supabase Storage
- **Google Maps embed** for in-store directions
- **Contact section** with one-tap WhatsApp CTA (+91 94434 65513)
- **Google Review popup** — rotating customer reviews, auto-shows every 2 minutes
- **Mobile-first responsive** layout with animated hamburger nav

### Admin Panel
- **Supabase Auth** login (email + password)
- **Add tab** — add or edit products:
  - English name + Tamil name
  - Category, badge tag, description
  - Up to 4 specification pairs
  - Multi-image drag-and-drop upload → Supabase Storage
- **Manage tab** — list all products with thumbnail, Edit ✏️ and Delete buttons
- **Real-time sync** — product grid updates instantly via Supabase `postgres_changes` subscription (no refresh needed)
- **Session timer** with idle-timeout warning and auto-logout
- Slide-in panel animation, scrollable content area

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Vanilla HTML · CSS · JavaScript (single file) |
| Database | Supabase PostgreSQL (`products` table) |
| Auth | Supabase Auth (email/password) |
| Storage | Supabase Storage (`product-images` bucket) |
| Realtime | Supabase `postgres_changes` channel |
| Fonts | Playfair Display · DM Sans (Google Fonts) |
| Hosting | Vercel (static) |

---

## 📁 Project Structure

```
/
└── index.html    # Entire application — HTML, CSS, and JS in one file
```



---

## 🎨 Design System

| Token | Value | Usage |
|---|---|---|
| `--clay` | `#c1440e` | Primary CTA, badges |
| `--gold` | `#d4a44c` | Headings, borders |
| `--wood` | `#7c4a1e` | Secondary elements |
| `--dark` | `#120b04` | Page background |
| `--cream` | `#faf5ee` | Body text |

**Typography:** Playfair Display (headings) + DM Sans (body)

---

## 📞 Business Contact

**S. Naganath Timber** · Since 1958 · Paramakudi, Tamil Nadu
📞 [+91 94434 65513](tel:+919443465513)
💬 [WhatsApp](https://wa.me/919443465513)
⭐ [Leave a Google Review](https://g.page/r/Ce2hhmKMF3nOEAE/review)

---

## 👨‍💻 Built by

**Siva** — MCA Student & Freelance Web Developer, Paramakudi
[GitHub](https://github.com/sivasankar515) · [LinkedIn](https://www.linkedin.com/in/siva-sankar-v-2a24ab292?utm_source=share_via&utm_content=profile&utm_medium=member_android)

---

## 📄 License

This project is built for **S. Naganath Timber** as a freelance project.
Not licensed for redistribution or reuse without permission.
