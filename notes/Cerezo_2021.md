[Cerezo et al. 2021 Variational Quantum Algorithms](https://www.arxiv.org/pdf/2012.09265.pdf) 
\
\
The authors made a literature review on VQA and the applications.\
They provide informations about the antzats and optimizers.\
They provide lots of informations about the VQA family\
\
\
**Research Question**\
\
\
**Hypothesis**\
\
\
**Limitation**\
→ ansatze \
→ noise ⇒ error mitigation technique\
→ number of Qubits and decoherence\
→ barren plateau ⇒ vanishing gradient\
→ trainability, accuracy, and efficiency\
→ NISQ system are prone to error and have a limited decoherent time.\
→ Cost function non-convex and can be complicated for the convergence [83]\
\
\
**Results**\
Application domains:\
→ ground state and excited states ⇒ VQE \
\
(to complete)
\
\
\
\
**Questions**\
Asymptotic scaling of quantum algorithms?\
What is Trotterizing?\
How a VQA can compute non-linearity?\
How to use a VQA to compute factorization?\
Why QPE isn't possible in NISQ?\
\
\
**Ideas**\
QAOA ⇒ VQA\
Use the variational classification in [135] to replicate [137]\
Auto encoder [138-142]\
Generative models [143-148]\
QNN [132,144,150-154]\
Quantum metrology \
QML [256-260]\
\
\
\
**Misc**\
Variational Quantum algorithms need a classical optimizer. Hybrid computation.\
The role of ansatze is very important but our capacity to write good one are limited.\
The cast function or the gradient of the VQA is computed with a quantum computer\
A cost function need to be efficiently computed, the minimum of the cost correspond to the minimum of the system.it need to be complex enough to be computed only on a QC\
\
Take a look at tensor product technique\
\
\
[[Fahri_2014]]\
[[Preskill_2018]]\
