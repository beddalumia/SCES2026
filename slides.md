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

---
layout: default
title: Why two-site entanglement
slide_info: false
---

# Why two-site entanglement?

<div class="grid w-full grid-cols-5 gap-8 mt-2">

<div class="col-span-3">

The SCES _bet_ on the third quantum revolution:

<v-clicks>

- strong interactions grant **richer quantum resources** than other platforms
- these resources are **operationally accessible**

</v-clicks>

<v-click>

-> we can **quantify** them, with **entanglement monotones**

-> in the simplest building block (a pair of sites $i, j$), the
   spin structure factor $\langle S_i\!\cdot\!S_j\rangle$  gives
   all the answers (first talk of the session by A. Scheie!)
</v-click>

<v-click>
  
**What changes when electrons can move?**

</v-click>

<v-click>

Orbital two-site entanglement arises also from **tunneling**: it can be large in **noninteracting** systems, with no obvious link to inter-particle correlations

</v-click>


</div>

<div class="col-span-2 flex justify-center items-start">
<img src="/images/nonlocal_mode_corr.svg" class="h-100 w-auto" />
</div>

</div>

<!--
Hook: The last click ties the talk to Scheie's opening talk.
      The last slide closes this loop.
-->

---
layout: default
title: SSR I
---

# Why to symmetry resolve?

<br />

<div class="neversink-pink-light-scheme ns-c-bind-scheme"> 
&nbsp; Operationally accessible entanglement: parity superselection rule (P-SSR)
</div>  
  <v-clicks>

  - **Fundamental rule** of quantum mechanics :   
    -> No superpositions of states with different parity of the electron number<sup>1</sup>   
  - It surely applies to full and reduced states of a fermionic system   
    -> in practice it applies to any _local_ operation<sup>2</sup> (**operational access**)
  - Even stronger (physical/formal) arguments for the local P-SSR:   
    -> It is needed by the no-signaling theorem<sup>3</sup>    
    -> It is required for mathematical consistency<sup>4</sup>    
    -> It ensures robustness along _typical_ quantum protocls<sup>5</sup>  

  </v-clicks>


<hr>    


<kbd v-click="1"> <sup>1</sup> Wick _et al._, *The Intrinsic Parity of Elementary Particles*, Physical Review **88**, 101 (1952) </kbd>  
<kbd v-click="2"> <sup>2</sup> Ding _et al._, _Physical entanglement between localized orbitals_, Quantum Sci. and Tech. **9**, 015005 (2023) </kbd>  
<kbd v-click="3"> <sup>3</sup> Friis, _Reasonable fermionic quantum information theories require relativity_, New J. Phys. **18**, 033014 (2016) </kbd>  
<kbd v-click="3"> <sup>4</sup> Szalay _et al._, _Fermionic systems for quantum information people_, J. Phys. A: Math. Theor. **54**, 393001 (2021) </kbd>  
<kbd v-click="3"> <sup>5</sup> Parez _et al._, _The Fate of Entanglement_, SciPost Phys. 20, 002 (2026) </kbd>

---
layout: default
title: SSR II
transition: slide-up
---

# Why to symmetry resolve?

<br />

<div class="neversink-pink-light-scheme ns-c-bind-scheme"> 
&nbsp; Operationally accessible entanglement: parity superselection rule (P-SSR)
</div>  

&nbsp; <kbd>[...]</kbd>

<div class="neversink-sky-light-scheme ns-c-bind-scheme"> 
&nbsp; Removing trivial entanglement from charge fluctuations: charge superselection rule (N-SSR) 
</div> 

<v-clicks>

- We expect a noninteracting metal to be very entangled in real space   
- But in momentum space it is trivially solved with Slater determinants!   
- At weak coupling it is well approximated by Hartree-Fock theory    

</v-clicks>  

<v-clicks>

&nbsp;&nbsp;&nbsp; -> Such real-space entanglement can be **simulated with a simple classical algorithm**   

&nbsp;&nbsp;&nbsp; -> ==Arguably not relevant for quantum technologies!== (or at least for strongly correlated systems)

<AdmonitionType type="tip" title="Idea" width="450px" v-drag="[495,432,450,73]">
Removing all charge superpositions, we may uncover nontrivial real-space entanglement (if any!)
</AdmonitionType>

</v-clicks>

---
layout: default
title: Symmetries of a mixed Hubbard dimer 1
---


<div class="neversink-green-light-scheme ns-c-bind-scheme"> 


# &nbsp; Symmetries of a (mixed) two-site Hubbard subsystem
</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_symmetries.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Rotated to highlight two-site symmetries  </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  <v-clicks>

  - The Hubbard model conserves the total charge and magnetization in the lattice     
    --> $\rho_{ij}$ is **block-diagonal** in $N_{ij}$ and $m_{ij}$
  - Of course, this does **not** imply a local conservation of $n_i$, $n_j$,
    $m_i$ and $m_j$
  - Off-diagonal **quantum amplitudes** (colored)
    compete with classical probabilities (black)  
    ==**->** entanglement between $i$ and $j$==
    <div class="flex justify-center my-4">
    <img src="/images/dimer_entangled.svg" width="200" />
    </div>

  </v-clicks></div>

</div>

---
title: Symmetries of a mixed Hubbard dimer 2
transition: none
---

<div class="neversink-green-light-scheme ns-c-bind-scheme"> 

# &nbsp; Amplitudes are labeled by local charge jumps

</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_ssr.svg" class="h-full w-auto ml-3.5 " />   
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Rotated to highlight single-site symmetries </kbd></div>

  <div class="grid-item grid-col-span-2 ml-7"> 

  <div class="flex justify-center mb-4">
    <img src="/images/dimer_entangled.svg" width="200" />
  </div>

  <v-clicks>

  - $\Delta n = 1$: one electron changes site    
    --> **hopping** amplitudes    
    ${\color{#F59D13}\rho_{t} \!=\, \mid \uparrow \rangle\langle \bullet\!\mid \otimes \mid\!\bullet \rangle\langle \uparrow \mid}$ (and many others)
  - $\Delta n = 0$: charges frozen, spins exchanged    
    --> **antiferromagnetic** amplitude    
    ${\color{#3D81F6}\rho_{\uparrow\downarrow} \!=\, \mid \uparrow \rangle\langle \downarrow \mid \otimes \mid\downarrow\rangle\langle \uparrow\mid}$ (spin-singlets)
  - $\Delta n = 2$: holons and doublons swap sites    
    --> **holon-doublon** amplitude    
    ${\color{#FB2D45}\rho_{\mathrm{hd}} \!=\, \mid \uparrow\downarrow \rangle\langle \bullet\!\mid \otimes \mid\!\bullet \rangle\langle \uparrow\downarrow \mid}$ (like $\eta$-pairing)

  </v-clicks>

  </div>

</div>

<!--
Define the colours here, as amplitudes of the two-site state. Do not map them onto t, J, pair hopping: the point of the partial-transpose slide is precisely that entanglement is a nonlinear competition between an amplitude and the populations of other configurations.
-->

---
layout: default
title: Partial Transposing 1
transition: none
---


<div class="neversink-fuchsia-light-scheme ns-c-bind-scheme"> 


# &nbsp; Quantifying entanglement via partial transposing
</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_pretranspose.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Rotated to highlight single-site symmetries  </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  Thanks to the _Peres-Horodecki_ criterion we can quantify the entanglement encoded in off-diagonal elements by **partial transposing**

  <v-click>

  $$\rho = \begin{pmatrix} A_{11} & A_{12} & \dots & A_{1n} \\ A_{21} & A_{22} & & \\ \vdots & & \ddots & \\ A_{n1} & & & A_{nn} \end{pmatrix}$$
  &nbsp;&nbsp;&nbsp;&nbsp;where $n = \dim \mathcal{F}_\mathrm{A}$, and $\dim A_{ij} \equiv \dim \mathcal{F}_\mathrm{B}$

  </v-click>

  </div>

</div>

---
layout: default
title: Partial Transposing 2
---


<div class="neversink-fuchsia-light-scheme ns-c-bind-scheme"> 


# &nbsp; Quantifying entanglement via partial transposing 
</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_partial_transpose.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Partial transposed on one of the two sites  </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  Thanks to the _Peres-Horodecki_ criterion we can quantify the entanglement encoded in off-diagonal elements by **partial transposing**

  $$\rho = \begin{pmatrix} A_{11} & A_{12} & \dots & A_{1n} \\ A_{21} & A_{22} & & \\ \vdots & & \ddots & \\ A_{n1} & & & A_{nn} \end{pmatrix}$$
  &nbsp;&nbsp;&nbsp;&nbsp;where $n = \dim \mathcal{F}_\mathrm{A}$, and $\dim A_{ij} \equiv \dim \mathcal{F}_\mathrm{B}$

$$\rho^{\color{#D848EE}T\!_{_{_\mathrm{B}}}} = \begin{pmatrix} A_{11}^{\color{#D848EE}T} & A_{12}^{\color{#D848EE}T} & \dots & A_{1n}^{\color{#D848EE}T} \\ A_{21}^{\color{#D848EE}T} & A_{22}^{\color{#D848EE}T} & & \\ \vdots & & \ddots & \\ A_{n1}^{\color{#D848EE}T} & & & A_{nn}^{\color{#D848EE}T} \end{pmatrix}$$

  </div>

</div>

---
layout: default
title: Fermionic Negativity
---


<div class="neversink-fuchsia-light-scheme ns-c-bind-scheme"> 

# &nbsp; Quantifying entanglement via partial transposing
</div>

<br />

&nbsp; &nbsp; &nbsp;
To account for ==$\mathrm{fermionic}$== anticommutation rules the partial transpose is best written as
<br />

<v-clicks>

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
--> We can measure the entanglement with the so-called **fermionic negativity**
$$
\mathcal{N}^\mathrm{F}_\mathrm{AB} = \log_2 \!\!\left[\sum_{\{\varepsilon^{T_{_\mathrm{B}}}\}}\Bigl(\varepsilon^{T_\mathrm{B}}\Bigr)\right], \quad \left\{\varepsilon^{T_\mathrm{B}}\right\} = \mathrm{SVD}(\rho^{T_\mathrm{B}})
$$


</v-clicks>

<!-- $$
\rho^{\color{#D848EE}T\!_{_{_\mathrm{B}}}}
    = \sum_{\Psi^\mathrm{A}_\lambda}\sum_{\Psi^\mathrm{A}_\nu}\sum_{\Psi^\mathrm{B}_\lambda}\sum_{\Psi^\mathrm{B}_\nu}
    \langle{\Psi^\mathrm{A}_\lambda\Psi_\lambda^\mathrm{B}}|{\rho}|{\Psi^\mathrm{A}_\nu\Psi_\nu^\mathrm{B}} \rangle
    |{\Psi^\mathrm{A}_\lambda}\rangle\langle{\Psi^\mathrm{A}_\nu}| \otimes 
    \Bigl(|{\Psi^\mathrm{B}_\lambda}\rangle\langle{\Psi^\mathrm{B}_\nu}|\Bigr)^{\color{#D848EE}\!\!T} \\
    = \sum_{\Psi^\mathrm{A}_\lambda}\sum_{\Psi^\mathrm{A}_\nu}\sum_{\Psi^\mathrm{B}_\lambda}\sum_{\Psi^\mathrm{B}_\nu}
    \langle{\Psi^\mathrm{A}_\lambda\Psi^\mathrm{B}_{\color{#D848EE}\nu}}|{\rho}|{\Psi^\mathrm{A}_\nu\Psi^\mathrm{B}_{\color{#D848EE}\lambda}}\rangle
    |{\Psi^\mathrm{A}_\lambda}\rangle\langle{\Psi^\mathrm{A}_\nu}| \otimes |{\Psi^\mathrm{B}_\lambda}\rangle\langle{\Psi^\mathrm{B}_\nu}|  \colorbox{#FDE589}{\color{#D8760E}$\exp{i\pi\phi_{nm}^\mathrm{AB}}$}
$$ -->

---
layout: default
title: SSR-PPT is bosonic
transition: slide-up
---


<div class="neversink-fuchsia-light-scheme ns-c-bind-scheme"> 


# &nbsp; Quantifying entanglement via partial transposing 
</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_partial_transpose.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Partial transposed on one of the two sites  </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  <br />

  **Important notes:**
  
  <v-clicks>

  - the ==$\exp\!\left(i\pi\phi_{\lambda\nu}^\mathrm{AB}\right)$== phase is nontrivial only for the elements in the dimer density matrix that ==break the local P-SSR==
  
  &nbsp;&nbsp;&nbsp;&nbsp;
  -> ${\Large \color{#3D81F6}\rho_{_{\uparrow\downarrow}}\!}$ and ${\Large \color{#F43F5E}\rho_{_\mathrm{hd}}}$ give qubit-like entanglement    
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
   (e.g. thermal death, tipically short range...)
  <br /><br />

  - If we __resolve__ the three contributions to $\mathcal{N}^\mathrm{F}_{ij}$ we
    might access meaningful physical insight    
    (RVB vs holon-doublon binding vs hopping)

  </v-clicks>

  </div>

</div>

---
layout: default
title: A way out
transition: slide-up
---


<div class="neversink-orange-light-scheme ns-c-bind-scheme"> 


# &nbsp; How to define our symmetry resolution 
</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_ssr_transpose.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Reshuffled to highlight PT symmetries  </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-0"> 

  $$
  \small
  \mathcal{N}^\mathrm{F}_\mathrm{AB} = \log_2 \!\!\left[\sum_{\{\varepsilon^{T_{_\mathrm{B}}}\}}\Bigl(\varepsilon^{T_\mathrm{B}}\Bigr)\right], \quad \left\{\varepsilon^{T_\mathrm{B}}\right\} = \mathrm{SVD}(\rho^{T_\mathrm{B}})
  $$

  - The local P-SSR (which **deletes** the ${\color{#F59D13}\Delta n=1}$ elements), recovers a block-diagonal form! 

  <v-clicks>   

  &nbsp;&nbsp;&nbsp;&nbsp;
  -> We can define ${\color{#3D81F6}\mathcal{N}_{\uparrow\downarrow}}$ and ${\color{#FB2D45}\mathcal{N}_\mathrm{hd}}$ by restricting  
  &nbsp;&nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp;&nbsp;
  the $\mathrm{SVD}$ to these blocks

  &nbsp;&nbsp;&nbsp;&nbsp;
  -> We would have $\mathcal{N}_{\tiny\text{P-SSR}} = {\color{#3D81F6}\mathcal{N}_{\uparrow\downarrow}} \overset{\star}{+} {\color{#FB2D45}\mathcal{N}_\mathrm{hd}}$     
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  $\tiny^\star\text{the composition rule for negativities involves a logarithm}$ 

  - Our way to define ${\color{#F59D13}\mathcal{N}_t^\mathrm{F}}$ is just as     
  ${\color{#F59D13}\mathcal{N}_t^\mathrm{F}} \equiv \mathcal{N}_\mathrm{AB}^\mathrm{F} \overset{\star}{-} \mathcal{N}_{\tiny\text{P-SSR}} = \mathcal{N}_\mathrm{AB}^\mathrm{F} \overset{\star}{-} {\color{#3D81F6}\mathcal{N}_{\uparrow\downarrow}} \overset{\star}{-} {\color{#FB2D45}\mathcal{N}_\mathrm{hd}}$

  <!-- &nbsp;&nbsp;&nbsp;&nbsp;
  -> Easy to do with $\mathcal{N}^\mathrm{F}_\mathrm{AB}$ as a measure of $E_\mathrm{AB}$ -->

  <!-- &nbsp;&nbsp;&nbsp;&nbsp;
  -> Hard open problem with monotones based    
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  $\,$on entropies, we can only dissect $E_{\tiny\text{P-SSR}}$ 🥲 -->
  <!-- NO TIME FOR THIS -->

  </v-clicks>

  </div>&nbsp;&nbsp;&nbsp;&nbsp;

</div>

<!--
Two sites embedded in the lattice (or in cluster + bath) are in a mixed state even at T = 0: entropies no longer measure entanglement, and the yellow elements couple the spin and charge blocks, so the full negativity does not split by itself. The P-SSR cut removes exactly those couplings.
If asked "why the negativity": for the superselected blocks, which are two-qubit states, the logarithmic negativity is the exact entanglement cost under PPT operations (Audenaert, Plenio, Eisert, PRL 90, 027901 (2003)), i.e. it counts ebits.
-->

---
layout: full
title: MIT 1
transition: none
---

<div class="neversink-rose-scheme ns-c-bind-scheme"> 

# &nbsp; Mott-Hubbard transition in CDMFT/ED

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-1 mt-7 mb-auto">
<div class="grid-item grid-col-span-2 pt-10"><img src="/images/half_sym_neg.svg" width=525/></div>
<div class="grid-item grid-col-span-1 text-left">

<img src="/images/2x2_plaquette.svg" class="w-45 ml-5 mt-0.5 mb-2" />

<!-- &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <kbd> Our CDMFT/ED parametrization </kbd> -->

<v-clicks>

- Plaquette CDMFT at $T=0$

- ED-type diagonalization

- Discrete (small!) bath

- We focus only on $\langle i j \rangle$

- We disallow AFM ordering

</v-clicks>

</div>
<div class="grid-item grid-col-span-2 text-center h-fit">

<hr/>

Full versus symmetry-resolved entanglement between sites $\langle i j \rangle$

</div>
</div>

---
layout: full
title: MIT 2
transition: slide-left
---

<div class="neversink-rose-scheme ns-c-bind-scheme"> 

# &nbsp; Mott-Hubbard transition in CDMFT/ED

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-1 mt-7 mb-auto">
<div class="grid-item grid-col-span-2 pt-10 mb-15"><img src="/images/half_sym_neg.svg" width=525/></div>
<div class="grid-item grid-col-span-1 text-left">

- ${\color{#F59D13}\mathcal{N}_t^\mathrm{F}}$ is very large for $U\ll t$

<v-clicks>

- ${\color{#3D81F6}\mathcal{N}_{\uparrow\downarrow}}$ & ${\color{#FB2D45}\mathcal{N}_\mathrm{hd}}$ are small for $U\ll t$
- ${\color{#3D81F6}\mathcal{N}_{\uparrow\downarrow}}$ saturates while
${\color{#FB2D45}\mathcal{N}_\mathrm{hd}}$ vanishes at $U\gg t$
</v-clicks>

<v-click>

&nbsp; &nbsp; &nbsp; &nbsp; --> _Hubbard dimer at T = 0_
<img src="/images/2-site.svg" class="h-44.5 ml-3 mt-0 mb-0" />

</v-click>

</div>
<div class="grid-item grid-col-span-2 text-center h-fit">

<hr/>

Full versus symmetry-resolved entanglement between sites $\langle i j \rangle$

</div>
</div>

<!-- The holon-doublon entanglement is missed in CDMFT at low U cause the mixedness of the state kills all entanglement there, as we have a highly nonlocalized metal. At large U the MIT helps recovering it.

Q&A ammo.
(1) "Isn't the orange curve just the kinetic energy?" It jumps UP at U_c, where the kinetic energy can only lose weight (Hellmann-Feynman + concavity of E(U): dE_kin/dU = -U dD/dU >= 0). Mechanism: after partial transposition each hopping amplitude competes with the populations of configurations with an unbound holon or doublon next to a spin; in the insulator the surviving charge fluctuations are virtual (amplitude ~ t/U, probability ~ (t/U)^2), so they beat their own background: less motion, but almost perfectly coherent. Away from U_c the orange curve does track the kinetic energy (both ~ t/U at large U).
(2) "Isn't blue just <S_i.S_j>?" In the Fermi liquid the NN spin correlator is finite (already -0.06 for free electrons on the square lattice) while N_updown is exactly zero: those correlations are classical.
(3) Strong-coupling hierarchy: singlet O(1), hopping O(t/U), holon-doublon O((t/U)^2), one power of t/U per unit of charge jump; this is why the red curve dies fastest.
(4) Benchmark: exact free electrons on the square lattice give 0.44 bit of NN negativity, all hopping, superselected parts exactly zero; residual values at U -> 0 come from the bath fit.
-->

---
layout: full
title: Doped QRE
---

<div class="neversink-rose-scheme ns-c-bind-scheme"> 

# &nbsp; Doping-driven delocalization

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-1 mt-7 mb-auto">
<div class="grid-item grid-col-span-2 pt-10 mb-16.3"><img src="/images/doped_sym_ree.svg" width=525/></div>
<div class="grid-item grid-col-span-1 ml-15">
<v-clicks at=0>

  - We dope the Mott insulator found at $U/D=2.3$
  - Both $\mathcal{N}_{\langle ij \rangle}^\mathrm{hd}$ and $\mathcal{N}_{\langle ij \rangle}^{\uparrow\downarrow}$ decrease in the bad metal up to $\delta\simeq0.2$
  - The spin-singlet $\mathcal{N}_{\langle ij \rangle}^{\uparrow\downarrow}$ vanishes in the normal Fermi liquid, while there is some residual $\mathcal{N}_{\langle ij \rangle}^\mathrm{hd}$...

</v-clicks>
</div>
<div class="grid-item grid-col-span-2 text-center h-fit">

<hr/>

Full versus symmetry-resolved entanglement between sites $\langle i j \rangle$ &nbsp; (density jump: Sordi _et al._, PRL **104**, 226402 (2010))

</div>
</div>

---
layout: full
title: Doped Negativity
transition: slide-left
---

<div class="neversink-rose-scheme ns-c-bind-scheme"> 

# &nbsp; Doping-driven delocalization

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-1 mt-7 mb-auto">
<div class="grid-item grid-col-span-2 pt-10 mb-16"><img src="/images/doped_sym_neg.svg" width=525/></div>
<div class="grid-item grid-col-span-1 text-left">
<v-clicks>

  - Remarkably, also $\mathcal{N}^{\uparrow\downarrow}_{\langle ij \rangle}$ vanishes in the Fermi liquid    
  -> here the PPT is faithful!

  <img src="/images/cdmft_ssr_transpose.svg" class="w-50 ml-10 mt-0 mb-10" />

  - $\mathcal{N}^\mathrm{hd}_{\langle ij \rangle}$ is
    instead finite (but small)    

</v-clicks>

</div>
<div class="grid-item grid-col-span-2 text-center h-fit">

<hr/>

Symmetry-resolved entropy vs negativity between sites $\langle i j \rangle$

</div>
</div>

<!--
The gap in the data is the first-order transition between the pseudogap metal and the Fermi liquid (Sordi, Haule, Tremblay, PRL 104, 226402 (2010); PRB 84, 075161 (2011)): densities in between cannot be converged. Optional bridge to the experiment: Sordi et al. (Sci. Rep. 2, 547 (2012)) identify T* with the Widom line emanating from this very transition, so the death across the jump at T = 0 and the death at T* in the experiment are two faces of the same picture. Qualitative, not a cuprate comparison.
-->

---
layout: iframe-right
title: Experimental measures?
color: black
url: #images/RVB.mp4
slide_info: true
#neversink_slug: Jubobroff for Wikipedia
transition: none
---

# Experimental measures?

<br/>

  <v-clicks>

  Surely easier to target ${\color{#3D81F6}\mathcal{N}_{\uparrow\downarrow}}$ and ${\color{#FB2D45}\mathcal{N}_\mathrm{hd}}$ than ${\color{#F59D13}\mathcal{N}_t^\mathrm{F}}$

  Unfortunately still hard to directly access it, at least on solid state systems...

  </v-clicks>

---
layout: image-right
title: Cold atom simulation!
color: black
image: /images/doped_cuprate.svg
slide_info: false
transition: none
---

# ==**Cold atom simulation**==

We have been able to compute the **N-SSR** **negativity** from their atom-gas experiment!

<img src="/images/bloch_bippus.svg" class="w-100 ml-0 mt-5 mb--5" />

<kbd> F. Bippus, T. Chalopin, **GB** et al., _arXiv (2026)_   </kbd>

<div style="height: 0.35rem"></div>

---
layout: image-right
title: RVB cartoon
color: black
image: /images/nonlocal_mode_corr.svg
slide_info: false
transition: none
---

# ==**Cold atom simulation**==

We have been able to compute the **N-SSR** **negativity** from their atom-gas experiment!

<img src="/images/bloch_bippus.svg" class="w-100 ml-0 mt-5 mb--5" />

<kbd> F. Bippus, T. Chalopin, **GB** et al., _arXiv (2026)_   </kbd>

<div style="height: 0.35rem"></div>

- The accessible entanglement of the pseudogap metal is carried by ==**nearest-neighbour valence bonds**==

<!--
Softened on purpose: a two-site quantity speaks to singlet formation, not to resonance (a multipartite coherence between coverings) nor to the absence of order (an input of paramagnetic CDMFT). Even the Neel-ordered Heisenberg ground state has NN singlet entanglement (<S.S> = -0.335 < -1/4).
-->

---
layout: default
title: Back to solids
transition: slide-up
---

<div class="neversink-teal-scheme ns-c-bind-scheme"> 

# &nbsp; Back to solids: what can a neutron certify?

</div>

<br />

<v-clicks>

- For localized spins, $\langle S_i\!\cdot\!S_j\rangle$ gives the concurrence (this session's opening talk):   
  &nbsp;&nbsp;&nbsp;&nbsp; $C = \max\{0,\, -2\langle S_i\!\cdot\!S_j\rangle - \tfrac{1}{2}\}$ for SU(2)-symmetric pairs
- With itinerant electrons the singlet entanglement lives where **both sites are singly occupied**; charge fluctuations only *dilute* it:   
  &nbsp;&nbsp;&nbsp;&nbsp; $\langle S_i\!\cdot\!S_j\rangle = P_{11}\,\langle S_i\!\cdot\!S_j\rangle_{11}$, &nbsp;&nbsp; $P_{11} \le \tfrac{4}{3}\langle S_i^2\rangle$
- Lower bound on the **accessible singlet negativity**, from the energy-integrated spin structure factor alone:

</v-clicks>

<v-click>

$$ 2^{\mathcal{N}_{\uparrow\downarrow}} - 1 \;\ge\; \max\Big\{0,\; -2\langle S_i\!\cdot\!S_j\rangle - \tfrac{2}{3}\langle S_i^2\rangle\Big\} $$

</v-click>

<v-clicks>

- $\langle S_i^2\rangle = 3/4$ gives back the spin-model concurrence; the measured **local moment tightens** it &nbsp;&nbsp; -> yes/no: $\langle S_i\!\cdot\!S_j\rangle / \langle S_i^2\rangle \lt -1/3$
- The holon-doublon part needs **pair correlations** between sites: outlook

</v-clicks>

<!--
Derivation: (i) the N-SSR state is block-diagonal and the only entangled block is the doubly-singly-occupied one, with weight P11; (ii) for two qubits the SWAP witness gives negativity >= max(0, -2<S.S>_11 - 1/2), with equality for SU(2)-symmetric (Werner) states; (iii) S_i vanishes on empty and doubly occupied sites, so <S_i.S_j> = P11 <S_i.S_j>_11, and P11 <= p1 = (4/3)<S_i^2>. For non-equivalent sites use the smaller local moment.
-->

---
layout: default
title: Take-home
---

<div class="neversink-rose-scheme ns-c-bind-scheme"> 

# &nbsp; Take-home

</div>

<br />

- Superselection rules split the two-site entanglement of the Hubbard model into ${\color{#F59D13}\text{hopping}}$, ${\color{#FB2D45}\text{holon-doublon}}$ and ${\color{#3D81F6}\text{spin-singlet}}$ contributions
- **Fermi liquid** (weak $U$, large doping): the superselected contributions are negligible, the large two-site entanglement is all hopping
- **Mott insulator and pseudogap metal**: nearest-neighbour singlet entanglement dominates; holon-doublon entanglement peaks at the Mott transition
- It **dies** at the first-order transition to the Fermi liquid ($T=0$, CDMFT) and at $T^*$ (quantum-gas microscope)

<div class="flex justify-around mt-10">
  <div class="text-center text-sm"><QRCode value="https://doi.org/10.1103/PhysRevB.109.115104" :size="90" render-as='svg'/> PRB 109, 115104</div>
  <div class="text-center text-sm"><QRCode value="https://arxiv.org/abs/2506.18709" :size="90" render-as='svg'/> arXiv:2506.18709</div>
  <div class="text-center text-sm"><QRCode value="https://arxiv.org/abs/2512.03689" :size="90" render-as='svg'/> arXiv:2512.03689</div>
  <div class="text-center text-sm"><QRCode value="https://arxiv.org/" :size="90" render-as='svg'/> cold atoms (arXiv)</div>
</div>

<!--
Replace the last QR code with the cold-atom arXiv link. Leave this slide up during Q&A.
Likely questions:
- Capello et al.: their mechanism is a long-range Jastrow that binds holons and doublons; what our NN entanglement resolves is the bound pair, whatever produces the binding. Explicitly NN doublon-holon factors: Kaplan-Horsch-Fulde 1982, Yokoyama-Shiba 1990.
- Standard symmetry-resolved entanglement (Goldstein-Sela, imbalance negativity): see the backup slide.
- RVB: "nearest-neighbour valence bonds"; see the note on the cold-atom slide.
-->

---
layout: image
title: Thank you for your attention!
image: /images/ThankYou.svg
slide_info: false
---


---
layout: section
color: indigo
title: Backup
---

# Backup slides

---
layout: full
color: white
title: CDMFT
---

<div class="neversink-rose-scheme ns-c-bind-scheme"> 

# &nbsp; Cluster Dynamical Mean-Field Theory at zero temperature

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-2 mt-20 mb-auto">
<div v-click=1 class="grid-item grid-col-span-1"><img src="/images/cdmft.svg" /></div>
<div v-click=2 class="grid-item grid-col-span-1"><img src="/images/cdmft_bath.svg" /></div>
<div v-click=3 class="grid-item grid-col-span-1"><img src="/images/cdmft_ed.svg" /></div>

<div v-click=1 class="grid-item grid-col-span-1 text-center h-fit m-3">   
<hr/>

We tile the lattice in real space

</div> 

<div v-click=2 class="grid-item grid-col-span-1 text-center h-fit m-3">   
<hr/>

Then map to an impurity model

</div>

<div v-click=3 class="grid-item grid-col-span-1 text-center h-fit m-3">   
<hr/>

&nbsp; Finally we discretize the bath

</div>

</div>

---
layout: default
title: Comparing entropy and negativity
transition: slide-up
---

<div class="neversink-teal-scheme ns-c-bind-scheme"> 

# &nbsp; Comparing von Neumann entropy and negativity

</div>

<div class="grid w-full h-fit grid-cols-5 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-3 h-91"><img src="/images/2-site.svg" class="h-full w-auto ml-3.5 " />   
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Analytical results for a pure Hubbard dimer  </kbd></div>

  <div class="grid-item grid-col-span-2 ml-7"> 

  ${S_\mathrm{A} = {\color{#3D81F6}S_{\uparrow\downarrow}} + {\color{#F59D13}S_{t}} + {\color{#FB2D45}S_\mathrm{hd}}}$

  $\mathcal{N}^\mathrm{F}_\mathrm{AB} = \log_2 \!\left[{\color{#3D81F6}N_{\uparrow\downarrow}} + {\color{#F59D13}N_{t}} + {\color{#FB2D45}N_\mathrm{hd}} \right]$

  <v-clicks>

  - It is well-known that $\mathcal{N}^\mathrm{F}_\mathrm{AB} \geq S_\mathrm{A}$ (the negativity equals the ½-Rényi entropy for pure states...)

  - The _qualitative_ behavior of the symmetry-resolved components matches in the two frameworks

  - ${\color{#3D81F6}E_{\uparrow\downarrow}}$ captures the well-known RVB singlet character in the atomic limit

  - Both ${\color{#F59D13}E_{t}}$ and ${\color{#FB2D45}E_\mathrm{hd}}$ simply decrease as the
  interaction grows stronger

  </v-clicks>

  

  </div>

</div>

---
layout: default
title: Symmetry resolution of mixed states?
---


<div class="neversink-orange-light-scheme ns-c-bind-scheme"> 


# &nbsp; Returning to the general mixed case: how to resolve? 
</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_ssr_transpose.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Reshuffled to highlight PT symmetries  </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/dimer_ssr_transpose.svg" class="h-full w-auto mr-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Reshuffled to highlight PT symmetries  </kbd></div>
  </div>

</div>

---
layout: iframe-left
title: Entropies for mixed states are hard
url: https://arxiv.org/html/2303.14170v2
slide_info: true
transition: none
---

## Hardness of entropic entanglement measures

<br/>



  In fact even the susperselected contributions are very hard to evaluate with entropy-based measures (**mixed states are really cursed!**)

  <br/>  

<v-click>
On the left the only recipe that I know of
</v-click>

<v-clicks>

- works only for rank-16 density matrices    

- is defined for fully symmetric dimers    

- can be forced to AFM states, not CDW    

- it assumes also either particle-hole or
  global-singlet symmetries

- it is analytic, but sensitive to data noise

</v-clicks>

---
layout: iframe-left
title: Entropy vs Negativity on mixed states
url: https://arxiv.org/html/2303.14170v2
slide_info: true
transition: slide-left
---

## Comparing entropies and negativies on mixed states

<img src="/images/sudden_death_PPTvsQRE.svg" class="w-70 h-auto ml-10 mt-10" />

---
layout: default
title: Backup imbalance sectors
---


<div class="neversink-orange-light-scheme ns-c-bind-scheme"> 


# &nbsp; Backup: resolving by charge imbalance instead? 
</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_imbalance_spy.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Reordered by the charge imbalance  </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  - The imbalance-resolved negativity<sup>1</sup> puts ${\color{#3D81F6}\rho_{_{\uparrow\downarrow}}}$, ${\color{#FB2D45}\rho_{_\mathrm{hd}}}$ and the ${\color{#F59D13}\text{hopping}}$ elements coupling them in the **same** $q=0$ sector

  - For a single site the charge-resolved entropies are trivial: $S(q) = (0,1,0)$ at every $U$

  - For pure states, configurational vs number entanglement<sup>2</sup> = $E_{\uparrow\downarrow}$ vs $E_t + E_\mathrm{hd}$

  <br />

  <kbd> <sup>1</sup> Cornfeld, Goldstein, Sela, PRA **98**, 032302 (2018) </kbd>    
  <kbd> <sup>2</sup> Wiseman, Vaccaro, PRL **91**, 097902 (2003); Barghathi _et al._, PRL **121**, 150501 (2018) </kbd>

  </div>

</div>

---
layout: full
title: MIT 2
---

<div class="neversink-rose-scheme ns-c-bind-scheme"> 

# &nbsp; Backup: larger clusters

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-1 mt-7 mb-auto">
<div class="grid-item grid-col-span-2 pt-10"><img src="/images/half_sym_ree.svg" width=525/></div>
<div class="grid-item grid-col-span-1 text-center">

<img src="/images/4x2_ladder.svg" class="w-50 ml-15 mt-0.5" />
<img src="/images/shells_inkscaped.svg" class="w-150 ml-3 mt-5 mb-5" />

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <kbd> G.Bellomia _et al._, PRB **109**, 115104 </kbd>

</div>
<div class="grid-item grid-col-span-2 text-center h-fit">

<hr/>

Full versus symmetry-resolved entanglement between sites $\langle i j \rangle$

</div>
</div>