# Open Quantum Systems
---
## 1.1 Quantum-Like Models: Motivation
---
In quantum-like modeling, a biosystem is a black box which information processing can’t be described by the classical probability [318] (CP) and, hence, the classical information theory. Biosystem’s size is not critical. The key point is that information processing in such a system follows the laws of quantum probability [271] (QP) and information.

**How and why do biosystems use the quantum-like representation of information?**

This question is rather perplexing and the answers are presented in the following chapters (see, especially Chap. 6).

It is important to denote that it can be found plenty of probabilistic data which doesn’t match CP, for example, in biology on all scales, from molecular biology to ecology, cognitive psychology, and decision-making. In decision-making, such data is typically coupled to probability fallacies and irrational behavior of agents (see Chap. 19 for paradoxes). The existence of this data is the primary reason for appealing to QP instead of CP [87, 386, 387]. The situation is similar to quantum physics derived not from natural physical principles, as say special relativity, but created “by hands” to describe the statistics of outputs of experiments in atomic physics, cf. Zeilinger [438].

**One may say that the appeal to QP and, consequently, to quantum information theory to model, e.g., humans’ behavior and decision-making is too exotic. The following natural question arises:**

- **Why do we apply QP to humans, or, generally, biosystems?**

Now we discuss the motivation for quantum-like modeling of decision-making in more detail. We recall that as early as the 1970s, Tversky, one of the most cited psychologists of all time, and Kahneman, who took the Nobel prize in economics in 2002, for prospect theory, which he co-developed with Tversky, have been demonstrating cases where classical probability prescription and human behavior persistently diverge [221–225]. 

**Kahneman points out that, today, we are at the theoretical cross-roads, with huge divisions across conflicting, entrenched theoretical positions:**

**Should we continue relying on CP as the basis for descriptive and normative pre- dictions in decision-making (and perhaps ascribe inconsistencies to methodological idiosyncrasies)?**

**Should we abandon probability theory completely and instead pursue explana- tions based on heuristics, as Tversky and Kahneman proposed?**

However, the use of probabilistic and statistical methods is really the cornerstone of the modern scientific methodology, both in natural and social sciences. Thus, although the heuristic approach to decision-making can’t be discarded completely, it seems more natural not to reject the probabilistic approach to decision-making, but to search for novel probabilistic models. And QP [26] is a good candidate for an alternative to CP. We continue the discussion on basics of quantum-like modeling in Chap. 4 by concentrating on its quantum information aspects and coupling with theory of open quantum systems.

Generally, the quantum-like modeling project is very successful. It is shown that such models can be applied to modeling the behavior of biosystems on all spatial scales. Genes, proteins, cells, animals, humans, and social systems can be treated as information processors and decision makers within the same mathematical model [25]. From the information perspective, we can speak about the creation of a new theory—quantum bioinformatics—which is a part of quantum information theory, but not of quantum biophysics. One of the advantages of this theory is its generality, its framework covers all possible biological systems.

Another advantage of the quantum-like representation is its linearity. The quan- tum state space is a complex Hilbert space and dynamical equations are linear differ- ential equations. The classical biophysical dynamics beyond quantum information representation are typically nonlinear and very complicated. The use of linear space representation simplifies the processing structure. The quantum information representation means that generally large clusters of classical biophysical states are encoded by a few quantum states: the quantum structure arises as the result of coarse graining (Chap. 6). It leads to essential information compressing. It also implies an increase of stability in state processing (Chap. 4). This is a rather unusual viewpoint on the use of the quantum information representation as lowering the complexity and instability of information encoding and processing.

Since the essential part of this book is devoted to psychology and decision-making, it is important to highlight the contribution of the quantum-like approach to math- ematical modeling of psychological effects, e.g., the order effect, conjunction and disjunction effects, and response replicability effect (see, e.g., [87, 89, 90, 190, 191, 254, 369, 370, 386–388, 452, 453]).

--- 
## 1.2 Briefly About Classical and Quantum Probabilities
In this section, we do not concern the complex problem of the interpretation of probability. We briefly discuss this problem in Chap. 20.
CP was mathematically formalized by Kolmogorov [318] (1933). This is the calculus of probability measures, nonnegative weight P(A) is assigned to any event A. Events are represented by a family of sets forming a special set-theoretical structure (Chap. 16). 

The main property of classical probability P is its additivity: if two events A1, A2 are disjoint, i.e., in the set-representation, $ A_1 ∩ A_2 = ∅ $, 

then the probability of disjunction of these events equals the sum of probabilities

$ P(A1 ∪ A2) = P(A1) + P(A2). $

In the mathematical theory, the condition of additivity is extended to countableadditivity, i.e., for a sequence of pairwise disjoint events $A_1,..., A_n,..., P(A_1 ∪ A_2 ∪···∪ A_n ∪...) = P(A_1)+ P(A_2)+···+ P(A_n)+... $.

However, as was emphasized by Kolmogorov [318], countable-additivity can’t be checked experimentally, so this is the pure mathematical condition which is needed for establishing the theory of Lebesque integration.

QP [26] is the calculus of complex probability amplitudes (wave functions) or in the abstract formalism complex vectors—quantum states. Thus, instead of the oper- ations with probability measures, one operates with vectors belonging to a complex Hilbert space.

In the L2-space, each complex amplitude $ ψ = ψ(x), x ∈ R3 $ is normalized by one, i.e., generates the probability by the Born rule:

Probability to find a quantum system at the point x is given by

$$
P(x|ψ) = |ψ(x)|2. 
$$

Then, for any (Borel) subset A of R3,A
(1.1)

$$
|ψ(x)|^2 dx = 1, R3
P(x ∈ A|ψ) = P(x|ψ)dx.
$$

If we consider just one observable, then the possibility to represent its probability distribution with the complex amplitude does not imply foundational consequences. The essence of QP is that the same amplitude (quantum state) can be used to generate the probability distributions for all possible quantum observables; some of them are incompatible, i.e., they can’t be represented as random variables on the same probability space. A probability measure P which can be used for all these observables does not exist, but a common complex amplitude ψ (quantum state) does exist.
What is its meaning? This is the most complicated foundational problem of QM, the problem of the interpretation of a quantum state. This problem is discussed by many authors, see also my books [231, 250, 251], and it is characterized by the diversity of viewpoints. 

For example, I suggested the Växjö interpretation [251, 256] (Chaps. 17 and 20). By this interpretation, a quantum state represents the complete experimental context, in other words, the combination of the preparation and measurement procedures. In cognitive applications, we can interpret ψ as a mental state or a belief state—we will use both terms equivalently. Of course, one can interpret a mental state. In Chap. 20, we discuss the problem of interpretations in connection with decision theory.

---

---

