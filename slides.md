---
colorSchema: light
color: indigo
layout: cover
routerMode: hash
title: SCES 2026
theme: neversink
neversink_slug: "SCES 2026"
transition: slide-up
---

### `Symmetry-resolved` two-site entanglement for Mott and pseudogap physics in the 2D Hubbard model

**GABRIELE BELLOMIA**    
Research assistant at the Technische Universität Wien --- _Institut für Festkörperphysik_     
<kbd> >> with C. Mejuto-Zaera, M. Capone, A. Amaricci (CDMFT) </kbd>    
<kbd> >> with F. Bippus, T. Chalopin, [...], A. Georges, A. Kauch, I. Bloch, K. Held (cold atoms and DΓA) </kbd>

<br />
    
<img src=/images/SCES2026_logo.svg width=300 class="float-left ml-7 mt-9 mb-5">
<img src=/images/SISSAlogo_dark.svg width=300 class="float-left ml-7 mt-9 mb-7">
<img src=/images/TUWdark.svg width=150 class="float-right mr-0 ml-7 mt-8">

:: note ::  
**SCES 2026** -- _International Conference on Strongly Correlated Electron Systems_ -- [Toyama, September 30, 2026]

---
layout: default
title: Why two-site entanglement
slide_info: false
---

# Why two-site entanglement?

<div class="grid w-full grid-cols-5 gap-8 mt-2">

<div class="col-span-3">

The SCES **bet** on the third quantum revolution:

<v-clicks>

- strong interactions may grant **richer quantum resources** with respect to other platforms
- these resources are **operationally accessible** (devices)

</v-clicks>

<v-clicks>

&nbsp;&nbsp;&nbsp;&nbsp; -> must **quantify** them, with **entanglement monotones**

&nbsp;&nbsp;&nbsp;&nbsp; -> in the simplest building block (two sites $i, j$) the spin    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; structure factor $\langle S_i\!\cdot\!S_j\rangle$ is sufficient for spin models     
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <kbd> >> first talk of the session by A. Scheie! </kbd>
</v-clicks>

<v-click>
  
**What changes when electrons can move?**

</v-click>

<v-click>

Orbital two-site entanglement arises also from **tunneling**: 

</v-click>

<v-clicks>

- it can be large in **noninteracting** systems

- no obvious link to inter-particle correlations

</v-clicks>


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

<v-click>

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
--> We can measure the entanglement with the so-called **fermionic negativity**
$$
\mathcal{N}^\mathrm{F}_\mathrm{AB} = \log_2 \!\!\left[\sum_{\{\varepsilon^{T_{_\mathrm{B}}}\}}\Bigl(\varepsilon^{T_\mathrm{B}}\Bigr)\right], \quad \left\{\varepsilon^{T_\mathrm{B}}\right\} = \mathrm{SVD}(\rho^{T_\mathrm{B}})
$$


</v-click>

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

  - the ==$\exp(i\pi\phi_{\lambda\nu}^{ij})$== phase is nontrivial only for the elements in the dimer density matrix that ==break the local P-SSR==
  
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
  \mathcal{N}^\mathrm{F}_{ij} = \log_2 \!\!\left[\sum_{\{\varepsilon^{T_{_j}}\}}\Bigl(\varepsilon^{T_j}\Bigr)\right], \quad \left\{\varepsilon^{T_j}\right\} = \mathrm{SVD}(\rho^{T_j})
  $$

  - The local P-SSR (which **deletes** the ${\color{#F59D13}\Delta n=1}$ elements), recovers a block-diagonal form! 

  <v-clicks>   

  &nbsp;&nbsp;&nbsp;&nbsp;
  -> We can define ${\color{#3D81F6}\mathcal{N}^{\uparrow\downarrow}_{ij}}$ and ${\color{#FB2D45}\mathcal{N}^\mathrm{hd}_{ij}}$ by restricting  
  &nbsp;&nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp;&nbsp;
  the $\mathrm{SVD}$ to these blocks

  &nbsp;&nbsp;&nbsp;&nbsp;
  -> We would have $\mathcal{N}_{\tiny\text{P-SSR}} = {\color{#3D81F6}\mathcal{N}^{\uparrow\downarrow}_{ij}} \overset{\star}{+} {\color{#FB2D45}\mathcal{N}^\mathrm{hd}_{ij}}$     
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  $\tiny^\star\text{the composition rule for negativities involves a logarithm}$ 

  - Our way to define ${\color{#F59D13}\mathcal{N}^{\mathrm{F}t}_{ij}}$ is just as     
  ${\color{#F59D13}\mathcal{N}^{\mathrm{F}t}_{ij}} \equiv \mathcal{N}_\mathrm{AB}^\mathrm{F} \overset{\star}{-} \mathcal{N}_{\tiny\text{P-SSR}} = \mathcal{N}_\mathrm{AB}^\mathrm{F} \overset{\star}{-} {\color{#3D81F6}\mathcal{N}^{\uparrow\downarrow}_{ij}} \overset{\star}{-} {\color{#FB2D45}\mathcal{N}^\mathrm{hd}_{ij}}$

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

- We focus only on $\langle i j \rangle$  **(today)**

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

- ${\color{#F59D13}\mathcal{N}^{\mathrm{F}t}}$ is very large for $U\ll t$

<v-clicks>

- ${\color{#3D81F6}\mathcal{N}^{\uparrow\downarrow}}$ & ${\color{#FB2D45}\mathcal{N}^\mathrm{hd}}$ are small for $U\ll t$
- ${\color{#3D81F6}\mathcal{N}^{\uparrow\downarrow}}$ rises and then saturates while
${\color{#FB2D45}\mathcal{N}^\mathrm{hd}}$ vanishes at $U\gg t$
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

<!-- SSR entanglement is killed in CDMFT at low U by the mixedness of the state, as we have a highly nonlocalized metal. At large U the MIT helps recovering it, finding Hubbard-dimer-like behavior.
Also hopping entanglement is depleted by mixing, and that's why it is enhanced at the MIT.

Strong-coupling hierarchy:    
- singlet O(1)    
- hopping O(t/U)
- holon-doublon O((t/U)^2)
  > one power of t/U per unit of charge jump

This is why the red curve dies fastest
-->

---
layout: full
title: Doped CDMFT 1
transition: none
---

<div class="neversink-rose-light-scheme ns-c-bind-scheme"> 

# &nbsp; Doping-driven delocalization in CDMFT/ED

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-1 mt-7 mb-auto">
<div class="grid-item grid-col-span-2 pt-10 mb-16.3"><img src="/images/doped_sym_neg.svg" width=525/></div>
<div class="grid-item grid-col-span-1 ml-1 mr-2">

  - We **dope the Mott insulator** found at $U/D=2.3$

<v-clicks>

  - Local **density jumps** as predicted by Sordi et al.    
    PRL 104, 226402 (2010)

  - The **full entanglement** $\mathcal{N}^\mathrm{F}_{\langle ij \rangle}$ describes a **generic damping of correlations with doping** (super expected, boring 🥱)

  - Both ${\color{#FB2D45}\mathcal{N}^\mathrm{hd}_{\langle ij \rangle}}$ and ${\color{#3D81F6}\mathcal{N}^{\uparrow\downarrow}_{\langle ij \rangle}}$ decrease in the bad metal up to $\delta\simeq0.2$

</v-clicks>

<v-click>

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; $\,$ -> ==**Then what?** 👀==

</v-click>

  <!-- - ${\color{#3D81F6}\mathcal{N}^{\uparrow\downarrow}}$ **vanishes in the overdoped Fermi liquid**, while there is some residual ${\color{#FB2D45}\mathcal{N}^\mathrm{hd}} < 10^{-3}$ 
  
  WE ALREADY SAY THIS IN THE NEXT SLIDE, stupid Claude...

  -->

</div>
<div class="grid-item grid-col-span-2 text-center h-fit">

<hr/>

Full versus symmetry-resolved entanglement between sites $\langle i j \rangle$

</div>
</div>

  <!--
  The gap in the data is the first-order transition between the pseudogap metal and the Fermi liquid (Sordi, Haule, Tremblay, PRL 104, 226402 (2010); PRB 84, 075161 (2011)): densities in between cannot be converged. 
  -->

---
layout: full
title: Doped CDMFT 2
transition: view-transition
---

<div class="neversink-rose-light-scheme ns-c-bind-scheme"> 

# &nbsp; Doping-driven delocalization in CDMFT/ED

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-1 mt-7 mb-auto">
<div class="grid-item grid-col-span-2 pt-10 mb-16"><img src="/images/doped_sym_neg.svg" width=525/></div>
<div class="grid-item grid-col-span-1 text-left">

  - Remarkably, ${\color{#3D81F6}\mathcal{N}^{\uparrow\downarrow}_{\langle ij \rangle}}$ vanishes exactly in the Fermi liquid  

<v-clicks> 

  &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; Small sector so a PPT is   
  &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; faithful: true separability!
  <img src="/images/cdmft_ssr_transpose.svg" class="w-50 ml-10 mt-0 mb-6.2" />

  - $\mathcal{N}^\mathrm{hd}_{\langle ij \rangle}$ is
    instead finite (but small)    

</v-clicks>

</div>
<div class="grid-item grid-col-span-2 text-center h-fit">

<hr/>

Full versus symmetry-resolved entanglement between sites $\langle i j \rangle$

</div>
</div>

---
layout: full
title: Doped CDMFT 3
transition: slide-up
---

<div class="neversink-rose-light-scheme ns-c-bind-scheme"> 

# &nbsp; Doping-driven delocalization in CDMFT/ED

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-1 mt-7 mb-auto">
<div class="grid-item grid-col-span-2 pt-10 mb-16"><img src="/images/doped_sym_inset.svg" width=525/></div>
<div class="grid-item grid-col-span-1 text-left">

  - Remarkably, ${\color{#3D81F6}\mathcal{N}^{\uparrow\downarrow}_{\langle ij \rangle}}$ vanishes exactly in the Fermi liquid  


  &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; Small sector so a PPT is   
  &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; faithful: true separability!
  <img src="/images/cdmft_ssr_transpose.svg" class="w-50 ml-10 mt-0 mb-6.2" />

  - $\mathcal{N}^\mathrm{hd}_{\langle ij \rangle}$ is
    instead finite (but small)    


</div>
<div class="grid-item grid-col-span-2 text-center h-fit">

<hr/>

Full versus symmetry-resolved entanglement between sites $\langle i j \rangle$

</div>
</div>


---
layout: image-right
title: Cold atom simulation!
color: black
image: /images/doped_diagrams.svg
slide_info: false
transition: none
---

## ==**And the "true" pseudogap?**==

<v-clicks>

We have been able to compute ${\color{#3D81F6}\mathcal{N}^{\uparrow\downarrow}_{ij}}$ from:

- Immanuel Bloch's ultra-cold atom gas simulation of the $2D$ Hubbard model!

- Ladder version of the Dynamical Vertex Approximation (spin lambda correction)

</v-clicks>

<v-click>

<img src="/images/bloch_bippus.svg" class="w-100 ml-0 mt-5 mb--5" />

F.Bippus, T.Chalopin, **GB**,... arXiv:2605.31240
</v-click>

<div style="height: 0.35rem"></div>

---
layout: image-right
title: RVB cartoon
color: black
image: /images/nonlocal_mode_corr.svg
slide_info: false
transition: slide-left
---

## ==**And the "true" pseudogap?**==

<img src="/images/bloch_bippus.svg" class="w-100 ml-0 mt-5 mb--3" />

<v-clicks>

- We verify that spin-singlet entanglement is **closely connected to the pseudogap** (thermal death at $T^*$, overdoping death)

- We find that it is **strictly confined to nearest neighbors** (Heisenberg-like)

</v-clicks>

<v-click>

&nbsp;&nbsp;&nbsp;&nbsp; --> ==_Hint_ of a **quasilocal [R]VB** state? 🤔==

</v-click>

---
layout: default
title: Back to solids
transition: slide-up
---

<div class="neversink-sky-light-scheme ns-c-bind-scheme"> 

# &nbsp; Back to solids: can neutron scattering measure this?

</div>

<br />

<v-clicks>

- For fully localized spins, $\langle S_i\!\cdot\!S_j\rangle$ gives the concurrence (this session's **opening talk by A. Scheie**):   
  $$
  C_{ij} = \max\{0,\, -2\langle S_i\!\cdot\!S_j\rangle - \tfrac{1}{2}\} \equiv 2^{\,\color{#3D81F6}\mathcal{N}^{\,\uparrow\downarrow}_{ij}} - 1
  $$

- **Out of the Heisenberg limit**, we can define spin entanglement by symmetry resolution, but we need the weight of the $\Delta n = 0$ sector --> **need to measure the relevant diagonal elements**:
  $$
  \rho_{ij}[4,4] = \mid\downarrow\downarrow\rangle\langle\downarrow\downarrow\mid= \left\langle(\hat n_{i,\downarrow} - \hat n_{i\uparrow}\hat n_{i\downarrow})\left(\hat n_{j,\downarrow} -  \hat n_{j\uparrow} \hat n_{j\downarrow}\right)\right\rangle
  $$
    $$
  \rho_{ij}[13,13] = \mid\uparrow\uparrow\rangle\langle\uparrow\uparrow\mid= \left\langle(\hat n_{i,\uparrow} - \hat n_{i\uparrow}\hat n_{i\downarrow})\left(\hat n_{j,\uparrow} -  \hat n_{j\uparrow} \hat n_{j\downarrow}\right)\right\rangle
  $$

</v-clicks>

<div style="height: 0.35rem"></div>

<v-click>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;==**Unfortunately, we also need the charge response: EELS, RIXS?** 😶‍🌫️== 

</v-click>

<div style="height: 0.35rem"></div>

<v-click>

- The holon-doublon part ${\color{#FB2D45}\mathcal{N}^\mathrm{hd}_{ij}}$ needs _pair correlations_ between sites: an **open experimental challenge**
<div style="height: 0rem"></div>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;--> to be fair, also in cold-atom experiments...

</v-click>

<!--

KARSTEN THINKS IT IS TOO DANGEROUS TO DISCLOSE THIS

- With itinerant electrons the singlet entanglement lives where **both sites are singly occupied**; charge fluctuations only *dilute* it:   
  &nbsp;&nbsp;&nbsp;&nbsp; $\langle S_i\!\cdot\!S_j\rangle = P_{11}\,\langle S_i\!\cdot\!S_j\rangle_{11}$, &nbsp;&nbsp; $P_{11} \le \tfrac{4}{3}\langle S_i^2\rangle$
- Lower bound on the **accessible singlet negativity**, from the energy-integrated spin structure factor alone:

</v-clicks>

<v-click>

$$ 2^{\mathcal{N}^{\uparrow\downarrow}_{ij}} - 1 \;\ge\; \max\Big\{0,\; -2\langle S_i\!\cdot\!S_j\rangle - \tfrac{2}{3}\langle S_i^2\rangle\Big\} $$

</v-click>

<v-clicks>

- $\langle S_i^2\rangle = 3/4$ gives back the spin-model concurrence; the measured **local moment ($\langle S_i^2\rangle$) tightens** it &nbsp;&nbsp; -> yes/no: $\langle S_i\!\cdot\!S_j\rangle / \langle S_i^2\rangle \lt -1/3$
-->

---
layout: default
title: Take-home
---

<div class="neversink-sky-light-scheme ns-c-bind-scheme"> 

# &nbsp; What to take home?

</div>

<br />

- Symmetry resolution splits the two-site entanglement of the Hubbard model into ${\color{#F59D13}\text{hopping}}$, ${\color{#FB2D45}\text{holon-doublon}}$ and ${\color{#3D81F6}\text{spin-singlet}}$ contributions. **The last two are operationally accessible.**
- **Fermi liquid** at $U\ll t$ --> the **accessible contributions are negligible**, hopping dominates.
- **Mott insulator and pseudogap in CDMFT/ED**: nearest-neighbor **singlet entanglement dominates.**   
 Holon-doublon entanglement peaks at the MIT --> **possible connection to holon-doublon binding?**
- **Spin entanglement dies with overdoping** at the transition to the Fermi liquid ($T=0$, CDMFT/ED)    
 **and heating** above  $T^*$ (quantum-gas simulator and ladder dynamical vertex approximation).

<div class="flex justify-around mt-10">
  <div class="text-center text-sm"><QRCode value="https://doi.org/10.1103/PhysRevB.109.115104" :size="100" render-as='svg'/>
  MIT in CDMFT</div>
  <div class="text-center text-sm"><img src="/images/wip.svg" class="w-26"/> Doped CDMFT</div>
  <div class="text-center text-sm"><QRCode value="https://arxiv.org/abs/2605.31240" :size="100" render-as='svg'/> Pseudogap</div>
</div>

<!--
Optional bridge to the experiment: Sordi et al. (Sci. Rep. 2, 547 (2012)) identify T* with the Widom line emanating from this very transition, so the death across the jump at T = 0 and the death at T* in the experiment may be two faces of the same picture.

**But what about Jan von Delft's recent QCP at T = 0, from DCA/NRG?**
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
slide_info: false
---

# Backup slides

---
layout: full
color: white
title: CDMFT
transition: slide-left
---

<div class="neversink-rose-scheme ns-c-bind-scheme"> 

# &nbsp; Backup: CDMFT/ED for the 2x2 plaquette

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
layout: full
title: ASCI
---

<div class="neversink-rose-scheme ns-c-bind-scheme"> 

# &nbsp; Backup: CDMFT/ASCI for larger clusters

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-1 mt-7 mb-auto">
<div class="grid-item grid-col-span-2 pt-10"><img src="/images/4x2_ladder.svg" class="w-400 mb-10"/></div>
<div class="grid-item grid-col-span-1 text-center">

<img src="/images/shells_inkscaped.svg" class="w-150 ml-3 mt-15 mb--3" />

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $\tiny \text{G. Bellomia, C. Mejuto-Zaera, M. Capone, A. Amaricci}$
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $\tiny \text{Phys. Rev. B \textbf{109}, 115104 (2024)}$

</div>
<div class="grid-item grid-col-span-2 text-center h-fit">

<hr/>

$2\times4\,$ ladder via Adaptive Sampling Configuration Interaction

</div>
</div>

---
layout: default
title: Comparing entropy and negativity 1
transition: slide-up
---

<div class="neversink-teal-scheme ns-c-bind-scheme"> 

# &nbsp; Backup: von Neumann entropy vs negativity on pure states

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
layout: full
title: Comparing entropy and negativity 3
transition: slide-left
---

<div class="neversink-teal-light-scheme ns-c-bind-scheme"> 

# &nbsp; Backup: relative entropy vs negativity in CDMFT/ED

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-1 mt-7 mb-auto">
<div class="grid-item grid-col-span-2 pt-10 mb-15"><img src="/images/half_sym_comparison.svg" width=525/></div>
<div class="grid-item grid-col-span-1 text-left">

- ${\color{#F59D13}\mathcal{N}^{\mathrm{F}t}}$ is very large for $U\ll t$

- ${\color{#3D81F6}\mathcal{N}^{\uparrow\downarrow}}$ & ${\color{#FB2D45}\mathcal{N}^\mathrm{hd}}$ are small for $U\ll t$
- ${\color{#3D81F6}\mathcal{N}^{\uparrow\downarrow}}$ rises and then saturates while
${\color{#FB2D45}\mathcal{N}^\mathrm{hd}}$ vanishes at $U\gg t$

&nbsp; &nbsp; &nbsp; &nbsp; --> _Hubbard dimer at T = 0_
<img src="/images/2-site.svg" class="h-44.5 ml-3 mt-0 mb-0" />

</div>
<div class="grid-item grid-col-span-2 text-center h-fit">

<hr/>

Full versus symmetry-resolved entanglement between sites $\langle i j \rangle$

</div>
</div>


---
layout: full
title: Comparing entropy and negativity 3
transition: slide-up
---

<div class="neversink-teal-light-scheme ns-c-bind-scheme"> 

# &nbsp; Backup: relative entropy vs negativity in CDMFT/ED

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-1 mt-7 mb-auto">
<div class="grid-item grid-col-span-2 pt-10 mb-16"><img src="/images/doped_sym_comparison.svg" width=525/></div>
<div class="grid-item grid-col-span-1 text-left">

  - Remarkably, ${\color{#3D81F6}\mathcal{N}^{\uparrow\downarrow}_{\langle ij \rangle}}$ vanishes exactly in the Fermi liquid  

  &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; Small sector so a PPT is   
  &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; faithful: true separability!
  <img src="/images/cdmft_ssr_transpose.svg" class="w-50 ml-10 mt-0 mb-6.2" />

  - $\mathcal{N}^\mathrm{hd}_{\langle ij \rangle}$ is
    instead finite (but small)    

</div>
<div class="grid-item grid-col-span-2 text-center h-fit">

<hr/>

Full versus symmetry-resolved entanglement between sites $\langle i j \rangle$

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
title: Alternative Symmetry Resolutions
---


<div class="neversink-orange-light-scheme ns-c-bind-scheme"> 


# &nbsp; Backup: alternative symmetry resolutions? 
</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_imbalance_spy.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Partial transpose: charge imbalance sectors</kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  <div style="height: 1.7rem"></div>

  - The imbalance-resolved negativity<sup>1</sup> puts ${\color{#3D81F6}\rho_{_{\uparrow\downarrow}}}$, ${\color{#FB2D45}\rho_{_\mathrm{hd}}}$ and the ${\color{#F59D13}\text{hopping}}$ elements coupling them in the **same** $q=0$ sector

  - For a single site the charge-resolved entropies are trivial: $S(q) = (0,1,0), ~\forall\,U$

  - For pure states, configurational vs number entanglement<sup>2,3</sup> gives $E_{\uparrow\downarrow}$ vs $E_t + E_\mathrm{hd}$

  <div style="height: 2.35rem"></div>

  <kbd> <sup>1</sup> Cornfeld, Goldstein, Sela, PRA **98**, 032302 (2018) </kbd>    
  <kbd> <sup>2</sup> Wiseman, Vaccaro, PRL **91**, 097902 (2003)</kbd>    
  <kbd> <sup>3</sup> Barghathi et al., PRL **121**, 150501 (2018) </kbd>

  </div>

</div>

---
layout: default
title: Symmetry resolution of pure two-site states (1)
transition: view-transition
---


<div class="neversink-orange-light-scheme ns-c-bind-scheme"> 


# &nbsp; On pure two-site states our symmetry-resolution is exact
</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_symmetries.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Generic mixed two-site state  </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/dimer_symmetries.svg" class="h-full w-auto mr-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Pure two-site state in at half-filling </kbd></div>
  </div>

</div>

---
layout: default
title: Symmetry resolution of pure two-site states (2)
---


<div class="neversink-orange-light-scheme ns-c-bind-scheme"> 


# &nbsp; On pure two-site states our symmetry-resolution is exact
</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_ssr_transpose.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Generic mixed two-site state  </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/dimer_ssr_transpose.svg" class="h-full w-auto mr-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Pure two-site state in at half-filling </kbd></div>
  </div>

</div>
