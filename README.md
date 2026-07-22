# 📡 Line Encoding Explorer

A light, browser-based interactive learning tool designed to visualize physical layer (Layer 1) data encoding schemes in networking. 

This explorer dynamically renders waveforms in real-time as bit sequences change, allowing students and engineers to visually analyze how digital data translates into electrical signals and compare synchronization, bandwidth, and edge-case behaviors across different algorithms.

---

## 🚀 Features

* **Real-Time Canvas Waveforms:** Visualizes bit streams instantly using the HTML5 Canvas API.
* **4 Encoding Schemes Supported:**
  * **NRZ-L (Level):** Standard voltage-level mapping.
  * **NRZ-I (Invert):** Differential encoding based on transitions.
  * **Manchester (IEEE 802.3):** Mid-bit transition self-clocking scheme.
  * **Bipolar AMI:** 3-level alternate mark inversion with built-in error detection logic.
* **Edge-Case Testing:** One-click presets for continuous `0`s, continuous `1`s, and exam-style bit patterns to test for baseline wander and clock drift.
* **Interactive Bit Strip:** Click individual bits or use controls (`+ bit`, `- bit`, `random`) to modify sequences up to 20 bits on the fly.
* **Zero Dependencies:** Built entirely with standard vanilla Web technologies—no frameworks, node packages, or build steps required.

---

## 🛠️ Built With

* **HTML5**
* **CSS3** (Flexbox, CSS Custom Properties / Variables)
* **Vanilla JavaScript** (HTML5 Canvas 2D Context API)

---

## 📖 How to Run Locally

Since this is a client-side static web application, no server installation or setup is needed:

🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to report a bug or suggest a feature (e.g., adding 2B1Q or 4B5B encoding).
