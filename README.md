# MonSoftAMoi

Ce dépôt n'est pas le serveur. Il ne contient que les manifests. Le serveur est déjà en ligne :

`POST https://www.monsoftamoi.fr/api/home/mcp`

Deux outils, sans compte : `lister_applications` et `decrire_application`. Pas de contenu d'application.

Le M du logo reprend les violets `#6530CF` et `#B876F9` du carré publié sur monsoftamoi.fr.

## Installer

- ChatGPT : coller l'URL du serveur dans le portail OpenAI. Authentification : aucune. La même soumission couvre Codex.
- Codex : `codex mcp add monsoftamoi --url https://www.monsoftamoi.fr/api/home/mcp`
- Claude Code : `claude mcp add --transport http monsoftamoi https://www.monsoftamoi.fr/api/home/mcp`
- Cursor : dans `mcp.json`, une entrée `monsoftamoi` avec cette URL.
- Antigravity : `agy plugin install https://github.com/monsoftamoi/monsoftamoi-plugin`

Les fiches d'annuaire (portails OpenAI, Claude, cursor.directory) se déposent à la main. Le mode d'emploi est dans le dépôt privé `msam_apps`, fichier `docs/CHATGPT_PLUGIN.md`.
