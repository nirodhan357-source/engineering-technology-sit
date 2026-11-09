# Engineering Technology static site

The live GitHub Pages site is published from the `main` branch of `nidarshanadaham-ux/engineering-technology-learning`. Its Pages configuration serves files from the repository root; this folder is the prepared site bundle used to update that published root.

To update the live site, copy the contents of this folder into the repository root and push to `main`. GitHub Pages serves the static HTML, CSS, JavaScript, and assets directly; no build command or server configuration is required.

`robots.txt` allows crawling and points to `sitemap.xml`. Submit the sitemap URL in Google Search Console after deployment; indexing and search-result appearance are controlled by Google and are not immediate.

Grade 12 lesson 7 opens `units-measurements.html`; its electrical-technology option opens `electrical-technology-lesson.html`, where learners choose the theory/simulation lesson or the separate formula calculator. The DDS simulator remains a distinct option on the lesson 7 page.

GitHub Pages is public static hosting. The site has no supported server-side runtime, database, CMS, administrator or learner login, protected content, or file upload/storage. Every deployed file is public. Edits are made in source files and deployed as commits. The AI tutor is a local, source-bounded search prototype, not a live generative AI service. A real generative tutor or private content workflow requires a separately hosted backend; provider secrets must never be embedded in this public site.
