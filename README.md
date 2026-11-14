# cockpit — le film (51 s)

Présentation de [cockpit](https://quaresc.github.io/cockpit/) pour de futurs utilisateurs.
Chaque agent de code, à côté de son ticket, sa PR, son CI et son déploiement.

https://github.com/jcmilouze/cockpit-promo/releases/download/v1/cockpit-promo.mp4

**[→ Lire la vidéo avec la page de présentation](https://github.com/jcmilouze/cockpit-promo/releases/tag/v1)**

- `cockpit-promo.mp4` — 1920×1080 · 30 fps · 20 Mo · musique instrumentale incluse (ACE-Step local)
- `index.html` — la page de lecture (à héberger sur un statique : GitHub Pages, Netlify…)
- `poster.jpg` / `poster-hero.jpg` — affiches

## Scènes

| temps | scène |
|---|---|
| 0:00 | Six agents, six onglets — et aucune idée de celui qui t'attend |
| 0:06 | cockpit : l'agent avec son ticket, sa PR, son CI, son déploiement |
| 0:12 | De l'install au poste de pilotage, en trois temps |
| 0:19 | Home : qui t'attend, en une seconde |
| 0:25 | Chaque agent avec son travail, ses questions répondues sur place |
| 0:31 | L'éditeur, le diff et tes remarques à portée de touche |
| 0:37 | Inbox, runbooks, réunions, to-do : une palette, ⌘K |
| 0:41 | Rien ne sort de ta machine |
| 0:46 | Trouve l'agent qui a besoin de toi |

## Installer cockpit

```sh
# dans Claude Code
/plugin install cockpit --marketplace quaresc/cockpit
/cockpit:setup

# dans un shell, pour n'importe quel autre agent
curl -fsSL https://raw.githubusercontent.com/quaresc/cockpit/main/install.sh | sh
cockpit setup
```

Film réalisé avec HyperFrames (HTML → MP4). Captures officielles de quaresc/cockpit (MIT).
