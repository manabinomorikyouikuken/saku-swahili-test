# Saku Saku Swahili

サクサクスワヒリ語 is a lightweight Swahili vocabulary learning app for Japanese learners.

The app is currently kept as a public test build for direct-link testing. The page intentionally uses `noindex,nofollow` and `robots.txt` disallow rules so that it does not become a search-facing public product before the vocabulary, audio, accessibility, and mobile layout checks are complete.

## Current Focus

- Swahili vocabulary practice for Japanese learners
- Card-based learning and test modes
- Local progress tracking
- Device speech playback where supported by the browser
- Larger, clearer audio controls for learners who benefit from explicit visual cues
- Accessibility improvements for keyboard operation and screen-reader-aware feedback

## Privacy

This app is a static HTML app. It does not send learning progress to a server.

Learning progress and settings are stored locally in the browser using `localStorage`. Users can export and import progress data from the app settings.

## Development

Open the app locally with a simple static server:

```bash
python3 -m http.server 8943
```

Then open:

```text
http://127.0.0.1:8943/
```

## Public-Test Policy

The current app page is intentionally excluded from search indexing:

- `index.html` includes `noindex,nofollow`
- `robots.txt` contains `Disallow: /`

If this project is later promoted from public test to a search-facing product page, update those files intentionally after a separate release review.

## License

MIT License. See `LICENSE`.
