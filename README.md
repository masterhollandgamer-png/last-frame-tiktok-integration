# Last Frame TikTok Integration

This repository hosts the public website and developer-verification materials for the Last Frame TikTok integration.

## Public URLs

- Public website: https://masterhollandgamer-png.github.io/last-frame-tiktok-integration/
- Privacy Policy: https://masterhollandgamer-png.github.io/last-frame-tiktok-integration/privacy.html
- Terms of Service: https://masterhollandgamer-png.github.io/last-frame-tiktok-integration/terms.html

## Desktop Login Kit callback

`http://127.0.0.1:48721/callback/`

The localhost callback is handled by the Last Frame desktop application. GitHub Pages is a public static site; it does not contain OAuth secrets, perform token exchange, or store credentials.

## TikTok verification files

When TikTok supplies a verification or signature file:

1. Preserve the exact filename.
2. Preserve the exact file contents.
3. Place it in the exact path TikTok requests.
4. Commit the unchanged file.
5. Push it to `main`.
6. Wait for the GitHub Pages deployment to complete.
7. Verify that the exact public verification URL loads successfully.
8. Complete verification inside TikTok Developer.

If TikTok requires URL-prefix verification, preserve the requested path exactly. Never invent a verification token or file.

## Security boundary

Never commit client secrets, access or refresh tokens, authorization codes, passwords, private keys, OAuth credential files, keyring exports, or `.env` files. The desktop OAuth and token-storage architecture remains outside this repository.
