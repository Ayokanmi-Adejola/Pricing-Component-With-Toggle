# Pricing Component with Toggle

A responsive pricing component featuring an interactive toggle switch to display annual and monthly pricing plans. Built with vanilla HTML, CSS, and JavaScript.

![Design preview for the Pricing component with toggle](preview.jpg)



## 🎯 Overview

This project is a solution to the [Pricing Component with Toggle challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/pricing-component-with-toggle-8vPwRMIC). The component displays three pricing tiers with the ability to toggle between annual and monthly billing cycles.

### The Challenge

Users should be able to:

- ✅ View the optimal layout for the component depending on their device's screen size
- ✅ Control the toggle with both their mouse/trackpad and their keyboard
- ✅ See hover states for all interactive elements
- ✅ Switch between annual and monthly pricing

## ✨ Features

- **Responsive Design**: Optimized for desktop (1440px) and mobile (375px) viewports
- **Interactive Toggle**: Smooth animation between annual and monthly pricing
- **Keyboard Accessibility**: Full keyboard navigation support with Tab and Enter/Space keys
- **Hover Effects**: Interactive feedback for all clickable elements
- **Modern CSS**: Uses CSS Grid, Flexbox, and CSS custom properties
- **Semantic HTML**: Proper HTML structure for accessibility and SEO
- **Cross-browser Compatible**: Works across all modern browsers

## 🛠 Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with Flexbox, Grid, and animations
- **JavaScript (ES6+)**: Interactive toggle functionality
- **Google Fonts**: Montserrat font family
- **SVG**: Scalable background graphics

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ayokanmi-Adejola/pricing-component-with-toggle.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd pricing-component-with-toggle
   ```

3. **Open in your browser**
   ```bash
   # Simply open index.html in your preferred browser
   # Or use a local server like Live Server in VS Code
   ```

## 🎮 Usage

### Basic Usage

1. Open `index.html` in your web browser
2. Click the toggle switch to switch between Annual and Monthly pricing
3. Use keyboard navigation (Tab to focus, Enter/Space to toggle)
4. Click "Learn More" buttons to interact with the pricing cards

### Customization

To customize the pricing plans, modify the HTML structure in `index.html`:

```html
<div class="pricing-card">
  <h2 class="card-title">Your Plan Name</h2>
  <div class="price">
    <span class="price-annual">&dollar;XX.XX</span>
    <span class="price-monthly">&dollar;XXX.XX</span>
  </div>
  <ul class="features">
    <li>Feature 1</li>
    <li>Feature 2</li>
    <li>Feature 3</li>
  </ul>
  <button class="learn-more-btn">Learn More</button>
</div>
```

## 📁 Project Structure

```
pricing-component-with-toggle/
├── index.html              # Main HTML file
├── images/                 # Image assets
│   ├── bg-bottom.svg      # Bottom background decoration
│   ├── bg-top.svg         # Top background decoration
│   └── favicon-32x32.png  # Favicon
├── design/                # Design reference files
├── README.md              # Project documentation
└── style-guide.md         # Design system specifications
```

## 🎨 Design Specifications

### Colors

- **Primary**:
  - Linear Gradient: hsl(237, 73%, 79%) to hsl(238, 63%, 64%)
- **Neutral**:
  - Very Light Grayish Blue: hsl(240, 78%, 98%)
  - Light Grayish Blue: hsl(234, 14%, 74%)
  - Grayish Blue: hsl(233, 13%, 49%)
  - Dark Grayish Blue: hsl(232, 13%, 33%)

### Typography

- **Font Family**: [Montserrat](https://fonts.google.com/specimen/Montserrat)
- **Font Weight**: 700
- **Font Size**: 15px (body text)

### Layout

- **Desktop**: 1440px
- **Mobile**: 375px

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+


## 🙏 Acknowledgments

- Challenge by [Frontend Mentor](https://www.frontendmentor.io)
- Design inspiration from the Frontend Mentor community
- Icons and graphics provided by Frontend Mentor

## 👨‍💻 Author


- Frontend Mentor: [@Ayokanmi-Adejola](https://www.frontendmentor.io/profile/Ayokanmi-Adejola)
