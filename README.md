# 🚀 TechSpace - Responsive Business Website

TechSpace is a fully responsive business website created using **HTML5**, **CSS3**, **Bootstrap 5**, and **Bootstrap Icons**.  
The project is designed to represent a modern startup or technology company website with multiple sections such as:

- Navigation Bar
- Hero Carousel
- Services
- About Company
- Statistics/Achievements
- Contact Form
- Footer

This project is beginner-friendly and helps developers understand responsive web design using Bootstrap.

---

# 📌 Project Overview

The website provides a clean and professional user interface for startups and businesses.  
It uses Bootstrap components and custom CSS styling to create a modern layout.

The website contains:

✅ Responsive Navigation Bar  
✅ Bootstrap Carousel Slider  
✅ Service Cards with Hover Effects  
✅ About Company Section  
✅ Achievement Statistics Section  
✅ Contact Form  
✅ Footer Section  
✅ Mobile Responsive Layout  

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| HTML5 | Structure of the website |
| CSS3 | Custom styling |
| Bootstrap 5 | Responsive layout and components |
| Bootstrap Icons | Icons used in services section |

---

# 📂 Project Structure

```bash
TechSpace/
│
├── index.html
└── README.md
```

---

# 🌐 Bootstrap CDN Links Used

## Bootstrap CSS

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
```

## Bootstrap Icons

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
```

## Bootstrap JavaScript

```html
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
```

---

# 🖥️ Website Sections Explanation

---

# 1️⃣ Navbar Section

The navbar is created using Bootstrap's responsive navigation component.

## Features

- Dark themed navbar
- Sticky navigation bar
- Responsive hamburger menu
- Navigation links:
  - Home
  - Services
  - About
  - Contact

## Code Used

```html
<nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
```

## Bootstrap Classes Explained

| Class | Purpose |
|------|----------|
| navbar | Creates navbar |
| navbar-expand-lg | Expands navbar on large screens |
| navbar-dark | Dark text style |
| bg-dark | Dark background |
| sticky-top | Navbar stays at top while scrolling |

---

# 2️⃣ Hero Carousel Section

This section contains an image slider using Bootstrap Carousel.

## Features

- Automatic image sliding
- Responsive images
- Previous/Next controls
- Text captions
- CTA buttons

## Carousel Code

```html
<div id="heroCarousel" class="carousel slide" data-bs-ride="carousel">
```

## Carousel Components

| Component | Purpose |
|-----------|----------|
| carousel-inner | Holds all slides |
| carousel-item | Individual slide |
| carousel-caption | Text over image |
| carousel-control-prev | Previous button |
| carousel-control-next | Next button |

---

# 3️⃣ Services Section

The services section displays company services using Bootstrap cards.

## Services Included

### 💻 Web Development
Responsive modern websites.

### 📱 App Development
Android and iOS mobile apps.

### 📈 Digital Marketing
Business growth strategies.

---

## Features

- Responsive card layout
- Hover animation
- Bootstrap icons
- Shadow effects

## Card Hover Effect

```css
.services-card:hover{
    transform: translateY(-5px);
    transition: 0.3s;
    background-color: rgb(197, 153, 153);
}
```

## Explanation

| Property | Purpose |
|----------|----------|
| transform | Moves card upward |
| transition | Smooth animation |
| background-color | Changes card color |

---

# 4️⃣ About Section

The About section provides company information.

## Features

- Responsive image
- Company introduction
- Read More button
- Two-column Bootstrap layout

## Bootstrap Grid Used

```html
<div class="row align-items-center">
```

## Layout

| Column | Content |
|--------|----------|
| Left | Company Image |
| Right | About Text |

---

# 5️⃣ Statistics Section

This section displays company achievements.

## Statistics Included

- 500+ Clients
- 120+ Projects
- 25 Awards
- 10+ Years Experience

## Features

- Responsive grid system
- Colored background
- White text styling

## CSS Used

```css
.stats-section{
    background-color: #6088c5;
    color: white;
}
```

---

# 6️⃣ Contact Section

The contact form allows users to send messages.

## Form Fields

- Name
- Email
- Message

## Bootstrap Form Components

| Component | Purpose |
|-----------|----------|
| form-control | Styled input fields |
| form-label | Labels |
| btn btn-primary | Submit button |

---

# 7️⃣ Footer Section

The footer contains copyright information.

## Features

- Dark background
- Center aligned text
- Simple layout

## CSS Used

```css
footer{
    background-color: #212529;
    color: white;
}
```

---

# 🎨 Custom CSS Explanation

---

# Body Styling

```css
body{
    font-family: Arial, sans-serif;
    background-color: rgb(213, 186, 186);
}
```

## Purpose

| Property | Explanation |
|----------|--------------|
| font-family | Sets text font |
| background-color | Changes page background |

---

# Carousel Image Styling

```css
.carousel-item img{
    height: 90vh;
    object-fit: cover;
}
```

## Explanation

| Property | Purpose |
|----------|----------|
| height: 90vh | Image covers 90% screen height |
| object-fit: cover | Prevents image distortion |

---

# 📱 Responsive Design

The website is fully responsive because of Bootstrap's grid system.

## Bootstrap Responsive Classes Used

| Class | Device Size |
|------|--------------|
| col-md-4 | Medium devices and above |
| col-md-6 | Half width on medium screens |
| container | Responsive container |
| row | Bootstrap row layout |

---

# 🚀 How to Run the Project

## Method 1: Direct Browser Open

1. Download the project folder.
2. Open `index.html`.
3. Run in any browser.

---

## Method 2: Using VS Code Live Server

### Steps

1. Open project in VS Code.
2. Install Live Server extension.
3. Right-click `index.html`.
4. Click **Open with Live Server**.

---

# 📸 Screens Included

The project contains:

✅ Navbar  
✅ Hero Slider  
✅ Service Cards  
✅ About Section  
✅ Achievement Section  
✅ Contact Form  
✅ Footer  

---

# 🔥 Features of This Project

- Beginner-friendly project
- Modern UI design
- Bootstrap 5 implementation
- Responsive layout
- Simple clean code
- Easy to customize
- Reusable sections

---

# 📚 Learning Concepts Covered

This project helps beginners learn:

- HTML Structure
- CSS Styling
- Bootstrap Grid System
- Bootstrap Components
- Responsive Web Design
- Forms
- Cards
- Carousel
- Icons
- Hover Effects

---

# 🧠 Future Improvements

You can improve this project by adding:

- Dark Mode
- Backend Integration
- Database Connectivity
- Login System
- Animations
- Testimonials Section
- Pricing Section
- Newsletter Subscription
- Real Contact Form Backend

---

# 👨‍💻 Author

JAKKI SIVAPRASAD

---

# 📄 License

This project is free to use for:
- Learning
- Practice
- Educational purposes

---

# ⭐ Conclusion

TechSpace is a beginner-friendly responsive website project that demonstrates how to build modern websites using Bootstrap 5 and custom CSS.

It is a great project for:
- Students
- Beginners
- Portfolio practice
- Bootstrap learning
- Frontend development practice

---
