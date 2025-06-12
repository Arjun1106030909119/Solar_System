# 🌌 3D Solar System Simulator

An interactive and visually-rich 3D simulation of the Solar System built using [Three.js](https://threejs.org/). This project offers educational insights into planetary data, dynamic orbits, textures, and celestial objects like asteroid belts and comets — all rendered in real-time within the browser.

## 🚀 Features

* 🌞 Realistic rendering of the Sun and all 8 planets with accurate relative sizes and textures
* 🌍 Interactive planet info panel (click on planets to learn more)
* 🌀 Orbital rings and elliptical comet paths
* 🌠 Starry sky background, dust particles, and asteroid belt
* 📈 Dynamic speed controls for each planet's orbit
* 🛰️ Realistic lighting using point, ambient, and hemisphere lights
* 📱 Responsive layout with mobile-friendly controls
* 🔭 OrbitControls for intuitive zoom and pan functionality

---

## 📷 Preview

![image](https://github.com/user-attachments/assets/ae78ff29-7ae8-4e48-8ff0-9bdf6a3cc46a)

https://arjun1106030909119.github.io/Solar_System/
 

---

## 🛠️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/Arjun1106030909119/solar_system.git
cd solar-system-simulator
```

### 2. Add Planet Textures

Place planet texture images (e.g. `earth.jpg`, `mars.jpg`, etc.) inside the `textures/` directory.

```
/textures
  |- sun.jpg
  |- mercury.jpg
  |- venus.jpg
  |- earth.jpg
  |- mars.jpg
  |- jupiter.jpg
  |- saturn.jpg
  |- uranus.jpg
  |- neptune.jpg
```

> You can find free planetary textures on sites like [Solar System Scope](https://www.solarsystemscope.com/textures/) or [NASA's planetary maps](https://www.solarsystemscope.com/textures/download/).

### 3. Launch the simulator

You can open the `index.html` file directly in a browser:

```bash
# Open with default browser
open index.html   # macOS
start index.html  # Windows
```

Or serve it locally using a development server:

```bash
npx http-server
# OR
python -m http.server
```

Then go to `http://localhost:8080` in your browser.

---

## 📚 Planet Data

Click on any planet to see:

* Diameter, mass, orbit duration
* Surface temperature
* Atmosphere composition
* Fun facts like moon count or rotation direction

---

## 🎮 Controls

| Action              | How                                 |
| ------------------- | ----------------------------------- |
| Rotate view         | Left-click + drag                   |
| Zoom in/out         | Mouse wheel / pinch on touch device |
| Pan view            | Right-click + drag                  |
| Change orbit speed  | Use sliders on top-left control box |
| View planet details | Click on a planet                   |
| Close info panel    | Click "X" on the info box           |

---

## 🧪 Tech Stack

* [Three.js](https://threejs.org/) – 3D rendering
* HTML5, CSS3, JavaScript
* WebGL (via Three.js)
* Textures loaded via `THREE.TextureLoader`

---

## 📦 Project Structure

```
solar-system-simulator/
│
├── index.html         # Main app file
├── textures/          # Planet textures (images)
├── README.md          # You're reading it!
```

---

## 🌠 Future Improvements

* Add planetary moons (e.g., Earth’s moon)
* Simulate day/night shading based on light source
* Add sound effects or background music
* More accurate orbital mechanics (elliptical orbits)
* VR support with WebXR

---



## 🙌 Credits

* Planet textures: [Solar System Scope](https://www.solarsystemscope.com/textures/)
* Data sources: NASA, ESA
* 3D framework: [Three.js](https://threejs.org/)
  

---
