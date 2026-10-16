# OUSFAL CONNECT

A static HTML, CSS, and JavaScript preview of the OUSFAL CONNECT marketplace.

## Run locally

Open `index.html` in a browser, or serve this folder with a local HTTP server, for example:

```sh
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a GitHub repository for this project. On GitHub Free, Pages requires the repository to be public.
2. Push the `main` branch to that repository.
3. In the repository, open **Settings → Pages** and select **GitHub Actions** as the build and deployment source.
4. Open the **Actions** tab and wait for **Deploy static site to GitHub Pages** to finish. The deployment job shows the published URL.

The workflow in `.github/workflows/pages.yml` publishes the root `index.html` and `assets/` directory on every push to `main`.

## Preview limitations

- This is a frontend preview. Sign-in is disabled; registration, listings, messages, and requests use browser-local storage and are not shared with other visitors.
- Example listings are sample content, not live offers from verified sellers.
- Do not put credentials, private customer information, or other secrets in this repository. A GitHub Pages site is publicly accessible.
- A production marketplace needs a backend for accounts, shared listings, messaging, image uploads, and administration.
