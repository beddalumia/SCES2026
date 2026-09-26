---
colorSchema: light
color: rose
layout: cover
routerMode: hash
title: SCES 2026
theme: neversink
neversink_slug: "SCES 2026"
transition: slide-up
---

### `Symmetry-resolved` two-site entanglement as a key to Mott and pseudogap physics in the 2D Hubbard model

**GABRIELE BELLOMIA**    
Research assistant at the Technische Universität Wien --- _Institut für Festkörperphysik_

<kbd> with C. Mejuto-Zaera, M. Capone, A. Amaricci (CDMFT) &nbsp;·&nbsp; F. Bippus, T. Chalopin _et al._ (cold atoms) </kbd>

<br />
    
<img src=/images/FWFlight.svg width=600 class="float-left ml-7 mt-9 mb-5">
<img src=/images/TUWlight.svg width=150 class="float-right mr-10 mb-5">

:: note ::  
**SCES 2026** --- [city, date] --- _International Conference on Strongly Correlated Electron Systems_

<!--
12 min + 3 min Q&A. Budget: 0:15 title, 0:45 motivation, 1:00 density matrix, 1:00 SSR, 1:45 partial transpose, 2:00 half filling, 1:30 doping, 1:30 cold atoms, 1:00 solids + take-home. Aim to finish at 10:45.
-->

---
layout: default
title: Why two-site entanglement
slide_info: false
---

# Why two-site entanglement?

<div class="grid w-full grid-cols-5 gap-8 mt-2">

<div class="col-span-3">

The SCES community approaches the _third quantum revolution_ under a two-fold, bold assumption:

<v-clicks>

- strong interactions grant **richer quantum resources** than other platforms
- these resources are **operationally accessible**

</v-clicks>

<v-click>

→ we should **quantify** them, with **entanglement monotones**, in the simplest building block: a pair of sites $\langle ij \rangle$

</v-click>

<v-click>

Yet, orbital (mode) entanglement between two sites arises already from **single-electron tunneling**: it is **large in noninteracting systems**, with no obvious link to strong correlations in the SCES sense

</v-click>

<v-click>

For localized spins the answer is in this session's opening talk: $\langle S_i\!\cdot\!S_j\rangle$ → concurrence.    
**What changes when the electrons can move?**

</v-click>

</div>

<div class="col-span-2 flex justify-center items-start">
<img src="/images/nonlocal_mode_corr.svg" class="h-100 w-auto" />
</div>

</div>

<!--
Hook from the abstract. The last click ties the talk to Scheie's opening talk: the shortcut works for spins because each site is a qubit; it breaks once charge fluctuates. The last slide closes this loop.
-->

---
layout: default
title: Two-site density matrix 1
---

<div class="neversink-green-light-scheme ns-c-bind-scheme"> 

# &nbsp; The two-site density matrix $\rho_{ij}$ of the Hubbard model

</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_symmetries.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Rotated to highlight two-site symmetries </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  <v-clicks>

  - The Hubbard model conserves the total charge $N$ and magnetization $m$ → $\rho_{ij}$ is block-diagonal in $(N_{ij}, m_{ij})$
  - The local charges $n_i$, $n_j$ are **not** conserved → off-diagonal **quantum amplitudes** between configurations (colored) next to classical probabilities (black)
  - Those amplitudes are the only place where ==entanglement between $i$ and $j$== can live
    <div class="flex justify-center my-4">
    <img src="/images/dimer_entangled.svg" width="200" />
    </div>

  </v-clicks></div>

</div>

---
title: Two-site density matrix 2
transition: none
---

<div class="neversink-green-light-scheme ns-c-bind-scheme"> 

# &nbsp; Three kinds of amplitudes, by local charge jump $\Delta n$

</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_ssr.svg" class="h-full w-auto ml-3.5 " />   
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Rotated to highlight single-site symmetries </kbd></div>

  <div class="grid-item grid-col-span-2 ml-7"> 

  <v-clicks>

  - $\Delta n = 1$: one electron changes site → **hopping** amplitudes    
    ${\color{#F59D13}\rho_{t} \!=\, \mid \uparrow \rangle\langle \bullet\!\mid \otimes \mid\!\bullet \rangle\langle \uparrow \mid}$
  - $\Delta n = 0$: charges stay put, spins are exchanged → **spin-singlet** (antiferromagnetic) amplitude    
    ${\color{#3D81F6}\rho_{\uparrow\downarrow} \!=\, \mid \uparrow \rangle\langle \downarrow \mid \otimes \mid\downarrow\rangle\langle \uparrow\mid}$
  - $\Delta n = 2$: a doublon and a holon swap sites → **holon-doublon** amplitude    
    ${\color{#FB2D45}\rho_{\mathrm{hd}} \!=\, \mid \uparrow\downarrow \rangle\langle \bullet\!\mid \otimes \mid\!\bullet \rangle\langle \uparrow\downarrow \mid}$

  </v-clicks>

  <v-click>

  <kbd> Labels for amplitudes of $\rho_{ij}$ — not expectation values of terms in $H$: no single amplitude *is* the entanglement </kbd>

  </v-click>

  </div>

</div>

<!--
Define the colours here, as amplitudes of the two-site state. Do not map them onto t, J, pair hopping: the point of the partial-transpose slide is precisely that entanglement is a nonlinear competition between an amplitude and the populations of other configurations.
-->

---
layout: default
title: Why SSR I
---

# Why superselection rules?

<br />

<div class="neversink-pink-light-scheme ns-c-bind-scheme"> 
&nbsp; Operationally accessible entanglement: parity superselection rule (P-SSR)
</div>  
  <v-clicks>

  - Fundamental rule of quantum mechanics :   
    -> No superpositions of states with different parity of the electron number<sup>1</sup>   
  - It surely applies to full and reduced states of a fermionic system   
    -> in practice it applies to any _local_ operation<sup>2</sup>
  - Even stronger (physical/formal) arguments for the local P-SSR:   
    -> It is needed by the no-signaling theorem<sup>3</sup>    
    -> It is required for mathematical consistency<sup>4</sup>    
    -> It ensures robustness against _typical_ evolution<sup>5</sup>  

  </v-clicks>


<hr>    


<kbd v-click="1"> <sup>1</sup> Wick _et al._, *The Intrinsic Parity of Elementary Particles*, Physical Review **88**, 101 (1952) </kbd>  
<kbd v-click="2"> <sup>2</sup> Ding _et al._, _Physical entanglement between localized orbitals_, Quantum Sci. and Tech. **9**, 015005 (2023) </kbd>  
<kbd v-click="3"> <sup>3</sup> Friis, _Reasonable fermionic quantum information theories require relativity_, New J. Phys. **18**, 033014 (2016) </kbd>  
<kbd v-click="3"> <sup>4</sup> Szalay _et al._, _Fermionic systems for quantum information people_, J. Phys. A: Math. Theor. **54**, 393001 (2021) </kbd>  
<kbd v-click="3"> <sup>5</sup> Parez _et al._, _The Fate of Entanglement_, SciPost Phys. 20, 002 (2026) </kbd>

<!--
Ten seconds: the point is that this is well established, not a private idea.
-->

---
layout: default
title: Why SSR II
transition: slide-up
---

# Why superselection rules?

<br />

<div class="neversink-pink-light-scheme ns-c-bind-scheme"> 
&nbsp; Operationally accessible entanglement: parity superselection rule (P-SSR)
</div>  

&nbsp; <kbd>[...]</kbd>

<div class="neversink-sky-light-scheme ns-c-bind-scheme"> 
&nbsp; Removing the trivial entanglement of charge fluctuations: charge superselection rule (N-SSR) 
</div> 

<v-clicks>

- A noninteracting metal is very entangled in real space, but it is a Slater determinant in momentum space   
- Such real-space entanglement can be **simulated with a simple classical algorithm** → arguably not the resource we are after

</v-clicks>  

<v-click>

<AdmonitionType type="tip" title="Idea" width="720px">
The N-SSR does not freeze the charge, it decoheres it: local occupations still fluctuate, but only as a classical mixture. Removing all charge superpositions, we may uncover the nontrivial (interaction-driven) real-space entanglement — if any!
</AdmonitionType>

</v-click>

<v-click>

&nbsp;&nbsp;&nbsp; In $\rho_{ij}$: the P-SSR deletes the ${\color{#F59D13}\text{odd-}\Delta n}$ amplitudes, the N-SSR also the ${\color{#FB2D45}\Delta n = 2}$ ones → &nbsp; $E \;\supseteq\; E_{\text{P-SSR}} \;\supseteq\; E_{\text{N-SSR}}$

</v-click>

<!--
Present the N-SSR as an a-priori idea, to be tested by the results. Avoid claiming that it removes free-fermion entanglement in general (the U=0 dimer keeps 0.585 bit of N-SSR negativity).
-->

---
layout: default
title: Partial Transposing 1
transition: none
---

<div class="neversink-fuchsia-light-scheme ns-c-bind-scheme"> 

# &nbsp; Quantifying: partial transpose and negativity

</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_pretranspose.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Rotated to highlight single-site symmetries </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  <v-clicks>

  - We want an **entanglement monotone**: a quantity that cannot grow under (SSR-compatible) local operations → it counts a **resource**, not a correlation
  - Transposing the indices of one site is a **partial time reversal**<sup>1</sup>: a classical mixture survives it as a valid state, an entangled one develops **negative eigenvalues**<sup>2</sup>
  - Fermionic (logarithmic) **negativity**: &nbsp; $\mathcal{N}^\mathrm{F}_{ij} = \log_2 \big\| \rho_{ij}^{\,T_j} \big\|_1$
  - It is blind to classical correlations, unlike the mutual information

  </v-clicks>

  <br />

  <kbd v-click="2"> <sup>1</sup> Shapourian, Shiozaki, Ryu, PRB **95**, 165101 (2017) </kbd>    
  <kbd v-click="2"> <sup>2</sup> Peres, PRL **77**, 1413 (1996); Horodecki _et al._, Phys. Lett. A **223**, 1 (1996) </kbd>

  </div>

</div>

---
layout: default
title: Partial Transposing 2
transition: none
---

<div class="neversink-fuchsia-light-scheme ns-c-bind-scheme"> 

# &nbsp; Quantifying: partial transpose and negativity

</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_partial_transpose.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Partial transposed on one of the two sites </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  Each amplitude now sits **between two populations**, and has to beat them:

  <v-clicks>

  - ${\color{#3D81F6}\rho_{\uparrow\downarrow}}$ lands between $\mid\!\uparrow\uparrow\rangle$ and $\mid\!\downarrow\downarrow\rangle$ → negative eigenvalue iff $|{\color{#3D81F6}\rho_{\uparrow\downarrow}}|^2 \gt P(\uparrow,\uparrow)\,P(\downarrow,\downarrow)$
  - ${\color{#FB2D45}\rho_{\mathrm{hd}}}$ lands between $\mid\!\bullet\,\bullet\rangle$ and $\mid\!\uparrow\downarrow\,\uparrow\downarrow\rangle$ → iff $|{\color{#FB2D45}\rho_{\mathrm{hd}}}|^2 \gt P(\bullet,\bullet)\,P(\uparrow\downarrow,\uparrow\downarrow)$
  - the fermionic phases of the partial transpose act only on the ${\color{#F59D13}\text{yellow}}$ (P-SSR-breaking) entries → the superselected parts behave "bosonically"

  </v-clicks>

  <v-click>

  ==Entanglement is a nonlinear competition between an amplitude and the probabilities of *other* configurations== — no single expectation value carries it

  </v-click>

  </div>

</div>

---
layout: default
title: Partial Transposing 3
transition: slide-up
---

<div class="neversink-fuchsia-light-scheme ns-c-bind-scheme"> 

# &nbsp; The hard part: mixed states (even at $T=0$)

</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_ssr_transpose.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Reshuffled to highlight PT symmetries </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  <v-clicks>

  - Two sites embedded in a lattice (cluster + bath) are in a **mixed state**, also at $T = 0$: entropies no longer measure entanglement
  - The ${\color{#F59D13}\text{yellow}}$ entries **couple** the ${\color{#3D81F6}\text{spin}}$ and ${\color{#FB2D45}\text{charge}}$ blocks: the full negativity does not split
  - The local P-SSR deletes exactly those couplings → block-diagonal → ${\color{#3D81F6}\mathcal{N}_{\uparrow\downarrow}}$ and ${\color{#FB2D45}\mathcal{N}_\mathrm{hd}}$ well defined
  - ${\color{#F59D13}\mathcal{N}_{t}}$ is *what the P-SSR removes*:    
    $\mathcal{N}^\mathrm{F}_{ij} = {\color{#F59D13}\mathcal{N}_{t}} \overset{\star}{+} {\color{#3D81F6}\mathcal{N}_{\uparrow\downarrow}} \overset{\star}{+} {\color{#FB2D45}\mathcal{N}_\mathrm{hd}}$ &nbsp;&nbsp; $\tiny^\star\text{composition rule for negativities}$
  - A second monotone, the relative entropy of entanglement (Ding _et al._), exists for the superselected parts only: $E_t$ from entropies is an open problem

  </v-clicks>

  </div>

</div>

<!--
Spoken version (about 1 min): "Take one bond and its two-site density matrix. The diagonal is classical statistics of configurations; everything quantum sits in the amplitudes, and there are only three kinds, labelled by how much the local charge jumps. Parity superselection — no physical operation creates or detects a superposition of even and odd fermion number — makes the hopping amplitudes useless to any local observer. If local operations also conserve particle number, only spin flips survive. The two rules act as nested filters and split the bond entanglement into hopping, holon-doublon and spin-singlet pieces."
If asked "why negativity": for two-qubit blocks (the superselected ones) the log-negativity is the exact entanglement cost under PPT operations (Audenaert, Plenio, Eisert, PRL 90, 027901 (2003)); it counts ebits.
-->

---
layout: full
title: MIT 1
transition: none
---

<div class="neversink-rose-scheme ns-c-bind-scheme"> 

# &nbsp; Interaction-driven Mott transition at half filling

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-1 mt-7 mb-auto">
<div class="grid-item grid-col-span-2 pt-10"><img src="/images/half_sym_ree.svg" width=525/></div>
<div class="grid-item grid-col-span-1 text-left">

<img src="/images/4x2_ladder.svg" class="w-50 ml-15 mt-0.5" />

<div class="mt-5 text-sm">

- cellular DMFT at $T=0$, **paramagnetic** normal state
- exact-diagonalization-type solvers (ED / ASCI), discretized bath
- nearest-neighbour bond $\langle ij\rangle$ inside the cluster

</div>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <kbd> G.Bellomia _et al._, PRB **109**, 115104 (2024) </kbd>

</div>
<div class="grid-item grid-col-span-2 text-center h-fit">

<hr/>

Full negativity and mutual information (right) are already $\approx 0.5$ bit in the free metal, and merely double at $U_c$: where is the Mott physics?

</div>
</div>

<!--
Before/after reveal: this page shows the unresolved quantities; the next page keeps the left panel and decomposes the right one.
-->

---
layout: full
title: MIT 2
transition: slide-left
---

<div class="neversink-rose-scheme ns-c-bind-scheme"> 

# &nbsp; Interaction-driven Mott transition at half filling

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-1 mt-7 mb-auto">
<div class="grid-item grid-col-span-2 pt-10 mb-15"><img src="/images/half_sym_neg.svg" width=525/></div>
<div class="grid-item grid-col-span-1 text-left">

<v-clicks>

- ${\color{#F59D13}\mathcal{N}_{t}}$ carries the entanglement of the metal: $\approx 0.47$ bit at $U \to 0$, superselected parts $\lesssim 0.02$ bit
- ${\color{#3D81F6}\mathcal{N}_{\uparrow\downarrow}}$ switches on at $U_c$ and plateaus: **spin-singlet** entanglement of the Mott insulator
- ${\color{#FB2D45}\mathcal{N}_\mathrm{hd}}$ peaks at $U_c$ (see left panel): nearest-neighbour **holon-doublon binding** at the transition
- two monotones (relative entropy, negativity), one picture

</v-clicks>

</div>
<div class="grid-item grid-col-span-2 text-center h-fit">

<hr/>

Symmetry-resolved relative entropy (left) vs negativity (right)

</div>
</div>

<!--
Q&A ammo.
(1) "Isn't the orange curve just the kinetic energy?" It jumps UP at U_c, where the kinetic energy can only lose weight (Hellmann-Feynman + concavity: dE_kin/dU = -U dD/dU >= 0). Mechanism: after partial transposition each hopping amplitude competes with the populations of configurations with an unbound holon or doublon next to a spin; in the insulator the surviving charge fluctuations are virtual (amplitude ~ t/U, probability ~ (t/U)^2), so they beat their own background. Less motion, but almost perfectly coherent. Away from U_c the orange does track the kinetic energy (both ~ t/U at large U).
(2) "Isn't blue just <S_i.S_j>?" In the Fermi liquid the NN spin correlator is finite (already -0.06 for free electrons on the square lattice) while N_updown is exactly zero: those correlations are classical. A monotone is a thresholded, nonlinear function; only it counts a resource.
(3) Strong-coupling hierarchy: singlet O(1), hopping O(t/U), holon-doublon O((t/U)^2): one power of t/U per unit of charge jump. This is why red dies fastest.
(4) Benchmark: exact free electrons on the square lattice give 0.44 bit of NN negativity, all hopping, superselected parts exactly zero; residual values at U->0 in CDMFT come from the bath fit.
-->

---
layout: full
title: Doping 1
transition: none
---

<div class="neversink-rose-scheme ns-c-bind-scheme"> 

# &nbsp; Doping-driven transition to the Fermi liquid

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-1 mt-7 mb-auto">
<div class="grid-item grid-col-span-2 pt-10 mb-16"><img src="/images/doped_sym_ree.svg" width=525/></div>
<div class="grid-item grid-col-span-1 ml-10 text-left">
<v-clicks at=0>

- we dope the Mott insulator found at $U/D = 2.3$ (fixed $U$)
- both superselected pieces decrease in the **pseudogap metal**, up to $\delta \simeq 0.2$
- there the density **jumps**: first-order transition between pseudogap metal and Fermi liquid<sup>4</sup> — no converged solutions inside the gap

</v-clicks>

</div>
<div class="grid-item grid-col-span-2 text-center h-fit">

<hr/>

Superselected entanglement (left), full negativity and mutual information (right) &nbsp; <kbd> <sup>4</sup> Sordi, Haule, Tremblay, PRL **104**, 226402 (2010); PRB **84**, 075161 (2011) </kbd>

</div>
</div>

---
layout: full
title: Doping 2
transition: slide-left
---

<div class="neversink-rose-scheme ns-c-bind-scheme"> 

# &nbsp; Doping-driven transition to the Fermi liquid

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-1 mt-7 mb-auto">
<div class="grid-item grid-col-span-2 pt-10 mb-16"><img src="/images/doped_sym_neg.svg" width=525/></div>
<div class="grid-item grid-col-span-1 ml-10 text-left">
<v-clicks>

- across the jump ${\color{#3D81F6}\mathcal{N}_{\uparrow\downarrow}}$ **dies**: the pseudogap metal inherits the singlet entanglement of the Mott insulator, the Fermi liquid has none (PPT is faithful here: zero means separable)
- ${\color{#FB2D45}\mathcal{N}_\mathrm{hd}}$ is small and dies as well
- ${\color{#F59D13}\mathcal{N}_{t}}$ barely notices the transition: hopping entanglement does not tell the phases apart

</v-clicks>

</div>
<div class="grid-item grid-col-span-2 text-center h-fit">

<hr/>

Symmetry-resolved relative entropy (left) vs negativity (right)

</div>
</div>

<!--
Optional bridge to the next slide, if you like the scenario: Sordi et al. (Sci. Rep. 2, 547 (2012)) identify T* with the Widom line emanating from this very first-order transition. Then the two "deaths" — across the jump at T=0 here, at T* in the experiment — are two faces of the same picture. Qualitative statement, not a cuprate comparison.
-->

---
layout: default
title: Cold atoms
---

<div class="neversink-indigo-scheme ns-c-bind-scheme"> 

# &nbsp; Quantum-gas microscope: singlet entanglement below $T^*$

</div>

<div class="grid w-full h-fit grid-cols-2 grid-rows-1 mt-8 mb-auto">

  <div class="grid-item grid-col-span-1">
  <img src="/images/bloch_bippus.svg" class="w-full h-auto" />

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <kbd> F. Bippus, T. Chalopin, **GB** _et al._, arXiv (2026) </kbd>

  </div>

  <div class="grid-item grid-col-span-1 ml-5">

  <v-clicks>

  - A Fermi-Hubbard quantum simulator reaches the **pseudogap** regime: from its data we compute the **N-SSR negativity** between nearest neighbours
  - Singlet entanglement lives in a **dome below $T^*$**: it dies by **overdoping** ($|\delta| \gtrsim 0.1$) and by **crossing the pseudogap temperature**
  - It is confined to **nearest neighbours**, as in CDMFT (spatial death)
  - The accessible entanglement of the pseudogap metal is carried by **nearest-neighbour valence bonds**

  </v-clicks>

  </div>

</div>

<!--
Replace bloch_bippus.svg with the arXiv version of the figure. Keep the wording "nearest-neighbour valence bonds": a two-site quantity speaks to singlet formation, not to resonance (a multipartite coherence between coverings) nor to the absence of order (an input of paramagnetic CDMFT).
-->

---
layout: default
title: Back to solids
---

<div class="neversink-teal-scheme ns-c-bind-scheme"> 

# &nbsp; Back to solids: what can a neutron certify?

</div>

<v-clicks>

- For localized spins (this session's opening talk): $\langle S_i \!\cdot\! S_j\rangle$ → concurrence, &nbsp; $C = \max\{0,\, -2\langle S_i\!\cdot\!S_j\rangle - \tfrac{1}{2}\}$ for SU(2)-symmetric pairs
- With itinerant electrons the singlet entanglement lives in the block where **both sites are singly occupied**; charge fluctuations only *dilute* it:    
  $\langle S_i\!\cdot\!S_j\rangle = P_{11}\,\langle S_i\!\cdot\!S_j\rangle_{11}$, &nbsp;&nbsp; $P_{11} \le \tfrac{4}{3}\langle S_i^2\rangle$
- Hence a **lower bound on the accessible singlet negativity**, from the energy-integrated spin structure factor alone:

</v-clicks>

<v-click>

$$ 2^{\mathcal{N}_{\uparrow\downarrow}} - 1 \;\ge\; \max\Big\{0,\; -2\langle S_i\!\cdot\!S_j\rangle - \tfrac{2}{3}\langle S_i^2\rangle\Big\} $$

</v-click>

<v-clicks>

- $\langle S_i^2\rangle = 3/4$ gives back the spin-model concurrence (equality); the measured **local moment tightens** the bound for itinerant electrons — the bare spin formula is still a valid, looser bound
- Yes/no version: $\langle S_i\!\cdot\!S_j\rangle / \langle S_i^2\rangle \lt -1/3$ certifies operationally accessible singlet entanglement
- The holon-doublon part needs **pair correlations** between sites: an open experimental challenge

</v-clicks>

<!--
Derivation in three lines: (i) the N-SSR state is block-diagonal, the only entangled block is the doubly-singly-occupied one, with weight P11; (ii) for two qubits the SWAP witness gives negativity >= max(0, -2<S.S>_11 - 1/2), equality for SU(2)-symmetric (Werner) states; (iii) S_i vanishes on empty and doubly occupied sites, so <S_i.S_j> = P11 <S_i.S_j>_11, and P11 <= p1 = (4/3)<S_i^2>. Checked on 20000 random two-site states conserving N and Sz. For non-equivalent sites use the smaller local moment.
-->

---
layout: default
title: Take-home
---

<div class="neversink-rose-scheme ns-c-bind-scheme"> 

# &nbsp; Take-home — thank you!

</div>

<br />

- Superselection rules split the two-site entanglement of the Hubbard model into ${\color{#F59D13}\text{hopping}}$, ${\color{#FB2D45}\text{holon-doublon}}$ and ${\color{#3D81F6}\text{spin-singlet}}$ parts; only the last two are **operationally accessible**
- **Fermi liquid** (weak $U$, large doping): the accessible part is essentially zero — the large two-site entanglement is all hopping
- **Mott insulator and pseudogap metal**: accessible entanglement carried by **nearest-neighbour valence bonds**; holon-doublon entanglement peaks at the Mott transition
- It **dies** at the first-order transition to the Fermi liquid ($T=0$, CDMFT) and at $T^*$ (quantum-gas microscope)
- Neutrons can certify, and bound, the accessible singlet entanglement of an itinerant system

<div class="flex justify-around mt-8">
  <div class="text-center text-sm"><QRCode value="https://doi.org/10.1103/PhysRevB.109.115104" :size="90" render-as='svg'/> PRB 109, 115104</div>
  <div class="text-center text-sm"><QRCode value="https://arxiv.org/abs/2506.18709" :size="90" render-as='svg'/> arXiv:2506.18709</div>
  <div class="text-center text-sm"><QRCode value="https://arxiv.org/abs/2512.03689" :size="90" render-as='svg'/> arXiv:2512.03689</div>
  <div class="text-center text-sm"><QRCode value="https://arxiv.org/" :size="90" render-as='svg'/> cold atoms (arXiv)</div>
</div>

<!--
Leave this up during Q&A. Replace the last QR code with the cold-atom arXiv link.
Likely questions:
- RVB: say "nearest-neighbour valence bonds"; resonance is multipartite, invisible in rho_ij; the absence of order is an input of paramagnetic CDMFT; the Neel-ordered Heisenberg ground state also has NN singlet entanglement (<S.S> = -0.335 < -1/4).
- Capello et al.: their mechanism is a long-range Jastrow that binds holons and doublons; what our NN entanglement resolves is the bound pair, whatever produces the binding. Explicitly NN doublon-holon factors: Kaplan-Horsch-Fulde 1982, Yokoyama-Shiba 1990.
- Symmetry-resolved entanglement (Goldstein-Sela): see backup.
-->

---
layout: section
color: indigo
title: Backup
---

# Backup slides

---
layout: default
title: Backup imbalance
---

<div class="neversink-orange-light-scheme ns-c-bind-scheme"> 

# &nbsp; Backup: imbalance-resolved negativity<sup>a</sup> vs our resolution

</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_imbalance_spy.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Reordered by the charge imbalance </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  - Resolving by charge imbalance lumps ${\color{#3D81F6}\text{spin}}$, ${\color{#FB2D45}\text{charge}}$ and the ${\color{#F59D13}\text{hopping}}$ entries coupling them into the **same** $q=0$ sector
  - Charge-resolved entropies of one site are trivial: $S(q) = (0,1,0)$ at every $U$
  - Pure states: configurational vs number entanglement<sup>b</sup> = $E_{\uparrow\downarrow}$ vs $E_t + E_\mathrm{hd}$; the parity split of the number part separates hopping from holon-doublon
  - Ours is finer, and survives mixedness

  <kbd> <sup>a</sup> Cornfeld, Goldstein, Sela, PRA **98**, 032302 (2018) &nbsp; <sup>b</sup> Wiseman, Vaccaro, PRL **91**, 097902 (2003); Barghathi _et al._, PRL **121**, 150501 (2018) </kbd>

  </div>

</div>

---
layout: default
title: Backup fermionic negativity
---

<div class="neversink-fuchsia-light-scheme ns-c-bind-scheme"> 

# &nbsp; Backup: the fermionic partial transpose 
</div>

<br />

&nbsp; &nbsp; &nbsp;
To account for ==$\mathrm{fermionic}$== anticommutation rules the partial transpose is best written as
<br />

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
$\rho^{\color{#D848EE}T\!_{_{_\mathrm{B}}}} = \displaystyle\sum_{\Psi^\mathrm{A}_\lambda}\sum_{\Psi^\mathrm{A}_\nu}\sum_{\Psi^\mathrm{B}_\lambda}\sum_{\Psi^\mathrm{B}_\nu}
    \langle{\Psi^\mathrm{A}_\lambda\Psi_\lambda^\mathrm{B}}|{\rho}|{\Psi^\mathrm{A}_\nu\Psi_\nu^\mathrm{B}} \rangle
    |{\Psi^\mathrm{A}_\lambda}\rangle\langle{\Psi^\mathrm{A}_\nu}| \otimes 
    \Bigl(|{\Psi^\mathrm{B}_\lambda}\rangle\langle{\Psi^\mathrm{B}_\nu}|\Bigr)^{\color{#D848EE}\!\!T}$
<br />

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
$\,\,=\displaystyle\sum_{\Psi^\mathrm{A}_\lambda}\sum_{\Psi^\mathrm{A}_\nu}\sum_{\Psi^\mathrm{B}_\lambda}\sum_{\Psi^\mathrm{B}_\nu}
    \langle{\Psi^\mathrm{A}_\lambda\Psi^\mathrm{B}_{\color{#D848EE}\nu}}|{\rho}|{\Psi^\mathrm{A}_\nu\Psi^\mathrm{B}_{\color{#D848EE}\lambda}}\rangle
    |{\Psi^\mathrm{A}_\lambda}\rangle\langle{\Psi^\mathrm{A}_\nu}| \otimes |{\Psi^\mathrm{B}_\lambda}\rangle\langle{\Psi^\mathrm{B}_\nu}|$ ==$\exp\!\left(i\pi\phi_{\lambda\nu}^\mathrm{AB}\right)$==
<br />

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
where ==$\small \color{#D8760E} \phi_{\lambda\nu}^\mathrm{AB} = \tfrac{1}{2}{\left(\mathrm{P}(\Psi^\mathrm{B}_\lambda)+\mathrm{P}(\Psi^\mathrm{B}_\nu)\right)} + {\left(\mathrm{P}(\Psi^\mathrm{A}_\lambda)+\mathrm{P}(\Psi^\mathrm{A}_\nu)\right)}\times{\left(\mathrm{P}(\Psi^\mathrm{B}_\lambda)+\mathrm{P}(\Psi^\mathrm{B}_\nu)\right)}$==    
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
and $\small \mathrm{P}(|n_1, n_2, \dots \rangle) = \biggl(\displaystyle\sum_i n_i \biggr)\!\!\!\!\!\mod 2\,$ is the parity of the given Fock state $|n_1, n_2, \dots \rangle$.

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
--> The phase is nontrivial only on the elements that break the local P-SSR; the **fermionic negativity** is
$$
\mathcal{N}^\mathrm{F}_\mathrm{AB} = \log_2 \!\!\left[\sum_{\{\varepsilon^{T_{_\mathrm{B}}}\}}\Bigl(\varepsilon^{T_\mathrm{B}}\Bigr)\right], \quad \left\{\varepsilon^{T_\mathrm{B}}\right\} = \mathrm{svd}(\rho^{T_\mathrm{B}})
$$

---
layout: default
title: Backup dimer
---

<div class="neversink-teal-scheme ns-c-bind-scheme"> 

# &nbsp; Backup: the pure Hubbard dimer, analytically

</div>

<div class="grid w-full h-fit grid-cols-5 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-3 h-91"><img src="/images/2-site.svg" class="h-full w-auto ml-3.5 " />   
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Isolated dimer at half filling, T = 0 </kbd></div>

  <div class="grid-item grid-col-span-2 ml-7"> 

  $\psi = \sqrt{1-2D}\,\mid\!\text{singlet}\rangle + \sqrt{2D}\,\mid\!\text{hd pair}\rangle$, &nbsp; $D = \langle n_\uparrow n_\downarrow\rangle$

  - ${\color{#3D81F6}S_{\uparrow\downarrow}} = 1 - 2D$ &nbsp; singlet weight (Wiseman-Vaccaro)
  - ${\color{#FB2D45}S_\mathrm{hd}} = 2D$ &nbsp; pair weight
  - ${\color{#F59D13}S_t} = h(2D)$ &nbsp; entropy of the local parity

  - P-SSR entanglement $= 1$ bit at **every** $U$: $U$ converts holon-doublon into singlet entanglement one-for-one
  - In CDMFT, instead, the holon-doublon part appears only around $U_c$

  </div>

</div>

---
layout: iframe-left
title: Backup entropies are hard
url: https://arxiv.org/html/2303.14170v2
slide_info: true
---

## Backup: hardness of entropic entanglement measures

<br/>

  Even the superselected contributions are hard to evaluate with entropy-based measures (**mixed states are really cursed!**)

  <br/>  

On the left the only recipe that I know of

- works only for rank-16 density matrices    

- is defined for fully symmetric dimers    

- can be forced to AFM states, not CDW    

- it assumes also either particle-hole or
  global-singlet symmetries

- it is analytic, but sensitive to data noise
