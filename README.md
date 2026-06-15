# Module 3 Assignment Solution — Food, LLC

An interactive, single-page responsive layout built to satisfy the core guidelines for **Module 3 of Coursera's HTML, CSS, and Javascript for Web Developers** course from Johns Hopkins University. 

This project explores utilizing the **Twitter Bootstrap (v3.3.7)** framework to implement flexible grids and custom-styled mobile drop-down navigation links.

---

## 🌐 Live Review Link
You can view the responsive deployment page here:
👉 **[Insert your GitHub Pages live site URL here, e.g., [(https://github.com/duongbaophuoc/Coding-the-Static-Restaurant-Site-Module-3-Coding-Assignment/tree/main)]**

---

## 🛠️ Assignment Requirements Fulfilled

### 1. Structure & Repository Organization
* **Directory Constraints:** Solution is safely housed inside its own isolated folder container (`module3-solution`).
* **Clean Code separation:** Structural code lives isolated inside `index.html`, while layout aesthetics are configured separately inside `css/styles.css` (Strictly zero inline styling used).

### 2. Navigation Architecture (Bootstrap Components)
* **Scroll Away Navbar:** Built without static or fixed top wrappers, allowing the brand element to naturally scroll out of focus with standard viewport movement.
* **Responsive Visibilities:** Desktop and tablet breakpoints explicitly hide the navigation list. When viewed via smaller mobile viewports (`xs`), a functional 3-bar hamburger utility toggles an expanded full-width, color-contrasted overlay container holding direct section anchors.

### 3. Responsive Layout Grid (Including Optional Steps)
The application leverages a unified, 12-column grid container row that dynamically shifts sections based on screen width profiles:
* **Desktop View (`md`):** Dispatches 3 equal-width boxes sitting perfectly on a single line (`col-md-4` each).
* **Tablet View (`sm`):** Shifts into an asymmetrical grid split where the first two elements rest side-by-side (`col-sm-6`), forcing the final element ("Sushi") to break and claim full width beneath them (`col-sm-12`).
* **Mobile View (`xs`):** Columns fluidly downscale into separate full-width vertical stacks (`col-xs-12` each).

### 4. Usability Design Rules
* **Distinct Contrast:** Background hues for the application's mobile menu tray and structural content divs are explicitly distinguished from normal margins to provide proper content grouping.
* **Scroll Enforcement:** Individual text sections employ min-height variables exceeding `750px` to guarantee physical scroll requirements are met.
* **Anchor Hyperlinks:** Interactive links are assigned at the lower boundary of each food segment, enabling users to jump straight back to the central page title seamlessly.

---

## 🚀 Technical Framework Stack Used
* **HTML5 & CSS3** — Base document skeleton and interface styling variables.
* **Bootstrap v3.3.7 (via CDN)** — Primary grid framework layer and navbar scaffolding.
* **jQuery v1.12.4** — Necessary component dependency to drive Bootstrap's mobile button collapse functionality.
