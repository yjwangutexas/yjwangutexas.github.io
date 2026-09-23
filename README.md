# Yijie Wang — academic website

A responsive, plain HTML/CSS academic website for **https://yjwangutexas.github.io/**. No build step or external fonts are required. Cloudflare Web Analytics uses a JavaScript beacon for traffic statistics; the page content works without JavaScript.

## Traffic analytics

Cloudflare Web Analytics is installed at the end of `index.html`. Reports are available in the owner's Cloudflare dashboard; no traffic counts or reports are displayed on the public homepage. The beacon token is a public collection identifier, not a credential for viewing reports. Analytics begin after installation and may miss visits when the beacon is blocked.

## Deployment checklist

1. Sign in to GitHub as **yjwangutexas** and create a public repository named **yjwangutexas.github.io** (or open that repository if it already exists).
2. Upload the contents of this folder to the repository's **main** branch. Put `index.html` directly at the repository root, alongside `style.css`, `.nojekyll`, and `assets/`. Do not upload the ZIP itself or nest the files inside another folder. If uploading through the website omits `.nojekyll`, create an empty file with that name in the repository.
3. Open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose **main** and **/ (root)**, then **Save**.
4. Wait for the Pages deployment to finish (changes can take up to 10 minutes). Visit **https://yjwangutexas.github.io/**.
5. Check the portrait, navigation, Google Scholar, publication links, and working-paper links. Check the page on a phone as well as a computer. If replacing an older version that included `files/CV_Yijie_Wang.pdf`, remove that old file from the repository as well.

Official instructions: [GitHub Pages quickstart](https://docs.github.com/en/pages/quickstart).

## Files

- `index.html` — all website content, grouped by named sections.
- `style.css` — typography, colors, responsive layout, and print styles.
- `assets/portrait.png` — the supplied portrait, unchanged.
- `.nojekyll` — serves the repository as a plain static website.

## Preview and maintenance

Open `index.html` in a browser to preview locally; no installation is necessary. Edit the text in `index.html` to update content. Replace the portrait at the same path to update the photo. Commit changes to `main` to update the published site.

The biography, education, experience, awards, service, and presentations are based on the supplied CV. The biography is adapted to first person. Education and Experience are independent sections. Teaching, CV downloads, and working-paper submission/review statuses are omitted at the owner's request.

Both email displays use `yijiewang [at] tongji.edu.cn`, with no mailto link or unobfuscated address in the HTML. The phone number and telephone link are removed. The original CV PDF is not included in this deployment package. The design uses restrained academic typography and a muted red accent; no MIT logo or affiliation is implied.

## Verified research links

The working-paper list follows the six publicly accessible working papers in the owner's [Google Scholar profile](https://scholar.google.com/citations?user=5BlufRsAAAAJ&hl=en), checked on September 23, 2026. Titles and author lists follow the linked public records; unpublished CV-only entries are excluded. Each working paper has a verified NBER or arXiv link:

- Machine Learning Meets Markowitz: https://www.nber.org/papers/w34861
- Gaussian mixtures: https://arxiv.org/abs/2509.14557
- Targeted integral probability metrics: https://arxiv.org/abs/2607.05731
- Legendre-regularized policies: https://arxiv.org/abs/2607.24007
- Quick response models: https://arxiv.org/abs/2508.00541
- Kernel regression: https://arxiv.org/abs/2407.10764

The four publication titles link to their official article pages or full text. The first publication's title uses the published “Prescriptive Analytics” wording. Existing CV author asterisks are retained for publications without assigning a meaning; working-paper author lines follow the public bibliographic records without asterisks.

- Prescriptive analytics: https://pubsonline.informs.org/doi/10.1287/msom.2024.0997
- Fairness constraints: https://pubsonline.informs.org/doi/10.1287/msom.2022.0230
- Strategic queues: https://pubsonline.informs.org/doi/10.1287/stsy.2022.0009
- Performative optimization (official full-text PDF): https://proceedings.neurips.cc/paper_files/paper/2025/file/cd97da5366de69250442901abcdd4c0a-Paper-Conference.pdf

This package is ready to upload. It does not itself create a GitHub repository or publish the website.

## Paper ordering

Both lists are ordered newest first by publication or first public release, not the latest preprint revision. Publications: prescriptive analytics (2026), performative optimization (NeurIPS 2025, following the official proceedings year), strategic queues (May 16, 2024), fairness constraints (April 30, 2024). Working papers: Legendre policies (July 27, 2026), targeted IPM (July 7, 2026), Machine Learning Meets Markowitz (February 2026), Gaussian mixtures (September 18, 2025), quick response (August 1, 2025), kernel regression (July 15, 2024). The grant number is omitted from the homepage.
