# FAIRPASS brand guide

Version 1, Nov 23, 2026. Open `brand-guide.html` in a browser for the visual version. Tokens for code are in `tokens.css`, and the landing page (`index.html`) loads them directly.

This folder is a copy of `brand/` in the app repo, `ryankolean/fair-pass`. Change the guide there first, then copy it here so the app and the landing page stay in step.

## Name

- Always **FAIRPASS**: one word, all caps, in the wordmark, headlines and captions.
- Never Fair Pass, FairPass, Fairpass, or FP on its own.
- Social handle: `@fairpasstix`, lowercase like every handle.

## Slogan

**The price on the ticket should be the price of the ticket.**

Stacked in five lines, Anton, uppercase:

```
THE PRICE
ON THE TICKET
SHOULD BE        <- the only highlighted words
THE PRICE
OF THE TICKET.
```

- Highlight only "should be". Every other word stays Ice.
- Highlight color: magenta on blue-lead work, electric blue on magenta-lead work.
- In a caption or bio, write it as a normal sentence in sentence case.

## Color

Every FAIRPASS surface is Night. Text is Ice. Electric blue and magenta are the two accents; each piece uses one as its lead.

| Token | Hex | Use |
| --- | --- | --- |
| Night | `#0A0A12` | Every background |
| Ice | `#E8ECFF` | Text and wordmark |
| Electric blue | `#2E5BFF` | Lead accent, large type only (24 px+, or bold 19 px+) |
| Magenta | `#FF2E88` | Second accent |
| Blue tint | `#8FA6FF` | Small blue text, links |
| Ice dim | `#B9C2EC` | Labels, source lines |

| Variant | Big number and lead | "Should be" | When |
| --- | --- | --- | --- |
| Blue lead | Electric blue | Magenta | Default for everything |
| Magenta lead | Magenta | Electric blue | Every other social post, for rhythm |

- No Ice text on a magenta fill (contrast too low). Use Night text on magenta.
- One accent per element. Never fade blue into magenta.
- Success, warning and error colors in the app are semantic and separate from the brand accents.

## Type

Both fonts are free on Google Fonts.

- **Anton** (display): wordmark, headlines, prices, the big multiple, the slogan. Always uppercase, regular weight.
- **Work Sans** (body): captions, bios, website text, labels. 400 for text, 600 for uppercase labels with wide tracking.

| Role | Font | Post (1080 px) | Web |
| --- | --- | --- | --- |
| Big multiple | Anton | 300 px | 96 px |
| Headline | Anton | 96 px | 48 px |
| Slogan stack | Anton, line height 1.0 | 72 px | 40 px |
| Price | Anton | 96 px | 32 px |
| Label | Work Sans 600, caps, 0.1 em | 28 px | 12 px |
| Body | Work Sans 400 | 32 px | 16 px |

## Wordmark and profile image

- Wordmark: FAIRPASS in Anton, letter spacing 0.05 em, Ice on Night.
- Profile image: FAIR stacked over PASS, PASS in electric blue, on a Night circle.
- Clear space: at least one letter height on every side. Don't stretch, outline, shadow or re-font it.

## Post templates

- **Price Gap** (1080 x 1350): show, venue, face value, resale price, the multiple, the stacked slogan, and a source line with the site and time checked.
- **Slogan** (1080 x 1080): the stacked slogan, `@fairpasstix` and the wordmark.

## Voice

From the Detroit campaign guardrails (`marketing/detroit-price-gap/README.md` in `ryankolean/fair-pass`, draft PR 8):

- Plain and factual: short sentences, real numbers, no hype.
- Every number has a source and a time. Recheck resale prices right before posting.
- Talk about the gap, not anyone's intent. No "scam" or "illegal".
- Say "we're building" and point to the waitlist. Don't promise features the product doesn't have yet.
- Blur names, emails, order numbers and barcodes on fan receipts.

## Do and don't

- Do keep every background Night, lead with one big number, alternate blue-lead and magenta-lead posts, and highlight only "should be".
- Don't use white, gray or photo backgrounds behind the slogan, highlight other words, mix both accents in one word or gradient, or set body text in Anton.
