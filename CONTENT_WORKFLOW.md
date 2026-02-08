# Blog Content Workflow (Local Edit + GitHub Publish)

This blog is a static Hugo site.

## Author workflow

1. Edit or create posts locally in `content/posts/`.
2. Preview locally with Hugo.
3. Commit and push to `master`.
4. GitHub Actions builds and deploys the static site.

## Create a post

Use Hugo CLI:

```bash
hugo new posts/my-new-post.md
```

Then edit the generated file and set `draft = false` when ready to publish.

## Notes

- No in-site admin or CMS is used.
- Readers can only read the published static site.
