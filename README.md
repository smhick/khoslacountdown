# 🎂 November 24 Birthday Countdown

A personalized birthday countdown web app celebrating November 24 across both **New Delhi (IST)** and **Amsterdam (CET)**, complete with live timezone clocks and a vintage childhood keepsake gallery.

## ✨ Features

- **Three Synchronized Countdowns:**
  - **00:00 Delhi Time (IST):** When November 24 officially begins in New Delhi (`UTC+5:30`).
  - **05:40 AM Delhi Time (IST):** Counting down to the exact moment she was born in New Delhi.
  - **00:00 Amsterdam Time (CET):** When November 24 begins at home in Amsterdam (`UTC+1`).
- **Live Dual-City Clocks:** Real-time clocks displaying the current time in both New Delhi and Amsterdam.
- **Childhood Keepsake Gallery:** Vintage polaroid-style photo frames with interactive full-screen lightbox viewing.
- **Interactive Celebration:** Built-in name customization and a celebratory confetti burst.

## 🚀 Hosting on GitHub Pages

1. **Upload the Files:**
   - Place `index.html` in the root of your repository.
   - Ensure the three image files are placed in the same directory (or update the `src` paths in `index.html` to match your folder structure, such as `images/photo1.jpg`).
2. **Enable GitHub Pages:**
   - Go to your repository's **Settings** → **Pages**.
   - Under **Build and deployment**, select **Deploy from a branch**.
   - Choose your main branch (`main` or `master`) and select the `/ (root)` folder, then click **Save**.
3. **Access Your Site:**
   - After a minute or two, your live countdown page will be available at `https://<your-username>.github.io/<your-repo-name>/`.

## 🛠️ Built With

- **HTML5 & CSS3** — Responsive layout, custom CSS variables, and smooth transitions.
- **Vanilla JavaScript** — Precision `Intl.DateTimeFormat` timezone calculations and real-time countdown timers with zero external dependencies.
