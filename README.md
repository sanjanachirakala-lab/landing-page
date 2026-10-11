# PulseWear X1 - Responsive Product Landing Page

Week 02 Minor Project (Web Development) - Unlox Academy
**Author:** Chirakala Sanjana

A responsive landing page for a fictional smartwatch, **PulseWear X1**. It shows how modern CSS and Tailwind CSS can be used to build a clean, mobile-friendly page.

## Sections

1. **Navigation bar** - brand name, links, and a hamburger menu on small screens
2. **Hero** - product title, description, product illustration (SVG), and call-to-action buttons
3. **Features** - four feature cards in a CSS Grid
4. **Benefits** - key selling points laid out with Flexbox
5. **Testimonials** - three sample customer reviews
6. **Pricing / CTA** - three pricing cards with "Buy Now" / "Get Started" buttons
7. **Footer** - contact email, social links, and copyright

## Technologies Used

- **HTML5** - semantic structure (`header`, `nav`, `main`, `section`, `article`, `footer`)
- **CSS3** - custom styles, gradients, transitions, keyframe animation (`style.css`)
- **Flexbox and CSS Grid** - page layouts
- **Tailwind CSS** (via CDN) - utility classes and responsive breakpoints (`sm`, `md`, `lg`)
- **JavaScript** - mobile menu toggle (`script.js`)
- **Git and GitHub** - version control and hosting

## Responsive Design

The layout adapts to mobile, tablet and desktop screens:

- Mobile: single column, hamburger menu
- Tablet (`sm`/`md`): two-column grids
- Desktop (`lg`): full navigation bar, four-column feature grid, three-column pricing

## Project Structure

```
landing-page/
├── index.html    # page markup + Tailwind classes
├── style.css     # custom CSS3
├── script.js     # mobile menu toggle
└── README.md
```

## How to Run

1. Clone or download this repository.
2. Open `index.html` in any browser. An internet connection is needed to load Tailwind from the CDN.

## Notes

- PulseWear is a fictional brand created for learning purposes.
- The testimonials are sample text written for this demo, not real customer reviews.
