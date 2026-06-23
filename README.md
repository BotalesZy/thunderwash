# ThunderWash & Barber - Responsive Landing Page

A highly responsive and animated landing page developed as a commercial proposal for a local hybrid business (Car Wash & Barbershop) in Mazatlán, Sinaloa. 

The main focus of this project was to achieve a seamless user experience across all devices using vanilla web technologies, implementing defensive CSS architecture to avoid common layout breakages on mobile devices.

## 🚀 Live Demo
[👉 Click here to view the live site]((https://botaleszy.github.io/thunderwash/))

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3 (Mobile-First approach)
* **Icons & Fonts:** Ionicons, Google Fonts (Spectral & Cookie)

## 🌟 Key Features & Technical Challenges Solved
* **Cross-Platform Bug Fixing:** Implemented specific CSS overrides (`[x-apple-data-detectors]`) to resolve rendering bugs and forced link-color anomalies on iOS/Safari devices.
* **Fluid Layout Transitions:** Developed custom `@keyframes` animations utilizing coordinated `cubic-bezier` timing functions to handle the logo and typography entry states.
* **Performance-First Marquee:** Built an infinite promotional banner using pure CSS animations instead of heavy JavaScript libraries, ensuring high rendering performance.
* **Defensive CSS Layout:** Managed complex screen responsiveness through a mobile-first approach, enforcing strict `box-sizing: border-box` bounds to eliminate horizontal overflow issues.
