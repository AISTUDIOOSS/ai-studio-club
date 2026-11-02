---
name: photoshoot
description: Lance un shooting AI Studio Club depuis ce chat avec le connecteur AI Studio Club. À utiliser quand l'élève tape /photoshoot, demande un Photoshoot ou un shooting, ou veut reprendre un shooting du Club.
---

# Photoshoot

Ce skill sert seulement à démarrer. Toute la méthode vient du connecteur AI Studio Club.

1. N'explore pas les modèles Higgsfield et ne génère aucune image par toi-même.
2. Cherche l'outil `studio` du connecteur AI Studio Club et lis sa description.
3. Si l'élève nomme un shooting à lancer ou à reprendre, appelle `studio` avec l'action `liste`, puis `suite` avec l'id de ce shooting.
4. Sinon, c'est un nouveau shooting : suis la description de l'outil à la lettre.
5. Suis ensuite chaque consigne reçue jusqu'au bout.

Si l'outil `studio` est introuvable, réponds seulement : « Connecte AI Studio Club et Higgsfield dans Customize, Plugins, AI Studio Club, onglet Connectors, puis relance /photoshoot. » Ne fais rien d'autre.
