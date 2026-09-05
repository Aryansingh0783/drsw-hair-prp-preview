# Dr SW Clinics Hair PRP previews

Draft landing pages for internal review. **The forms are not connected to anything.** Not for distribution, and not to be put in front of a patient.

Three design variations of one Hair PRP package, each with its own thank-you page.

## Start here

The current set is in [`rev-05-sep/`](rev-05-sep/), revised to Allen's copy and layout brief of 5 September 2026.

| Page | File | Preview |
| --- | --- | --- |
| V1 landing | [`rev-05-sep/v1-offer.html`](rev-05-sep/v1-offer.html) | https://aryansingh0783.github.io/drsw-hair-prp-preview/rev-05-sep/v1-offer.html |
| V1 thank-you | [`rev-05-sep/v1-thankyou.html`](rev-05-sep/v1-thankyou.html) | https://aryansingh0783.github.io/drsw-hair-prp-preview/rev-05-sep/v1-thankyou.html |
| V2 landing | [`rev-05-sep/v2-education.html`](rev-05-sep/v2-education.html) | https://aryansingh0783.github.io/drsw-hair-prp-preview/rev-05-sep/v2-education.html |
| V2 thank-you | [`rev-05-sep/v2-thankyou.html`](rev-05-sep/v2-thankyou.html) | https://aryansingh0783.github.io/drsw-hair-prp-preview/rev-05-sep/v2-thankyou.html |
| V3 landing | [`rev-05-sep/v3-outcome.html`](rev-05-sep/v3-outcome.html) | https://aryansingh0783.github.io/drsw-hair-prp-preview/rev-05-sep/v3-outcome.html |
| V3 thank-you | [`rev-05-sep/v3-thankyou.html`](rev-05-sep/v3-thankyou.html) | https://aryansingh0783.github.io/drsw-hair-prp-preview/rev-05-sep/v3-thankyou.html |

The files at the top level of this repository are the earlier 4 September build. They are kept unchanged for comparison and are not the current version.

## Working with the HTML

Each page is one self-contained HTML file. The CSS sits in a `<style>` block in the head, every selector is scoped under `.lp`, and there are no external stylesheets, fonts or scripts. The only external link on a page is the clinic's privacy policy beside the form. V2 carries one inline script, at the end of the body, which drives its carousel. Without it the carousel becomes a swipeable row.

Images use relative paths under `assets/`. During funnel assembly each one is uploaded to the GoHighLevel media library and its `src` replaced.

To download a single file, use its raw URL:

```
https://raw.githubusercontent.com/Aryansingh0783/drsw-hair-prp-preview/main/rev-05-sep/v1-offer.html
```

Or clone the lot:

```
git clone https://github.com/Aryansingh0783/drsw-hair-prp-preview.git
```

## Before any of this goes live

- The forms have no endpoint, no lead destination and no redirect. Nothing launches until a real test submission has confirmed all three on each page, and no thank-you page may appear after a failed submission.
- Answers are still needed from the clinic, including the infrared description, the wording for the scalp microneedling step, and patient consent and case history for the before-and-after photographs. The pages carry no invented copy in place of any of it. The full list is in the handoff.
- Every page carries a `noindex` tag and `robots.txt` disallows crawling.
