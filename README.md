# Reformulation géométrique de la propagation lumineuse
## suivi d'une note sur la structure nulle et l'existence temporelle

---

**Avertissement de structure.** Ce texte comporte deux parties de statut épistémique distinct.

La **Partie I** (§1–§10) est démonstrative. Elle expose la lecture géométrique de la propagation lumineuse en relativité restreinte : ses énoncés sont des théorèmes au sens usuel, et ils sont ceux de la littérature standard, reformulés.

La **Partie II** (§11) est interprétative. Elle propose une lecture ontologique des résultats précédents. Elle n'établit aucun résultat physique, ne prédit rien, et ne prétend pas au statut de la Partie I. Elle est signalée comme conjecturale du début à la fin.

Cette séparation est délibérée : mélanger les deux registres affaiblit les deux.

---

# PARTIE I — REFORMULATION GÉOMÉTRIQUE

**Thèse.** La description habituelle du photon comme « particule se déplaçant à la vitesse c » est référentiel-dépendante et anthropomorphique. Une formulation géométrique équivalente, mais plus fondamentale, le présente comme une structure causale de l'espace-temps, dépourvue de temps propre.

---

## 1. Cadre mathématique

### 1.1 Axiomes de base

Soit (M, η) l'espace-temps de Minkowski, où :

- M = ℝ⁴ est la variété d'espace-temps
- η est une métrique pseudo-riemannienne de signature (−,+,+,+)

En coordonnées (x⁰, x¹, x², x³) = (ct, x, y, z) :

**η_μν = diag(−1, 1, 1, 1)**

L'intervalle infinitésimal entre deux événements s'écrit :

**ds² = η_μν dx^μ dx^ν = −c²dt² + dx² + dy² + dz²**

### 1.2 Classification des intervalles

| Type | Condition | Terminologie | Interprétation |
|------|-----------|--------------|----------------|
| Genre temps | ds² < 0 | *timelike* | Trajectoire de particule massive |
| Genre espace | ds² > 0 | *spacelike* | Séparation spatiale, aucun lien causal |
| Genre lumière | ds² = 0 | *null / lightlike* | Trajectoire de particule de masse nulle |

**Définition 1 (temps propre).** Le temps propre le long d'une courbe γ(λ) est

**τ = ∫ √(−ds²/c²) = ∫ √(−η_μν ẋ^μ ẋ^ν / c²) dλ**, où ẋ^μ = dx^μ/dλ.

**Lemme 1.** Le long d'une courbe de genre lumière, le temps propre est identiquement nul.

*Preuve.* Si ds² = 0 en tout point de γ, alors dτ = 0 en tout point. ∎

---

## 2. Structure géométrique du photon

### 2.1 Géodésiques nulles

**Définition 2 (géodésique nulle).** Une courbe γ(λ) est une géodésique nulle si :

1. elle est de genre lumière : η_μν ẋ^μ ẋ^ν = 0 ;
2. elle satisfait l'équation des géodésiques : ẍ^μ + Γ^μ_αβ ẋ^α ẋ^β = 0.

En espace-temps plat (Γ = 0), la seconde condition se réduit à ẍ^μ = 0.

**Proposition 1.** Les géodésiques nulles de Minkowski sont des droites vérifiant

**(dx/dt)² + (dy/dt)² + (dz/dt)² = c²**

*Preuve.* De ds² = 0 : −c²dt² + dx² + dy² + dz² = 0, d'où la contrainte. Avec ẍ^μ = 0, les solutions sont affines en λ. ∎

**Remarque sur le paramétrage.** Le paramètre λ d'une géodésique nulle n'est pas arbitraire : il est **affine**, c'est-à-dire défini à transformation λ → aλ + b près. Ce paramétrage n'est pas une simple commodité de calcul — il intervient dans l'équation de Raychaudhuri pour les congruences nulles, dans la description des générateurs d'horizon, et dans l'expansion des faisceaux en lentillage gravitationnel. Ce qui manque à une géodésique nulle n'est pas *tout* paramètre, mais un paramètre métriquement privilégié.

### 2.2 Quadri-impulsion photonique

**Définition 3.** Pour une particule de masse m > 0, la quadri-impulsion est p^μ = m u^μ = m dx^μ/dτ.

**Difficulté.** Pour un photon, dτ = 0 : cette définition est singulière.

**Résolution.** On définit la quadri-impulsion à partir du vecteur tangent à la géodésique, paramétrée affinement :

**p^μ = dx^μ/dλ = ℏk^μ = (E/c, p⃗)**

où k^μ est le quadri-vecteur d'onde, E = ℏω et p⃗ = ℏk⃗.

**Contrainte de masse nulle :**

**p_μ p^μ = −E²/c² + |p⃗|² = 0  ⟹  E = c|p⃗|**

### 2.3 Conséquence fondamentale

**Théorème 1 (absence de temps propre).** Une particule de masse nulle ne possède pas de temps propre. Sa ligne d'univers admet un paramétrage affine, défini à transformation affine près, mais aucun paramètre métriquement privilégié : il n'existe pas d'horloge le long d'une géodésique nulle.

*Preuve.*
1. Soit γ la ligne d'univers du photon.
2. m = 0 implique p_μ p^μ = 0.
3. Donc ds² = 0 le long de γ.
4. Par le Lemme 1, dτ = 0.
5. Le paramétrage affine subsiste, mais aucune normalisation métrique ne le fixe, la norme du vecteur tangent étant nulle. ∎

**Corollaire 1.** La quadri-vitesse u^μ = dx^μ/dτ n'existe pas pour un photon. La quadri-impulsion, elle, existe et dérive du vecteur tangent.

---

## 3. Observateurs massifs et flux temporel

### 3.1 Quadri-vitesse

**Définition 4.** Un observateur inertiel est une particule massive (m > 0) suivant une géodésique de genre temps. Sa quadri-vitesse est u^μ = dx^μ/dτ, normalisée par

**u_μ u^μ = −c²**

**Proposition 2.** Dans un référentiel où l'observateur a la vitesse v⃗ :

**u^μ = γ(c, v⃗)**, avec γ = 1/√(1 − v²/c²)

*Preuve.* Vérification directe de la normalisation. ∎

### 3.2 Observateur au repos

**Corollaire 2.** Pour v⃗ = 0 : u^μ = (c, 0, 0, 0).

**Interprétation.** Même immobile spatialement, un observateur massif « avance » à la vitesse c dans la direction temporelle. Le mouvement dans l'espace-temps d'une particule massive est, au repos, purement temporel.

Cette formulation est imagée et doit être prise pour ce qu'elle est : la norme de la quadri-vitesse est une contrainte de normalisation, non une vitesse observable. Elle a néanmoins le mérite de rendre visible que la répartition entre composantes temporelle et spatiales est ce que la transformation de Lorentz redistribue.

---

## 4. Observateurs contre structures causales

### 4.1 La description usuelle

**Affirmation courante.** « Un photon est émis en A à t = 0 et reçu en B à t = L/c ; il se déplace donc de A vers B. »

Cette description est correcte dans un référentiel donné, et référentiel-dépendante par construction.

### 4.2 La description invariante

**Théorème 2 (structure causale).** Soient A et B deux événements séparés par un intervalle nul (ds²_AB = 0). La géodésique nulle γ reliant A à B est une structure invariante de l'espace-temps.

*Preuve.*
1. ds² est un invariant de Lorentz.
2. Si ds²_AB = 0 dans un référentiel, alors dans tous.
3. γ est déterminée par la structure métrique de (M, η).
4. γ existe indépendamment de tout observateur. ∎

**Corollaire 3.** γ ne « se déplace » pas : elle est un élément de la géométrie de l'espace-temps.

### 4.3 Ce qu'est une détection

**Proposition 4.** Détecter un photon, c'est intersecter une géodésique nulle.

Formellement, soient γ_obs(τ) la ligne d'univers de l'observateur (genre temps) et γ_phot(λ) la géodésique nulle. L'événement de détection E vérifie

**γ_obs(τ*) = γ_phot(λ*) = E**

**Théorème 3 (relativité de la description).** L'événement E est invariant ; sa description en termes de « quand » et « où » dépend du référentiel.

**Lecture.** L'observateur progresse selon dτ > 0 jusqu'à rencontrer une structure causale fixe. Le feuilletage temporel qui fait apparaître un « déplacement » est un choix, non une donnée.

---

## 5. La constante c

### 5.1 Son rôle dans la métrique

**ds² = −c²dt² + d𝓁²**, où d𝓁² = dx² + dy² + dz².

c n'y est pas un paramètre optique : c'est un **facteur de conversion dimensionnel** entre temps et espace.

### 5.2 Unités naturelles

En posant c = 1 : ds² = −dt² + d𝓁². Temps et espace acquièrent la même dimension. La constante ne fait que restaurer les unités conventionnelles.

### 5.3 Universalité

**Proposition 5.** c apparaît dans toutes les théories relativistes, indépendamment de l'existence des photons :

1. Équation d'Einstein : G_μν = (8πG/c⁴) T_μν
2. Relation énergie-impulsion : E² = (pc)² + (mc²)²
3. Transformation de Lorentz : t′ = γ(t − vx/c²)
4. Condition de connexion causale : Δs² ≤ 0

**Théorème 4.** Si l'on découvrait que le photon possède une masse m_γ > 0, alors la lumière se propagerait à v < c, mais c demeurerait la vitesse limite causale.

*Preuve.* La structure de (M, η) ne dépend pas des particules qui l'habitent. c est une propriété de η, non des photons. ∎

Ce théorème est le point le plus important de la Partie I, et le moins souvent explicité : il rend manifeste que « vitesse de la lumière » nomme l'occupant contingent d'une place structurelle.

### 5.4 Terminologie

Appellations équivalentes et plus rigoureuses :

- constante de structure de l'espace-temps
- vitesse limite causale
- facteur de conversion espace-temps
- vitesse des particules de masse nulle

Le nom « vitesse de la lumière » est un héritage historique (Maxwell, Michelson–Morley) antérieur à la compréhension relativiste.

---

## 6. Énergie et limite causale

### 6.1 Relation énergie-impulsion

**E² = (pc)² + (mc²)²**

**Cas m > 0.** E = γmc². Quand v → c : γ → ∞ et E → ∞. Barrière énergétique infinie.

**Cas m = 0.** E = pc, p = E/c, v = c automatiquement. Aucune accélération n'est requise : il n'y a pas d'histoire d'accélération.

### 6.2 Lecture géométrique

**Théorème 5.** Accélérer une particule massive vers c reviendrait à transformer sa ligne d'univers de genre temps en ligne de genre lumière.

*Preuve.*
1. Genre temps : ds² < 0, donc dτ > 0.
2. Genre lumière : ds² = 0, donc dτ = 0.
3. La transition exigerait dτ/dt → 0.
4. Or γ = dt/dτ = 1/√(1 − v²/c²), et E = γmc² = mc²·(dt/dτ).
5. Donc E → ∞ quand dτ/dt → 0. ∎

**Corollaire 4.** Atteindre c reviendrait à sortir du flux temporel. La barrière énergétique protège la structure causale : les particules massives ne peuvent pas cesser de durer.

**Réserve importante.** Cette preuve montre qu'aucune accélération finie ne conduit à ds² = 0. Elle ne montre pas que le genre lumière serait la limite du genre temps : c'est précisément ce que le §11.2 examinera, et le résultat est négatif.

---

## 7. Objections et réponses

### 7.1 « Mais dans mon référentiel, le photon se déplace bien. »

Dans votre référentiel, vous constatez qu'à t = 0 le photon est en x = 0 et qu'à t = t₁ il est en x = ct₁. Cette description est exacte et référentiel-dépendante.

La donnée invariante est autre : la géodésique nulle γ existe entre les événements (0,0) et (ct₁, ct₁), et votre ligne d'univers la croise. Ce que vous appelez propagation est la lecture d'une structure fixe dans un feuilletage temporel choisi.

### 7.2 « Le photon a une quadri-impulsion, donc une dynamique. »

Oui — et le photon est pleinement dynamique. Sa quadri-impulsion est conservée, échangée dans les interactions, et source du tenseur énergie-impulsion. Elle est mesurable : pression de radiation, effet Compton, refroidissement laser.

Ce qui n'existe pas n'est pas la dynamique, c'est la quadri-vitesse u^μ = dx^μ/dτ. La quadri-impulsion dérive du vecteur tangent p^μ = dx^μ/dλ, où λ est affine. L'absence de temps propre n'ôte rien à l'impulsion ; elle ôte l'observateur.

### 7.3 « Cela contredit les manuels. »

Non : c'est une reformulation équivalente.

Les manuels disent : le photon se propage à la vitesse c.
Nous disons : la géodésique nulle est une structure causale de l'espace-temps.

Ces énoncés sont mathématiquement équivalents. Le second est référentiel-indépendant, évite les anthropomorphismes, et s'étend sans modification à la relativité générale, où les géodésiques sont des structures intrinsèques de la variété. Le premier a des vertus pédagogiques réelles, notamment pour l'optique.

### 7.4 « Et la mécanique quantique ? »

En électrodynamique quantique, le photon est une excitation du champ électromagnétique.

Les **états asymptotiques** — photons réels, entrants et sortants — sont sur la couche de masse, donc sur le cône de lumière : la lecture géométrique s'y applique directement.

Les lignes internes des diagrammes ne sont pas des photons observables. Le propagateur de Feynman

**D_F(x−y) = ∫ d⁴k/(2π)⁴ · i/(k² + iε) · e^{−ik·(x−y)}**

comporte un pôle décalé de iε qui autorise des contributions **hors couche de masse** ; en espace des positions, il ne s'annule pas hors du cône. Il ne décrit donc pas un objet qui voyagerait le long d'un cône de lumière.

Cela ne contrarie pas la thèse — cela la renforce : il n'y a pas d'objet qui se déplace, il y a une amplitude de transition entre deux événements.

---

## 8. Formulation axiomatique

### 8.1 Axiomes

**Axiome 1.** L'espace-temps est une variété pseudo-riemannienne (M, g) de signature (−,+,+,+).

**Axiome 2.** Les particules libres suivent des géodésiques de g.

**Axiome 3.** Les particules se classent selon la norme de leur quadri-impulsion :
- g(p,p) < 0 : massives (genre temps)
- g(p,p) = 0 : de masse nulle (genre lumière)
- g(p,p) > 0 : exclu (tachyons)

### 8.2 Théorème central

**Théorème 6 (dichotomie).** Les objets de l'espace-temps se répartissent en deux catégories géométriquement distinctes.

**Observateurs (m > 0)**
- lignes d'univers de genre temps
- temps propre τ défini, dτ > 0
- durent

**Structures causales (m = 0)**
- géodésiques nulles
- dτ = 0, paramétrage affine seulement
- ne durent pas : elles constituent la structure causale

*Preuve.* Conséquence directe de la classification des intervalles et du Théorème 1. ∎

**Point capital.** Cette dichotomie est **catégorielle et non graduelle**. Il n'existe pas de suite de lignes de genre temps convergeant vers une ligne de genre lumière tout en restant de genre temps : le signe de ds² ne s'annule pas continûment le long d'une famille de trajectoires physiques. Nous y reviendrons au §11.2, car ce point est fréquemment mal formulé — y compris dans une version antérieure de ce texte.

### 8.3 Corollaire épistémologique

**Corollaire 5.** L'énoncé « le photon se déplace » est un artefact du choix d'un feuilletage temporel. La donnée invariante est la géodésique nulle comme structure causale.

---

## 9. Extensions

### 9.1 Relativité générale

En remplaçant η par g(x), tous les résultats précédents se transposent. Les géodésiques nulles y définissent la structure causale : cônes de lumière, horizons, diagrammes conformes.

### 9.2 Gravité quantique

Le « problème du temps » suggère que le temps pourrait être émergent plutôt que fondamental. Si cette voie aboutissait, elle renforcerait la primauté des structures nulles sur le flux temporel des observateurs. Ce n'est à ce jour ni établi ni consensuel.

### 9.3 Principe holographique

Les conjectures holographiques encodent l'information d'une région sur une frontière de genre lumière, ce qui confère aux structures nulles un rôle informationnel fondamental. Là encore, statut conjectural.

---

## 10. Synthèse de la Partie I

### 10.1 Résultats

1. Le photon n'a pas de temps propre (Théorème 1).
2. Sa ligne d'univers est une structure géométrique invariante (Théorème 2).
3. Les observateurs massifs durent (Corollaire 2).
4. Détecter, c'est intersecter (Proposition 4).
5. c est une constante de structure, non une propriété des photons (Théorème 4).

### 10.2 Tableau de correspondance

| Formulation usuelle | Formulation géométrique |
|---------------------|-------------------------|
| Le photon se déplace à la vitesse c | Le photon est une géodésique nulle |
| Le photon voyage de A vers B | A et B sont causalement connectés |
| Le trajet prend t = L/c | L'observateur dure τ jusqu'à croiser γ |
| c = vitesse de la lumière | c = constante de structure de l'espace-temps |

### 10.3 Statut

Cette reformulation est mathématiquement équivalente à la formulation usuelle et produit les mêmes prédictions. Son avantage est d'être référentiel-indépendante et de s'étendre sans retouche à l'espace-temps courbe. Elle n'est pas nouvelle : c'est la ligne suivie par la littérature géométrique classique (§ bibliographie).

### 10.4 Discussion pédagogique

Le langage géométrique dissout plusieurs difficultés classiques : le paradoxe du « point de vue du photon », l'idée d'une course-poursuite avec un rayon lumineux, la surprise devant l'invariance de c. En contrepartie, le langage cinématique reste plus efficace en optique et en électromagnétisme appliqué. Il ne s'agit donc pas de substituer l'un à l'autre, mais de savoir lequel est en usage et ce qu'il présuppose.

---

# PARTIE II — NOTE SPÉCULATIVE

## 11. Structure nulle et existence temporelle

*Cette partie est interprétative. Elle propose une lecture ontologique des résultats de la Partie I. Elle n'établit aucun résultat physique, ne fournit aucune prédiction testable, et ne prétend pas au statut démonstratif des sections précédentes.*

### 11.0 Remarque préalable sur l'échelle de Planck

Toute excitation quantique possède une longueur de Compton λ_C = ℏ/(mc) ; toute masse possède un rayon de Schwarzschild r_S = 2Gm/c². La condition de localisabilité

**λ_C > r_S  ⟺  ℏ/(mc) > 2Gm/c²**

se sature à l'échelle de Planck, **m_P = √(ℏc/G) ≈ 2,18 × 10⁻⁸ kg** (le facteur numérique exact dépend de la convention : avec ou sans 2, avec ou sans 8π).

**Ce que cette borne signifie.** Au-delà, la notion d'excitation élémentaire localisée cesse d'avoir un sens opérationnel : la courbure propre de l'objet enferme sa propre extension quantique, et aucune théorie établie ne décrit ce régime.

**Ce qu'elle ne signifie pas.** Elle ne borne ni la durée, ni l'existence en général, ni les objets composites. Une bille de plomb dépasse m_P de neuf ordres de grandeur sans difficulté, n'étant pas une excitation élémentaire. Surtout, **elle ne dit rien du temps propre** : dτ se lit sur ds² = −c²dt² + d𝓁², où la masse ne figure pas. Le temps propre dépend du genre de la ligne d'univers, jamais de la valeur de la masse.

Cette précision est nécessaire, car l'inférence inverse est tentante et fausse.

### 11.1 Rigidité du contenant

**Proposition 11.1 (invariance conforme de la structure nulle).** Soit g une métrique lorentzienne et Ω(x) > 0 une fonction lisse. Sous la transformation conforme g̃ = Ω²g :

- les temps propres changent : dτ̃ = Ω dτ
- les longueurs changent
- le genre des vecteurs est préservé : g̃(v,v) = Ω² g(v,v), de même signe
- en particulier, les cônes de lumière sont inchangés, et les géodésiques nulles demeurent des géodésiques nulles, à reparamétrage affine près

*Preuve.* Le signe de g(v,v) est invariant par multiplication par Ω² > 0. La condition ds² = 0 est donc conformément invariante, ce qui préserve la structure des cônes. ∎

**Lecture.** Tout ce qui relève de la mesure — durées, distances, temps propres — est déformable par un facteur conforme. La structure causale ne l'est pas.

C'est un énoncé précis, et standard, de ce que la dichotomie du Théorème 6 laissait pressentir : **le contenu est élastique, le contenant est rigide**. C'est d'ailleurs ce qui rend possibles les diagrammes de Penrose, où l'on déforme radicalement les distances pour ramener l'infini à portée de regard, sans jamais altérer les cônes.

### 11.2 Deux manières de cesser d'être un observateur

Être un observateur suppose une ligne d'univers de genre temps, donc un temps propre. Cela peut cesser de deux façons — et il importe qu'elles ne soient **pas symétriques**.

**(a) Devenir la structure.** ds² < 0 → ds² = 0.

Ce n'est pas une limite. Aucune séquence de lignes de genre temps ne converge vers une ligne nulle en restant de genre temps, et surtout : faire tendre m vers 0 ne fait pas tendre dτ vers 0. Un neutrino de masse infime possède un temps propre parfaitement fini. Le passage est **catégoriel** : un changement de genre de la ligne d'univers, non l'aboutissement d'un allègement.

L'erreur inverse — traiter m → 0 comme une transition continue vers la lumière — est d'autant plus tentante qu'elle produit une image agréable. Elle est fausse, et elle ruinerait toute conclusion qui s'appuierait sur elle.

**(b) Être enfermé par la structure.** Formation d'un horizon.

Ici la description est graduelle en un sens — la courbure croît continûment — mais le résultat est de nouveau une **surface nulle** : les générateurs d'un horizon des événements sont des géodésiques nulles. L'objet ne s'effondre pas *en* quelque chose : il devient, localement, une structure causale. Il cesse d'être observable comme objet pour ne plus être qu'une région.

**Observation centrale.** Les deux issues aboutissent au même genre géométrique — le nul — par des chemins de natures différentes : une frontière franche d'un côté, une pente de l'autre. C'est cette asymétrie, et non un intervalle de masses, qui donne sa forme correcte à l'intuition.

### 11.3 Énoncé de la conjecture

> **Conjecture (cohérence-limite).**
> L'existence en tant qu'observateur est le régime intermédiaire entre deux régimes nuls : celui qui **est** la structure causale (ds² = 0, masse nulle) et celui qui **devient sa propre frontière** causale (horizon). Dans les deux cas, ce qui disparaît n'est ni la matière ni l'énergie, mais le temps propre — c'est-à-dire la possibilité d'être un observateur plutôt qu'une région.

Formulée ainsi, la conjecture ne fait plus intervenir la masse comme paramètre de bascule, ce qui la met hors d'atteinte de l'objection principale. Elle demeure interprétative.

### 11.4 Ce que la conjecture ne dit pas

Par précaution explicite :

1. Elle ne dit pas que la masse détermine le temps propre — elle ne le détermine pas.
2. Elle ne dit pas que m = 0 est la limite de m petit — ce n'en est pas la limite.
3. Elle ne dit pas que m_P borne l'existence — m_P borne la localisabilité d'une excitation élémentaire.
4. Elle ne constitue pas un résultat de physique, mais une lecture des résultats de la Partie I.

### 11.5 — Statut épistémique de la conjecture

Cette conjecture n'est pas invérifiable par défaut de formulation, mais par construction. Elle porte sur la frontière entre être un observateur et être une structure causale ; or vérifier suppose un observateur. Toute position d'où l'on pourrait constater le franchissement est une position où l'on ne constate plus rien.

L'invérifiabilité n'est donc pas ici un aveu de faiblesse mais une conséquence du Théorème 1. Une conjecture sur la limite de l'observation ne peut pas être testée depuis l'intérieur du domaine observable.

---



## Annexe — Notation et conventions

**Signature.** (−,+,+,+). Indices μ, ν ∈ {0,1,2,3}. Convention de sommation d'Einstein.

**Symboles.**

| Symbole | Signification |
|---------|---------------|
| x^μ, x_μ | coordonnées contravariantes, covariantes |
| η_μν | métrique de Minkowski |
| g_μν | métrique générale |
| ds² | intervalle infinitésimal |
| dτ | temps propre |
| λ | paramètre affine (géodésiques nulles) |
| u^μ | quadri-vitesse (m > 0 uniquement) |
| p^μ | quadri-impulsion |
| γ | facteur de Lorentz, ou courbe géodésique selon le contexte |
| Ω | facteur conforme |
| λ_C | longueur de Compton |
| r_S | rayon de Schwarzschild |
| m_P | masse de Planck |

**Unités.** SI, sauf mention contraire. c = 299 792 458 m/s (exact par définition du mètre). Certaines sections emploient les unités naturelles c = 1.

**Note sur γ.** Le symbole désigne à la fois le facteur de Lorentz et une courbe géodésique. Cet usage, hérité de la littérature, est conservé ; le contexte lève l'ambiguïté sans difficulté.
