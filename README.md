# Y. William Zheng — research portfolio (website source)

Source for <https://williamyixiangzheng.github.io/WYZ-Neuro-Portfolio/>.

A dependency-free static site: hand-written HTML with a single shared stylesheet
(`assets/site.css`), deployed through GitHub Pages. There is no build step — edit the
HTML and push.

## Pages

| File | Purpose |
| --- | --- |
| `index.html` | Homepage: hero, research interests, four featured projects, contact |
| `research.html` | All projects, grouped as current / published / earlier |
| `software.html` | Analysis workflows and computational work |
| `publications.html` | Preprints, manuscripts in preparation, presentations, non-author contributions |
| `about.html` | Research trajectory and how I approach research |
| `writing.html` | Course and concept proposals (not active projects) |
| `Project_*.html`, `Research_In_Peking_University.html` | Individual project pages |
| `proposals.html` | Redirect to `writing.html` (kept for old inbound links) |

## Editing notes

- Every page links `assets/site.css`; do not add page-level `<style>` blocks.
- The sidebar navigation is duplicated per page. Mark the current page with
  `aria-current="page"`.
- Unpublished projects must not carry results, statistics, participant information, or
  manuscript figures. Status labels come from a fixed set: Published, Preprint, Under
  review, Manuscript in preparation, Ongoing, Earlier research experience, Concept
  proposal.
- Search `TODO` for items that need confirmation or PI approval before they go public.
