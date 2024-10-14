# CSS Flex Example Project

This project demonstrates the use of CSS Flexbox for creating responsive layouts. It includes several pages showcasing different applications of Flexbox.

## Why is this important?

CSS Flexbox is a powerful layout tool that helps create flexible and responsive designs. It's easier to use than traditional layout methods and works well on different screen sizes.

## What's included?

1. A main page with navigation
2. Employee cards page
3. Student profiles page
4. Delivery information page
5. Examinee information page

## Key CSS Snippets

### Basic Setup

```css
* {
    box-sizing: border-box;
}
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    background-color: #f0f0f0;
}
```

This sets up the basic layout and styling for the entire site.

### Flexbox Navigation

```css
.nav-list {
    list-style: none;
    padding: 0;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 15px;
}
```

This creates a flexible, centered navigation menu.

### Card Layout

```css
.employee-container,
.student-container,
.delivery-container,
.examinee-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 20px;
}
```

This sets up the flexible card layout used on various pages.

## How to Use

1. Open `index.html` in your browser to view the main page.
2. Click on the navigation links to explore different pages.
3. Resize your browser window to see how the layout adapts.

Feel free to modify the CSS to experiment with different Flexbox properties!
