# Nguyen Vo An Vi - AI Engineer Portfolio

A responsive one-page static portfolio. It does not need Node.js, a database, environment variables, or a backend.

## Preview locally

Open `index.html` directly in a browser, or run a local server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy on Vercel

1. Create a GitHub repository, for example `ai-engineer-portfolio`.
2. Extract the ZIP and push **all extracted files** to the repository root. Do not upload only the ZIP file.
3. In Vercel, choose **Add New > Project** and import the repository.
4. Choose **Other** as the framework preset if Vercel does not detect it automatically.
5. Leave Build Command empty and set Output Directory to `.` if Vercel asks.
6. Click **Deploy**.

## Do I need Render?

No. This portfolio is a static frontend, so Vercel alone is enough. Render is only needed for a separate backend/API such as the FastAPI backend of the UIT Chatbot.

## Edit content

- Main content: `index.html`
- Visual design: `styles.css`
- Small reveal animation: `script.js`
- Downloadable CV: `public/Nguyen_Vo_An_Vi_CV.pdf`

When your CV changes, replace the PDF while keeping the same filename.
