# Aide by TAG Sleaford

Static site for Aide, a trading name of TAG Sleaford Ltd (company number 12870323).

- Preview: https://wilsonclawde-cpu.github.io/aide/
- Hosting: GitHub Pages, branch `main`, folder `/` (root)
- Final address: aide.tagsleaford.com. There is deliberately no `CNAME` file yet. Add one (containing `aide.tagsleaford.com`) only once DNS points at GitHub.
- sitemap.xml and robots.txt already use the final address.

## Files
- index.html: home page, price list and enquiry form
- directory.html: Lincolnshire Directory (listing data is the `LISTINGS` block in its script)
- privacy.html, terms.html: drafts, need review and the `[DATE]` filled in

## Before it goes live
- Enquiry form: GitHub Pages cannot run server code. Until a form endpoint is set (`FORM_ENDPOINT` near the bottom of index.html), the form opens the visitor's email app addressed to aide@tagsleaford.com.
- Add Stripe Payment Links to `STRIPE_LINKS` in index.html.
- Confirm addresses for any listing that has none.
