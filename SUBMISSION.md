# Obsidian Community Plugin Submission

## community-plugins.json Entry

```json
{
  "id": "memo-timeline-feed",
  "name": "Memo Timeline Feed",
  "author": "lbb2445",
  "description": "Display #timeline notes, diary-style feeds, and image-only galleries in a polished Obsidian view.",
  "repo": "lbb2446/bestmemo"
}
```

## Pull Request Title

```text
Add plugin: Memo Timeline Feed
```

## Pull Request Description

```md
<!-- Keep the upstream PR template structure. Only fill in the fields and checkboxes. -->

## Summary

Adds `Memo Timeline Feed`, an Obsidian plugin for browsing notes in three visual modes:

- Timeline view for notes tagged with `#timeline`
- Diary Feed view for daily notes and diary-style content
- Photos view for image-only browsing

## Repository

- Repo: https://github.com/lbb2446/bestmemo
- Release tag: 1.0.0

## Checklist

- [x] I have read the developer policies.
- [x] I have verified that the plugin version matches the release tag.
- [x] I have included `README.md`, `LICENSE`, and `manifest.json` in the repository root.
- [x] I have attached `main.js`, `manifest.json`, and `styles.css` to the GitHub release.
- [x] I have tested the plugin in Obsidian.
```

## Submission Steps

1. Push `main` and `v1.0.0` to GitHub.
2. Create a GitHub release with tag `1.0.0`.
3. Upload `main.js`, `manifest.json`, and `styles.css` as release assets.
4. Fork or open the Obsidian community plugins repository.
5. Append the JSON entry above to `community-plugins.json`.
6. Open a pull request using the upstream template. Do not remove any sections from the template.
