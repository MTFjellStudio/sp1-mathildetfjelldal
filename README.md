# Community Science Museum - Semester Project 1

## Project Overview
This repository contains the code and design files for Semester Project 1 (SP1) [1]. The goal of this project is to design and develop a fully responsive, multi-page website for the "Community Science Museum," an interactive science museum targeting children aged 7 to 15 and families with young children [2]. The site aims to be informative, engaging, accessible, and visually appealing to inspire visitors to explore the museum in person [2, 3]. 

## Design Concept
The website's visual identity is heavily inspired by **Bauhaus geometric modernism** mixed with a "retro technology" aesthetic, for example taking inspiration from the space race of 1960's to 1980's. It features strong structural grids, thick dividing lines, and a strict color palette tailored for both aesthetic impact and WCAG accessibility compliance [4-13]:
*   **Oxidized Iron (Red):** `#B12306`
*   **Royal Gold (Yellow):** `#F4D35E`
*   **Regal Navy (Blue):** `#0D3B66`
*   **Lemon Chiffon (Off-white):** `#FAF0CA`
*   **Ink Black:** `#020A12`

Geometric shapes (circles, triangles, and squares) are utilized systematically to create unique visual identities for the five main exhibition spaces (Cosmology, Evolution, Biology and Medicine, Robotics and AI, Ecology) and the special Energetica exhibition [14-18].

## Built With
*   **Semantic HTML5** [19]
*   **Pure CSS3** (Utilizing Flexbox and CSS Grid for layout structuring) [20]

*Note: In strict accordance with the project brief, this site is built entirely without JavaScript or CSS frameworks (e.g., Bootstrap, Tailwind) [3, 19].*

## Site Structure
The project consists of 6 interconnected HTML pages [20]:
1.  **Index (`index.html`):** A space-themed hero landing page introducing the museum and highlighting the "Young Stars" club for kids [21-23].
2.  **Exhibitions (`exhibitions.html`):** A bento-box style CSS grid showcasing all museum exhibition categories [14-17].
3.  **Cosmology (`cosmology.html`):** A dedicated exhibition page detailing solar exploration and the cosmos [14].
4.  **Events & Community (`events.html`):** Features special events (like the "Night in the Museum" sleepover) and ways to get involved, such as volunteering and internships [24-26].
5.  **Visit Us (`visit.html`):** Practical info including location, free admission details, hours, accessibility resources, and guided tours for teachers [18, 27-29].
6.  **Coming Soon (`coming-soon.html`):** A placeholder page used to mimic interactive functionalities (like newsletter sign-ups, ticket bookings, or logins) as required by the technical constraints [4].

## Technical Requirements & Constraints
*   **Accessibility:** The site adheres to WCAG accessibility principles, utilizing semantic HTML for screen reader compatibility, descriptive `alt` text for all images, and strictly passing color contrast ratios [4].
*   **Responsive Design:** The layout adapts flawlessly across mobile, tablet, and desktop viewports with zero horizontal scrollbars [20].
*   **SEO Optimization:** Every single page includes a unique `<title>`, a unique `<meta name="description">`, and a unique `<h1>` tag [30].
*   **Performance:** All image assets are compressed to approximately 200KB or less to ensure fast loading times [4].
*   **Mimicked Functionality:** Features that typically require JavaScript or a backend are implemented as simple HTML links navigating to the "Coming Soon" placeholder page [4].

