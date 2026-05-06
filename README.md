# Elementor Custom CSS Snippets

A collection of reusable CSS snippets for Elementor-based WordPress websites.

These are simple, practical styles I use in real client projects to improve design, responsiveness, and user experience.

## 🔧 Included Snippets

```css
/* 1. Rounded Profile Image (Perfect Circle) */
img.pro {
    border-radius: 50%;
    aspect-ratio: 1 / 1;
    object-fit: cover;
}
```

---

```css
/* 2. Button Hover Lift Effect */
.elementor-button {
    transition: all 0.3s ease;
}

.elementor-button:hover {
    transform: translateY(-2px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.15);
}
```

---

```css
/* 3. Fix Heading Alignment on Blog Posts */
.single-post .elementor-widget-heading .elementor-heading-title {
    text-align: left !important;
}
```

---

```css
/* 4. Responsive Heading Size (Mobile Fix) */
@media (max-width: 767px) {
    h1 {
        font-size: 42px !important;
    }
}
```

---

```css
/* 5. Image Hover Zoom Effect */
.elementor-widget-image img {
    transition: transform 0.4s ease;
}

.elementor-widget-image:hover img {
    transform: scale(1.05);
}
```

---

```css
/* 6. Sticky Header Scroll Effect */
header.scrolled {
    backdrop-filter: blur(10px);
    background: rgba(255,255,255,0.9);
    transition: all 0.3s ease;
}
```

---

```css
/* 7. Section Padding Fix (Mobile) */
@media (max-width: 767px) {
    .elementor-section {
        padding-left: 20px !important;
        padding-right: 20px !important;
    }
}
```

---

```css
/* 8. Center Content Vertically (Flexbox Fix) */
.elementor-column {
    display: flex;
    align-items: center;
}
```

---

```css
/* 9. Smooth Scroll Behavior */
html {
    scroll-behavior: smooth;
}
```

---

```css
/* 10. Hide Element on Mobile */
@media (max-width: 767px) {
    .hide-mobile {
        display: none !important;
    }
}
```
