# Contributing to the War in the Mediterranean wiki

Thanks for helping. Corrections from people who play are the best way to keep this wiki right.

## How the pages are made

The pages in `docs/` are generated. The mod author keeps a master copy of every page, with notes on where each fact
comes from, and the site is rebuilt from it before each update. When your pull request is merged, your change is
copied into that master copy first, so it survives the next rebuild.

What that means for you:

- Your change will be kept, but the wording may be adjusted to match the rest of the wiki.
- Edit the page text in `docs/`. Leave the menu (`nav` in `zensical.toml`) alone unless you are adding a page; say
  where the page should go in the pull request instead.
- The theme (`docs/assets/extra.css`) is edited directly and is not regenerated.

## Good pull requests

- **Fixing a fact:** say where you saw it in game (place, War Level, what happened), or quote the mod file that sets
  it. The wiki describes what the mod does, so that is what gets checked.
- **Something new:** a new page or section on a mechanic, a tip, or a clearer explanation. Keep it about what players
  see and do.
- **Small fixes:** typos, broken links, unclear sentences.

## House style

- Short, direct sentences. Say what happens in game first.
- The two sides are **Gray** (Italy) and **Green** (France).
- No emoji.
- Pictures: your own screenshots only, no Keen textures, icons or logos.
- Keep server join details (address, password) off the wiki; they live in the WitM Discord.

## Not sure?

Open an issue describing the problem instead. That works just as well.
