# Web Hoster — verified static starter

A responsive front-end MVP for creating a simple website, previewing it, saving drafts in this browser, and exporting the created site as a ZIP.

## Publish the Web Hoster app on Netlify (manual static deploy)

1. Extract this ZIP on your computer.
2. Open the extracted `web-hoster-verified` folder.
3. Open the `public` folder and confirm it contains `index.html`, `app.js`, and `styles.css`.
4. Open https://app.netlify.com/drop and sign in.
5. Drag the **`public` folder itself** into the drop area.
6. Wait for the deploy to finish, then open the URL Netlify shows.

If Netlify rejects the folder, create a new folder named `web-hoster-site`, copy the contents of `public` directly into it, and upload `web-hoster-site`. Do not upload only the ZIP file.

## What works in this starter

- Responsive dashboard and landing page
- Basic website templates and editing controls
- Preview of the website being created
- Drafts stored in the current browser
- ZIP export of the website being created

## Honest limitations

This is a **front-end starter**, not a finished multi-user hosting company. The static Netlify Drop deployment does not run backend functions. Drafts are local to the browser and do not sync across devices. Exporting a ZIP is not the same as publishing a customer's website to a new public URL. Real automatic publishing requires a secure backend, authentication, persistent storage, and a deployment provider/API. Never put private API tokens in browser JavaScript.

## Technical checks

- No build step required for the static front end.
- `public/index.html`, `public/app.js`, and `public/styles.css` are the static entry files.
- `public/app.js` passes Node.js syntax validation.
