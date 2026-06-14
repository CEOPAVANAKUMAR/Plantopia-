# 🌿 Plantopia — Grow Your World

A beautiful, fully functional **plant store website** built with pure HTML, CSS, and JavaScript. No frameworks, no backend, no database needed — runs entirely in the browser!

---

## ✨ Features

- 🛍️ Product listing with category filters (Indoor, Outdoor, Succulents, Flowering)
- 💬 WhatsApp ordering — customers tap "Order" and message you directly
- 📸 Admin panel to add/edit/delete plants with photo upload
- 🏷️ Badges — Bestseller, New Arrival, Limited, Sale
- 📱 Fully responsive — works on mobile, tablet, and desktop
- 💾 Data saved in browser `localStorage` — no server needed
- 🎨 Elegant dark gold theme with animations
- 🔐 Password-protected admin panel
- 🚀 Scrolling ticker, floating WhatsApp button, hero section

---

## 🗂️ Folder Structure

```
plantopia/
├── index.html       ← the entire website (single file)
└── README.md
```

> Everything — HTML, CSS, and JavaScript — is in one single `index.html` file.

---

## 🚀 How to Use

**1. Clone the repo**
```bash
git clone https://github.com/YOUR_USERNAME/plantopia.git
```

**2. Open the website**

Just double-click `index.html` — opens in any browser. No server needed!

**3. Set your WhatsApp number**

- Open the site in browser
- Scroll to footer → click **⚙ Admin Panel**
- Default password: `plantopia123`
- Go to **Settings** → enter your WhatsApp number with country code
  - Example for India: `919876543210`
- Click **Save WhatsApp**

**4. Add your plants**

- Open Admin Panel → **Add Plant** tab
- Fill in name, price, category, description
- Upload photos (up to 5 per plant)
- Click **Add Plant to Store**

---

## 🖥️ Admin Panel

Access it from the footer → **⚙ Admin Panel**

| Tab | What you can do |
|---|---|
| ➕ Add Plant | Add new plants with photos, price, badge, category |
| 📋 Manage | Edit or delete existing plants |
| ⚙ Settings | Set WhatsApp number, delivery threshold, change password |

**Default password:** `plantopia123`
> ⚠️ Change it immediately from Settings after first login!

---

## 📱 How Ordering Works

1. Customer clicks **"Order"** on any plant
2. WhatsApp opens with a pre-filled message (plant name + price)
3. Customer sends it to your number
4. You confirm and process the order manually

No payment gateway needed — pure WhatsApp-based ordering!

---

## ⚙️ Quick Customization

Open `index.html` and find this line near the top of the `<script>` section:

```javascript
const WA_DEFAULT = '919566670218'; // ← Replace with your WhatsApp number
```

Change colors by editing CSS variables at the top:
```css
:root {
  --gold: #C9A84C;   /* accent color */
  --dk:   #080B0D;   /* background   */
  --gr2:  #2D6B25;   /* ticker color */
}
```

---

## 💾 Data Storage

All plant data is saved in the browser's `localStorage`:

- ✅ Works without any server or database
- ✅ Data persists after closing the browser
- ⚠️ Data is per browser/device — not synced across devices
- ⚠️ Clearing browser data resets plants to sample defaults

---

## 🌐 Free Hosting Options

| Platform | Steps |
|---|---|
| **GitHub Pages** | Push repo → Settings → Pages → Deploy from `main` |
| **Netlify** | Drag & drop `index.html` at netlify.com/drop |
| **Vercel** | Connect GitHub repo → auto deploy |

---

## 🛠️ Built With

- Pure HTML5, CSS3, Vanilla JavaScript
- Google Fonts — Cormorant Garamond + DM Sans
- localStorage for data persistence
- WhatsApp Click-to-Chat API for ordering

---

## 📄 License

MIT License — free to use, modify, and deploy for your business.
