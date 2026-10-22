# InterPoP website

A small static landing page for InterPoP. It introduces the current product features and provides links to the macOS download and browser app.

## Preview locally

Run this command from the repository root:

```bash
python3 -m http.server 4173 --bind 127.0.0.1
```

Then open <http://127.0.0.1:4173/>.

## Placeholder URLs

Before publishing, replace these placeholder URLs in `index.html`:

- macOS download: `https://downloads.example.com/interpop/InterPoP-0.1.0-arm64-mac.zip`
- browser app: `https://app.example.com/interpop`

The macOS archive should normally live in the application repository's GitHub Releases or in object storage instead of this website repository.
