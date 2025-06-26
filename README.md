
# Pure Water Analytics Website

## How to Upload to GitHub Pages

1. Create a new repository on GitHub or use an existing one.
2. Upload the contents of this folder (`index.html` and `logo.png`) to the repository.
3. In the repository settings, scroll down to the **GitHub Pages** section.
4. Set the source branch to `main` (or `master`) and folder to `/ (root)`.
5. Save settings. Your site will be published at `https://yourusername.github.io/repositoryname/`.

## Updating the Contact Form

This website uses [Formspree](https://formspree.io/) for the contact form.

1. Sign up for a free Formspree account.
2. Create a new form and get your form endpoint URL.
3. Replace the `action` attribute URL in the `<form>` tag in `index.html`:

```html
<form action="https://formspree.io/f/your-form-id" method="POST">
```

Change `"https://formspree.io/f/your-form-id"` to your actual form endpoint URL.

## Replace the Logo

Replace `logo.png` with your own logo file. Make sure it is named `logo.png` and placed in the same directory as `index.html`.

## Contact

For any issues, reach out to support@purewateranalytics.com.
