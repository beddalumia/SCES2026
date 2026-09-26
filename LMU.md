---
colorSchema: light
color: rose
layout: cover
routerMode: hash
title: LMU - ASC (2026)
theme: neversink
neversink_slug: "LMU - ASC (2026)"
transition: slide-up
---

### `Superselected` entanglement as a key to strongly correlated physics in the 2D Hubbard model

**GABRIELE BELLOMIA**    
Research assistant at the Technische Universität Wien --- _Institut für Festkörperphysik_

<br />
    
<img src=/images/FWFlight.svg width=600 class="float-left ml-7 mt-9 mb-5">
<img src=/images/TUWlight.svg width=150 class="float-right mr-10 mb-5">

:: note ::  
**Chair Seminar** --- April 15<sup>th</sup> 2026, LMU --- _Arnold Sommerfeld Center for Theoretical Physics_


---
layout: image-right
image: /images/armitage_quanta.jpg
neversink_slug: Kristina Armitage for Quanta Magazine
---


# Why entanglement?

Many-body entanglement has proven to

<v-clicks at="+1">

- be a central tool in statistical physics
- mark states of high quantum complexity

  
</v-clicks>

<v-clicks>

It is also expected to be a **resource for quantum technologies**, provided that

</v-clicks>

<v-clicks at="+1">

- it is operationally accessible
- it goes beyond (easy) classical simulation   
  
</v-clicks>

<v-click>

&nbsp;&nbsp;&nbsp;&nbsp;
-> or, at least, this would be the **"special"**    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
entanglement **brought by interactions!**   

</v-click>

<v-click>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
_...the truly many-body part_

</v-click>

---
layout: image-right
image: /images/armitage_quanta.jpg
neversink_slug: Kristina Armitage for Quanta Magazine
transition: none
---


# Particle entanglement?

Evaluating the entanglement between particles would
be the _gold-standard_ to study strongly-correlated systems.

<v-click>

Yet, there are many hills to climb:

</v-click>

<v-clicks>

- Celebrated and measurable witnesses, like the **QFI**, are not really
  quantitative     
  and are highly operator dependent.

- Quantitative objects, as the **nonfreeness**,
  can reliably quantify correlations, but do not
  resolve quantum and classical terms.

- Most new proposals for evaluating the **quantum nongaussian correlations**, appear very hard to define and compute.

- Almost all inter-particle quantities bind
  **nonlocal and multipartite** correlations together (much harder then bipartite!)

</v-clicks>

---
layout: image-right
title: Advertisement Nonfreeness
image: /images/armitage_quanta.jpg
neversink_slug: Kristina Armitage for Quanta Magazine
transition: none
---


# Particle entanglement?

We are working on it, but the multipartite monster is slowing us a lot!

---
layout: iframe-right
title: Advertisement Hubbard
url: https://arxiv.org/html/2506.18709v2
slide_info: false
transition: none
---


# Particle entanglement?

We are working on it, but the multipartite monster is slowing us a lot!

- Local correlations in the **Hubbard model** are **fully classical** (no quantum discord)
  <QRCode value="https://arxiv.org/abs/2506.18709" :size="80"  render-as='svg' class="float-right mr-7 mt-2"/> 

---
layout: iframe-right
title: Advertisement SU(N)
url: https://arxiv.org/html/2512.03689v3
slide_info: false
transition: none
---

# Particle entanglement?

We are working on it, but the multipartite monster is slowing us a lot!

- Local correlations in the **Hubbard model** are **fully classical** (no quantum discord)

<br><br><br>

- Local correlations of **SU(N) fermions** are also **fully classical** (no quantum discord)
  <QRCode value="https://arxiv.org/abs/2512.03689" :size="80"  render-as='svg' class="float-right mr-7 mt-2"/> 

---
layout: image-right
title: Advertisement Hund
image: /images/wip.svg
transition: slide-left
---

# Particle entanglement?

We are working on it, but the multipartite monster is slowing us a lot!

- Local correlations in the **Hubbard model** are **fully classical** (no quantum discord)

<br><br><br>

- Local correlations of **SU(N) fermions** are also **fully classical** (no quantum discord)

<br><br><br>

- Local **quantum** correlations emerge with **Hund's coupling** but U kills them quickly

---
layout: image-right
title: Orbital entanglement 1
color: black
image: images/mps_peps.svg
transition: slide-up
slide_info: true
neversink_slug: "	J. Phys. A: Math. Theor. 51 135301 (2018)"
---

# Orbital entanglement

The framework of **orbital entanglement is much more mature**, thanks to the rise of tensor networks and related algorithms.

<v-clicks>

- Partitioning into **distinguishable subsystems** (orbitals, modes)

</v-clicks>

---
layout: image-right
title: Orbital entanglement 2
color: black
image: images/nonlocal_mode_corr.svg
slide_info: false
---

# Orbital entanglement

The framework of **orbital entanglement is much more mature**, thanks to the rise of tensor networks and related algorithms.

- Partitioning into **distinguishable subsystems** (orbitals, modes)

- Much more developed information theory (e.g. **nonlocal bipartite entanglement**)

<v-clicks>

- Particles are not anymore the main actors

</v-clicks>

<v-click>
&nbsp;&nbsp;&nbsp;&nbsp;
 --> spatial correlations also from tunneling
</v-click>
<br/><br/>
<v-click>
&nbsp;&nbsp;&nbsp;&nbsp;
 --> can be large in noninteracting systems
</v-click>
<br/><br/>
<v-click>
&nbsp;&nbsp;&nbsp;&nbsp;
 --> no obvious link to strong-correlations
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; in the sense of the SCES community
</v-click>


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


# &nbsp; Symmetries of a Hubbard dimer (in a general mixed state) 
</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_symmetries.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Rotated to highlight two-site symmetries  </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  <v-clicks>

  - The Hubbard model conserves the charge $N$ (and magnetization $m$)
  - Of course this does not imply a local conservation of $n_i$ and $n_j$
  - So in general we have quantum superpositions (off-diagonals)    
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

# &nbsp; Symmetries of a Hubbard dimer (in a general mixed state) 

</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_ssr.svg" class="h-full w-auto ml-3.5 " />   
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Rotated to highlight single-site symmetries  </kbd></div>

  <div class="grid-item grid-col-span-2 ml-7"> 

  - So in general we have quantum superpositions (off-diagonals)    
    ==**->** entanglement between $i$ and $j$==
    <div class="flex justify-left my-4 ml-17 ">
    <img src="/images/dimer_entangled.svg" width="150" />
    </div>  

  <v-clicks depth=2>

  - But **local** SSRs inhibit all quantum superpositions except:
    - holon-doublon binding   
      ${\color{#F43F5E}\rho_{_\mathrm{hd}} \!\!=\, \mid \uparrow\downarrow \rangle\langle \bullet\!\mid \otimes \mid\!\bullet \rangle\langle \uparrow\downarrow \mid}$ 
    - antiferromagnetic (RVB) fluctuations  
      ${\color{#3D81F6}\rho_{_{\uparrow\downarrow}} \!\!=\, \mid \uparrow \rangle\langle \downarrow \mid \otimes \mid\downarrow\rangle\langle \uparrow\mid}$ 

  </v-clicks></div>

</div>

---
layout: default
title: Partial Transposing 1
transition: none
---


<div class="neversink-fuchsia-light-scheme ns-c-bind-scheme"> 


# &nbsp; Detecting entanglement via partial transposing 
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


# &nbsp; Detecting entanglement via partial transposing 
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

# &nbsp; Detecting entanglement via partial transposing 
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
\mathcal{N}^\mathrm{F}_\mathrm{AB} = \log_2 \!\!\left[\sum_{\{\varepsilon^{T_{_\mathrm{B}}}\}}\Bigl(\varepsilon^{T_\mathrm{B}}\Bigr)\right], \quad \left\{\varepsilon^{T_\mathrm{B}}\right\} = \mathrm{svd}(\rho^{T_\mathrm{B}})
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


# &nbsp; Detecting entanglement via partial transposing 
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
  -> ${\Large \color{#3D81F6}\rho_{_{\uparrow\downarrow}}\!}$ and ${\Large \color{#F43F5E}\rho_{_\mathrm{hd}}}$ give "~boson entanglement"    
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
   (~spinon, ~holon, ~doublon)
  <br /><br />

  - If we __resolve__ the three contributions we
    might access meaningful physical insight

  </v-clicks>

  </div>

</div>

---
layout: default
title: Pure Hubbard dimer
transition: none
---


<div class="neversink-green-light-scheme ns-c-bind-scheme"> 


# &nbsp; Simpler case: a pure Hubbard dimer (${\small T=0}$, isolated) 
</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_symmetries.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Most general mixed state for a Hubbard dimer  </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/dimer_symmetries.svg" class="h-full w-auto mr-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Ground state of an isolated Hubbard dimer </kbd></div>
  </div>

</div>

---
layout: default
title: Mixed vs Pure 1
transition: none
---


<div class="neversink-green-light-scheme ns-c-bind-scheme"> 


# &nbsp; Simpler case: a pure Hubbard dimer (${\small T=0}$, isolated) 
</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_ssr.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Rotated to highlight single-site symmetries   </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/dimer_ssr.svg" class="h-full w-auto mr-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Rotated to highlight single-site symmetries  </kbd></div>
  </div>

</div>

---
layout: default
title: Mixed vs Pure 2
transition: none
---


<div class="neversink-green-light-scheme ns-c-bind-scheme"> 


# &nbsp; Simpler case: a pure Hubbard dimer (${\small T=0}$, isolated) 
</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_pretranspose.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Rotated to highlight single-site symmetries   </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/dimer_pretranspose.svg" class="h-full w-auto mr-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Rotated to highlight single-site symmetries  </kbd></div>
  </div>

</div>

---
layout: default
title: Mixed vs Pure 3
transition: none
---


<div class="neversink-green-light-scheme ns-c-bind-scheme"> 


# &nbsp; Simpler case: a pure Hubbard dimer (${\small T=0}$, isolated) 
</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_partial_transpose.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Partial transposed on one of the two sites  </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/dimer_partial_transpose.svg" class="h-full w-auto mr-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Partial transposed on one of the two sites  </kbd></div>
  </div>

</div>

---
layout: default
title: Mixed vs Pure 4
transition: slide-left
---


<div class="neversink-green-light-scheme ns-c-bind-scheme"> 


# &nbsp; Simpler case: a pure Hubbard dimer (${\small T=0}$, isolated) 
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
title: Symmetry resolution of PPT
---

<div class="neversink-green-scheme ns-c-bind-scheme"> 

# &nbsp; Symmetry decomposition of the fermionic negativity

</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/dimer_ssr_transpose.svg" class="h-full w-auto ml-3.5 " />   
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Reshuffled to highlight PT symmetries  </kbd></div>

  <div class="grid-item grid-col-span-2 ml-7"> 

  <br />

$$
\mathcal{N}^\mathrm{F}_\mathrm{AB} = \log_2 \!\!\left[\sum_{\{\varepsilon^{T_{_\mathrm{B}}}\}}\Bigl(\varepsilon^{T_\mathrm{B}}\Bigr)\right], \quad \left\{\varepsilon^{T_\mathrm{B}}\right\} = \mathrm{svd}(\rho^{T_\mathrm{B}})
$$

  <br />

  <v-click>

  $$
  \left\{\varepsilon^{T_\mathrm{B}}\right\} = {\color{#3D81F6}\left\{\varepsilon^{T_\mathrm{B}}_{\uparrow\downarrow}\right\}} \cup {\color{#F59D13}\left\{\varepsilon^{T_\mathrm{B}}_{t}\right\}} \cup {\color{#FB2D45}\left\{\varepsilon^{T_\mathrm{B}}_\mathrm{hd}\right\}}
  $$

  </v-click>

  <br />

  <v-click>

  $$
  \mathcal{N}^\mathrm{F}_\mathrm{AB} = \log_2 \!\left[{\color{#3D81F6}N_{\uparrow\downarrow}} + {\color{#F59D13}N_{t}} + {\color{#FB2D45}N_\mathrm{hd}} \right]
  $$

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  **--> Success!**

  </v-click>

  </div>

</div>

---
title: Symmetry resolution of von Neumann entropy
---

<div class="neversink-indigo-scheme ns-c-bind-scheme"> 

# &nbsp; For a pure state we can resolve the von Neumann entropy

</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/dimer_ssr_transpose.svg" class="h-full w-auto ml-3.5 " />   
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Reshuffled to highlight PT symmetries  </kbd></div>

  <div class="grid-item grid-col-span-2 ml-7"> 

  $$
  \small
  E_\mathrm{AB} \equiv S_\mathrm{A} = -\sum_i p_i \log_2 p_i
  $$

  <v-click>

  $$
  \small
  \{p_i\} = \{\delta+D,n_\uparrow-D,n_\downarrow-D,D\}
  $$

  $$
  \small
  \delta = 1 - n_\uparrow - n_\downarrow, \enspace D = \langle n_\uparrow n_\downarrow \rangle
  $$

  </v-click>

  <v-click>

  $$
  {\footnotesize \color{#3D81F6}S_{\uparrow\downarrow} = (p_2+p_3)\log_2(p_2+p_3) - p_2\log_2 p_2 - p_3\log_2 p_3} 
  $$

  $$
  \footnotesize
  {\color{#F59D13}S_{t} = -(p_1+p_4)\log_2(p_1+p_4) - (p_2+p_3)\log_2(p_2+p_3)}
  $$

  $$
  \footnotesize 
  {\color{#FB2D45}S_\mathrm{hd} = (p_1+p_4)\log_2(p_1+p_4) - p_1\log_2 p_1 - p_4\log_2 p_4} 
  $$
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Ding _et al._, JCTC 17, 79-95 (2020) </kbd>

  </v-click>

  <v-click>

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  ${
  S_\mathrm{A} = {\color{#3D81F6}S_{\uparrow\downarrow}} + {\color{#F59D13}S_{t}} + {\color{#FB2D45}S_\mathrm{hd}}}\enspace$ **--> &nbsp;&nbsp; Success!**

  </v-click>

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
layout: default
title: A way out
transition: slide-up
---


<div class="neversink-orange-light-scheme ns-c-bind-scheme"> 


# &nbsp; Returning to the general mixed case: how to resolve? 
</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_ssr_transpose.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Reshuffled to highlight PT symmetries  </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  - The local P-SSR (which ==deletes the yellow== elements), recovers a block-diagonal form! 

  <v-clicks>   

  &nbsp;&nbsp;&nbsp;&nbsp;
  -> We can define ${\color{#3D81F6}E_{\uparrow\downarrow}}$ and ${\color{#FB2D45}E_\mathrm{hd}}$ in a clear way

  &nbsp;&nbsp;&nbsp;&nbsp;
  -> We would have $E_{\tiny\text{P-SSR}} = {\color{#3D81F6}E_{\uparrow\downarrow}} \overset{\star}{+} {\color{#FB2D45}E_\mathrm{hd}}$     
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  $\tiny^\star\text{recall the composition rule for negativities}$ 

  - The best way to define ${\color{#F59D13}E_{t}}$ is just as     
  $E_\mathrm{AB} \equiv {\color{#F59D13}E_{t}} \overset{\star}{+} {\color{#3D81F6}E_{\uparrow\downarrow}} \overset{\star}{+} {\color{#FB2D45}E_\mathrm{hd}}$, i.e.$\,$the portion suppressed by the P-SSR

  &nbsp;&nbsp;&nbsp;&nbsp;
  -> Easy to do with $\mathcal{N}^\mathrm{F}_\mathrm{AB}$ as a measure of $E_\mathrm{AB}$

  &nbsp;&nbsp;&nbsp;&nbsp;
  -> Hard open problem with entanglement    
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  $\,$measures based on entropies 🥲

  </v-clicks>

  </div>&nbsp;&nbsp;&nbsp;&nbsp;

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
layout: section
color: rose
title: Results from CDFMT
---

# Results from Cluster-DMFT


Across both the `interaction-driven` and `density-driven` Mott transitions

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
title: MIT 1
slide_info: false
---

<div class="neversink-rose-scheme ns-c-bind-scheme"> 

# &nbsp; Interaction-driven Mott metal-insulator transition (MIT)

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-1 mt-0 mb-auto">

  <div class="grid-item grid-col-span-2 mr-0 mt-14">

  - We start from a noninteracting metal: free electronic quasiparticles

  <br>

  <v-click>

  - As we increase the interaction $U$, we start losing quasiparticles

  </v-click>

  <br>

  <v-click>

  - The missing weight goes to high-energy incoherent excitations

  </v-click>

  <br>

  <v-click>

  - At large $U$, the incoherent excitations form two gapped bands

  </v-click>

  <br>

  <v-click>

  - Eventually, all quasiparticles are gone and a Mott insulator is born

  </v-click>

  </div>

  <div class="grid-item grid-col-span-1">
    <img src="/images/dos_dmft.svg" class="w-56 mt-10 mb-10 ml-15" />
  </div>

</div>


---
layout: full
title: MIT 2
---

<div class="neversink-rose-scheme ns-c-bind-scheme"> 

# &nbsp; Interaction-driven paramagnetic MIT

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-1 mt-7 mb-auto">
<div class="grid-item grid-col-span-2 pt-10"><img src="/images/half_sym_ree.svg" width=525/></div>
<div class="grid-item grid-col-span-1 text-center">
<v-click at=0>

<img src="/images/4x2_ladder.svg" class="w-50 ml-15 mt-0.5" />
<img src="/images/shells_inkscaped.svg" class="w-150 ml-3 mt-5 mb-5" />

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <kbd> G.Bellomia _et al._, PRB **109**, 115104 </kbd>

</v-click>
</div>
<div class="grid-item grid-col-span-2 text-center h-fit">

<hr/>

Symmetry-resolved versus full entanglement between sites $\langle i j \rangle$

</div>
</div>


---
layout: full
title: MIT 3
transition: slide-left
---

<div class="neversink-rose-scheme ns-c-bind-scheme"> 

# &nbsp; Interaction-driven paramagnetic MIT

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-1 mt-7 mb-auto">
<div class="grid-item grid-col-span-2 pt-10 mb-15"><img src="/images/half_sym_neg.svg" width=525/></div>
<div class="grid-item grid-col-span-1 text-left">

Hubbard dimer reference:

<img src="/images/2-site.svg" class="h-40 ml-3 mt-0 mb-5" />

- ${\color{#3D81F6}E_{\uparrow\downarrow}}$ still plateaus at $U\gg t$
- ${\color{#FB2D45}E_\mathrm{hd}}$ nearly vanishes at $U\ll t$
- ${\color{#F59D13}E_{t}}$ accounts for the quite 
  large negativity in the $U\ll t$ regime


</div>
<div class="grid-item grid-col-span-2 text-center h-fit">

<hr/>

Symmetry-resolved entropy vs negativity between sites $\langle i j \rangle$

</div>
</div>

<!-- The holon-doublon entanglement is missed in CDMFT at low U cause the mixedness of the state kills all entanglement there, as we have a highly nonlocalized metal. At large U the MIT helps recovering it. -->

---
layout: image-right
title: Doped Diagram
image: /images/doped_diagrams.svg
slide_info: false
---

# Doping a Mott insulator

<v-clicks>

- Relevant to the physics of cuprate superconductors (high $T_\mathrm{c}$ $d$-wave)

- Our zero-temperature analysis neglects all spontaneous symmetry breaking channels

- Similar to the **partial delocalization** to a **pseudogap metal** (at high temperature)

- At larger dopings, we enter again a Fermi liquid metal (no gaps in the Fermi surface)

- The **pseudogap** phase is often deemed as a highly incoherent "bad metal" with **strong short-range correlations**

- Hence we expect entanglement properties to be **similar to a Mott insulator**, despite being a metallic (delocalized) phase

</v-clicks>

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
  - Both $E_{\langle ij \rangle}^\mathrm{hd}$ and $E_{\langle ij \rangle}^{\uparrow\downarrow}$ decrease in the bad metal up to $\delta\simeq0.2$
  - The spin-singlet $E_{\langle ij \rangle}^{\uparrow\downarrow}$ vanishes in the normal Fermi liquid, while there is some residual $E_{\langle ij \rangle}^\mathrm{hd}$...

</v-clicks>
</div>
<div class="grid-item grid-col-span-2 text-center h-fit">

<hr/>

Symmetry-resolved versus full entanglement between sites $\langle i j \rangle$

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


---
layout: section
color: indigo
title: Experiments
---

# Experimental verification


Can we verify/extend our statements for the 2D Fermi-Hubbard model?

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

  Surely easier to target ${\color{#3D81F6}E_{\uparrow\downarrow}}$ and ${\color{#FB2D45}E_\mathrm{hd}}$ than ${\color{#F59D13}E_{t}}$

  Unfortunately still hard to directly access it, at least on solid state systems...

  </v-clicks>


---
layout: iframe-right
title: Thomas Chalopin
color: black
url: https://arxiv.org/html/2412.17801v2
slide_info: false
transition: slide-left
---

# Experimental measures?

<br/>

  Surely easier to target ${\color{#3D81F6}E_{\uparrow\downarrow}}$ and ${\color{#FB2D45}E_\mathrm{hd}}$ than ${\color{#F59D13}E_{t}}$

  Unfortunately still hard to directly access it, at least on solid state systems...

  Yet, **a recent experiment**  has succeeded in entering the
  pseudogap phase in a **quantum gas simulator** for the Fermi-Hubbard model!

  <v-clicks>

  - They reach **low enough temperatures** to develop signatures of a pseudogap

  - <img src="/images/chalopin_connected_correlators.svg" class="w-100 ml-0 mt-0 mb-5" />

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

<kbd> F. Bippus, T. Chalopin, **GB** et al., _in preparation_   </kbd>

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

<kbd> F. Bippus, T. Chalopin, **GB** et al., _in preparation_   </kbd>

<div style="height: 0.35rem"></div>

- It supports a ==**quasilocal RVB theory**== of the pseudogap metal in high-$T_\mathrm{c}$ cuprates



---
layout: default
title: Thermal Death of Entanglement
color: white
transition: none
---

<div class="neversink-indigo-scheme ns-c-bind-scheme"> 

# &nbsp; Is the thermal death of entanglement a general feature?

</div>

<!-- ## ==**Is the thermal death of entanglement a more general feature?**== -->
<br>

<v-clicks>

- In the atomic limit, **very small temperatures wipe away the SSR entanglement** of the Hubbard dimer
  <img src="/images/lexin_dissociation.svg" class="w-150 mt-3 mb-5" /> 

- In the 2D Fermi-Hubbard model, entanglement survives **up to the pseudogap temperature** (high!)     
  <kbd> >> F. Bippus, T. Chalopin, **GB** et al., _in preparation_   </kbd>

- ==**How to connect these regimes?**== 

- ==**What are the common properties?**== 

</v-clicks>
---
layout: default
title: Advertisement
color: white
transition: slide-up
---

<div class="neversink-indigo-scheme ns-c-bind-scheme"> 

# &nbsp; Is the thermal death of entanglement a general feature?

</div>

<!-- ## ==**Is the thermal death of entanglement a more general feature?**== -->

<img src="/images/Thermal_Death_Teaser.svg" class="block w-200 mx-auto mt-15 mb-5" />


---
layout: image
title: Thank you for your attention!
image: /images/ThankYou.svg
slide_info: false
---