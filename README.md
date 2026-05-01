# teaching-assets

Public CSS and asset files referenced by my course content in Codio and other learning platforms.

## What's here

This repository hosts files that need to be web-accessible to other systems but aren't large enough to justify a CDN or hosting service. Files are organized by type:

- `css/` — stylesheets
- `images/` — illustrations and graphics referenced from course content
- `data/` — sample data files (CSVs, JSON) for student exercises
- `fonts/` — typefaces

Not every directory will exist at all times. New ones are created as needed.

## How to reference a file

Files are served via GitHub Pages. To use any file from this repository, construct the URL as:

```
https://<username>.github.io/teaching-assets/<directory>/<filename>
```

For Codio specifically, paste the URL into **Course Details → Extra Guides CSS URL** for stylesheets, or reference the URL directly from markdown content for images.

## Notes

Files in this repository are public by virtue of being referenced via web URLs. Do not commit anything to this repository that should not be publicly accessible.

## License

MIT. See `LICENSE`.
