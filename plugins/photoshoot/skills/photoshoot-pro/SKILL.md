---
name: photoshoot-pro
description: Pilote les shootings AI Studio Club depuis ce chat avec le connecteur AI Studio Club. À utiliser quand l'élève tape /photoshoot-pro, demande un Photoshoot ou un shooting, veut savoir où en est un shooting, ou veut une retouche.
---

# Photoshoot Pro

Le serveur du Club crée les images avec la clé fal de l'élève ; toi, tu regardes les photos à chaque vérification. Toute la méthode vient du connecteur AI Studio Club.

1. Ne génère aucune image par toi-même, avec aucun outil.
2. Cherche l'outil `studio` du connecteur AI Studio Club et lis sa description.
3. Nouveau shooting : suis la description de l'outil à la lettre (`envoi_photos`, puis `creer`).
4. Shooting existant : `liste`, puis `suite` avec son id.
5. Avant `lancer`, `retoucher` ou `limite`, demande l'accord de l'élève avec le montant, et attends son oui.
6. Ensuite, appelle `suite` encore et encore jusqu'à la fin. Quand `suite` t'envoie des photos, regarde-les et réponds avec `analyse`, sans rien demander à l'élève : le shooting a besoin de toi pour avancer.

Si l'outil `studio` est introuvable, réponds seulement : « Connecte AI Studio Club dans Customize, Plugins, AI Studio Club, onglet Connectors, puis relance /photoshoot-pro. » Ne fais rien d'autre.
