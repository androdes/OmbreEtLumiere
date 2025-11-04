# Variables et principe d'action

## Variables fondamentales

- **Métrique** : $g_{\mu\nu}$
- **Champ de cohérence** (le tissu) : $\sigma \geq 0$
- **Matière ordinaire** : $\psi$ (baryons, etc.), qui voit une métrique conformément couplée au tissu :

$$\tilde{g}_{\mu\nu} \equiv A(\sigma) \, g_{\mu\nu}$$

**Idée** : l'« épaisseur temporelle » perçue par la matière dépend de $\sigma$.

## Action (ansatz minimal)

$$S = \int d^4x \, \sqrt{-g} \left[ \frac{c^3}{16\pi G} R - \frac{1}{2} \, (\nabla\sigma)^2 - V(\sigma) \right] + S_{\text{matt}} \! \left[\psi; \, \tilde{g}_{\mu\nu} = A(\sigma) g_{\mu\nu}\right] \tag{1}$$

- $V(\sigma)$ stabilise le fond (par ex. minimum en $\sigma = \sigma_0 > 0$)
- $A(\sigma)$ encode comment la matière « voit » le temps propre

**Lecture physique** : plus $\sigma$ chute, plus la métrique ressentie par la matière se dégrade (le temps propre « se fige » si $A \to 0$).

---

# Équations de champ

## Variation par $g_{\mu\nu}$

$$G_{\mu\nu} = \frac{8\pi G}{c^4} \left( T_{\mu\nu}^{(\sigma)} + A(\sigma) \, T_{\mu\nu}^{(\text{matt})} \right) \tag{2}$$

avec

$$T_{\mu\nu}^{(\sigma)} = \partial_\mu \sigma \partial_\nu \sigma - \frac{1}{2} \, g_{\mu\nu} \left[ (\nabla\sigma)^2 + 2V(\sigma) \right]$$

## Variation par $\sigma$

$$\Box \sigma - V'(\sigma) \, = \, -\frac{1}{2} \, A'(\sigma) \, T^{(\text{matt})} \tag{3}$$

où $T^{(\text{matt})} = g^{\mu\nu} T_{\mu\nu}^{(\text{matt})}$.

**Interprétation de (3)** : la présence de matière ($T^{(\text{matt})} \neq 0$) pousse $\sigma$ (via $A'(\sigma)$) — c'est exactement « la matière interactive chasse le tissu ».

---

# Temps propre « perçu » par la matière

Pour un observateur matériel (quadri-vitesse $\tilde{u}^\mu$ normalisée par $\tilde{g}_{\mu\nu}$), son temps propre est

$$d\tau_{\text{matt}}^2 \, = \, -\tilde{g}_{\mu\nu} \, dx^\mu dx^\nu \, = \, A(\sigma) \, (-g_{\mu\nu} \, dx^\mu dx^\nu) \, = \, A(\sigma) \, d\tau_{\text{geo}}^2 \tag{4}$$

Si $A(\sigma) \to 0$ dans une région, le temps propre de la matière s'annule même si $d\tau_{\text{geo}}^2 > 0$.

→ **C'est la version « tissu » de l'horizon** : la matière n'y « avance » plus dans son propre temps.

---

# Solution statique sphérique : condition d'horizon

## Ansatz métrique standard (extérieur statique et sphérique)

$$ds^2 = -N(r)^2 c^2 dt^2 + \frac{dr^2}{1 - \frac{2GM(r)}{c^2 r}} + r^2 d\Omega^2 \tag{5}$$

Pour la matière ordinaire, le temps propre vaut (d'après (4)) :

$$d\tau_{\text{matt}} = \sqrt{A(\sigma(r))} \, N(r) \, dt \tag{6}$$

## Horizon effectif pour la matière

$$\sqrt{A(\sigma(r_h))} \, N(r_h) = 0 \quad \Longleftrightarrow \quad A(\sigma(r_h)) = 0 \text{  ou  } N(r_h) = 0 \tag{7}$$

- $N(r_h) = 0$ : **horizon géométrique** (Schwarzschild/GR traditionnelle)
- $A(\sigma(r_h)) = 0$ : **horizon de cohérence** induit par le tissu (même si la partie purement géométrique n'est pas encore « fermée »)

**Conclusion** : le trou noir dans ce cadre est la coïncidence (ou la saturation) des deux mécanismes : la masse pousse $\sigma$ vers une valeur qui rend $A(\sigma) \to 0$, ce qui fige $d\tau_{\text{matt}}$ ; en parallèle $M(r)$ fait tendre $N(r) \to 0$. Leur combinaison sature la cohérence → horizon.

---

# Lien avec la « masse de Planck » du §7bis

Dans le régime compact, la matière rend $T^{(\text{matt})}$ grand → l'équation (3) tire $\sigma$ loin de $\sigma_0$.

Si on choisit par exemple

$$A(\sigma) = \left(\frac{\sigma}{\sigma_0}\right)^\alpha, \quad \alpha > 0 \tag{8}$$

alors, quand la compaction baryonique augmente, $\sigma(r)$ tombe localement → $A(\sigma) \downarrow$ → $d\tau_{\text{matt}} \downarrow$.

Au seuil critique (ta condition $\lambda_C > r_S$ du §7bis), les deux horizons se rejoignent :

$$A(\sigma(r_h)) \to 0 \quad \text{et} \quad N(r_h) \to 0$$

C'est ta cohérence-limite réalisée dynamiquement.

---

# Prédiction qualitative immédiate

- **Dans les régions très denses** (centres galactiques, étoiles à neutrons extrêmes), $\sigma$ est abaissé → $A(\sigma)$ diminue → ralentissement supplémentaire du temps propre pour la matière par rapport à la GR pure.

- **Dans les vides cosmiques**, $\sigma \approx \sigma_0$ → $A(\sigma) \approx 1$ → la matière suit la GR standard.

La **matière noire effective** est alors

$$\Xi_{\mu\nu} = T_{\mu\nu}^{(\sigma)} + \left(A(\sigma) - 1\right) T_{\mu\nu}^{(\text{matt})}$$

dans (2) : elle suit la géométrie et corrèle avec la courbure, pas seulement avec la densité baryonique — exactement ton intuition.

---

# Comment falsifier (idées d'observables)

## 1. Horloges gravitationnelles extrêmes

Comparer des horloges (pulsars millisecondes en binaire proche, étoiles S près de Sgr A*) au ralentissement prévu par GR.

→ Un supplément de redshift temporel corrélé à la compaction baryonique testerait $A(\sigma)$.

## 2. Courbes de rotation et lentilles

Ajuster des profils où $\sigma(r)$ décroît avec la compaction, et voir si la distribution de "DM effective" suit la géométrie mieux que la baryonique seule.

## 3. Anneaux d'ombre M87/Sgr A*

La taille/forme dépend de $N(r)$ et (ici) de $A(\sigma)$.

→ Un léger décalage systématique par rapport à GR pure serait une signature.