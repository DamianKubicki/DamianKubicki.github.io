# Damian Kubicki — academic website

A minimalist bilingual academic website inspired by the structure of Pamela Jakiela's academic website. This is an original implementation, not a copy of another website's code or content.

## Preview on your computer

Open `index.html` in a browser to view the English version. Open `pl/index.html` to view the Polish version.

## Publish for free on GitHub Pages

1. Sign in to https://github.com and create a **public** repository named `<YOUR_GITHUB_USERNAME>.github.io` (replace with your actual GitHub username).
2. Upload **the contents of this folder** (not the ZIP itself) to the repository. Preserve the directory structure (`assets/`, `pl/`, `news/`). For easy uploads with nested folders use GitHub Desktop, Git, or drag the folder's contents into the web interface, then verify the folders.
3. Open repository **Settings → Pages**.
4. Under **Build and deployment → Source**, select **Deploy from a branch**. Choose branch `main`, directory `/(root)` and click **Save**.
5. Once deployed, open `https://<YOUR_GITHUB_USERNAME>.github.io/`.

GitHub Pages hosting is free for suitable public repositories on GitHub Free. No domain purchase is needed at this stage. Later you can buy and connect a .pl or .com domain through Settings → Pages → Custom domain; follow GitHub's DNS instructions and enable HTTPS.

## Before making the site public

- Confirm that your name, current affiliation, and project descriptions are exactly how you wish to present them publicly.
- The three publications from 2024 are now included with verified titles, authors, journal details, official publisher URLs and DOI links. The source is the publisher’s Przegląd Prawno-Ekonomiczny website; publication dates in the publisher records may differ from dates in third-party indexing services.
- The ORCID link is already active, using the verified author identifier from the publisher’s official article records. Add other profile links (Google Scholar, LinkedIn, Academia.edu) only when you provide exact URLs. Avoid posting private contact details inadvertently.
- Add a portrait if desired. The DK initials are a deliberate placeholder, not a fake picture.
- If the University's article about your internship becomes available, add its link in the news entry, while preserving an original copy of the text on your own site.
- The Athens economics university is provisionally identified as Athens University of Economics and Business, based on earlier discussion. Please confirm the university before you publish the news article.

## File structure

```
index.html                                 English homepage
pl/index.html                              Polish homepage
news/greek-research-stay/index.html        English internship news
pl/aktualnosci/staz-badawczy-grecja/index.html  Polish internship news
assets/styles.css                          Responsive visual design
.nojekyll                                  Publish static files directly
```

## How to edit the site

- **About / Research / Papers:** edit `index.html` and `pl/index.html` in a text editor or GitHub's built-in editor.
- **News article:** edit the two `news` HTML files.
- **Colors and appearance:** `assets/styles.css` includes the primary colours at the top (`:root`).
- If editing HTML is inconvenient later, we can migrate content to Markdown / Jekyll so it is easier to maintain.

No cookies, analytics, trackers, or external fonts are included.

## Academic profile links (version 2)

The homepages feature a visible academic profiles block. ORCID is active and verified via the journal website. Google Scholar, LinkedIn, and Academia.edu are intentionally inactive until their URLs are verified. Never link them to another person's account.

To activate the remaining profiles, replace their `<div class="profile-card" ...>` with `<a class="profile-card" href="YOUR_VERIFIED_URL" target="_blank" rel="noopener noreferrer"> ... </a>` in both the English and Polish homepages.

The prominent numerical counters were removed in version 2, so the site presents your research rather than drawing undue attention to the current publication count.


### Version 3 — Profile icons

The homepage now has four compact outlined profile icons (Google Scholar, ORCID, LinkedIn and Academia.edu) in both languages. These are placeholders until the owner supplies their public profile URLs. An academic CV can be added in the future as a separate menu item.

### Version 4 — Light theme

Restored the light academic palette around the profile cards while retaining all four original v3 SVG icon outlines and button shapes.

## Research interests (v5)

The English and Polish homepage now include the updated user-provided interests. The broad thematic tags are under **Research interests / Zainteresowania naukowe**. Research projects remain in a separate section; the NARDL method is not treated as the user's only research interest. Edit the About paragraph and `.interests-list` in `index.html` and `pl/index.html` to update them.


## Publications (v6)

Three real journal articles published in 2024 have been entered on both homepages. They all appear in *Przegląd Prawno-Ekonomiczny*. DOI and journal-page links point to official sources:

- Papka & Kubicki, no. 4/2024, pp. 57–76 — https://doi.org/10.31743/ppe.17680
- Kubicki, no. 3/2024, pp. 49–68 — https://doi.org/10.31743/ppe.17572
- Kubicki, no. 1/2024, pp. 61–94 — https://doi.org/10.31743/ppe.16813

The English page keeps the published Polish article titles rather than inventing translations. The public ORCID verified in publisher records is https://orcid.org/0009-0001-7566-8115.


## Affiliation (v7)

The **Affiliation / Afiliacja** section now shows only **Doctoral School, KUL / Szkoła Doktorska KUL**. The University of Western Macedonia remains mentioned solely in the context of the research internship, not as an affiliation. The navigation label has also been changed in both languages.
