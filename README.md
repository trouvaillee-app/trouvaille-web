# Trouvaille Web

Official website for **Trouvaille: Camera & Editor**, a film camera, photo editor, and composition studio for iPhone. Part of Syntheticae Group.

## Local preview

```sh
npx wrangler pages dev .
```

This previews the static website and the retirement notice for legacy recipe URLs.

## Cloudflare Pages

Import this repository in Cloudflare Pages and use these build settings.

| Setting | Value |
| --- | --- |
| Production branch | `main` |
| Framework preset | None |
| Build command | `exit 0` |
| Build output directory | `.` |

The public review pages are `/privacy`, `/terms`, and `/support`.

[Cloudflare Pages static HTML guide](https://developers.cloudflare.com/pages/framework-guides/deploy-anything/)
