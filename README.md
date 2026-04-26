# Nederlandse vertaling voor YOURLS

> Volledige Nederlandse vertaling voor [YOURLS](https://yourls.org/) — admin, foutmeldingen, plug-in API, alles wat YOURLS uit zichzelf weergeeft.

**English:** Full Dutch (`nl_NL`) translation for YOURLS — admin pages, errors, plugin API messages, everything YOURLS itself emits.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Latest release](https://img.shields.io/github/v/release/toineenzo/YOURLS-nl_NL?display_name=tag&label=release)](https://github.com/toineenzo/YOURLS-nl_NL/releases)
[![Listed in Awesome YOURLS!](https://img.shields.io/badge/Awesome-YOURLS-C5A3BE)](https://github.com/YOURLS/awesome)

<p align="center">
  <!-- TODO: drop a screenshot of the YOURLS admin in Dutch in docs/screenshots/admin-nl.png -->
  <img src="docs/screenshots/admin-nl.png" alt="YOURLS admin in het Nederlands" width="720">
</p>

---

## Installatie / Installation

1. **Download** het laatste `.zip`-bestand van de [Releases](https://github.com/toineenzo/YOURLS-nl_NL/releases)-pagina, of pak `nl_NL.po` en `nl_NL.mo` los uit deze repository. <br/>_Download the latest `.zip` from [Releases](https://github.com/toineenzo/YOURLS-nl_NL/releases), or grab `nl_NL.po` + `nl_NL.mo` directly from this repo._
2. **Plaats beide bestanden** in `<je-yourls>/user/languages/`. <br/>_Drop both files into `<your-yourls>/user/languages/`._
3. **Open** `user/config.php` en wijzig: <br/>_Open `user/config.php` and change:_

   ```php
   define( 'YOURLS_LANG', '' );
   ```

   in / to:

   ```php
   define( 'YOURLS_LANG', 'nl_NL' );
   ```

4. **Ververs** de admin in je browser. De interface staat nu in het Nederlands. <br/>_Refresh the admin in your browser — the UI is now Dutch._

---

## Geverifieerd voor / Tested with

- **YOURLS** 1.9 en nieuwer. De meegeleverde `YOURLS.pot` wordt elke zondag automatisch gesynchroniseerd met de upstream `YOURLS/YOURLS.pot`-repository, dus nieuwe strings duiken direct op in `nl_NL.po`. <br/>_YOURLS 1.9 and newer. The bundled `YOURLS.pot` is auto-synced from upstream every Sunday, so new strings show up in `nl_NL.po` right away._

---

## Bijdragen / Contributing

Vertaling onnauwkeurig? Iets vergeten? Open een [issue](https://github.com/toineenzo/YOURLS-nl_NL/issues) of stuur een pull request met een aanpassing op `nl_NL.po`. Het `nl_NL.mo`-bestand wordt automatisch gecompileerd door GitHub Actions zodra de `.po` is bijgewerkt — je hoeft alleen de `.po` te raken.

_Spotted a translation issue? Open an [issue](https://github.com/toineenzo/YOURLS-nl_NL/issues) or send a pull request against `nl_NL.po`. The `nl_NL.mo` is auto-recompiled by GitHub Actions whenever the `.po` changes — you only have to touch the `.po`._

---

## Dank / Credits

Oorspronkelijk onderhouden door [@Beun](https://github.com/Beun); deze versie is een onderhoudsfork.

_Originally maintained by [@Beun](https://github.com/Beun); this is a maintenance fork._

---

## Licentie / License

[MIT](LICENSE).
