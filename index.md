---
---

Welcome to the Photonic Quantum Systems (PhoQuS) group at the University of Maryland, College Park, led by Prof. Saikat Guha. We investigate fundamental and applied problems relating to the quantum nature of information bearing light.



{% include section.html %}

## Photonic Quantum Systems Overview

{% capture text %}

We are interested in exploring new insights and foundational connections between the quantum versions of estimation theory, information theory and detection theory. Examples of problems in this space include pursuing avenues for proving the long-standing [entropy photon number inequality](https://ieeexplore.ieee.org/document/4601037) such as by developing appropriate [scaled-addition operations](https://ieeexplore.ieee.org/document/7541390) and [de Bruijn identities](https://ieeexplore.ieee.org/document/8006658), [monotonicity of von Neumann entropy](https://dspace.mit.edu/bitstream/handle/1721.1/41840/1/Saikat%20Guha-TR723.pdf) in the bosonic central limit theorem, and developing quantum versions of the well-known [estimation-information relationships](https://ieeexplore.ieee.org/document/1412024) that led to elegant proofs of many problems in classical information theory. We also are interested in exploring properties of many-body entanglement and its connections back to principles from information theory, such as [entanglement in noisy stabilizer states](https://ieeexplore.ieee.org/document/10619666), transformation of [multi-site entanglement](https://www.computer.org/csdl/proceedings-article/qce/2023/432301b154/1SuQDgfl1oA) as it spreads via multi-qubit projections, distributed [manipulation of entanglement](https://arxiv.org/abs/2407.15652) to optimize specific utility metrics, and variations of percolation problems such as [multilayer](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.93.062310) and [site-bond](https://www.nature.com/articles/s41534-022-00536-0) percolation relevant to studying properties of many-body entanglement.

<!-- {%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%} -->

{% endcapture %}

{%
  include feature.html
  image="images/qc_temp.jpeg"
  link="research"
  flip=true
  title="Quantum Information Theory"
  text=text
%}



{% capture text %}

We explore multiple roles that the quantum theory of light plays in data communications. Utilizing quantum processing within the receiver can yield fundamentally higher data communications rate and higher photon-information efficiencies (bits encoded per received photon) compared with traditional optical receivers, for classical laser communications. The classical-quantum performance gap is the most pronounced in the regime of low received photon flux, making this an attractive solution for deep-space communications. Research topics includes the study of information theoretic concepts such as the quantum versions of [entropic inequalities](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=4601037) underlying classical communications capacity of a quantum channel, [superadditivity](https://ieeexplore.ieee.org/document/6034073) (a quantum effect that allows a collective measurement acting on more than one symbol extract more number of bits per symbol than possible with symbol-by-symbol measurements), novel error correcting codes and decoding algorithms (such as studying their [symmetry properties](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.92.062333) and novel codes such as the [polar code](https://ieeexplore.ieee.org/document/6302198), and [quantum belief propagation](https://www.nature.com/articles/s41534-021-00422-1)), joint-detection receivers to approach communications rates close to the ultimate quantum limits (such as the [Green Machine](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.106.240502), [sequential decoding](https://ieeexplore.ieee.org/document/6284251), and the [USD measurement](https://ieeexplore.ieee.org/document/6620209)), light-matter interactions for [receivers using atomic processors](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.87.052320), and experimental demonstrations of novel receivers (such as [conditional pulse nulling](https://www.nature.com/articles/nphoton.2012.113) and the [Green Machine](https://arxiv.org/abs/2310.05889)). Second, pre-shared entanglement among the transmitting and receiving parties can [enhance communications rates](https://ieeexplore.ieee.org/document/9173940) in the regime of very low transmitter brightness and high thermal noise, making this [concept](https://journals.aps.org/prapplied/abstract/10.1103/PhysRevApplied.19.064015) attractive for [covert communications](https://opg.optica.org/abstract.cfm?uri=QUANTUM-2020-QM6B.5). Finally, photons are the only viable carrier of quantum data (e.g., encoded in a stream of qubits), and there are many problems our group studies underlying the design of future quantum communications systems and networks. The research spans: capacity of quantum [communications](https://www.nature.com/articles/ncomms6235) and [networking](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10438882), developing a deep understanding of [decoherence](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.6.013055) mechanisms in atomic quantum memories, characterizing [physical-layer entanglement](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.5.033149), [quantum repeater](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.92.022357) architectures that use [time-muliplexed](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.104.052612) (including [multi-qubit](https://ieeexplore.ieee.org/document/9605337)) projective measurements at network nodes to lengthen the reach of entanglement and [high-rate photonic entanglement sources](https://journals.aps.org/prapplied/abstract/10.1103/PhysRevApplied.19.054029), error correction codes for quantum communications (both forward ECCs such as [quantum convolutional codes](https://ieeexplore.ieee.org/document/4106119) and [concatenated codes](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.5.043056) as well as codes and efficient decoders for [entanglement distillation](https://arxiv.org/abs/2408.06299)), [all-photonic repeaters](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.95.012304), and [routing protocols](https://www.nature.com/articles/s41534-019-0139-x) to lay the foundations of an eventual global quantum internet.

<!-- {%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%} -->

{% endcapture %}

{%
  include feature.html
  image="images/qn_temp.jpeg"
  link="research"
  title="Quantum Networking and Communications"
  text=text
%}

{% capture text %}

Quantum sensing uses the principles of quantum mechanics to achieve ultra-precise measurements that surpass classical limits. By exploiting quantum phenomena such as entanglement and coherent superpositions of states, quantum sensors can detect minute changes in physical quantities such as time, strain, magnetic fields, or gravitational waves. These advancements promise to transform industries ranging from healthcare to navigation and environmental monitoring. Our research spans the following broad topics: (1) Imaging: we study the [quantum limits](https://ieeexplore.ieee.org/document/8006566) of the precision of parameter estimation in passive imaging of information-bearing incoherent thermal radiation field, especially in the regime where the scene features of interest are far smaller than the [Rayleigh resolution limit](https://opg.optica.org/josaa/fulltext.cfm?uri=josaa-37-8-1288&id=433687). Our research includes the theory and design of reconfigurable [spatial mode sorters](https://opg.optica.org/abstract.cfm?uri=CLEO_AT-2022-JTh3A.28) to achieve quantum-limited resolution, with applications to [discriminating objects](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.129.180502) from a library, [localizing](https://ieeexplore.ieee.org/document/9919344) a cluster of point emitters, [exo-planet detection](https://arxiv.org/abs/2407.12776), quickest [detection of change](https://opg.optica.org/view_article.cfm?pdfKey=4020f6f8-7568-4979-89f8d2b769966894_541652) in an object, imaging [extended objects](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.99.033847), and imaging complex scenes with [long-base telescopes](https://arxiv.org/abs/2406.16789) that brings together techniques from modal imaging and entanglement assisted sensing. (2) Sensing: we study the use of squeezed light and [multi-mode entanglement](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.3.033114) derived from squeezing and other non-classical optical resources for quantum-enhanced parameter estimation, and its applications to various areas such as [fiber-optic gyroscopes](https://journals.aps.org/prapplied/abstract/10.1103/PhysRevApplied.14.034065), [beam deflectometry](https://opg.optica.org/abstract.cfm?uri=CLEO_AT-2022-JW3A.24) and [quantum radar](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10619544). 

<!-- {%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%} -->

{% endcapture %}

{%
  include feature.html
  image="images/qs_temp.jpeg"
  link="research"
  title="Quantum sensing and imaging"
  flip=true
  style="bare"
  text=text
%}