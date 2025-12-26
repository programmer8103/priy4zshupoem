# Poetic Journal - Old Writer Theme

This is a collection of HTML pages themed like an old journal/writer's notebook, perfect for showcasing your poetry.

## Files Included:
- `index.html` - Main page listing all poems
- `poem1.html` to `poem5.html` - Individual poem pages with the same theme

## How to Customize:

### 1. Update Your Name
- In `index.html`, find the `<h1>Your Name</h1>` in the header and replace with your name
- Update the signature at the bottom of each page

### 2. Add Your Poems
- Edit the poem links in `index.html`:
  - Change the text inside `<div class="poem-title">` for poem titles
  - Update the `href` attribute to point to your poem files
  - Modify the excerpt text in `<div class="poem-excerpt">`

### 3. Add Your Poetry Content
- Open each `poem*.html` file
- Replace the sample poem text inside the `<div class="poem-content">` tag
- Update the title in the `<h1>` tag
- Make sure to keep the `pre-line` whitespace formatting for proper poetry layout

### 4. Adding More Poems
- Copy one of the existing `poem*.html` files
- Rename it to `poem6.html`, `poem7.html`, etc.
- Update the content
- Add a new list item in `index.html` with a link to the new poem

### 5. Using Your Own Images
If you want to add your photo:
- Place your photo in the same directory
- Add an img tag in the header of `index.html` like:
  `<img src="your-photo.jpg" alt="Your Name" style="max-width: 100px; border-radius: 50%;">`

## Theme Features:
- Old journal paper appearance with textured background
- Vintage border design
- Decorative elements (inksplatters, quill symbols)
- Elegant typography with classic fonts
- Antique color scheme
- Responsive design for different screen sizes
- "Back to Poems" link on each poem page

Simply open `index.html` in any web browser to view your poetic journal!