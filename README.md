# War in the Mediterranean: player wiki

Player-facing wiki for the War in the Mediterranean Space Engineers scenario, built with
[Zensical](https://zensical.org). Pages are Markdown in `docs/`; the sidebar is `nav` in `zensical.toml`.

- Preview: `pip install zensical==0.1.3`, then `zensical serve` and open http://localhost:8000.
- Publish: pushing to `main` builds and deploys to GitHub Pages (`.github/workflows/docs.yml`; set the repo's Pages
  source to GitHub Actions).
- **Pages are generated**: `docs/*.md` and the `nav` menu in `zensical.toml` are written by `tools/wiki/player_edition.py`
  in the private se-mod-production repo. Don't edit them here; the theme (`docs/assets/extra.css`) is edited here.
- Look and colours follow the WitM Brand Guide v1.0.
- Contributions: see [CONTRIBUTING.md](CONTRIBUTING.md). Pull requests are welcome; merged changes are copied into the master
  copy before the next build.
- Facts come from the mod's own files. Keep Keen assets (textures, icons, logos) off this site.
