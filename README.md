# the-weekly-frames

Public image hosting for **The Weekly** newsletter.

Gmail can only display images that are already on the public web. Each issue's
in-article video frames (and the cover) live here, grouped by issue date, and
are referenced from the newsletter as:

```
https://raw.githubusercontent.com/jameschtsai/the-weekly-frames/main/<YYYY-MM-DD>/<filename>.jpg
```

Hero thumbnails in the email still come from YouTube (`i.ytimg.com`). Only the
in-article stills and the cover are stored in this repository.

Files are published as compressed JPEGs (typically under 150 KB). A GitHub
Action decodes the `.jpg.b64` payloads pushed by the magazine pipeline into
the final `.jpg` files.
