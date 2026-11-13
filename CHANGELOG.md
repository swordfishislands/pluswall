# Changelog

## 1.0.3

- Render the banner avatar and About link directly from the native Blogger Profile gadget.
- Move the native Blog Search gadget to the header and remove the duplicate search form.
- Use Blogger's built-in 1200×630 Open Graph metadata; remove duplicate tags.
- Hide the RSS link when Blogger feeds are disabled.
- Keep a local-only post-avatar fallback and the 2px banner border.

## 1.0.2

- Read post author photos from Blogger v2 `author.authorPhoto.image` instead of the legacy `.url` field.
- Set `og:image` from a 1200×630 `featuredImage`, with `postImageUrl` fallback; remove the 72px thumbnail.
- Preserve the 2px white border on the banner avatar.

## 1.0.0 — Initial public release candidate

- Google+ inspired masonry-style Blogger post wall.
- Responsive banner and profile avatar, with a 2 px white outline.
- Navigation through the native Blogger Link List gadget.
- Normal Blogger author photographs; no custom image override.
- Threaded comments, jump breaks, search, labels, and individual post views.
- Renamed internal `google-plus` selectors to `pluswall`.
- Removed obsolete Google+ sharing references and unused legacy resources.

*Release date to be added when the GitHub release is published.*
