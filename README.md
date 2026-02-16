
# Assignment 05 – Hero Layout Clone
🎯 Objective

Recreate the hero page design from the provided screenshot using semantic HTML and CSS Flexbox.
The goal is to match the layout, colors, spacing, and typography as closely as possible.

📸 Preview:
![image alt](https://github.com/iqraiqrashahzadi355-a11y/Assignment-05/blob/9c346f75ac4ca9a68484a0e3069c8bb4830b6322/mohammad-bin-zayed-university-of-artificial-intelligence-banner-and-navigation-design.png)

Note: This design is desktop-first. Mobile responsiveness will be handled with media queries in future lessons.

## 📂 Project Structure:
```bash
│
├─ index.html         # Main HTML file
├─ style.css          # External CSS 
├─ assets/            # Folder containing all images
│   ├─ mbzuai-logo.png
│   ├─ banner-bg-modal.png
│   └─ students.png
└─ README.md          # Project documentation
```

##✨ Implementation Details
General

Font: sans-serif

Base font size: Default for body text

Centered container: Max width 1200px to prevent layout stretching

🖥️ Top Navbar (Light)

Background color: #ffffff

Link color: #212529

Font size: 12px

Font weight: bold

Horizontal separator: 1px solid #000000

Right-aligned links: Careers | Contact | Links | EN | AR | 0

## 🟨 Second Navbar (Sand)

Background color: #e5c687

Link font size: 15px

Font weight: 400

Button:

Background: #ffffff

Text color: #000000

Font size: 1em

Icon background: #154677

Layout: Logo on left, menu links on right

🔹 Hero Section

Background color: #154677

Default text color: #FFFFFF

Layout: Flexbox two columns

Left column: 55% width

Hero heading: 80px, font-weight 100

Highlighted span text: color #e5c687

Right column: 45% width

Info panel:

Label color: #27bf56

Label font size: 18px

Value color: #FFFFFF

Value font size: 34px

Apply button: Background #e5c687, text color #154677

Background image applied behind info panel

Student image at bottom fills container width

## 🖼️ Images

Banner background: object-fit: cover;

Student image: object-fit: cover;

Maintains intrinsic sizing without distortion

## ⚡ Key CSS Techniques Used

Flexbox for:

Navbar alignment

Hero section layout

Button and text alignment

Absolute positioning for info panel within the right hero column

Object-fit for images to maintain aspect ratio and cover container

## 📝 Notes

Mobile responsiveness is not implemented yet (desktop-first design)

Future enhancements:

Media queries for mobile view

Interactive hover effects for buttons

Smooth scroll for navbar links.

FINNAL:
This is what we get.....
![image alt](https://github.com/iqraiqrashahzadi355-a11y/Assignment-05/blob/22a70efad540bf041a31a1224eb40cc36fda6e95/Screenshot%20(506).png)

## ▶️ How to Run

Clone or download the project folder

Open index.html in a web browser

Ensure the assets/ folder is in the same directory to load images correctly

##🔗 References

MDN: CSS Flexbox

MDN: Object-fit Property

MDN: Intrinsic Size
MDN: Intrinsic Size
