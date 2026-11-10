# Christmas list

A simple wish list website. You edit one file, `items.json`, and the page updates.

## Add an item

Open `items.json` and add an entry:

```json
{
  "title": "Cast iron skillet",
  "url": "https://example.com/skillet",
  "description": "10 inch, pre-seasoned.",
  "price": "$30"
}
```

- `title` is required.
- `url`, `description` and `price` are optional.
- Separate entries with commas, and don't put a comma after the last one.
- You can edit the file right on GitHub: open `items.json`, click the pencil icon, then **Commit changes**.

## Publish it (GitHub Pages)

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. After a minute your list is live at `https://<your-username>.github.io/<repo-name>/`.

## Preview locally

The page loads `items.json`, so open it through a local server rather than double-clicking:

```
python3 -m http.server
```

Then visit http://localhost:8000.
