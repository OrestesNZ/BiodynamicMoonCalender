# Biodynamic Live
Track Moon Movements and apply Biodynamic Principles. 

# 🌕 Biodynamic Live: Moon Cycle Tracker (Vineyard Edition)

## Table of Contents
*   [Introduction](#introduction)
*   [Features](#features)
*   [How to Use](#how-to-use)
*   [Biodynamic Principles](#biodynamic-principles)
*   [Technical Details](#technical-details)
*   [Deployment](#deployment)
*   [Author](#author)
*   [License](#license)

## Introduction
"Biodynamic Live" is a single-page web application designed to provide precise biodynamic astronomical data and actionable advice for viticulture and organic gardening. It calculates the Moon's phase, sidereal constellation (zodiac), tropical declination, and orbital distance for any given date, offering highly contextualized recommendations based on these cosmic rhythms.

Developed with a focus on real-time, client-side calculations, this tool helps farmers and gardeners align their activities with lunar and solar influences to enhance growth and quality.

## Features
*   **Live Moon Data:** Displays the current Moon phase (e.g., Full Moon, Waxing Crescent), illumination percentage, and precise orbital distance.
*   **Hemisphere Selection:** Toggle between Northern and Southern Hemispheres to ensure accurate declination (path) and solar phenology calculations relevant to your location.
*   **Temporal Shift Scrubber:** A user-friendly slider allows you to explore Moon data up to +/- 28 days from the current date, with a "SYNC TO NOW" button for quick resets.
*   **Sidereal Zodiac:** Identifies the constellation the Moon is currently traversing and its corresponding elemental day (Fruit, Root, Flower, Leaf) with indicative emoji.
*   **Tropical Declination (Path):** Tracks the Moon's ascending or descending path, crucial for understanding sap flow within plants and recommending specific biodynamic preparations.
*   **Orbital Distance:** Highlights periods of Perigee (Moon closest to Earth, high gravitational pull) and Apogee (Moon furthest, low germination), providing insights into their impacts.
*   **Draconic Node Alerts:** Displays a prominent warning during Moon Node Crossings, advising against all critical vineyard and cellar activities due to unstable cosmic influences.
*   **Cosmic Action Engine:** Provides clear, detailed, and dynamic recommendations for primary viticulture/cellar tasks or general garden activities, synthesized from all active astronomical factors.
*   **Solar Phenology:** Shows the current solar season (Sun in Zodiac sign) and its corresponding phase of vine growth (e.g., Bud Burst, Veraison), dynamically adjusted for the selected hemisphere.
*   **Interactive Wave Chart:** A visual overview plotting the Moon's light, path, and distance rhythms over a +/- 10-day context window.
*   **Enhanced Tooltips:** Hover over key metrics (Path, Constellation, Distance, Solar Phenology) for deep-dive explanations encompassing astronomical facts, general biodynamic principles, and specific viticultural/enological synthesis.
*   **Mode Toggle:** Switch between "Vineyard Pro" (highly detailed advice for viticulture and cellar work) and "Standard Garden" (simplified recommendations for general gardening).

## How to Use
1.  **Access the Application:** Open the `index.html` file in your web browser or visit the live deployment (e.g., via GitHub Pages).
2.  **Select Your Hemisphere:** Use the "N" (Northern) or "S" (Southern) buttons in the header to ensure calculations align with your geographical location. The app defaults to Southern Hemisphere (New Zealand).
3.  **Explore Different Dates:** Adjust the "Temporal Shift" slider to view biodynamic data and recommendations for past or future dates. Click the "⚡ SYNC TO NOW" button to instantly return to the current day.
4.  **Understand Recommendations:** The "Primary Viticulture Task" (or "Primary Garden Task" depending on your selected mode) card provides the key actionable advice.
5.  **Deep-Dive with Tooltips:** For detailed explanations behind the advice, hover your mouse over the "Path (Tropical)", "Constellation", "Distance", and "Solar Phenology" cards. These tooltips offer a multi-layered synthesis.
6.  **Toggle Operating Mode:** Use the "Mode: Garden / Vineyard Pro" toggle to switch between simplified advice for general gardening and highly specific recommendations for professional viticulture and cellar management.
7.  **Observe Cautions:** Pay attention to the "Caution" card for alerts like "Moon Node Crossing" or "Perigee (Fungal Risk)".

## Biodynamic Principles
The application is built upon key biodynamic astronomical rhythms:
1.  **Synodic Cycle (Phase - ~29.5 Days):** Relates to Moon's illumination. Waxing (light) periods are associated with high moisture and upward energy; Waning (dark) periods with sinking moisture and root activity.
2.  **Tropical Cycle (Declination/Path - ~27.3 Days):** Tracks the Moon's ascending or descending path relative to the celestial equator. Ascending periods draw sap upwards (good for foliar sprays, harvesting), Descending periods draw sap downwards (good for root work, pruning, composting).
3.  **Sidereal Cycle (Constellation/Element - ~27.3 Days):** Correlates the Moon's position against the zodiac constellations with elemental qualities:
    *   **Fire (Fruit Days):** Best for harvesting fruits, pruning fruit trees, grafting.
    *   **Earth (Root Days):** Ideal for planting, transplanting, cultivating root crops.
    *   **Air (Flower Days):** Favorable for flowering plants, pollination, delicate sprays.
    *   **Water (Leaf Days):** Promotes leaf growth, irrigation, liquid manure applications.
4.  **Draconic Cycle (Nodes - ~27.2 Days):** Critical interruption points when the Moon crosses the ecliptic plane. These periods are generally considered unfavorable for all major biodynamic activities.

## Technical Details
*   **Frontend:** Pure HTML, CSS (utility-first framework TailwindCSS via CDN), and Vanilla JavaScript for all astronomical calculations, UI updates, and interactive elements.
*   **Astronomical Engine:** A custom, lightweight JavaScript engine calculates precise Julian dates, moon longitude, declination, phase angle, illumination, and orbital distance.
*   **Responsiveness:** Designed with a mobile-first approach using TailwindCSS to ensure a seamless experience across various screen sizes.
*   **Offline Functionality:** As a static, client-side application, it can function offline once fully loaded in the browser.

## Deployment
This is a static web application and can be hosted effortlessly on platforms like GitHub Pages, Netlify, Vercel, or any standard web server.

### Deploying to GitHub Pages:
1.  **Rename File:** Ensure your main HTML file is named `index.html`.
2.  **Push to GitHub:** Commit your `index.html` file and other assets to a public GitHub repository (e.g., `BiodynamicMoonCalender`).
3.  **Enable GitHub Pages:**
    *   Go to your repository on GitHub.
    *   Click on the **"Settings"** tab.
    *   In the left sidebar, click on **"Pages"** under "Code and automation".
    *   Under "Build and deployment", select `Deploy from a branch`.
    *   For "Branch", choose `main` (or the branch where your `index.html` resides).
    *   For the folder, select `/root`.
    *   Click **"Save"**.
4.  **Access Your Site:** After a few minutes, your site will be published at `https://YOUR_USERNAME.github.io/YOUR_REPOSITORY_NAME/`.

## Author
This application was generated and refined by a Gemini-powered AI.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details (if applicable, otherwise omit this line).
