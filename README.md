# Ose Prosper

AI Automation Engineer portfolio — n8n, Claude & CRM Integrations.

A clean, single-page portfolio build for Ose Prosper. Shows services, case studies, an insights section, and a contact form.

## Tech stack

- HTML5
- CSS3 (custom, no framework) — `assets/css/style.css`
- Vanilla JavaScript (no build step)
- Fonts: **JetBrains Mono** (body/mono), **Instrument Serif** (headings)

## Folder structure

```
Ose Prosper/
├── index.html
├── README.md
├── package.json
├── .gitignore
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   └── images/
│       └── ose-photo.jpg   <-- add your photo here
```

## Getting started

Open `index.html` directly in a browser, or serve it locally:

```bash
# Using Python
python -m http.server 8000

# Using Node (if you have http-server)
npx http-server
```

Then visit `http://localhost:8000`.

## Configuration

Edit the `CONFIG` object at the top of the `<script>` block in `index.html`:

```js
const CONFIG={
  whatsapp:"YOUR_NUMBER",
  linkedin:"YOUR_LINKEDIN_URL",
  upwork:"YOUR_UPWORK_URL",
  email:"YOUR_EMAIL",
};
```

Replace `assets/images/ose-photo.jpg` with your own headshot.

## Colors

- Background: near-black `#0a090f` (`--d`)
- Panel: dark slate `#11101b` (`--p`)
- Accent: indigo `#7c83ff` (`--y`) — replaces the original lime green
- Muted: `#rgba(255,255,255,.72)` (`--m`)

## License

MIT — free to use and adapt for your own portfolio.
