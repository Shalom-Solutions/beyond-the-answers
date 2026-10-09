# Beyond the Answers

A mobile-first relationship reflection website. It is intentionally static: no account, server, or automatic response sharing is used.

## Privacy and saving
- Answers and progress are saved in the current browser's `localStorage` on the current device.
- Responses are not uploaded or automatically sent to anyone.
- If the user clears browser data, uses private browsing, or changes device/browser, locally saved responses may be lost.
- The user can export reflections as a `.txt` file from the closing screen.

## Run locally
Open `index.html` in a browser. For a local web server, from this folder run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish online with Vercel (static site)
1. Create a GitHub repository and upload `index.html` (and optionally this README) to the repository root.
2. Sign in to Vercel and choose **Add New → Project**.
3. Import the GitHub repository.
4. For a plain static HTML site, no framework is required. Leave build command and output directory blank if Vercel permits, or use the static deployment defaults. If prompted for a framework, select **Other**.
5. Deploy. Vercel will give you an HTTPS URL to share.

Alternative: use Netlify's manual deploy by dragging the `beyond-the-answers` folder into its deploy area. Do not include personal answers in the published folder.

## Important
The URL is public to anyone who receives it; this version does not require a passcode. The answers themselves remain local to the browser and are not visible to the site owner. If you want an access code or synced answers later, add a proper authentication/storage design and explain the sharing rules clearly before collecting responses.
# beyond-the-answers
