# CSS Basic

This project builds on the foundational HTML project by introducing **CSS (Cascading Style Sheets)** to style and layout web pages. It includes applying basic styles, using Flexbox for layout, and making the design responsive across screen sizes.

## Learning Objectives

By the end of this project, I was able to:

- Understand what CSS is and how it works with HTML
- Add style using inline styles, internal, and external stylesheets
- Use selectors, classes, and attributes
- Understand and apply **CSS specificity**
- Create responsive layouts using **Flexbox**
- Use **box properties** like margin, padding, and overflow
- Make a website responsive to mobile devices using media queries and viewport settings

---

## Tasks Completed

### 0. Some Early Styling
- Created `base.css` and `styles.css`
- Linked both stylesheets in `index.html` and `tweets.html`
- Imported base styles that improve readability and presentation

### 1. Positioning
- Applied **Flexbox** to layout the structure:
  - `<body>` uses column direction
  - `<main>` uses row direction
- Split content area: `<article>` (2/3 width) and `<aside>` (1/3 width)
- Enabled vertical scrolling in `<article>` and `<aside>`

### 2. Responsive Web Design
- Added `class="works_on_smartphone"` to `<body>` in `index.html`
- Included `<meta name="viewport" content="width=device-width, initial-scale=1.0">` to support mobile responsiveness

### 3. Additional Styling
- Customized styles in `styles.css`
- Added a unicode character as a **logo** to the header navigation
- Enhanced visual appearance with background colors, fonts, and borders
- Ensured consistent styling across `index.html` and `tweets.html`

---

## Files in This Directory

| File | Description |
|------|-------------|
| `index.html` | Main web page with layout and styles |
| `tweets.html` | Secondary page embedding a Tweet |
| `base.css` | Shared base styles (provided) |
| `styles.css` | Custom project-specific styles |

---

## Technologies Used

- HTML5  
- CSS3  
- Flexbox  
- Responsive Design  
- [W3C Validator](https://validator.w3.org/) for HTML/CSS compliance