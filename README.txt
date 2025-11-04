Novatis - Updated site package
Changes applied:
- Removed private address strings
- Default root redirects to nl/index.html
- Language dropdown in header for NL/EN/TR
- Hero added to main pages
- Services pages enriched (cards + SVG placeholders)
- Contact pages updated with KVK, Rotterdam, email, and Formspree action
- Modernized CSS and light minification
- Lazy-loading added for images
- Thank-you pages for form redirect created

Formspree setup:
- Form action is set to https://formspree.io/f/xovporay
- To receive emails, ensure the form is activated in your Formspree dashboard.

Deploy to GitHub Pages (simple):
1. Create a new GitHub repo and push the contents of this folder to the repo root.
2. In GitHub repository settings -> Pages, set source to branch 'main' (or 'gh-pages') and folder '/ (root)'. 
3. Save. Your site will be available at https://<username>.github.io/<repo>/nl/index.html (root redirects to nl).