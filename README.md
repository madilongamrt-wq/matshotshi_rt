# Rudzani Matshotshi Portfolio

A responsive single-page portfolio built with plain HTML, CSS, and JavaScript. It has no build dependencies.

## What is included

- `index.html`, the complete portfolio site.
- Sections for profile, selected platform work, operating approach, career history, skills, and contact.
- Responsive navigation, selected-work filters, expandable project details, keyboard focus styles, and reduced-motion support.

## Run locally

From this directory, run:

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000` in a browser. Stop the server with Ctrl+C.

## Publish with GitHub Pages

The source contains the email address and phone number from the CV. A public GitHub repository and a GitHub Pages site expose those details on the internet. Review `index.html` and remove either contact method first if you do not want it published.

1. Create a repository named `matshotshi_rt` under the GitHub account `madilongamrt-wq`.
2. Choose Public if you want the repository and source code open to employers. GitHub Pages is available for public repositories on GitHub Free.
3. Add `index.html` and `README.md` to the repository root, then commit them to the `main` branch.
4. Open the repository's Settings, then Pages.
5. Under Build and deployment, select `Deploy from a branch`.
6. Choose branch `main` and folder `/(root)`, then select Save.
7. Wait for the Pages deployment. The expected project URL is `https://madilongamrt-wq.github.io/matshotshi_rt/`.

GitHub's current guide: https://docs.github.com/en/pages/quickstart
Publishing-source guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Update the site

After changing `index.html`, commit and push the change to `main`. GitHub Pages will rebuild from the configured branch.

## Build and verification history

The initial portfolio was built as a static HTML page with inline CSS and JavaScript. The content came from the supplied CV. The page was checked with Python's HTML parser and the inline JavaScript passed `node --check`. The source was pushed to the Sites source repository at commit `2d0162fea21e4e77474a26d1dbe66a7c9fac5939`, packaged as static assets, and deployed. Sites reported deployment success. The Sites portfolio was later changed to public access at the user's request.

