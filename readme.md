# 🌍 Wanderlust Travel: Project Style Guide

Welcome to the Wanderlust Travel homepage project! This README contains all the design specifications you need to build the webpage. Your goal is to replicate the design using only HTML and basic CSS (no Flexbox or Grid!).

## 🎨 Color Palette

Use these specific hex codes to style your elements:

*   **Main Background Color:** `#f4f7f6` (Light, cool gray)
*   **Primary Text Color:** `#333333` (Dark charcoal gray)
*   **Header & Footer Background:** `#2c3e50` (Dark slate/navy blue)
*   **Header & Footer Text:** `white`
*   **Primary Accent Color:** `#18bc9c` (Mint green/teal — use for links, card titles, and buttons)
*   **Accent Hover Color:** `#128f76` (Darker teal for button hover states)
*   **Card Background:** `white`
*   **Card Border Color:** `#dddddd` (Soft, light gray)

## 🔤 Typography

*   **Font Family:** Use a clean, sans-serif font stack (e.g., `'Segoe UI', Tahoma, Geneva, Verdana, sans-serif`).
*   **Line Spacing (Line Height):** `1.6` for comfortable reading.
*   **Navigation Links:** Bold, slightly larger than standard text, colored in the Primary Accent Color, with no underlines. On hover, they should turn white.
*   **Main Logo/Title (Header):** Add extra breathing room between the letters (`letter-spacing: 2px`).

## 📏 Layout & Spacing Rules

*   **Global Reset:** Remember to zero out default browser margins and padding (`margin: 0; padding: 0;`), and set `box-sizing: border-box;`.
*   **The Main Container:** Constrain the main content wrapper to **80% width** and center it perfectly in the middle of the page using margins.
*   **Section Padding:** Give the top and bottom of the header, footer, and main sections plenty of space (around `20px` to `40px` of padding).

## 🖼️ Component Styles

### The Hero Section (Top Banner)
*   **Background:** White.
*   **Corners:** Slightly rounded (`8px`).
*   **Border:** Add a thick, `4px` solid border across the *bottom* using the Primary Accent Color.

### The Buttons
*   **Background:** Primary Accent Color.
*   **Text:** White, bold, no underline.
*   **Padding:** `10px` top/bottom and `25px` left/right.
*   **Corners:** Slightly rounded (`5px`).

### The Destination Cards (3-Column Layout)
*   **Width:** Each card must take up exactly **30%** of the container's width.
*   **Spacing:** Apply a **1%** margin on all sides of each card.
*   **Borders:** Give them a thin, light gray `1px` solid border and slightly rounded corners (`8px`).
*   **Images:** 
    *   Must span the full 100% width of the card. 
    *   Set the height to exactly `200px`.
    *   Use `object-fit: cover;` so the images act like picture frames and do not get squished or distorted.
*   **Text Area:** Apply `15px` of padding inside the cards so the text does not touch the edges.

---
*Happy coding!*