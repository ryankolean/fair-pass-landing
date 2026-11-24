# FAIRPASS landing page

Single-file static site (`index.html`) served by GitHub Pages from `main`. The brand guide it follows is in `brand/` (copied from the app repo, `ryankolean/fair-pass`).

## Email signup (Kit)

The waitlist form signs people up for FAIRPASS app updates through a Kit (kit.com) form. No API key is used or needed.

1. In Kit, create (or open) the FAIRPASS form and choose **Embed > HTML**.
2. Copy the form's `action` URL. It looks like `https://app.kit.com/forms/1234567/subscriptions`.
3. In `index.html`, set `const KIT_FORM_ACTION = '...'` to that URL.

Until `KIT_FORM_ACTION` is set, the form falls back to opening an email to `waitlist@fairpass.io`.

The Fan / Venue / Artist toggle is only included in that fallback email for now. To keep it in Kit, add a custom field or tags to the Kit form and send them from the submit handler.

## Social links

- Instagram: `@fairpasstix`, linked in the waitlist section and the footer.
- Facebook: the links are in place but carry `hidden` until the FAIRPASS Page is live. Remove `hidden` from both `data-social="facebook"` links to show them.
