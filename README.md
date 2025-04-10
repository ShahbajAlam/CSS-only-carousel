# 🎠 CSS-Only Carousel — No JavaScript Needed!

What if I told you this fully interactive **carousel** runs on *zero lines of JavaScript*? That's right — all the scrolling, snapping, and clickable navigation is powered purely by **HTML + CSS** ✨

This project uses modern CSS features like:

- **`scroll-snap-type`** — to snap slides into perfect position
- **`::scroll-marker-group`** — a container that auto-generates scroll markers
- **`::scroll-marker`** — clickable thumbnail markers to jump between slides

---

## 💡 Features

### 🔁 Smooth Snapping with `scroll-snap-type`
Each slide "locks" into place horizontally as the user scrolls — creating a sleek, app-like experience with zero JS.

### 🎯 Visual Navigation with `::scroll-marker-group`
This experimental pseudo-element automatically creates a group of clickable markers linked to each carousel item.

### 🖼️ Thumbnail Markers using `::scroll-marker`
Each slide defines its own mini-thumbnail using `background-image`. Clicking on any thumbnail scrolls directly to the respective slide — super intuitive and smooth.

---

📸 Demo
[css-only-carousel.mp4](https://shorturl.at/VUEk9)

---

🧪 Browser Compatibility

| Feature	| Supported In |
| --- | --- |
| scroll-snap-type	| ✅ Chrome, Firefox, Safari |
| ::scroll-marker	| ⚠️ Experimental (try in Canary) |
| ::scroll-marker-group	| ⚠️ Experimental (try in Canary) |

---

🛠️ Built With

* HTML5
* CSS3 (with experimental scroll-linked marker support)
* Zero JavaScript

---

📎 Credits
Product images from Flipkart (used for demonstration purposes only)

📄 License
This project is open-source and available under the MIT License.
