# Comprendre le système — qui fait quoi, et pourquoi

## 1. Le principe en une phrase

Le site attire des visiteurs via Google (gratuitement), certains cliquent sur
un outil recommandé et s'abonnent, et l'éditeur du logiciel te reverse une
commission chaque mois tant qu'ils restent clients. **Ton rôle n'est pas de
vendre à quelqu'un** — c'est de garder le site à jour et honnête pour que
Google continue de te faire confiance et de t'envoyer des visiteurs.

## 2. Qui fait quoi, concrètement

| Tâche | Qui la fait |
|---|---|
| Écrire le contenu des articles | Gemini (avec le prompt du guide) |
| Vérifier que les prix/infos sont vrais | **Toi** (rapide, quelques minutes) |
| Mettre le contenu en ligne | Toi (copier-coller dans ton hébergeur) |
| Trouver de nouveaux sujets d'articles | Toi, en t'aidant de la liste du guide |
| Repérer si un article est devenu faux (prix changé, etc.) | Toi + Gemini en appui |
| Décider si on ajoute un nouvel outil au comparatif | Toi |
| Chercher de nouveaux partenariats d'affiliation | Toi (1x/mois) |

Autrement dit : **Gemini rédige, toi tu vérifies et publies.** Ce n'est pas
zéro travail, mais c'est très peu comparé à démarcher des clients — quelques
dizaines de minutes par semaine, à un rythme que tu choisis.

---

## 3. Le guide, point par point, en langage simple

### Point 1 — Le positionnement
C'est le rappel de ta règle de base : le site parle uniquement d'IA +
immobilier. Pourquoi c'est important : si tu ajoutes un jour un article sur
un sujet totalement différent (ex: "meilleur aspirateur 2026"), Google
comprend moins bien de quoi parle ton site dans son ensemble, et ça peut
diluer la confiance qu'il t'accorde sur ta vraie spécialité. **Règle simple :
si un sujet d'article ne concerne pas l'immobilier ET l'IA en même temps, ce
n'est pas pour ce site.**

### Point 2 — Les programmes d'affiliation
C'est la liste des outils pour lesquels tu touches vraiment une commission
(Karlia, Simple CRM) vs ceux que tu mentionnes juste pour être complet et
honnête (Netty, Hektor...). Seuls les deux premiers te rapportent de l'argent
aujourd'hui.

### Point 3 — Les mots-clés
C'est ta liste d'idées de sujets d'articles. Chaque ligne est une requête que
des gens tapent réellement sur Google. Tu piocheras dedans pour savoir quoi
écrire ensuite.

### Point 4 — Le prompt pour Gemini
C'est le texte tout prêt que tu colles dans Gemini pour qu'il t'écrive un
article. Tu remplaces juste `[INSÈRE LE MOT-CLÉ CIBLE]` par un sujet de la
liste du point 3.

### Point 5 — La checklist avant publication
Une vérification rapide avant de mettre un article en ligne, pour ne jamais
publier une erreur factuelle (un faux prix, une fausse fonctionnalité).

### Point 6 — Le rythme de publication
Une recommandation de fréquence, pas une obligation stricte.

### Point 7 — La routine hebdomadaire
Ce que tu fais chaque semaine, 30 minutes, un seul bloc regroupé.

### Point 8 — Le signal d'alerte
Comment repérer si quelque chose ne va pas globalement sur le site (pas juste
un article) et quoi faire dans ce cas.

---

## 4. Exemple concret complet — du sujet à la publication

Suivons un cycle entier avec un seul article, pour que tu voies exactement à
quoi ressemble une session de travail.

### Étape A — Tu choisis un sujet
Tu ouvres le guide, section 3. Tu vois la ligne : **"karlia avis"**. C'est un
bon choix car Karlia est un de tes deux partenaires actifs (point 2) — un
article dédié à cet outil peut convertir directement en commission.

### Étape B — Tu génères l'article avec Gemini
Tu ouvres Gemini, tu colles le prompt du point 4, et tu remplaces
`[INSÈRE LE MOT-CLÉ CIBLE]` par :
```
Sujet de l'article : karlia avis — CRM immobilier français, avis complet 2026
```
Gemini te génère un article de 900-1300 mots avec un tableau comparatif, une
section limites, une FAQ.

### Étape C — Tu passes la checklist (5-10 min)
Tu relis l'article généré et tu coches mentalement (ou sur papier) la
checklist du point 5 :
- Le prix mentionné pour Karlia est-il vrai ? → Tu vérifies rapidement sur le
  site officiel de Karlia (ils affichent "sur devis", donc tu ajustes le
  texte de Gemini s'il avait inventé un chiffre précis).
- Une fonctionnalité citée existe-t-elle vraiment ? → Tu vérifies sur leur
  page fonctionnalités.
- Le lien d'affiliation est-il bien celui de ton compte partenaire Karlia
  (pas juste leur site normal) ? → Tu remplaces le lien par TON lien de
  tracking personnel une fois inscrit à leur programme.
- Y a-t-il un vrai point faible mentionné ? → Si Gemini n'a écrit que du
  positif, tu lui demandes une phrase supplémentaire honnête, ou tu l'ajoutes
  toi-même.

### Étape D — Tu publies
Tu copies le texte final dans ton hébergeur (la page que tu as déjà :
`index.html`, ou une nouvelle page si tu structures le site en plusieurs
pages plus tard).

### Étape E — Tu passes au sujet suivant
Tu reviens à la liste du point 3, tu prends la ligne suivante
("comparatif CRM immobilier prix" par exemple), et tu recommences.

**C'est tout le cycle.** Une fois que tu l'as fait deux ou trois fois, ça
devient mécanique et ça prend 20-30 minutes par article.

---

## 5. Le point sur "1x/mois, vérifier les nouveaux programmes d'affiliation"

Voici ce que ça veut dire concrètement, avec un exemple.

**Le problème que ça résout :** dans ton comparatif, tu mentionnes des outils
comme Netty, Hektor ou Prospeneo — mais ils n'ont pas (encore) de programme
d'affiliation public. Ça veut dire que si un visiteur clique et s'abonne chez
eux, **tu ne touches rien**, même si c'est toi qui les as convaincus. C'est
une perte d'argent silencieuse.

**Pourquoi ça change dans le temps :** les éditeurs de logiciels lancent
souvent leur programme d'affiliation *après* avoir grandi un peu — pas dès le
premier jour. Un outil qui n'a pas de programme aujourd'hui peut très bien en
ouvrir un dans 3 mois, sans que tu en sois informé automatiquement.

**Ce que tu fais concrètement, une fois par mois :**
1. Tu prends ta liste d'outils sans programme actif (Netty, Hektor,
   Prospeneo...).
2. Pour chacun, tu tapes dans Google : `Netty programme affiliation` (puis
   `Hektor programme affiliation`, etc.)
3. Si un résultat apparaît (une page "Devenez partenaire" ou "Programme
   affilié"), tu t'inscris, tu récupères ton lien de tracking, et tu mets à
   jour la fiche de cet outil sur ton site pour y ajouter le lien — ce qui
   transforme un article déjà existant en nouvelle source de revenu, sans
   avoir eu à écrire quoi que ce soit de nouveau.
4. Si rien ne change, tu ne fais rien de plus, tu réessaieras le mois
   prochain.

C'est une vérification de 10 minutes qui peut, un jour, débloquer une
commission sur du contenu que tu as déjà publié.

---

## 6. Est-ce que Gemini peut faire cette routine tout seul ?

Je vais être honnête avec toi sur ce qui est réellement possible aujourd'hui,
sans survendre.

### Ce que Gemini NE peut PAS faire seul
Ni Gemini, ni Claude, ni aucun assistant IA grand public ne va **se réveiller
tout seul** une fois par semaine, vérifier ton site sans que tu lui demandes
rien, et t'envoyer un message spontané. Il faut toujours que ce soit toi qui
ouvres la conversation et qui déclenches la vérification.

### Ce que Gemini PEUT faire, pour t'aider dans ta routine
Une fois que **toi** tu ouvres Gemini et lui donnes la liste des outils et
prix actuellement sur ton site, il peut :
- Faire une recherche web pour chaque outil et te dire si le prix affiché a
  changé
- Comparer ce qu'il trouve à ce que tu lui donnes et te lister uniquement les
  écarts (pas besoin de tout relire toi-même)
- Te rédiger direct le texte corrigé si un prix a changé

**Concrètement, ta routine hebdomadaire du point 7 devient :**
```
Voici les infos actuellement sur mon site :
- Karlia : CRM tout-en-un, prix "sur devis"
- Simple CRM : commission jusqu'à 45%, cookie 120 jours
- Netty : ~89 €/mois
- Hektor : 70-150 €/mois

Vérifie sur le web si ces prix ou informations ont changé depuis, et
dis-moi uniquement ce qui a bougé.
```
Tu colles ça une fois par semaine (ou toutes les deux semaines), et Gemini te
fait le travail de vérification — mais c'est bien toi qui déclenches l'action
à chaque fois, ce n'est pas une surveillance automatique en arrière-plan.

### S'il te faut une vraie automatisation (optionnel, plus technique)
Si un jour tu veux que ça tourne vraiment sans que tu y penses, il existe une
solution plus technique : un petit script programmé (via Google Apps Script
ou un outil comme Make/Zapier) qui appelle l'API de Gemini automatiquement
chaque semaine et t'envoie un email récapitulatif. C'est faisable vu ton
niveau en informatique, mais c'est une étape en plus — je te propose qu'on
commence avec la routine manuelle ci-dessus, et si dans quelques semaines tu
sens que tu veux l'automatiser complètement, on construit ce script ensemble.
