---
title: find
slug: Mozilla/Add-ons/WebExtensions/API/find
tags:
  - API
  - Add-ons
  - Extensions
  - Reference
  - WebExtensions
  - find
translation_of: Mozilla/Add-ons/WebExtensions/API/find
---
{{AddonSidebar}}

Trouve un texte dans une page web, et met en évidence les correspondances.

Pour utiliser cette API, vous devez disposez de la [permission](/fr/docs/Mozilla/Add-ons/WebExtensions/manifest.json/permissions) "find".

## Fonctions

- {{WebExtAPIRef("find.find()")}}
  - : Trouver du texte dans une page web.
- {{WebExtAPIRef("find.highlightResults()")}}
  - : Mettez en surbrillance le dernier jeu de correspondance trouvé.
- {{WebExtAPIRef("find.removeHighlighting()")}}
  - : Supprimez toute mise en évidence.

## Compatibilité du navigateur

{{Compat("webextensions.api.find", 1, 1)}} {{WebExtExamples("h2")}}
