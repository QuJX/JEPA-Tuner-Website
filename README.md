# JEPA-Tuner

Project website for **JEPA-Tuner: From Predictive Fine-Tuning to Asynchronous Execution of Vision-Language-Action Models**.

Project website: <https://qujx.github.io/JEPA-Tuner-Website/>

This is a static website. No package installation or build step is required.

## Preview locally

From this directory, run:

```sh
python3 -m http.server 8000
```

Open <http://localhost:8000>.

## Publish with GitHub Pages

Push this directory to the repository, with `index.html`, `static/`, `videos/`, and `.nojekyll` at its root.

In the repository's **Settings → Pages**, select **Deploy from a branch**, choose **main** and **/(root)**, and save. GitHub will display the published project URL after deployment. Further pushes to `main` update the website automatically.

See the [GitHub Pages publishing documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Files

- `index.html`: page content, styles, interactions, and embedded rollout manifest.
- `static/`: method and results figures.
- `videos/comparison/`: four comparison videos.
- `videos/rollouts/`: 80 individual rollout videos.
- `videos/manifest.json`: rollout metadata; keep it in sync with the embedded `MANIFEST` in `index.html` when changing clips.
- `.nojekyll`: serves the static files directly through GitHub Pages.
