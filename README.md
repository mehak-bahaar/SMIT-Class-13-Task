# Contact Form - CSS Grid Layout

A modern, responsive contact form built with HTML and CSS Grid. This project demonstrates a clean two-column layout with a contact form on the left and a decorative image on the right.

## Features

- ✨ **Modern UI Design** - Clean and minimalist interface
- 📱 **Responsive Layout** - Fully responsive design that adapts to different screen sizes
- 🎨 **CSS Grid Implementation** - Built entirely using CSS Grid for layout management
- 🖼️ **Visual Appeal** - Beautiful two-column layout with decorative image
- 🎯 **Form Validation Ready** - Structured form fields ready for backend integration

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Grid and Flexbox
- **Google Fonts (Poppins)** - Typography

## Project Structure

```
class 13 task/
│
├── index.html          # Main HTML file
├── style.css           # Stylesheet with CSS Grid layout
├── leaves-window.webp  # Decorative image
└── README.md          # Project documentation
```

## Form Fields

The contact form includes the following fields:

1. **Full Name** - Text input for user's name
2. **Email Address** - Email input with validation
3. **Subject** - Text input for message subject
4. **Message** - Textarea for detailed message
5. **Send Message Button** - Submit button with hover effects

## CSS Grid Implementation

### Main Container Grid
```css
.container {
    display: grid;
    grid-template-columns: 1fr 1fr;  /* Two equal columns */
    gap: 40px;
}
```

### Form Grid Layout
```css
form {
    display: grid;
    grid-template-columns: 1fr 1fr;  /* Name and Email side by side */
    gap: 20px;
}
```

- **Name and Email** fields are placed side by side using `grid-template-columns: 1fr 1fr`
- **Subject and Message** fields span the full width using `grid-column: 1 / -1`
- **Submit Button** also spans full width and is left-aligned

## Responsive Design

The layout includes a media query for mobile devices:

- **Desktop**: Two-column layout (form | image)
- **Mobile (< 968px)**: Single-column layout with stacked elements

## How to Use

1. **Clone or download** this repository
2. **Open** `index.html` in your web browser
3. **No build process required** - works directly in the browser

### Local Development

Simply open the `index.html` file in any modern web browser:

```bash
# Using Python (if installed)
python -m http.server 8000

# Or using Node.js (if installed)
npx http-server

# Or just double-click index.html
```

Then navigate to `http://localhost:8000` in your browser.

## Customization

### Colors
- Primary Button Color: `#73a85f` (Green)
- Hover Button Color: `#5c8d4a` (Dark Green)
- Background: `#ffffff` (White)
- Container Background: `#faf9fa` (Light Gray)

### Typography
- Font Family: Poppins (Google Fonts)
- Font sizes and weights can be adjusted in `style.css`

### Layout
- Container width: `80%` with `max-width: 1400px`
- Grid gap: `40px` between columns
- Form gap: `20px` between form fields

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)

## Future Enhancements

- [ ] Add form validation (JavaScript)
- [ ] Backend integration for form submission
- [ ] Add loading states and success/error messages
- [ ] Implement form field animations
- [ ] Add dark mode support

## License

This project is open source and available for educational purposes.

## Author

Created as part of Class 13 Assignment - CSS Grid Layout Implementation.

