# Aide by TAG Sleaford

Static site for Aide, a trading name of TAG Sleaford Ltd (company number 12870323).

- Preview: https://wilsonclawde-cpu.github.io/aide/
- Hosting: GitHub Pages, branch `main`, folder `/` (root)
- Final address: aide.tagsleaford.com. There is deliberately no `CNAME` file yet. Add one (containing `aide.tagsleaford.com`) only once DNS points at GitHub.
- sitemap.xml and robots.txt already use the final address.

## Files
- index.html: home page, price list and enquiry form
- directory.html: Lincolnshire Directory (listing data is the `LISTINGS` block in its script)
- privacy.html, terms.html: drafts dated 2 October 2026; adviser-review placeholders in square brackets remain

## Before it goes live
- Enquiry form: posts to Web3Forms (key in `WEB3FORMS_KEY`, near the bottom of index.html), delivering to the TAG Sleaford inbox. For a dedicated Aide inbox, create a Web3Forms key for aide@tagsleaford.com and replace the key.
- Add Stripe Payment Links to `STRIPE_LINKS` in index.html.
- Confirm addresses for any listing that has none.
