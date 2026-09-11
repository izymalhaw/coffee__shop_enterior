# Bunna & Bloom - Boutique Specialty Coffee Shop 3D Interior

An interactive 3D boutique specialty coffee shop interior built with **Three.js** using procedural PBR materials, dynamic lighting, post-processing bloom, and interactive equipment inspection.

![3D Coffee Shop Interior Preview](https://raw.githubusercontent.com/izymalhaw/coffee__shop_enterior/main/preview.png)

---

## 🌟 Architectural & Design Highlights

### 1. Architectural Shell & Materials
- **Dimensions:** 12m width &times; 8m depth &times; 3.8m ceiling height.
- **Back Wall:** Distressed red-brown exposed brick texture with high-resolution running-bond masonry, mortar relief, and bump mapping (`MeshStandardMaterial`, roughness `0.85`).
- **Flooring:** Wide-plank dark oak / walnut hardwood flooring with rich longitudinal grain lines and soft satin specular sheen (`roughness ~0.35`).
- **Side Wall & Windows:** Off-white textured plaster with floor-to-ceiling multi-pane industrial black steel windows revealing gentle natural daylight and exterior terrace architecture.
- **Ceiling:** Dark reclaimed wood beams and a suspended wooden ladder rig supporting vintage lighting.

### 2. Main Service Counter & Backdrop
- **Linear Bar Counter:** 6.4m long bar featuring vertical dark rustic wood slats with a 6cm thick polished live-edge timber countertop.
- **Artistic Chalkboard Wall:** A large matte-black framed chalkboard mounted on the brick back wall featuring hand-drawn vacuum siphon diagrams, coffee cherries, and specialty drinks/pastries with prices.
- **Floating Display Shelves:** Two tiers of floating timber shelves holding artisanal single-origin craft coffee bean bags, glass storage jars, and ceramic drinkware.

### 3. Equipment & Workflow on the Bar
- **Espresso Machines (2 units):** Brushed stainless steel and matte black dual-boiler espresso machines with dual group heads, brass portafilters, steam wands, analog pressure dials, and top cup warming racks.
- **Vacuum Siphon Brewers (2 units):** Twin classic Hario-style siphon coffee makers with dual spherical glass chambers, metallic brass support stands, and glowing burner heaters.
- **Industrial Coffee Grinder:** Upright commercial coffee grinder with a transparent tinted conical hopper filled with roasted coffee beans and a precision portafilter fork.
- **Beverage Dispensers (2 units):** Dual vintage glass urns on elevated wrought-iron tripod stands with metal spigots (one vibrant mango-orange juice, one ruby beetroot/pomegranate elixir).
- **Fresh Fruit Centerpiece:** Hand-woven wicker basket piled with lemons, oranges, apples, and a tropical pineapple.
- **Signature Service Details:** Walnut presentation tray holding a small glass cup of crema-topped espresso, a chilled sparkling water tumbler, and a ceramic saucer with organic Medjool dates.
- **Pastry Showcase Vitrine:** Glass-and-wood countertop showcase display with croissants, pain au chocolat, and muffins.
- **Traditional Ethiopian Jebena Pot:** Authentic black clay Jebena pot celebrating ancestral Ethiopian coffee ceremony heritage.

### 4. Cozy Seating & Lounge Zone
- Built-in continuous banquette bench with cognac distressed leather cushions.
- **4 Plush Accent Pillows:** Curated in terracotta velvet, mustard yellow, cream linen, and muted olive green.
- Low rustic solid timber coffee tables on matte black hairpin iron legs.
- Mid-century wooden cafe chairs with bent plywood backrests and slender black iron frames.
- Authentic geometric bohemian area rug under the lounge tables.
- Tabletop flickering candle jars and potted snake plant (*Sansevieria*).

### 5. Lighting & Atmosphere
- **Suspended Pendants:** Exposed vintage Edison filament bulbs hanging by raw cords from the ceiling ladder rig with glowing tungsten spirals.
- **Dynamic Shadows & Fill:** Soft PointLights inside each bulb casting realistic dynamic shadows (`castShadow = true`).
- **Directional Sunlight:** Gentle daylight streaming through the industrial side windows.
- **Cinematic Bloom:** Post-processing `UnrealBloomPass` for filament glow and atmospheric ambiance.
- **Steam Particles:** Animated rising semi-transparent steam particles over fresh espresso and siphon chambers.

---

## 🎮 Interactive Controls

- **Orbit Navigation:** Click and drag to rotate, right-click to pan, scroll to zoom.
- **Camera View Presets:**
  - 🎥 **Overview:** Wide cinematic cafe view
  - ☕ **Barista Bar:** Close-up of the espresso machines & grinders
  - 🧪 **Siphon Lab:** Detail view of the vacuum siphon glass chambers
  - 🛋️ **Lounge:** Cozy seating nook with banquette, pillows & tables
  - 🪟 **Window:** Serene daylight view by the industrial windows
- **Lighting Atmosphere Modes:**
  - 🌅 **Golden Hour:** Warm amber sunset glow
  - 🌙 **Candlelit Night:** Dramatic night mood with glowing filaments and cool exterior moonlight
  - ☀️ **Morning Daylight:** Bright natural morning sunlight streaming through the windows
- **Prop Inspector:** Click any piece of equipment on the bar to inspect its technical specifications.
- **Soundscape Synthesizer:** Toggle procedural warm cafe ambient rain & vinyl sound (no external audio assets required).

---

## 🚀 Local Development & Vercel Deployment

### Run Locally
```bash
# Using standard HTTP server or npm
npx serve .
# Or open index.html directly in any modern WebGL-compatible browser
```

### Deploy on Vercel
```bash
# Deploy directly with Vercel CLI
npx vercel

# Or push to GitHub and connect the repository to Vercel:
git add .
git commit -m "feat: complete Three.js boutique coffee shop interior"
git push origin main
```
