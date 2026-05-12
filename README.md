<div align="center">
<a href="https://pondiai.netlify.app/" rel="noopener noreferrer">
<img 
  src="https://capsule-render.vercel.app/api?type=blur&color=0:0f172a,40:1d4ed8,70:06b6d4,100:67e8f9&height=260&section=header&text=%20PONDI%20AI%20&fontSize=54&fontColor=00FFFF&animation=fadeIn&fontAlignY=36&desc=Smart%20Travel%20•%20AI%20Insights%20•%20Live%20Exploration&descAlignY=70&descSize=21"
  alt="Pondi AI Banner"
  width="100%"
/>
</a>
</div>

## 🌊 PondiAI — Intelligent Travel Guide for Pondicherry

> *Where French colonial grandeur meets Tamil coastal soul — powered by AI.*

A cinematic, AI-powered single-page travel experience for Pondicherry, built with pure HTML, CSS, and vanilla JavaScript. No frameworks, no build tools — just crafted code.

---

## ✨ Features

### 🎬 Cinematic Experience
- Full-screen animated loading/intro screen
- GSAP-powered scroll-triggered reveal animations
- Lenis smooth scrolling throughout
- Glassmorphism UI with premium dark design system

### 🌤️ Live Intelligence
- **Live weather** fetched from Open-Meteo API (temperature, condition, wind)
- **Dynamic hero background** that shifts gradients based on time of day (morning / afternoon / evening / night) and weather conditions (rain, clouds)

### 🗺️ Explore Pondicherry
- **Interactive Leaflet map** with custom markers for key attractions
- **Category navigation** — Beaches, Temples, Cafes, Shopping, Heritage, Nature & more
- Expandable subcategory detail panels
- **Featured Destinations grid** with hover image zoom effects

### 📸 Gallery
- Vertical auto-slideshow of 24+ iconic Pondicherry places
- Animated progress bar navigation — click any bar to jump to a slide
- Pause-on-hover with smooth crossfade transitions

### 📊 Tourism Analytics Dashboard
- **KPI Cards** — animated count-up stats (trips planned, satisfaction, rating)
- **Weekly Tourist Traffic** — Bar chart (Chart.js)
- **Visitor Interests** — Doughnut/Pie chart (Chart.js)
- **Pondicherry vs Competitors** — Radar chart comparing Goa & Kochi
- **Live Crowd Heatmap** — grid-based crowd density by location and time slot
- **AI Alerts** — real-time crowd advisories (e.g., avoid Paradise Beach after 5PM)

### 🤖 AI Chatbot
- Floating chat panel powered by the Anthropic Claude API
- Context-aware travel assistant for Pondicherry queries
- Smooth open/close animation

### 🔊 Audio Narrator
- Text-to-speech narration triggered on scroll (Web Speech API)
- Section-based contextual narration

### 🆘 Emergency Support
- Quick-access buttons for Hospitals, Police, Pharmacies, Ambulance, Women Safety, Embassy
- One-tap SOS modal with local emergency numbers

### 📱 Fully Responsive
- Fluid typography with `clamp()` — scales from 320px to 1440px+
- Mobile-first layout reflows (single-column grids, stacked nav)
- Touch-friendly controls and mobile chatbot panel sizing

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (custom design system, CSS variables, glassmorphism) |
| Logic | Vanilla JavaScript (ES6+) |
| Animations | GSAP 3 + ScrollTrigger |
| Smooth Scroll | Lenis |
| Maps | Leaflet.js |
| Charts | Chart.js 4 |
| Weather | Open-Meteo API |
| AI Chat | Anthropic Claude API |
| Fonts | Cormorant Garamond · Plus Jakarta Sans (Google Fonts) |

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/pondi-ai.git
cd pondi-ai
```

### 2. Add your images

Place your images inside an `images/` folder in the project root. The slideshow expects filenames like:

```
images/
├── mahatma-gandhi-statue.jpg
├── white-town-charm.jpg
├── providence-mall.jpg
├── botanical-garden.jpg
├── ganesh-temple.jpg
└── ... (see slidesData in index.html for full list)
```

### 3. Configure your API key (optional — for AI chatbot)

The chatbot uses the Anthropic Claude API. Open `index.html` and find the chatbot fetch call, then add your key:

```js
headers: {
  "x-api-key": "YOUR_ANTHROPIC_API_KEY",
  ...
}
```

> ⚠️ For production, proxy API calls through a backend to keep your key secure.

### 4. Open in browser

```bash
# Option A: just open the file
open index.html

# Option B: use a local server (recommended for map + API features)
npx serve .
# or
python3 -m http.server 8080
```

Then visit `http://localhost:8080`

---

## 📁 Project Structure

```
pondi-ai/
├── index.html          # Entire app — HTML, CSS, and JS in one file
├── images/             # Local images for gallery & hero
└── README.md
```

---

## 🎨 Design System

| Token | Value |
|---|---|
| Primary | `#1E8FA6` (Teal) |
| Accent | `#C8962A` (Gold) |
| Background | `#06101C` |
| Surface | `#0B1A2A` / `#0F2035` |
| Display Font | Cormorant Garamond |
| Body Font | Plus Jakarta Sans |

---

## 📈 Stats Showcased

- **1.2M+** trips planned
- **98%** traveller satisfaction
- **50+** AI-curated routes
- **4.9★** app rating
- **24/7** AI assistance

---

## 🙋 Author

**Gokul Raj**
- 🌐 Portfolio: [gokulrajprofile.netlify.app](https://gokulrajprofile.netlify.app/)
- 📸 Instagram: [@race_caller](https://www.instagram.com/race_caller)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">Made with ❤️ for Pondicherry</p>
