# HH Goa 2026 · Frame & ID Generator

> Build your branded HH Goa 2026 PFP or Builder ID Card in seconds – fully client-side, zero uploads, no sign-up.

![Screenshot](https://via.placeholder.com/800x400?text=HH+Goa+2026+Generator+Preview)  
*(Replace with a live screenshot or GIF)*

## 🚀 Overview

This is a **high-performance, single‑page web application** that lets you upload a photo and instantly generate two branded graphic formats for the **HH Goa 2026** event:

- **Format A – PFP Frame / Overlay** (1:1 square) – perfect for X (Twitter) profile pictures. Choose from four tropical cyberpunk themes, add sticker overlays and filters, and drag/zoom your photo for perfect framing.
- **Format B – Builder ID Card** (3:4 Portrait or 16:9 Landscape) – a professional event badge with your photo, name, X handle, tech stack pills, a custom builder title, and a QR code that you can personalise.

All processing happens **entirely in your browser** – your images are never uploaded to any server, and you don’t need to create an account.

## ✨ Features

- **Zero‑login, zero‑upload** – complete privacy, instant rendering
- **Dual format support** – switch between PFP and ID Card modes with one click
- **Drag‑and‑drop photo upload** – supports JPG, PNG, WebP, and iPhone HEIC (auto‑converted)
- **Real‑time preview** – see changes instantly as you adjust settings
- **Interactive canvas** – drag to pan and scroll to zoom your photo
- **PFP themes** – Goa Sunset, Cyber Neon, Golden Elite, Minimal Dark – each with unique gradients, rings, and decorative elements
- **Sticker overlays** – add emojis (Sun, Bolt, Star, Wave)
- **Filter effects** – Warm, Neon, Vintage
- **Builder ID Card** – fully customisable fields: name, handle, stack/role, title, QR data
- **“Magic” title generator** – get a random fun builder persona (20+ options like *GPU Whisperer*, *10x Ship Machine*)
- **Export options** – download as PNG or JPG with 1×, 2×, or 4× DPI for crisp outputs
- **Copy to clipboard** – copy the generated image directly
- **Share to X (Twitter)** – opens a pre‑filled tweet with a link
- **Responsive design** – works on desktop, tablet, and mobile

## 🖥️ Live Demo

You can try the generator right away by opening the `index.html` file in your browser – no installation required.

## 📦 Installation & Local Development

Since the application is a single HTML file with all CSS and JavaScript embedded, you can simply:

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/hh-goa-2026-generator.git
   cd hh-goa-2026-generator
   ```

2. **Open in your browser**
   - Double‑click `index.html` – it works offline (except for external CDN resources like fonts and libraries).  
   - Or use a local static server for the best experience (e.g., VS Code Live Server, Python `http.server`, or Node.js `http-server`).

   If you prefer the included Node.js server (optional):
   ```bash
   node server.js
   ```
   Then visit `http://localhost:3000`.

> **Note:** The app loads fonts and libraries (Font Awesome, heic2any, QRCode.js) from CDNs – an internet connection is required for those.

## 🛠️ Technology Stack

- **HTML5 / CSS3** – semantic markup, glassmorphism UI, custom HSL theming
- **JavaScript (ES6)** – all application logic, Canvas rendering, event handling
- **Canvas API** – high‑performance graphics with super‑sampling (1×, 2×, 4× DPI)
- **heic2any** – converts HEIC images from iPhones to PNG automatically
- **QRCode.js** – generates QR codes dynamically on the ID card
- **Font Awesome** – icons
- **Google Fonts** – Inter (sans‑serif) and Orbitron (display)

## 📸 How to Use

1. **Upload a photo** – drag & drop or click the drop zone. The app accepts JPG, PNG, WebP, and HEIC.
2. **Choose your format** – switch between **PFP** and **ID Card** using the toggle at the top.
3. **Customise**:
   - *PFP mode*: pick a theme, sticker, and filter.
   - *ID Card mode*: fill in your name, handle, stack, title, and QR data. Click the **Magic** button for a random title.
4. **Interact with the preview** – drag to pan and scroll to zoom the photo (works on both mouse and touch).
5. **Export** – click **PNG** or **JPG** to download, **Copy** to copy to clipboard, or **Share** to post to X.

## 📁 Project Structure

```
hh-goa-2026-generator/
├── index.html          # The entire application (HTML, CSS, JS)
├── server.js           # Optional Node.js static server (uses built‑in http module)
└── README.md           # This file
```

*(All code is self‑contained in `index.html` – no external files needed.)*

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues or pull requests for improvements, bug fixes, or new features.

## 📄 License

This project is open‑source and available under the **MIT License**.

---

Made with ❤️ for the HH Goa 2026 builder community.  
*All processing is client‑side – your data stays with you.*
