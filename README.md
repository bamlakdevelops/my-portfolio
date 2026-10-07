# Personal Portfolio Website

This project is a polished one-page portfolio inspired by the screenshots you provided.

## Files

- `index.html` — the main webpage
- `style.css` — custom styling
- `thank-you.html` — optional thank-you page
- `assets/` — placeholder images you can replace with your own

## Open it

1. Open the folder in VS Code.
2. Open `index.html`.
3. Run it with Live Server if you have the VS Code Live Server extension.
4. You can also double-click `index.html` to open it directly in a browser.

## IMPORTANT: make the contact form use your email

Open `index.html` and find:

```html
action="https://formsubmit.co/YOUR_EMAIL@example.com"
```

Replace `YOUR_EMAIL@example.com` with the email address where you want to receive messages.

Also replace the email shown in the contact section:

```html
YOUR_EMAIL@example.com
```

The form uses FormSubmit, which allows a static HTML website to submit a form without you building a backend server. On the first submission, the service may ask you to confirm/activate the receiving email address.

If you later put the site on a real domain, you can also enable the `_next` redirect to `thank-you.html`.

## Replace the placeholders

Search for `YOUR NAME` and replace it with your real name.

Replace:

- `assets/profile-placeholder.svg` with your own photo
- the 3 project images with screenshots of your real projects
- the LinkedIn and GitHub `href="#"` values with your real links
- project titles/descriptions/links

## Bootstrap

The page uses Bootstrap 5.3.8 through the official jsDelivr CDN links.

You are also using custom CSS in `style.css` so you can keep practicing the CSS you are learning while still using Bootstrap for the layout, grid, buttons, forms, navbar, and responsive behavior.
