# Organizr Plugins Marketplace

This repository provides a **custom plugin marketplace source for Organizr**.

Plugins available in this repository are listed in:

```
plugin.json
```

Organizr can use this file to install plugins directly from GitHub.

---

# Available Plugins

## wizarrInvite

wizarrInvite is an Organizr plugin that allows administrators to **generate and manage Wizarr invitation links directly from Organizr**.

Main features:

* Wizarr invitation generation
* automatic invitation maintenance
* automatic parameter validation
* automatic invitation regeneration when configuration changes
* server and library selection
* public invitation display page
* multi-language display support

Repository:

```
https://github.com/Katsugami/wizarrInvite
```

---

# Adding this marketplace to Organizr

In Organizr:

```
Settings
→ Plugins
→ Marketplace
→ Add Repository
```

Add the GitHub repository URL that contains the `plugin.json` file.

After adding the repository, the plugin will appear in the marketplace list.

---

# Plugin Structure

Each plugin repository should contain at minimum:

```
plugin.php
api.php
page.php
main.js
settings.js
logo.png
```

Optional files:

```
display-fr.php
display-en.php
display-es.php
config.php
```

---

# Authors

Katsugami

AI development assistance: ChatGPT

The majority of the code for the plugins listed in this repository was generated with the assistance of ChatGPT, with final integration and project assembly performed by Katsugami.

---
