# Mini Galaxie

Bienvenue sur **Mini Galaxie**, une simulation dynamique et interactive de notre système solaire créée avec THREE.js et le framework Vite. Ce projet présente diverses fonctionnalités avancées et effets pour offrir une expérience immersive des corps célestes de notre système solaire.

**Développé par l'Équipe 404**

![Solar_System](images/solar_system.png)

![Earth](images/earthnew.png)

![Mercury](images/mercury.png)

![Mars](images/mars.png)

## Features

### Standard Setup
- **Scene, Camera, Renderer**: Basic setup for rendering 3D scenes using THREE.js.
- **Controls**: Interactive controls for navigating the 3D space.
- **Texture Loaders**: Efficient loading of textures for planets, moons, and other objects.

### Postprocessing Effects
- **BloomPass**: Adds a glowing effect to the Sun.
- **OutlinePass**: Highlights planets with a white outline when hovered over.
- **EffectComposer**: Manages and combines all postprocessing effects for rendering.

### Star Background
- A realistic starry sky that provides a beautiful backdrop for the solar system.

### Interactive Controls
- **dat.GUI**: Allows users to adjust parameters such as orbit speed and the intensity of the Sun's glow.

### Lighting
- **AmbientLight**: Provides soft lighting throughout the scene.
- **PointLight**: Positioned at the center of the Sun to cast realistic shadows.

### Detailed Planet Creation
- **Attributes**: Size, position, tilt, texture, bump material, rings, and atmospheres.
- **Moons**: Includes moons with realistic textures and orbits.
- **Special Materials**: Earth’s ShaderMaterial for day/night transitions and moving clouds.
- **Non-Spherical Moons**: Phobos and Deimos are modeled from 3D objects for realism.

### Realistic Orbits and Rotations
- Planets and moons orbit the Sun and rotate on their axes with scaled distances and speeds.
- Scaled sizes for better visual representation: Mercury, Venus, Earth, Mars, and Pluto are at actual scale, while larger planets are scaled down for balance.

### Shadows
- Realistic shadow casting from the PointLight at the Sun’s center.

### Asteroid Belts
- **Procedurally Generated**: 1000 asteroids for the belt between Mars and Jupiter, 3000 for the Kuiper belt.
- **Performance Optimization**: Simplified textures to ensure high performance.

### Select Feature
- **Hover Effect**: White outline around planets when hovered.
- **Zoom In**: Camera zooms in and displays planet details on click.
- **Zoom Out**: Returns to default view on closing the pop-up.

## Resources
3D objects and textures were sourced from the following free repositories:
- [NASA 3D Resources](https://nasa3d.arc.nasa.gov/images)
- [Solar System Scope Textures](https://www.solarsystemscope.com/textures/)
- [Planet Pixel Emporium](https://planetpixelemporium.com/index.php)
- [TurboSquid](https://www.turbosquid.com/)

## Installation et Configuration
1. Cloner le dépôt:
    ```sh
    git clone https://github.com/your-username/mini_galaxie.git
    ```
2. Naviguer vers le répertoire du projet:
    ```sh
    cd mini_galaxie
    ```
3. Installer les dépendances:
    ```sh
    npm install
    ```
4. Démarrer le serveur de développement:
    ```sh
    npm run dev
    ```
5. Ouvrir votre navigateur et aller sur `http://localhost:3000` pour voir Mini Galaxie en action.

## Conclusion
Ce projet est une représentation complète de notre système solaire, réunissant modélisation réaliste, effets visuels avancés et fonctionnalités interactives. Explorez les planètes, leurs lunes et les vastes ceintures d'astéroïdes, depuis votre écran.

## Licence

Ce projet est sous licence [MIT License](./LICENSE).

N'hésitez pas à contribuer, suggérer des améliorations ou utiliser ce projet comme base pour vos propres expérimentations THREE.js. Bonne exploration!

---
**Développé avec ❤️ par l'Équipe 404**
