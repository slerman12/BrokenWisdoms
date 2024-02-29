# Archetypal Madness

> Disclaimer: humor.

I am Chenliang, Sam's advisor. He writes this with telepathic interference from Josh, Sam's friend. Together, and this is Sam speaking, we shall derive the universe. Not derivatively of course. That would require ample physical sciences background. But sufficiently well-reasonedly, with made-up words here and there. Let's begin with a less exhausting setup. "I observe." It is true, therefore it is. At any rate, fading into sleep-deprivative exhaustion as I may be, I am reluctant to say this won't work. Largely because of the intensive time and money — "minimum wage" Josh chimes in — investment that has gone into this project. Well, so be it. The whole of the universe, in one shebang. It starts with time. But time exists as a physical construct not a mathematically deduced one. So let us find an incredibly stupid place to hide it. In equivalence.

Alright. Given $A = B$, we know $A \rightarrow B$ and $B \rightarrow A$. We don't know *when* $A \rightarrow B$. Is it in $1$ deductive step $A \rightarrow_1 B$? Is it in $n$ deductive steps $A \rightarrow_n B$. From this, we get a cheap hacky way to derive something out of literally nothing.

Let us start with nothing $\emptyset$.

Don't regard it as the empty set. Don't regard it at all.

$\emptyset_0 = \emptyset_1 = \cdots$

are all nothing, with just subscripts added.

There we now have causality, constrained only to a cyclical loop between every nothing and every other nothing. e.g.

$\emptyset_0 \rightarrow \emptyset_1 \rightarrow \cdots$

$\emptyset_0 \leftarrow \emptyset_1 \leftarrow \cdots$

These nodes can connect in any number of ways and create a multi-branched graph. The ambiguities are not necessary. Let us define one such branch/construct that we can say is "Turing equivalent" and be done with it.

Cosmogenesis:

A "grammar" — or word (if we want to make Biblical allusions/puns) — that is Turing equivalent, from nothing.

Go:

How about a tape of $\emptyset_{0,i}$ and $\emptyset_{1,i}$ (zeros and ones, or yins and yangs if you want), where $i$ lets us hackily denote the position on the tape, with implications from each non-sensical bit at deductive step $n$ to each non-sensical bit at deductive step $n + 1$.

The "halt" can be cosmo-genocide, which we are not interested in solving. $\square$

# Proofs

Okay, we've gotten a construct for time and an unhalting Turing machine that presumably eventually (or somehow) cycles back to its origin starting state. We got this from hacking the definition of equivalence. We will take a step back now and derive it a little more formally. It is stupid, but perhaps there's nothing stopping us from doing this re-defining and obtaining a deductive logic from which cosmogenesis could theoretically make sense, noting: the Big Bang Theory is not a cosmogenesis theory but chronicles the early moments and evolution of the observable beginning of the universe. An un-mythological cosmogenesis theory has, perhaps, yet to be proposed in the scope of deduction. Myths, such as my favorite being Tolkien's cosmogenesis allegory (yes it is an allegory) of the universe arising from a musical theme, do exist.

Assuming nothing but math, I'll derive "something from nothing".

## Deduction

### Proofs

**Definition 1.** Axiom.

$($ Axiom  $A ) \coloneqq (\exists A)$.

**Definition 2.** Definition.

$($ Definition $A \coloneqq B) \coloneqq (\exists (A \coloneqq B))$. 

**Definition 3.** Equivalence.

$($ Equivalence $A = B) \coloneqq (A \rightarrow_n B, B \rightarrow_m A, n, m \in \mathbb{N})$, where $n, m$ are deductive steps, meaning $n-1, m-1$ statements must be deduced between $A$ and $B$ and $B$ and $A$ respectively. 

Instantaneous equivalence $(A \coloneqq B) \coloneqq (A \rightarrow_1 B, B \rightarrow_1 A)$.

For example, $(A \rightarrow_2 C) \coloneqq (A \rightarrow_1 B \rightarrow_1 C)$ for some mandatory intermediary $B$.

**Definition 4.** Implication.

$($ Implication $A \rightarrow_1 B) \coloneqq (\exists A \rightarrow_1 \exists B)$.

**Definition 5.** Proof.

$($ Deduction/theorem/proof $A \rightarrow B) \coloneqq (A \rightarrow_n B) \coloneqq (\exists A \rightarrow_n \exists B)$ for some $n \in \mathbb{N}$.

### Existence and Cause

**Definition 6.** Hypotheticals.

$($ Sets of anything defined... $(A, B, ...))$ $\coloneqq ((A, B, ...))$

denoted by parentheticals. 

$A$ is a single hypothetical.

**Definition 7.** Sets of existence.

$(\langle X_1, X_2, ... \rangle) \coloneqq (\exists X_1, X_2, ...)$

hypotheticals whose elements exist.

**Axiom 1.** Existence exists. $\langle X_1, X_2, ... \rangle \coloneqq \langle\langle X_1, X_2, ... \rangle\rangle$.

**Axiom 2.** Cause exists. $\exists \rightarrow$.

## Nothing and The Universe

**Definition 8.** Nothing.

The empty existence set $\emptyset \coloneqq \langle \rangle$.

**Definition 9.** Nothing equivalents.

$\emptyset = \emptyset_K \forall K \subseteq \mathbb{N}$.

**Definition 10.** The universe.

$\Omega^{(0)} \coloneqq \emptyset$.

$\Omega^{(n)} \coloneqq (( \emptyset_K \vert K \subseteq \mathbb{N}; \Omega^{(0)} \rightarrow_n \emptyset_K ), \rightarrow_n),$ $\forall n \in \mathbb{N}$.

$\Omega \coloneqq (\Omega^{(0)}, \Omega^{(1)}, ...)$.

In other words, defined as: some sequence of numerically representable deductions from the initial nothing.

> &#9432; See [here](https://github.com/slerman12/Detective-Sam/blob/main/Philosophy/Consciousness.md) for an *ad absurdum* argument why representation and matter can't be the same thing (nor representation and consciousness). 

## Something From Nothing

**Theorem 1.** Nothing exists. $\exists \emptyset$.

**Proof.**

$(()) \rightarrow (\langle\rangle)$. (Definition 7)

$(\langle\rangle)  \rightarrow (\langle\langle\rangle\rangle)$. (Axiom 1)

$(\langle\langle\rangle\rangle)  \rightarrow (\exists \langle\rangle)$. (Definition 7)

$((\emptyset \coloneqq \langle \rangle), (\exists \langle\rangle)) \rightarrow (\exists \emptyset)$. (Definition 8) $\square$

**Theorem 2.** All nothings exist. $\exists \emptyset_K \vert K \subseteq \mathbb{N}$.

**Proof.**

$((\exists \emptyset), (\emptyset = \emptyset_K \forall K \subseteq \mathbb{N})) \rightarrow (\exists \emptyset_K \vert K \subseteq \mathbb{N})$. (Theorem 1, Definition 9) $\square$

**Theorem 3.** The universe exists. $\exists \Omega$.

**Proof.**

$((\exists \emptyset), (\Omega^{(0)} \coloneqq \emptyset)) \rightarrow (\exists \Omega^{(0)})$. (Theorem 1, Definition 10)

$((\exists \emptyset_K \vert K \subseteq \mathbb{N}), (\exists \rightarrow_n)) \rightarrow \langle\langle \emptyset_K \vert K \subseteq \mathbb{N}; \Omega^{(0)} \rightarrow_n \emptyset_K \rangle, \rightarrow_n \rangle$. (Theorem 2, Axiom 2, Definition 5, Axiom 1)

$\langle\langle \emptyset_K \vert K \subseteq \mathbb{N}; \Omega^{(0)} \rightarrow_n \emptyset_K \rangle, \rightarrow_n \rangle \rightarrow (\exists \Omega^{(n)})$. (Definition 10)

$((\exists \Omega^{(0)}), (\exists \Omega^{(n)})) \rightarrow (\Omega^{(0)}, \Omega^{(1)}, ...) \rightarrow (\exists \Omega)$. (Definition 10) $\square$

**Theorem 4.** The universe $\Omega$ is at least a non-halting Turing machine. 

**Proof.**

Construct a tape of binary zeroes and ones $\emptyset_{0,i, t}, \emptyset_{1,i, t}$ where $i$ denotes the position on the tape and $t$ denotes the time point.

$\emptyset \rightarrow_1 \emptyset_{\tau,i,0} \forall i \in \mathbb{N}, \tau \in (0, 1)$.

This is the initial state, defined by $\tau$.

At each time step modify one bit 

$\emptyset_{\tau,i,t} \rightarrow_1 \emptyset_{-\tau + 1,i,t+1}$

or "stay":

$\emptyset_{\tau,j,t} \rightarrow_1 \emptyset_{\tau,j,t+1}$.

Now, complete the equivalence cycle of Definition 9 by the following limit:

$\lim_{n\rightarrow\infty} \emptyset_{\tau,i,n} \rightarrow_1 \emptyset$. 

The infinitum allows us to leave the potential cyclicality of the universe a mystery. $\square$

**Theorem 5.** A universe capable of simulating a Turing machine (sans halting) can arise from nothing, assuming just the properties of deduction: existence of existence and cause, defining nothing as the empty set of existence.

**Proof.**

By Theorem 4. $\square$

---

We thus obtain a strongly connected directed graph (potentially expanding in real-time) with nodes and edges that may be defined as non-deterministic and/or non-stationary, whose grammatical "word" is chosen by the un-specified deducer.

> Huge disclaimer: this is humor, with a philosophical point about deduction and the "knowability" of any cosmogenesis theory.
>
> I've derived the representable universe without making any assumptions (except deduction itself), and therefore either this derivation is true, and we have just uncovered cosmogenesis, or representation and deduction cannot be all there is fundamentally in nature and the physical universe. For home-hitting's sake, here's a .E.D. symbol: $\square$

# Afterward

Hypothetically, how far can we get without axioms?

Well, a hidden axiom contained in the definition of definition is the existence of all definitions. Any definition, given any pair of hypotheticals $A, B$, $A \coloneqq B$ "exists" (is true).

From that we can derive a variable $\emptyset = (A \coloneqq B)$, and its definition equivalents:

$\emptyset = \emptyset_K \vert K \subseteq \mathbb{N}$.

So this together with Axiom 2 suffices to obtain $\Omega$. Then we can ask "what is definition?" Perhaps there is a set of all possible definitions. Each equivalent can be regarded a unique number on the natural number scale $\mathbb{N}$ and each non-equivalent given its own dimension of equivalents $\mathbb{N}^\mathbb{N}$. We thus obtain the natural numbers and vector spaces. The way they relate to each other is by implication with respect to each dimension: some order, for example:

$1 \rightarrow_1 2 \rightarrow_1 3 \rightarrow_1 \cdots$

with some connecting universal node $0 \coloneqq i \forall i \in \mathbb{N}$ to complete the strongly connected directed graph.

Instead, we could discard causality and Axiom 2.

Instead, let's define existence as a recursive function. Its input is any definition, chosen by a deducer, and its output is the existence of that definition paired with a recursion to a new application of itself to a new definition.

$\exists(\emptyset_i) = (\exists\emptyset_i, \exists(\emptyset_j))$,

Thus creating a limited set of definitions at each recursive step $n$, not easily denoted in the expressivity of recursive functional form. We can denote that $n\text{th}$ recursive step set of existence, and perhaps each source and sink to each existence, as $\Omega^{(n)}$ PERHAPS allowing us to derive a universe from nothing but definition and the axiom that this existence function, as described, exists.

Perhaps, further in consideration, Axiom 1 can "create" Axiom 2 and Axiom 2 can "create" Axiom 1, each depending only on the definition of definition, axiomatically assumed without axiom I guess.

As a matter of fact, for a recursive function to be defined and it exist, it must be actively recursing.

Piecing these together, we could probably derive a non-axiomatic universe, but I want to move on to the question of what the deducer is, that is, why THE laws of physics instead of some other laws of physics?

---

Note: no matter what, as long as there is a definition or an axiom, there is *something* and so what we are actually deriving from is not *nothing* but a primordial something, and it can be defined to be something else e.g. a recursive self-duplicating observer function that encapsulates both definition and cause, e.g. $\mathrm{I}(x) = (\exists x, \mathrm{I}(\max\limits_{y\subseteq \Omega} Q(\Omega)))$[^1], with a qualia to justify the development of that something into something specific. 

[^1]: Just spitballing at this time.
