# krzysztof-walas — personal page

A single-file, dependency-free personal homepage for roboticist **Krzysztof Walas**, ready for GitHub Pages.

```
index.html     the whole site (HTML + CSS inline)
assets/        portrait, social card (og:image) and selected-work thumbnails (.jpg)
robots.txt     allows all crawlers, points to the sitemap
sitemap.xml    single-URL sitemap
README.md      this file
```

## Deploy on GitHub Pages (about 2 minutes)

1. Create a repository named `<your-github-username>.github.io` (the site will then live at
   `https://<your-github-username>.github.io/`). Any other repo name works too — the URL becomes
   `https://<username>.github.io/<repo>/`.
2. Add `index.html`, `README.md` and the `assets/` folder to the repository root and push to `main`.
3. In the repository go to **Settings → Pages**, set **Source** to *Deploy from a branch*, pick **main** and **/ (root)**, save.
4. Wait a minute and open the URL shown on that settings page.

No Jekyll, no build step, no analytics. Custom domain: add a `CNAME` file containing the domain and point the DNS at GitHub Pages.

## Photo and images

The portrait is `assets/krzysztof-walas.jpg` (640×640). Selected-work thumbnails are shown at 16:9 with
`object-fit: cover`, so other aspect ratios are cropped. `assets/social-card.jpg` (1200×630) is the preview
image used by link unfurls.

## Domain

The canonical URL, Open Graph tags, JSON-LD in `index.html`, `robots.txt` and `sitemap.xml` all use
`https://christow.github.io/`. Update them together if the site moves to its own domain.

## Where the content came from

Everything on the page was taken from public sources, checked on 29 Aug 2026, except the Lute role and its
2026 start date, which were confirmed directly. Please read it through once — in particular the dates in the
*Bio* timeline and the INTENTION start date, which the sources do not state.

The page deliberately carries **no email address, postal address or phone number**. Contact runs through the
linked profiles only. If you add a contact route later, put it in the `#contact` section.

| Content | Source |
|---|---|
| Lute, CTO role and company description | Confirmed directly by Krzysztof Walas; company copy from the `website` repo (lute.one) |
| Lute product details — order picking at 40k+ SKUs, sub-mm wire threading, fleet/MES tooling, offices | lute.one site content (`website` repo: `content/blog-posts.ts`, `content/business.ts`, `content/site-config.ts`) |
| OpenGVL benchmark | https://arxiv.org/abs/2509.17321 |
| Bio, degrees, postdoc, LIDER/THING/REMODEL, ELLIS membership | https://ideas-ncbr.pl/en/krzysztof-walas-joins-ellis-society/ and https://ellis.ideas.edu.pl/people/ |
| Current PUT role, ORCID, LinkedIn | https://robotics.put.poznan.pl/perception-for-physical-interaction/ |
| Project dates, funders and PI role | https://robotics.put.poznan.pl/research-projects/ |
| REMODEL details | https://cordis.europa.eu/project/id/870133 |
| THING details | https://cordis.europa.eu/project/id/780883 |
| INTENTION project and team | https://intention.put.poznan.pl/ |
| Adra Board of Directors (June 2024) | https://ideas-ncbr.pl/en/krzysztof-walas-joins-adra-board-of-directors/ and https://adr-association.eu/index.php/about-us |
| IDEAS Research Institute affiliation | https://ellis.ideas.edu.pl/people/ |
| Science Robotics article | https://doi.org/10.1126/scirobotics.adp1956 |
| Other publications | ResearchGate / SciProfiles / dblp / publisher pages for each item |
| Google Scholar | https://scholar.google.com/citations?user=0FZ0cZQAAAAJ |
| LinkedIn | https://www.linkedin.com/in/krzysztof-walas-850492a7/ |
| X | https://x.com/KrzysztofTWalas |

## Editing

- Colours, fonts and spacing are CSS variables at the top of `index.html` (`:root`).
- Fonts load from Google Fonts (Inter) with system fallbacks.
