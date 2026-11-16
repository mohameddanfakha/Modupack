# ModuPack — contexte du projet

Projet de création d'entreprise (PCE), cours ICE, M1 Finance, Université Paris Nanterre. Travail de groupe. ModuPack est une entreprise **fictive**.

## L'entreprise
- Produit : un carton d'expédition en **une seule pièce**, sans colle ni scotch (type FEFCO 0427), simple cannelure, 30 × 20 × 20 cm intérieur.
- Réglable en **hauteur (20 ou 15 cm)** et en **largeur intérieure (20 ou 15 cm)** : **4 formats** (H20-L20, H20-L15, H15-L20, H15-L15).
- Prix HT par carton selon le lot (le lot de 250 est la référence du prévisionnel) :
  - S : 0,72 € (50), 0,63 € (250), 0,60 € (1 000), 0,57 € (palette de 2 500)
  - M : 1,32 €, 1,15 €, 1,09 €, 1,04 €
  - L : 2,32 €, 2,02 €, 1,92 €, 1,82 €
  - Environ +25 % par rapport à un carton standard. 20 cartons d'essai offerts. Logisticiens : contrat annuel au prix palette (−10 %).
- Prix d'achat moyen chez le cartonnier : 0,71 € (S ≈ 0,40, M ≈ 0,73, L ≈ 1,29), puis −10,5 % dès 2030. Hypothèse, devis demandés.
- Modèle : négoce sans usine. Un cartonnier partenaire fabrique et livre directement le client. La forme de découpe nous appartient.
- Cible : petites boutiques et PME qui expédient (maison/déco d'abord, puis mode, accessoires, beauté ; logisticiens plus tard). Lancement fictif à Lyon en janvier 2027.
- Argument central : la règle européenne PPWR (règlement (UE) 2025/40, art. 24) limite le vide à 50 % dans les colis e-commerce à partir du 1er janvier 2030 ; le calage compte comme du vide. La méthode de calcul officielle est attendue d'ici février 2028.
- Plan (scénario réaliste, 15/11/2026) : 25 clients fin 2027 (24 boutiques + 1 logisticien). Boutiques fin d'année 24 / 90 / 210 / 360 / 560, logisticiens 1 / 3 / 7 / 12 / 20 (2027 → 2031). Boutique = 250 colis/mois, logisticien = 5 000 colis/mois.
- CA 70 / 311 / 804 / 1 527 / 2 504 k€ ; résultat net 22,5 / −46,2 / −16,7 / 79,6 / 133,9 k€ ; marge brute 33 % puis 41 % dès 2030 ; trésorerie jamais sous 132 k€.
- Financement : 300 k€ = 60 k€ d'apports (6 × 10 k€) + 50 k€ de subventions + 190 k€ de prêt (7 ans, 4 %). Pas de bilan demandé par le prof.
- Détail complet : Google Doc « ModuPack – Volet financier (soutenance 3) ».
- Pas de brevet possible : ne jamais écrire « brevet » ni « arriver les premiers » comme protection. Protection = forme de découpe à nous, suivi de chaque client, plan B de licence.
- Ne plus utiliser : prix unique 0,75 €, plan 36 k€ → 360 k€, plan 32 k€ → 318 k€, prix 0,60 / 1,09 / 1,92 €, « 6 formats », « 3 dimensions ».

## Le site (index.html)
- Un seul fichier HTML, sans dépendance à part Google Fonts. Deux vues routées par le hash : `#accueil` et `#diagnostic`.
- Le diagnostic calcule tout dans le navigateur : taux de vide = (volume carton − volume produit) ÷ volume carton ; conforme si ≤ 50 %.
- Les chiffres du bouton « Voir un exemple d'abord » sont **inventés** (boutique fictive, calage à 0,20 €/colis). Ne jamais les présenter comme des résultats réels.
- Le formulaire de contact n'envoie rien (site de démonstration).

## Style
- Couleurs : noir charbon #1E1E1E, brun kraft #A8743F (accent seulement), blanc, gris neutre #F1F1F0, vert #2E6B4E (lignes de pli, « conforme »), brun-rouge #B5452F (coupe, « non conforme »).
- **Pas de fond crème ou beige** : l'équipe trouve que ça fait « site par défaut de Claude ».
- Polices : Bricolage Grotesque (titres), Instrument Sans (texte), Caveat (petites notes manuscrites, avec parcimonie).
- Forme inspirée de premierprompt.fr : bandeau d'annonce, carte à droite du titre, rangée de 3 offres, liste datée, bloc final sombre.
- Ton : français simple et naturel, « on » / « vous », phrases courtes, pas de jargon. Éviter tout ce qui fait « généré par IA » (tirets longs, points médians comme séparateurs, petites étiquettes en majuscules).

## Façon de travailler
- Réponses courtes, en français.
- Après chaque modification du site, l'ouvrir dans un navigateur et vérifier l'accueil, le diagnostic et le bouton d'exemple.
- Toute nouvelle donnée chiffrée (prix, statistique, loi) doit avoir une source.
