# NU Admission Result Calculator

A lightweight, responsive web calculator that estimates a National University (NU) admission score using SSC GPA, HSC GPA, and an optional MCQ mark.

## Features

- Calculates SSC contribution using a 40% weighting.
- Calculates HSC contribution using a 60% weighting.
- Accepts an optional MCQ mark (0–100).
- Displays each score component and the combined score out of 200.
- Validates GPA and MCQ input ranges with inline error messages.
- Includes a reset button to clear the form and results.
- Responsive layout for desktop and mobile screens.
- Uses a separate `logo.png` image for the page icon and header.

## Scoring Formula

The calculator applies the following formula:

| Component | Calculation | Maximum |
| --- | --- | ---: |
| SSC contribution | SSC GPA × 8 | 40 |
| HSC contribution | HSC GPA × 12 | 60 |
| MCQ mark | Entered mark (optional; defaults to 0) | 100 |
| **Total** | **SSC + HSC + MCQ** | **200** |

**Example:** With SSC GPA 5.00, HSC GPA 5.00, and MCQ mark 80, the estimated total is 180 out of 200.

> **Important:** This is an independent score calculator based on the formula implemented in this project. Admission authorities may change their official admission rules or calculation method. Always check the latest NU admission circular; this tool does not guarantee admission or an official result.

## Getting Started

No build tools, package installation, or backend server are required.

1. Clone or download this repository.
   ```bash
   git clone https://github.com/FoysalAhmmedSadin/nu.git
   ```
2. Open the project folder.
3. Open `index.html` in a modern web browser.
4. Enter your SSC and HSC GPA, optionally enter your MCQ mark, then select **Calculate Result**.

Keep `index.html` and `logo.png` in the same directory so the logo displays correctly.

## Project Structure

```
nu/
├── index.html   # Calculator interface, styles, and JavaScript logic
└── logo.png     # Application logo and favicon
```

## Technology

- HTML5
- CSS3
- Vanilla JavaScript

The project runs entirely in the browser and does not require an external JavaScript framework or database.

## Deployment

The project can be hosted on any static web hosting service, including GitHub Pages. For GitHub Pages, open the repository's **Settings → Pages**, select the `main` branch and root folder, and save.

## License

No separate license file was present in the repository when this README was prepared. Unless a license is added, all rights remain with the copyright holder and reuse is not automatically granted.

## Author

**Foysal Ahmmed Sadin**

- GitHub: [@FoysalAhmmedSadin](https://github.com/FoysalAhmmedSadin)
