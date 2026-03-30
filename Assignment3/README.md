Personal Blog Project

A multi-page, responsive static personal blog built with HTML5 and CSS3.

Implemented Features

1. Website Structure & Semantic HTML

Homepage (index.html): Includes a blog title, navigation bar, short introduction, and a preview grid of the latest blog posts.

Blog Entries : Five individual blog posts featuring a title, author name, date, formatted content, and header images.

Semantic Structure: Extensive use of HTML5 tags (<header>, <nav>, <main>, <section>, <article>) to ensure content separation from presentation.

2. Required CSS Selectors

The style.css demonstrates the following required selectors:

Element Selectors: body, h1, nav

Class Selectors: .container, .blog-card, .page-section

ID Selectors: #message, #name, #email

Grouping Selectors: h1, h2, h3, h4

Attribute Selectors: input[type="text"], article a[href^="https"]

Combinator Selectors: .blog-card > img (Child), nav a (Descendant)

3. Box Model Implementation

The CSS box model is actively controlled throughout the application:

Margin & Padding: Used extensively to dictate flow and whitespace (e.g., .container padding, main margins).

Border: Applied to .blog-card and form inputs for definition.

Width and Height: Controlled via max-widths (.container), responsive percentages (Flexbox item bases), and set heights (e.g., #message { min-height: 150px; }).

4. Typography, Colors & Gradients

Typography: Utilizes clean Arial, sans-serif scaling with distinct line heights for readability.

Backgrounds & Gradients: A seamless linear-gradient is applied to the base body, shifting cleanly from light blue to white. Blog cards and containers utilize contrasting solid backgrounds.

5. Navigation Bar Styling

Layout: A fully horizontal layout utilizing Flexbox.

Interactivity: Features styled links with distinct borders and background transitions on hover, creating a tactile user experience.

6. Layout System

Flexbox Grid System: The blog feed (.blog-grid) uses a flexible layout (display: flex; flex-wrap: wrap;) that automatically adjusts column widths, organizing cards smoothly.

7. Pseudo Classes

Interactive CSS effects are implemented using all three required pseudo-classes:

:hover - Elevates blog cards (transform) and changes button/link backgrounds.

:active - Applied to navigation links.

:focus - Highlights form inputs to aid accessibility.

8. Responsive Design 

Media Queries: Breakpoints (@media (max-width: 768px), 600px, 480px) ensure the layout adapts. Flexbox containers switch from multi-column rows to single-column stacks on mobile.

9. Form Styling 

Contact Form: Located in contact.html, featuring fully styled name, email, and message fields, alongside a custom submit button with transition effects.

Project Structure

- blog-site/index.html - Homepage.

- blog-site/blog.html - The main blog feed containing all published articles.

- blog-site/about.html - A brief biography page.

- blog-site/contact.html - Styled contact form interface.

- blog-site/Blog1.html to blog-site/Blog5.html - The five required blog entries.

- blog-site/css/style.css - The external stylesheet.

- README.md - The documentation.