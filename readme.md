# Three.js Galaxy
---

### Preview Prorject
![image](https://github.com/user-attachments/assets/f86da641-160c-4d97-a248-cb66ec2b7635)


---

## Project Setup
Download [Node.js](https://nodejs.org/en/download/).
Run this followed commands:

``` bash
# Install dependencies (only the first time)
npm install

# Run the local server at localhost:8080
npm run dev

# Build for production in the dist/ directory
npm run build
```

---

Core Concept : 
- Float32Array to handle Positions and Colors of each particle
- Dispose old geometry after update
- Custom Tweaks using Lil-Gui
- Trigonometry (Sin & Cos) to handle position of each particle to decide Horizontal and Depth
