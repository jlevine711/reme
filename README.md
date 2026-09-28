# Reme — Real Estate Landing Page

A single-file, responsive landing page (`index.html`) for Reme's real estate business. No build step: open it in a browser, or deploy the folder to GitHub Pages, Netlify, or Vercel.

## Sections
Hero with search · Stats · About · Featured listings · Services (buy / sell / invest) · Testimonials · Contact form · Footer

## Customizing
- Every placeholder is wrapped in `[[double brackets]]`. Search for `[[` to find them all (city, phone, email, brokerage, license #, stats, listings, bio, reviews).
- **Photos:** the current images are Unsplash stock. Swap in Reme's headshot and real listing photos (e.g. drop them in an `images/` folder and update the `src` attributes).
- **Colors:** change `--accent` in the `:root` block at the top of the `<style>` tag to re-brand.
- **Contact form:** by default it opens the visitor's email app pre-filled. To receive submissions directly, point the form at a service like Formspree (instructions are in a comment above the form).
- **Testimonials:** the quotes are samples. Replace them with real client reviews before launch.

## Publishing on GitHub Pages
Repo **Settings → Pages →** deploy from the branch, root folder. The site goes live at `https://<user>.github.io/reme/`.
