# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Overview
This project is a responsive product preview card that is optimized for both desktop and mobile views. The product card includes elements such as:
- Product image (with a different image for mobile view),
- Product name and description,
- Price information,
- An "Add to Cart" button. 
The card adapts dynamically based on the screen size using **CSS media queries** to ensure it is displayed correctly on both **desktop** (1440px width) and **mobile** (375px width) devices. This project also explores using **CSS Flexbox** for layout and **responsive images** for better performance across devices.

## My Process
1. **HTML Structure:**
Used semantic HTML to create the card's structure, including a **div** for the main card (**#product-bg**) and separate **divs** for the image (**#product-img**) and product details (**#comb, #sentenc, etc.**).

2. **Styling with CSS:**
- Styled the card with a combination of Flexbox and standard CSS properties such as **font-family, font-size, color, margin, and padding**.
- Ensured that the card looks good on larger screens by defining properties like width and height for desktop views.

3. **Responsive Design:**
- Added media queries to adjust the card’s layout and image for mobile views.
- A mobile-specific image (portrait mode) was introduced using the **picture element** in HTML.

4. **Optimization for Mobile:**
Ensured that the card scales well and is readable on smaller screens by adjusting font sizes, margins, and paddings.

### What I learned
1. **Responsive Web Design:**
Understanding how to use **CSS media queries** and **Flexbox** to create a layout that adapts to both mobile and desktop screens was a key takeaway.

2. **Image Handling for Different Devices:**
Learned how to use the picture element to swap images depending on screen size, ensuring the most appropriate image is displayed for each device.

3. **Media Queries for Styling:**
Practiced creating various breakpoints for different screen sizes, and how these breakpoints can alter the styling of the page for optimal user experience.

### Continued Development
- **Responsiveness:** Learn more about media query.
- **Interactivity:** Implement JavaScript for more interactive features. 

**Find the Desktop and Mobile Preview Here**
[Desktop Preview](./Designs/Desktop%20Preview.PNG)
[Mobile Preview](./Designs/Mobile%20Preview.PNG)