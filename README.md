# War in the Mediterranean: player wiki

Player-facing wiki for the War in the Mediterranean Space Engineers scenario, built with
[Zensical](https://zensical.org). Pages are Markdown in `docs/`; the sidebar is `nav` in `zensical.toml`.

- Preview: `pip install zensical==0.1.3`, then `zensical serve` and open http://localhost:8000.
- Publish: pushing to `main` builds and deploys to GitHub Pages (`.github/workflows/docs.yml`; set the repo's Pages
  source to GitHub Actions).
- Facts come from the mod's own files. Keep Keen assets (textures, icons, logos) off this site.
