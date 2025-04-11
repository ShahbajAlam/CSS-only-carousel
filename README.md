# 🎠 CSS-Only Carousel — No JavaScript Needed!

What if I told you this fully interactive **carousel** runs on *zero lines of JavaScript*? That's right — all the scrolling, snapping, and clickable navigation is powered purely by **HTML + CSS** ✨

This project uses modern CSS features like:

- **`scroll-snap-type`** — to snap slides into perfect position
- **`::scroll-marker-group`** — a container that auto-generates scroll markers
- **`::scroll-marker`** — clickable thumbnail markers to jump between slides

---

### 💡 Features

#### 🔁 Smooth Snapping with `scroll-snap-type`
Each slide "locks" into place horizontally as the user scrolls — creating a sleek, app-like experience with zero JS.

#### 🎯 Visual Navigation with `::scroll-marker-group`
This experimental pseudo-element automatically creates a group of clickable markers linked to each carousel item.

#### 🖼️ Thumbnail Markers using `::scroll-marker`
Each slide defines its own mini-thumbnail using `background-image`. Clicking on any thumbnail scrolls directly to the respective slide — super intuitive and smooth.

---

### 📸 Demo

[](https://github-production-user-asset-6210df.s3.amazonaws.com/58190404/432664595-de4fca3e-a37f-4ade-b026-d54b038e5a4c.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20250411%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250411T082017Z&X-Amz-Expires=300&X-Amz-Signature=e5185a8f1308ba251b4c0866566cd612493527d4af57d3865f8fb7f71cc431cb&X-Amz-SignedHeaders=host)

---

### 🧪 Browser Compatibility

| Feature	| Supported In |
| --- | --- |
| scroll-snap-type	| ✅ Chrome, Firefox, Safari |
| ::scroll-marker	| ⚠️ Experimental (try in Canary) |
| ::scroll-marker-group	| ⚠️ Experimental (try in Canary) |

---

### 🛠️ Built With

* HTML5
* CSS3 (with experimental scroll-linked marker support)
* Zero JavaScript

---

### 📎 Credits

Product images from Flipkart (used for demonstration purposes only)

### 📄 License

This project is open-source and available under the MIT License.
