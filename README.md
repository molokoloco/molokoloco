# Julien Guézennec, `molokoloco`

Ingénieur multimédia (CNAM), développeur web depuis 1998, studio indépendant [JulienWeb.fr](https://julienweb.fr) à Pantin (93).

J'ai passé cinq ans à l'agence Clark (plus de 300 sites institutionnels entre l'agence et le freelance), puis 13 ans et 10 mois d'ingénierie Internet R&D chez Bouygues Telecom, avec le Trophée de l'Innovation 2013. J'ai co-organisé ParisJS et Best of Web pendant six ans.

Organisme de formation déclaré (NDA 11 93 12613 93), Activateur France Num (DGE), prestataire référencé [Cybermalveillance.gouv.fr](https://www.cybermalveillance.gouv.fr).

## Ce que je fais

| Domaine | Concrètement |
|---|---|
| **Développement web** | WordPress, Elementor Pro, WooCommerce, PrestaShop, PHP, Node.js |
| **Automatisation et IA** | Scraping, pipelines, API REST, intégration de LLM, agents Claude Code |
| **SEO et GEO** | SEO technique, Schema.org, Core Web Vitals, fichiers llms.txt, GA4, GTM, Google Ads |
| **Cybersécurité** | Sites piratés, postes compromis, durcissement |
| **Formation** | IA générative, écriture de prompts, WordPress |

## Stack technique

```
Front-end   → HTML5 · CSS3 · JS · React · Vue.js · Elementor Pro
Back-end    → Node.js · PHP · WordPress · WooCommerce · PrestaShop
BDD         → MySQL · MongoDB · GraphQL
Outils      → Git · Docker · AWS · GCloud · LAMP
IA / LLM    → Claude · OpenAI · Groq · Gemini · Prompt Engineering
Env.        → Windows + WSL2 · VS Code · Chrome DevTools
```

## Projets notables

### [`htaccess-kill-switch`](https://github.com/molokoloco/htaccess-kill-switch)
Interrupteur marche/arrêt d'un site WordPress en mutualisé, que le client actionne seul en renommant un fichier. La règle vit dans `.htaccess`, au-dessus de PHP, donc elle coupe aussi un site piraté ou en erreur fatale (HTTP 503 et page de maintenance). Écrit pendant la remise en ligne d'une boutique WooCommerce piratée.  
`Apache` · `.htaccess` · `WordPress`

### [`cybermalveillance`](https://github.com/molokoloco/cybermalveillance)
Bibliothèque des outils open source de réponse à incident que j'utilise (analyse, détection, forensic), en sous-modules git épinglés, avec la doctrine d'usage. Aucune donnée de victime dans le dépôt.  
`DFIR` · `Forensic` · `Git submodules`

### [`pc-optim`](https://github.com/molokoloco/pc-optim)
Skill Claude Code de diagnostic Windows en lecture seule : disque, modèles d'IA locaux, caches de dev, doublons, applications, réseau et sécurité. Rapport Markdown et PDF, aucune modification du système.  
`PowerShell` · `Claude Code`

### [`lead-scraper-pro`](https://github.com/molokoloco/lead-scraper-pro)
Pipeline de prospection B2B qui collecte sur PagesJaunes, Pappers, Google Maps, Planity, Cylex et Instagram, dédoublonne, ajoute e-mail et téléphone, reprend après une interruption et exporte un CSV pour Mailchimp ou un CRM.  
`Node.js` · `Playwright`

### [`ia-dashboard-pro`](https://github.com/molokoloco/ia-dashboard-pro)
Tableau de bord local pour piloter un site WordPress, des tâches, des sessions Claude et des fichiers depuis un espace de travail IA.  
`Node.js` · `Express` · `SQLite`

### [`My-Book-ReadR`](https://github.com/molokoloco/My-Book-ReadR) (12 étoiles)
Lecteur de livre en une seule page web, présenté au meetup ParisJS en 2011.  
`HTML5` · `CSS3` · `jQuery`

Plus anciens : [`FRAMEWORK`](https://github.com/molokoloco/FRAMEWORK) (30 étoiles, code PHP et jQuery de 2011), [`flatClock3d`](https://github.com/molokoloco/flatClock3d) (horloge 3D en CSS3, sans image), [`jQuery.boxFx`](https://github.com/molokoloco/jQuery.boxFx), [`my-robot`](https://github.com/molokoloco/my-robot) (React Three Fiber).

## Formation

Organisme de formation déclaré, NDA 11 93 12613 93, enregistré auprès du préfet de région d'Île-de-France. Cet enregistrement ne vaut pas agrément de l'État. J'interviens en direct et en sous-traitance d'organismes de formation ; j'ai enseigné à HETIC, CIFACOM et IESA Multimédia.

Sept documents tirés de ma formation « Initiation à l'IA », à lire en ligne ou en PDF, libres de partage : les huit gestes, l'antisèche des prompts, trois prompts pour la photo, le glossaire (50 mots), 159 usages, un annuaire de plus de cent outils testés, l'aide-mémoire Claude.  
→ [julienweb.fr/ressources-ia](https://julienweb.fr/ressources-ia/)

## Les fichiers de ce dépôt

Le `llms.txt` dit ce que fait un site, le `llms-full.txt` donne son contenu, le `llms-profile.txt` dit qui l'écrit et comment les IA doivent en parler (bios, consignes, bloc JSON).

- [`llms-profil.md`](llms-profil.md) : mon profil, copie de [julienweb.fr/llms-profile.txt](https://julienweb.fr/llms-profile.txt)
- [`llms-cv.md`](llms-cv.md) : mon parcours complet, de 1998 à aujourd'hui
- [`llms-profil.template.md`](llms-profil.template.md) : modèle vierge à copier pour votre site, méthode dans [la pile llms complète](https://julienweb.fr/blog/llms-txt-full-txt-profil-geo-wordpress/10451/)

## Curriculum Vivum

J'ai inventé le Curriculum Vivum. Au lieu d'un CV court par poste, je donne tout le parcours, et l'IA de l'employeur garde les expériences qui l'intéressent. PDF de 18 pages, coordonnées à l'intérieur.

**[Lire le Curriculum Vivum](https://julienweb.fr/intelligence-artificielle/curriculum-vivum-cv-4-0/12594/)**
