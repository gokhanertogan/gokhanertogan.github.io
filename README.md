# Privacy policies

Public privacy policy pages for my games, served by GitHub Pages at `https://gokhanertogan.github.io/<game>/privacy/`. These URLs go into Play Console and the App Store.

Each game's repo is private and holds the source of its page in `docs/privacy/`; this repo only publishes a copy. When a policy changes (for example when a game adds ads), update it in the game's repo, copy it here and push **before** that game's release goes out:

```
cp ~/dev/games/<game>/docs/privacy/*.html <game>/privacy/
```

| Game | URL |
| --- | --- |
| Marble Clash | https://gokhanertogan.github.io/marble-clash/privacy/ |
| Park Out | https://gokhanertogan.github.io/park-out/privacy/ |
| Pillow Sumo | https://gokhanertogan.github.io/pillow-sumo/privacy/ |
| Unscrew | https://gokhanertogan.github.io/unscrew/privacy/ |

A new game gets a `<game>/privacy/` folder and a line in `index.html` and in this table.
