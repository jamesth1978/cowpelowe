# Cowpe Lowe Engineering Static Website

This is a static replica of the Cowpe Lowe Engineering website, built using HTML, CSS, and Bootstrap for simplicity and ease of editing.

## Files

- `index.html`: The main webpage
- `style.css`: Custom styles
- `assets/images/`: Images used on the site

## Hosting on GitHub Pages

The site is hosted on GitHub Pages at https://jamesth1978.github.io/cowpelowe/

To enable custom domain (cowpelowe.co.uk):

1. Go to the repository settings on GitHub.
2. Scroll to "Pages" section.
3. Select "Deploy from a branch" and choose "main".
4. Save.

For custom domain:

- The CNAME file is already added with "cowpelowe.co.uk".
- In your domain registrar (where cowpelowe.co.uk is registered), set the DNS records:
  - For apex domain: Add A records pointing to:
    - 185.199.108.153
    - 185.199.109.153
    - 185.199.110.153
    - 185.199.111.153
  - Or if using www, CNAME www to jamesth1978.github.io

## Editing the Site

- Edit `index.html` to change content.
- Edit `style.css` to change styles.
- Replace images in `assets/images/` as needed.

## Contact Form

The contact form is currently non-functional as it's static. To make it work, integrate with a service like Formspree or Netlify Forms.
Static site for Cowpe Lowe
