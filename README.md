# Site Artisan Rivetti Jean-Luc

Démo construite le 25/08/2026 pour le **RDV du mercredi 26/08 à 17h** (visio, événement créé par Thomas depuis le Sheet, confirmation automatique).

## Le prospect

- **Jean-Luc Rivetti**, peintre en bâtiment à **Port-de-Bouc (13110)**, 30 Cité Kuhlmann
- Tél 06 09 57 04 70 · jeanlucrivetti@gmail.com · **5,0/5 sur 6 avis Google**
- Fiche Google : https://maps.google.com/?cid=6678158747644061554
- **EI créée en avril 2000** (26 ans de métier), SIRET 430 402 941 00032, siège Villa n°30, Cité Kuhlmann, 13110 Port-de-Bouc, NAF 43.34Z peinture et vitrerie
- **Sa demande (appel du 25/08)** : une page très simple, sans photos, pour que son nom sorte en haut sur Google

## Sources publiques exploitées

Trois, toutes vérifiées le 25/08 : sa fiche Google Maps, le registre des entreprises, son profil **SeFaireAider**, et son profil **StarOfService** (`starofservice.com/professionnel/enlevement-de-peinture/port-de-bouc/178197159/rivetti-jean-luc`), sur lequel il **vient de s'inscrire**. Plus la photo de son camion fournie par Thomas. Données brutes archivées dans `scraper-leads-app/Photos/Artisan Rivetti Jean-Luc/`.

## La trouvaille qui change le dossier

Son profil **SeFaireAider** (sefaireaider.com/p/1571692/), rempli avec ses mots : « **Artisan Peintre Décorateur depuis avril 2000, je vous propose toute sorte de décoration ancienne et nouvelle** ». Prestations détaillées : **enduit à l'ancienne, patine sur murs, stucco, plâtre ciré, trompe-l'œil, faux marbre, faux bois**, ravalement de façade, boiseries, ferrures, dégâts des eaux, **zone 50 km autour de Martigues, 2 personnes qualifiées + lui**. Un autre annuaire (batiment.e-pro.fr) confirme l'EI d'avril 2000.

Sa fiche Google dit « peintre en bâtiment » générique : le site vend ce que ses annuaires disent et que personne ne vend dans la zone, **le peintre décorateur aux techniques anciennes**.

## Prestations : la liste s'est enrichie le 25/08

Aux quatre prestations de départ s'ajoutent, toutes sourcées :
- **Tapisserie & papier peint** (floqué sur son camion : « Peinture · Décoration · Tapisserie »)
- **Décapage & remise à nu** et **Application au pistolet** (déclarés par lui sur StarOfService)

## Direction artistique : « Le masquage »

- La signature d'un peintre soigné : les arêtes nettes au scotch de masquage. Titres posés sur des bandes de tape, hero avec un **grand aplat bleu à bord net** (« le mur ») qui se peint au chargement et porte la liste de ses savoir-faire rares, un coin de tape encore posé.
- Palette : blanc sous-couche #F6F4EF, blanc #FDFCFA, **bleu #1F4A73**, tape #EFE9DC, encre #23272B. Le bleu de son logo (#17488C, teinte 215°, échantillonné sur la photo du camion) a été essayé le 25/08 puis **écarté par Thomas, jugé trop vif** : il tire vers le bleu roi et durcit une page dont tout l'intérêt est la douceur. Le #1F4A73, plus sourd, reste la couleur du site.
- Typo : **Young Serif** (titres) / **Onest** (texte), non bloquantes, jamais utilisées sur les autres sites
- **Une seule photo, la sienne** : son camion floqué, **intégré dans le même cadre que sa fiche d'informations** dans la section L'artisan, en un seul bloc aligné au texte (une première version posait la photo et la fiche en deux blocs séparés, ce qui créait un décalage). Sa demande était « sans photos », mais celle-ci porte son logo, son numéro et ses trois métiers : elle prouve au lieu de décorer.

## SEO (le cœur de sa demande)

- Title et H1 : « Jean-Luc Rivetti, peintre en bâtiment et décorateur à Fos-sur-Mer »
- JSON-LD HousePainter (foundingDate 2000-04, areaServed 8 communes, sameAs fiche Google) + FAQPage (5 questions, égal à la FAQ affichée)
- Requêtes rares couvertes par le contenu réel : stucco, patine, trompe-l'œil, plâtre ciré, faux marbre, dégât des eaux + toutes les villes de l'étang de Berre
- **Point de vente clé pour le RDV** : sa fiche Google est à l'abandon (0 photo, 0 réponse aux avis en 9 ans, aucune description, catégorie générique). « Être en haut sur Google » = le site + la fiche optimisée ensemble. La brique fiche Google de la grille tarifaire est l'add-on naturel de ce dossier.
- **Correction du 25/08, importante** : le site avait d'abord été construit sur « Fos-sur-Mer », ville lue dans la colonne `Ville` du pipeline. Or cette colonne enregistre **la ville cherchée par le scraper**, pas l'adresse du prospect. Sa fiche Google **et** le registre disent tous deux `30 Cité Kuhlmann, 13110 Port-de-Bouc`. Title, H1, JSON-LD, zone et footer ont été recalés sur Port-de-Bouc. Fos-sur-Mer et Martigues restent comme villes desservies.

## Ce qui est vrai / ce qui ne l'est pas

**Vrai :**
- Les **2 avis affichés sont verbatim** (S.R. et Nadia M., initiales par sobriété), la note 5,0/5 et les 6 avis sont réels
- Depuis avril 2000, la zone 50 km, l'équipe, les techniques déco : tout vient de SES propres annuaires
- La citation dans L'artisan (« un artisan qui connaît son métier… ») vient mot pour mot de l'avis de S.R.

**Pas vérifié / à confirmer au RDV :**
- **Le prénom au registre est « Jean », pas « Jean-Luc »** (SIRET à faire confirmer pour les mentions légales)
- **Qui est Gianni ?** (l'avis S.R. le nomme, gianni r et marine rivetti ont laissé des avis : entreprise familiale ?)
- **Il a un vrai logo**, trouvé le 25/08 sur la photo de son camion : un éclat de couleurs **flou et vaporeux** à cinq teintes, avec un **œil finement dessiné** au centre. Une reproduction vectorielle a été tentée (`logo-rivetti.svg`, conservée dans le dossier) puis **retirée du site** : ses pointes géométriques et son œil graphique s'écartent trop du sien, et montrer à un artisan une approximation de sa propre identité est exactement le détail qui le fait douter du reste. L'en-tête est donc revenu au wordmark « Rivetti ».
  - **À en faire un sujet au RDV, pas un manque** : son logo n'existe apparemment que **flanqué sur son camion**, il n'a probablement aucun fichier vectoriel. C'est une brique facturable de la grille (« le logo est une brique, jamais un geste »), et c'est aussi ce qui lui manque pour sa fiche Google, ses devis et son site. Question à poser : « votre logo, vous l'avez en fichier quelque part, ou seulement sur le camion ? »
- L'avis S.R. mentionne Gianni en premier : vérifier que ça lui va de l'afficher
- Zone exacte et villes prioritaires, horaires (non affichés), assureur décennale
- Sait-il qu'il a une fiche Google ? (aucun signe de pilotage en 9 ans)

## V2 avec l'image IA en hero (refaite le 25/08, décision de Thomas)

**`index-v2.html`** : la photo ChatGPT (`images/ambiance-chantier.jpg`) passe en **hero pleine largeur**, texte posé sur la grande zone vide du mur avec un voile clair dégradé pour la lisibilité au soleil. Différences avec la V1 : le **mur bleu des savoir-faire disparaît du hero** (les techniques restent dans la carte « Décoration ancienne et nouvelle » des Prestations), tout le reste est identique. Une première V2 en bande d'ambiance au milieu de page a été essayée puis écartée par Thomas. **L'image est une illustration, pas un chantier de Rivetti**, à annoncer comme telle au RDV. Au RDV : montrer la V1 (typographique) puis la V2 (photo) et le laisser choisir. Si la V2 gagne, prévoir de réintégrer la liste des techniques quelque part au-dessus du pli.

## Option visuel IA pour le hero (sa case « éventuellement »)

Si Redouan… si **Jean-Luc** valide l'idée, générer via ChatGPT (méthode du 19/08) et remplacer l'aplat bleu par l'image. Prompt prêt, conforme aux règles (pas de texte lisible, pas de visage net, pas de surcorrection lumière) :

> Photographie réaliste, lumière naturelle de fin de matinée : un mur intérieur en cours de peinture dans une maison provençale, moitié basse déjà peinte en bleu profond, arête parfaitement nette protégée par du ruban de masquage beige, un rouleau posé sur un bac à peinture propre au premier plan, aucun personnage, aucun texte visible nulle part, aucune étiquette, tons chauds naturels sans saturation excessive, espace négatif en haut à gauche.

## Technique

- `index.html` (CSS/JS intégrés, aucune image), `mentions-legales.html`, `favicon.svg`, `robots.txt` (**Disallow: / tant que non signé**), `sitemap.xml` (URL placeholder)
- Trame : menu L'artisan · Prestations · Avis · FAQ · Contact + Devis gratuit (**pas de Réalisations, décision de Thomas du 25/08**, ordre standard conservé), numéro en clair dans le hero, badge avis → #avis, titre Avis → fiche Google, bouton d'appel flottant (numéro desktop, icône mobile, masqué au footer), formulaire Prénom/Nom + téléphone + e-mail + liste des prestations (tous requis, comme A.V.E. et Deco Peinture Arnaud) (mode démonstration honnête), footer « Tous droits réservés » + crédit Thom Digital → fiche Maps
- Audité sur 8 formats (2560 → 390, écrans bas compris), captures contiguës dans `audit/`, menu mobile testé à l'ouverture ET à la fermeture

## Reste avant mise en ligne (si signature)

- EmailJS, domaine à choisir avec lui (rivetti-peinture.fr ? jeanluc-rivetti.fr ?). **Brancher le champ `email` du formulaire en `reply_to` du template** : c'est la raison d'être du champ, sans lui le « Répondre » de sa messagerie ne repart pas vers le client. Le champ est obligatoire, `reply_to` est donc toujours renseigné.
- Dépôt GitHub + Cloudflare Pages (rien n'est déployé)
- `robots.txt` en Allow + vraie URL sitemap + soumission Search Console
- SIRET/prénom confirmés dans les mentions légales, assureur décennale
- Et le vrai levier de sa demande : **revendiquer et remplir sa fiche Google** (brique de la grille, 149 €). Tout le dossier commercial (script du RDV, benchmark, offre) est dans `livrables/prospection/3-dossiers-prospects/rivetti-peintre/`
