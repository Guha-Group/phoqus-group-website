---
---

Welcome to the Photonic Quantum Systems (PhoQuS) group at the University of Maryland, College Park, led by Prof. Saikat Guha. We investigate fundamental and applied problems relating to the quantum nature of information bearing light.



{% include section.html %}

## Photonic Quantum Systems Overview

{% capture text %}

We explore multiple roles that the quantum theory of light plays in data communications. Utilizing quantum processing within the receiver can yield fundamentally higher data communications rate and higher photon-information efficiencies (bits encoded per received photon) compared with traditional optical receivers, for classical laser communications. The classical-quantum performance gap is the most pronounced in the regime of low received photon flux, making this an attractive solution for deep-space communications. Research topics includes the study of information theoretic concepts such as the quantum versions of [entropic inequalities](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=4601037) underlying classical communications capacity of a quantum channel, [superadditivity](https://ieeexplore.ieee.org/document/6034073) (a quantum effect that allows a collective measurement acting on more than one symbol extract more number of bits per symbol than possible with symbol-by-symbol measurements), novel error correcting codes and decoding algorithms (such as studying their [symmetry properties](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.92.062333) and novel codes such as the [polar code](https://ieeexplore.ieee.org/document/6302198), and [quantum belief propagation](https://www.nature.com/articles/s41534-021-00422-1)), joint-detection receivers to approach communications rates close to the ultimate quantum limits (such as the [Green Machine](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.106.240502), [sequential decoding](https://ieeexplore.ieee.org/document/6284251), and the [USD measurement](https://ieeexplore.ieee.org/document/6620209)), light-matter interactions for [receivers using atomic processors](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.87.052320), and experimental demonstrations of novel receivers (such as [conditional pulse nulling](https://www.nature.com/articles/nphoton.2012.113) and the [Green Machine](https://arxiv.org/abs/2310.05889)). Second, pre-shared entanglement among the transmitting and receiving parties can [enhance communications rates](https://ieeexplore.ieee.org/document/9173940) in the regime of very low transmitter brightness and high thermal noise, making this [concept](https://journals.aps.org/prapplied/abstract/10.1103/PhysRevApplied.19.064015) attractive for [covert communications](https://opg.optica.org/abstract.cfm?uri=QUANTUM-2020-QM6B.5). Finally, photons are the only viable carrier of quantum data (e.g., encoded in a stream of qubits), and there are many problems our group studies underlying the design of future quantum communications systems and networks. The research spans: developing a deep understanding of [decoherence](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.6.013055) mechanisms in atomic quantum memories, characterizing [physical-layer entanglement](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.5.033149), [quantum repeater](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.92.022357) architectures that use [time-muliplexed](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.104.052612) (including [multi-qubit](https://ieeexplore.ieee.org/document/9605337)) projective measurements at network nodes to lengthen the reach of entanglement and [high-rate photonic entanglement sources](https://journals.aps.org/prapplied/abstract/10.1103/PhysRevApplied.19.054029), error correction codes for quantum communications (both forward ECCs such as [quantum convolutional codes](https://ieeexplore.ieee.org/document/4106119) and [concatenated codes](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.5.043056) as well as codes and efficient decoders for [entanglement distillation](https://arxiv.org/abs/2408.06299)), [all-photonic repeaters](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.95.012304), and [routing protocols](https://www.nature.com/articles/s41534-019-0139-x) to lay the foundations of an eventual global quantum internet.

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
  title="Quantum Networking and Communication"
  text=text
%}

{% capture text %}

Quantum photonic sensing uses the principles of quantum mechanics to achieve ultra-precise measurements that surpass classical limits. By exploiting quantum states like entanglement and coherence, quantum sensors can detect minute changes in physical quantities such as time, magnetic fields, or gravitational waves. These advancements promise to transform industries ranging from healthcare to navigation and environmental monitoring.

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
  title="Quantum sensing"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Photonic quantum computing harnesses the unique properties of light to perform computations that are fundamentally different from classical methods. By encoding information in photons, we can achieve high-speed operations and leverage quantum phenomena like superposition and entanglement to solve complex problems more efficiently. This approach has the potential to revolutionize fields such as cryptography, material science, and artificial intelligence.

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
  title="Quantum Computing"
  text=text
%}
