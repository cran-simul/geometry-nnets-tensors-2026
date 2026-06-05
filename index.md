## Geometry of Neural Networks and Tensors in Nancy (2026)

![IDMC](SRC-1516-01-1.jpg)

**Location**: IDMC (Institut des Sciences du Digital Management & Cognition), Pôle Herbert Simon, 13 rue Michel Ney, Nancy (rooms 206 / 207).  [How to get there](https://www.openstreetmap.org/directions?engine=fossgis_osrm_foot&route=48.68995%2C6.17449%3B48.69743%2C6.17170#map=16/48.69372/6.17266) from the train station. 

**Date**: 9:15am, Wednesday June 10th, 2026.

## About the Workshop
This one-day workshop will focus on the theoretical study of neural networks  and tensor decompositions using geometric tools. The main topic is the geometry of the corresponding algebraic varieties: neurovarieties (in case of neural networks) and secant varieties (for tensor decompositions). In machine learning theory, understanding  geometry of neurovarieties has proven to be the key to reveal many of their fundamental properties such as their identifiability, expressivity, and the behavior of optimization algorithms (see, for example, [neuroalgebraicgeometry.ai](https://neuroalgebraicgeometry.ai) ). The workhop will present recent developments and discuss connections between neural networks and tensor decompositions.
This is a follow-up of the [workshop on geometry of tensors](https://cran-simul.github.io/tensors-geometry-workshop/) organized in 2025.

The topics of the workshop include, but not limited to: 
 * geometry of low-rank matrix/tensor decompositions
 * geometry of neural networks
 * neurovarieties and secant varieties, X-rank decompositions
 * uniqueness/identifiability of models
 * expressivity
 * optimization and characterization of critical points

## Registration
Registration is free but mandatory (by June 1). You are welcome to present a poster related to the topics of the workshop.


## Invited speakers
- [Kathlén Kohn](https://kathlenkohn.github.io/) (KTH, Stockholm, Sweden)
- [Alex Massarenti](http://mcs.unife.it/alex.massarenti/index.html) (University of Ferrara, Ferrara, Italy)
- [Maksym Zubkov](https://www.maksymzubkov.info/) (University of British Columbia, Vancouver, Canada)

### Poster contributions 
- Sanyam Agarwal (Saarland University) *The Limits of Tractable Marginalization*
- Ricardo Borsoi (CRAN) *Identifiability of Deep Polynomial Neural Networks*
- Julian Brandon (ENS Paris) *Emergent Riemannian geometry over learning discrete computations on continuous manifolds*
- Antonio Fazzi (CRAN) *Structured low-rank approximation for multiple signal recovery from correlations*
- Chuong Luong (CRAN) *Structural Criteria for Generic Essential Uniqueness of Block-Term Decompositions*
- Konstantin Usevich (CRAN) *Uniqueness and algorithms for ParaTuck-2 tensor decompositions*
- Lyuhui Wu (Sorbonne Université) *Convex Analysis and Monge–Ampère Equations on Tropical Varieties*


<a name="schedule"></a>
## Schedule

| **Time**         | **Session**                             |
|------------------|-----------------------------------------|
| 08:50-09:15      | Welcome,  coffee + pastries               |
|------------------|------------------------------------------|
| 09:15-09:30      | Opening remarks (from organizers)                     |
| 09:30-10:45      | Kathlén Kohn <br/>  *Algebraic Neural Network Theory*  [(abstract)](#kathlen-kohn)  |
| 10:45-11:15      | Coffee break                        |
| 11:15-12:30      | Alex Massarenti <br/> *Bronowski’s Conjecture, Identifiability, and Neurovarieties*   [(abstract)](#alex-massarenti)                    |
| 12:30-14:00      | Lunch   (on site, for registered participants)                    |
| 14:00-15:15     | Maksym Zubkov <br/> *The Interplay of Tensors and Neural Networks*    [(abstract)](#maksym-zubkov)               |         
| 15:15-15:30  |  Poster teasers                  |
| 15:30-17:00      | [Poster session](#poster-abstracts) + coffee      |

<a name="kathlen-kohn"></a>
### Kathlén Kohn 
*Algebraic Neural Network Theory*

**Abstract:** 
The space of functions parametrized by a fixed neural network architecture is known as
its ’neuromanifold’, a term coined by Amari. Training the network means to solve an optimization
problem over the neuromanifold. Thus, a complete understanding of its intricate geometry would
shed light on the mysteries of deep learning. This talk explores the approach to approximate neural
networks by algebraic ones that have semialgebraic neuromanifolds. Such approximation is possible
for any continuous network on a compact data domain. By the universal approximation theorem,
algebraic neural networks are essentially the only ones whose neuromanifolds span finite-dimensional
ambient spaces. In this setting, we can interpret training the network as finding a ‘closest’ point
on the neuromanifold to some data point in the ambient space. This perspective enables us to
understand the loss landscape better, which is the graph of the loss function over the neuromanifold.
In particular, the singularities (and boundary points) of the neuromanifold can cause a tradeoff
between efficient optimization and good generalization: On the one hand, singularities can yield
numerical instability and slow the learning process (which was already observed by Amari). On
the other hand, we will observe how the same singularities cause implicit bias to stable and sparse
solutions. Computing the singularities is often a technical endeavor, and requires us to determine
both the hidden parameter symmetries of the network and the critical points of the network’s
parametrization map. This talk overviews how machine-learning concepts can be formulated in 
algebro-geometric terms and compares 3 popular architectures: multilayer perceptrons, 
convolutional networks, and self-attention networks.

[(back to schedule)](#schedule)


### Alex Massarenti 
*Bronowski’s Conjecture, Identifiability, and Neurovarieties*

**Abstract:** 
I will discuss recent results, obtained in collaboration with Massimiliano Mella, on polynomial neural networks and their associated neurovarieties, focusing on expected dimension, non-defectiveness, and global identifiability. I will then relate these ideas to Bronowski-type criteria for identifiability, including an amended form of Bronowski’s conjecture that reduces identifiability questions to secant defectiveness for a broad class of varieties.

[(back to schedule)](#schedule)

### Maksym Zubkov 
*The Interplay of Tensors and Neural Networks*

**Abstract:**
In this talk, we will explore (neuro)algebraic geometry, an emerging field analogous to algebraic statistics that uses algebraic geometry to study the theory of deep learning. We fix a feedforward neural network architecture with polynomial or rational activation functions and associate an algebraic (neuro)variety to the given architecture. I will present recent results showing how the study of neurovarieties arising from shallow polynomial and rational neural networks connects to several classical questions in algebraic geometry, including Chow varieties, secant varieties of Veronese and Grassmann varieties, Weyl’s conjectures, and other related topics. On the other hand, moving beyond shallow architectures brings a rich collection of classical algebro-geometric objects into focus, whose study may help us better understand the geometry underlying deep learning theory. More broadly, the talk will illustrate how algebro-geometric tools complement the more familiar statistical and probabilistic approaches to the mathematical foundations of deep learning.

[(back to schedule)](#schedule)

## Poster abstracts

### Sanyam Agarwal (Saarland University) 
*The Limits of Tractable Marginalization*

**Abstract:**
Marginalization -- summing a function over all assignments to a subset of its inputs -- is a fundamental computational problem with applications from probabilistic inference to formal verification. Despite its computational hardness in general, there exist many classes of functions (e.g., probabilistic models) for which marginalization remains tractable, and they can all be commonly expressed by arithmetic circuits computing multilinear polynomials. This raises the question, can all functions with polynomial time marginalization algorithms be succinctly expressed by such circuits? We give a negative answer, exhibiting simple functions with tractable marginalization yet no efficient representation by known models, assuming FP $\neq$ #P (an assumption implied by P $\neq$ NP). To this end, we identify a hierarchy of complexity classes corresponding to stronger forms of marginalization, all of which are efficiently computable on the known circuit models. We conclude with a completeness result, showing that whenever there is an efficient real RAM performing virtual evidence marginalization for a function, then there are small arithmetic circuits for that function's multilinear representation.

[(back to schedule)](#schedule)

### Ricardo Borsoi (CRAN) 
*Identifiability of Deep Polynomial Neural Networks*

**Abstract:**
Polynomial Neural Networks (PNNs) possess a rich algebraic and geometric structure. However, their identifiability-a key property for ensuring interpretability-remains poorly understood. In this work, we present a comprehensive analysis of the identifiability of deep PNNs, including architectures with and without bias terms. Our results reveal an intricate interplay between activation degrees and layer widths in achieving identifiability. As special cases, we show that architectures with non-increasing layer widths are generically identifiable under mild conditions, while encoder-decoder networks are identifiable when the decoder widths do not grow too rapidly compared to the activation degrees. Our proofs are constructive and center on a connection between deep PNNs and low-rank tensor decompositions, and Kruskal-type uniqueness theorems. We also settle an open conjecture on the dimension of PNN's neurovarieties, and provide new bounds on the activation degrees required for it to reach the expected dimension.

[(back to schedule)](#schedule)

### Julian Brandon (ENS Paris) 
*Emergent Riemannian geometry over learning discrete computations on continuous manifolds*

**Abstract:**
Many tasks require mapping continuous input data (e.g. images) to discrete task outputs (e.g. class labels). Yet, how neural networks learn to perform such discrete computations on continuous data manifolds remains poorly understood. Here, we show that signatures  of such computations emerge in the representational geometry of neu ral networks as they learn. By analysing the Riemannian pullback metric across layers of a neural network, we find that network computation can be decomposed into two functions: discretising continuous input features and performing logical operations on these discretised variables. Furthermore, we demonstrate how different learning regimes (rich vs. lazy) have contrasting metric and curvature structures, affecting the ability of the networks to generalise to unseen inputs. Overall, our work provides a geometric framework for understanding how neural networks learn to perform discrete computations on continuous manifolds.

### Antonio Fazzi (CRAN) 
*Structured low-rank approximation for multiple signal recovery from correlations*

**Abstract:**
We address the recovery of multiple complex signals from noisy correlation-based measurements. The inverse problem is nonlinear and is affected by intrinsic global phase ambiguity. The main idea is to lift the correlation tensor to block subresultant structured matrices, where signal identifiability is encoded by rank deficiency and a one-dimensional kernel. This formulation leads naturally to a weighted structured low-rank approximation problem for noisy data, with weights induced by the measurement operator. This framework provides both identifiability guarantees and algorithms for signal reconstruction from noisy correlation measurements.


[(back to schedule)](#schedule)


### Chuong Luong (CRAN) 
*Structural Criteria for Generic Essential Uniqueness of Block-Term Decompositions*

**Abstract:**
We study generic uniqueness questions for non-uniform block-term tensor decompositions. For a prescribed block type ($(L_r,M_r,N_r)_{r=1}^R$), we formulate the problem at the level of mode subspaces by interpreting the decomposition through an associated join of subspace varieties. This leads to a subspace-level notion of essential uniqueness, where the goal is to recover the block mode subspaces up to permutation. Our main result gives a structural sufficient criterion for this uniqueness. In the multi-block case ($R \geq 3$), we show that three conditions—splitting in one mode, a separation condition in the (($B \otimes C$))-mode, and a rectangular rigidity condition—imply subspace essential uniqueness of the induced join model. The proof combines Terracini’s lemma with a contact-point rigidity argument, showing that tangential contact points cannot mix several supporting blocks. Finally, under the one-mode splitting assumption, the recovered subspaces determine the block summands themselves by projection. Hence the criterion yields generic essential uniqueness of the corresponding block-term decompositions, up to permutation of the typed blocks and the standard blockwise changes of bases.

[(back to schedule)](#schedule)


### Konstantin Usevich (CRAN) 
*Uniqueness and algorithms for ParaTuck-2 tensor decompositions*

**Abstract:**
The ParaTuck-2 decomposition (PT2D) of third-order tensor is a two-layer generalization of the well-known canonical polyadic decomposition (CPD). While being more flexible than the CPD, the PT2D also possesses similar uniqueness properties. In this paper, we show than under the best known uniqueness conditions, the exact PT2D can be computed by an algebraic algorithm (i.e., can the PT2D problems can be reduced to computing nullspaces and eigenvalues of certain matrices). We do so by lifting the slices of the tensor to higher-dimensional space, which also allows for refining the existing uniqueness conditions. The algorithms are developed for general PT2D and its symmetric version (DEDICOM), which leads to an algebraic algorithm for another generalization of the CPD, the PARAFAC2 decomposition. 

[(back to schedule)](#schedule)


### Lyuhui Wu (Sorbonne Université) 
*Convex Analysis and Monge–Ampère Equations on Tropical Varieties*

**Abstract:**
In the first part, we present convex functions on polyhedral spaces. We define a convex function on a polyhedral space as a continuous function that admits a local affine support function at each point. This class of convex functions turns out to coincide with the class introduced by Botero-Burgos-Sombra. We present several convex-analytic results, including a regularization theorem stating that every convex function on a polyhedral space can be uniformly approximated by piecewise linear convex functions.
In the second part, we introduce the Monge-Ampère measure for functions on a tropical variety, and studies tropical Monge-Ampère equations. We present the result the tropical analogue of Calabi-Yau theorem fails on any tropical variety which is of dimension at least $2$ and satisfies some genericity condition.


[(back to schedule)](#schedule)

## Organizers
- [Ricardo Borsoi](https://ricardoborsoi.github.io) 
- [Marianne Clausel](https://sites.google.com/site/marianneclausel/home)
- [Konstantin Usevich](http://w3.cran.univ-lorraine.fr/konstantin.usevich/)
- [SiMul research group](https://cran-simul.github.io) of [CRAN](https://www.cran.univ-lorraine.fr)
  
Contact: firstname.lastname @ univ-lorraine.fr


---
### Sponsors

This event was supported in part by:
- The PEPR IA project [TENSOR4ML](https://www.pepr-ia.fr/projet/tensor4ml-2/) (ANR-25-PEIA-0003) 
- The [IA Cluster ENACT Grand Est](https://cluster-ia-enact.ai/)
- The [University of Lorraine](https://www.univ-lorraine.fr/), pôle AM2I
- The [Réseau Thématique MAIAGES](https://rt-maiages.math.cnrs.fr/) 
- The [CNRS](https://www.cnrs.fr/en)



<table width="100%" cellspacing="0" cellpadding="0" border="0" style="border-collapse: collapse; border: none;">
  <tr>
    <td align="center" width="15%">
      <img src="ENACT_LOGO_noir.png" alt="ENACT" style="max-width: 100%; height: auto;" />
    </td>
    <td align="center" width="10%">
      <img src="Logotype_france2030.png" alt="PEPR" style="max-width: 100%; height: auto;" />
    </td>
    <td align="center" width="12%">
      <img src="Logo_CRAN.jpg" alt="CRAN" style="max-width: 100%; height: auto;" />
    </td>
    <td align="center" width="15%">
      <img src="LOGO_UL.png" alt="UL" style="max-width: 100%; height: auto;" />
    </td>
    <td align="center" width="10%">
      <img src="Logo_CNRS.png" alt="UL" style="max-width: 100%; height: auto;" />
    </td>
    <td align="center" width="15%">
      <img src="LOGO_GDR_IASIS.png" alt="CNRS-IASIS" style="max-width: 100%; height: auto;" />
    </td>
    <td align="center" width="12%">
      <img src="rt_maiages-300x225.png" alt="MAIAGES" style="max-width: 100%; height: auto;" />
    </td>

  </tr>
</table>



---

&copy; 2026 Geometry of  Neural Networks and Tensors in Nancy
