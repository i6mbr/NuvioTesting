# Nuvio Artwork Library

Personal artwork repository for Nuvio collection covers.

## Folder structure

- `actors/`
- `directors/`
- `genres/`
- `franchises/`
- `studios/`
- `streaming/`
- `decades/`
- `awards/`
- `holidays/`
- `based-on/`
- `now-on-nuvio/`

## Image standards

### Poster
- Aspect ratio: 2:3
- Recommended size: 1200 × 1800 px
- Best for: actors, directors, awards, and poster-style collections

### Landscape
- Aspect ratio: 16:9
- Recommended size: 1920 × 1080 px
- Best for: genres, streaming services, studios, decades, franchises, and general collection covers

## Naming rules

- Use lowercase filenames
- Use hyphens instead of spaces
- Keep filenames stable after they are used in Nuvio
- Prefer `.jpg` for photographic artwork
- Prefer `.png` for artwork that needs transparency

Examples:

```
actors/robert-de-niro.jpg
directors/christopher-nolan.jpg
genres/horror.jpg
franchises/star-wars.jpg
streaming/netflix.png
```

## Direct image URL format

Files in this public repository can be used in Nuvio with raw GitHub URLs:

```
https://raw.githubusercontent.com/i6mbr/NuvioTesting/main/<folder>/<filename>
```

Example:

```
https://raw.githubusercontent.com/i6mbr/NuvioTesting/main/actors/robert-de-niro.jpg
```

## Important

Once an image URL is used in Nuvio, avoid renaming or moving that file. Replacing the image while keeping the same path is safe and lets the Nuvio JSON keep the same URL.
