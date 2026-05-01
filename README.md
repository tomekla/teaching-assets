# teaching-assets

Public CSS and asset files referenced by my course content in Codio and other learning platforms.

## What's here

This repository hosts files that need to be web-accessible to other systems (primarily Codio) but aren't large enough to justify a CDN or hosting service. GitHub serves the raw files directly, which is sufficient for the modest traffic of course rendering.

## Files

### `codio-book.css`

Custom CSS applied at the course level in Codio. Constrains image sizing so that large illustrations don't force the page layout wider than the content area.

To use this in a Codio course, copy the raw URL of this file:

```
https://raw.githubusercontent.com/<username>/teaching-assets/main/codio-book.css
```

Then in Codio: **Courses → [your course] → Course Details → Extra Guides CSS URL**, paste the URL, save.

The CSS will be loaded in addition to Codio's default styles for every page in every assignment in that course.

## Notes

Files in this repository are public by virtue of being referenced via raw GitHub URLs. Do not commit anything to this repository that should not be publicly accessible.

## License

Content in this repository is released under the MIT License unless otherwise specified.
