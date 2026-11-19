# Discoverability and Metadata Starter

Use this small site for Module 6 practice if you do not want to use your capstone yet.

## Files

- `index.html`: sample page with intentionally weak metadata and link text.
- `styles.css`: simple styling so the page can be inspected in a browser.
- `garden-workshop.svg`: sample image asset.

## Practice goal

Improve:

- page title
- meta description
- crawlable/descriptive links
- canonical decision
- image filename/context/alt decision
- social preview metadata
- structured-data decision
- ranking-claim limits

Document each change and what evidence supports it.

## Module 6: Metadata and Crawlability Lab
Kiara McRae

### Title and description
I replaced the “Home” with “Garden Skills Day | Free Community Gardening Workshop.” I also replaced the description with: “Explore a free neighborhood workshop covering container gardening, accessible garden paths, desert shade, and seasonal maintenance.” Both reflect the visible workshop content.

### Internal links
I replaced the three navigation labels with:
- “Garden Skills Day home” linking to `index.html`
- “Workshop schedule” linking to `#schedule`
- “Registration information” linking to `#register`


### Canonical decision
One note I will add here is that I intentionally omitted a canonical tag because this is a local practice page without a confirmed public URL. I documented this decision in an HTML comment inside the `<head>`. After publication, I would of course add the final public URL.

### Image context
For the image context, I kept the descriptive filename `garden-workshop.svg` and replaced the plain alt text “image” with `alt=""`. The illustration is decorative, and the adjacent heading and paragraph provide the workshop information that is necessary here.

### Source inspection
I also inspected the page using Chrome’s View Page Source. The title, meta description, and canonical decision comment appear inside the `<head>`, before the stylesheet link. The navigation links and decorative image appear in the `<body>`. Evidence is saved under the evidence folder as `m6-page-source.png`.

### Unsupported ranking claim
I would definitely not claim that these changes guarantee a first place search ranking or increased traffic. They make the page’s purpose more clear without proving a ranking outcome.

### AI disclosure
For this week, I used ChatGPT to help draft metadata and identify some checks I was missing. I applied all of the changes and reviewed the page source myself.