# She Matters Initiative — Website

A multi-page static website for She Matters Initiative, a Nigerian NGO empowering teenage girls.

## Pages
- `index.html` — Home page
- `about.html` — About Us
- `projects.html` — Community Projects
- `contact.html` — Contact
- `style.css` — Shared stylesheet

## Images Required
Place these image files in the same folder as the HTML files:
- `logo.jpeg`
- `outreach1.jpeg`
- `outreach2.jpeg`
- `outreach3.jpeg`

## How to Deploy on GitHub Pages (Free Hosting)

1. Create a free account at [github.com](https://github.com)
2. Click **"New repository"**
3. Name it: `shematters` (or any name you like)
4. Set visibility to **Public**
5. Click **"Create repository"**
6. Upload all files (index.html, about.html, projects.html, contact.html, style.css, and all .jpeg images)
7. Go to **Settings → Pages**
8. Under "Source", select **"Deploy from a branch"**
9. Choose **main branch / root folder**
10. Click **Save**

Your site will be live at: `https://yourusername.github.io/shematters`

## To Make the Contact Form Work
The contact form currently shows a success message only. To receive actual emails:
1. Sign up free at [formspree.io](https://formspree.io)
2. Create a new form and get your form endpoint (e.g. `https://formspree.io/f/xxxxxx`)
3. In `contact.html`, change `<form id="contactForm" onsubmit="handleSubmit(event)">` to `<form action="https://formspree.io/f/xxxxxx" method="POST">`
4. Remove the `handleSubmit` function from the script

## To Update Bank Details
In `index.html`, find the `#bank-details` section and replace the placeholder text with your actual bank name and account number.
