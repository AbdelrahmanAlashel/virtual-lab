# 🧪 Virtual Science Lab

An interactive, responsive single-page virtual science lab designed to simulate core physics and chemistry experiments for middle school science curricula, with a dedicated focus on **Thermal Energy, Heat Transfer, and Thermal Insulation**.

---

## 🌟 Interactive Modules & Experiments

### 1. Convection Currents (`تيارات الحمل الحراري`)
* **Water Basin Investigation:**
  * Simulates fluid movement driven by density changes when heated from the center base.
  * **Hot Fluid (Red Ink):** Particles become less dense, ascend through the center, and settle at the surface.
  * **Cold Fluid (Blue Ink):** Particles become denser, sink along the edges, and settle at the bottom.
  * Features permanent flow indicators illustrating continuous convection cycles.
* **Two-Flask Rig Investigation:**
  * **Cold Over Warm:** Pulling the dividing barrier triggers active convective exchange for 3.5 seconds before fluids homogenize into purple.
  * **Warm Over Cold:** Pulling the barrier demonstrates fluid stability with no convective mixing occurring, as the less dense fluid already rests on top.

### 2. Building Thermal Insulation (`العزل الحراري`)
* **Roof Geometry Testing:**
  * Evaluates heat penetration across different roof structures: Thermal paper only, Flat roof, and Pyramidal roof.
* **Insulation Materials Testing:**
  * Tests the thermal resistance of real-world materials: Plastic, Bubble wrap, and Wood.
* **Controlled Experimental Rig:**
  * Fixed 5 cm distance from heat lamp to container to ensure a fair test.
  * Standardized baseline initial temperature ($23^\circ\text{C}$).
  * Synchronized 5-minute digital heating timer and live temperature probe.
  * Dynamic result tables that highlight empirical data identical to standard textbook measurements.

### 3. General Chemistry Lab (`المختبر العام`)
* **Universal Indicator & pH Testing:**
  * Visual test tube simulation demonstrating distinct color changes across the pH spectrum:
    * Strong Acid ($\text{pH } 2$ — Red)
    * Neutral Distilled Water ($\text{pH } 7$ — Green)
    * Strong Base ($\text{pH } 12$ — Purple)

---

## 🛠 Tech Stack

* **Core:** HTML5, Vanilla JavaScript (ES6+)
* **Styling & Icons:** Tailwind CSS (via CDN), Font Awesome 6
* **Visuals & Physics:** HTML5 Canvas API, SVG vector graphics
* **Typography & Direction:** Google Fonts (`Cairo`), native RTL (Right-to-Left) Arabic UI

---

## 🚀 Getting Started

This project is completely self-contained in a single file (`index.html`) and requires no build tools, package managers, or server runtimes.

### Option A: Local Run (Offline)
1. Download or clone `index.html`.
2. Double-click `index.html` to open it in any modern web browser (Google Chrome, Microsoft Edge, Safari, Mozilla Firefox).

### Option B: Deploying to GitHub Pages (Free Hosting)
1. Push `index.html` to the root of your GitHub repository.
2. In your repository, navigate to **Settings** > **Pages**.
3. Under **Build and deployment** > **Branch**, select `main` (or `master`) and folder `/(root)`.
4. Click **Save**.
5. Your live URL will be ready within 1–2 minutes at:
   ```text
   https://<your-username>.github.io/<your-repository-name>/
