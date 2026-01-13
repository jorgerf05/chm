# Consciousness Hypergraph Model (CHM)

> A process-based, non-representational model of consciousness — implemented as code.

This repository contains a **runnable, exploratory implementation** of the **Consciousness Hypergraph Model (CHM)**.

CHM is **not** a neural network, **not** a symbolic system, and **not** a cognitive architecture.  
It is a **dynamical model** where consciousness is treated as something that *happens*, not something that is stored or represented.

If you’re a developer:  
👉 think **process**, **global updates**, **collective dynamics**, **no hidden-state magic**.

---

## What is this repository?

This repository has two goals:

1. Explain the CHM in an **intuitive, developer-friendly way**
2. Provide **working code** that lets you observe the dynamics directly

You do **not** need to agree with the theory to run or explore the code.

If you’ve ever wondered:

> *“What if time, attention, and integration were first-class computational objects?”*

this repo is for you.

---

## Core idea (developer version)

CHM is built on four simple principles.

### 1. No objects — only relations

There are no privileged “things” in the system.

Everything is modeled as a **relation**, and relations may involve **many elements at once** (not just pairs).

> Think **hyperedges**, not edges.

---

### 2. Consciousness = what is active *right now*

At every update step, some relations are **active**.

That active set is called **the Now**.

- Not a snapshot  
- Not memory  
- Not representation  

Just *what is currently integrated*.

---

### 3. Time is not a variable — it is an update

Time does not flow continuously.

Instead:

- The entire system **rewrites itself**
- Each rewrite is one discrete step
- Time emerges from the ordering of these rewrites

If you’ve worked with:

- game loops  
- simulation steps  
- synchronous GPU kernels  

you already understand the model.

---

### 4. Attention is regulation, not focus

Attention is not “what the system looks at”.

Attention determines:

- what persists  
- what fades  
- what stabilizes  
- what collapses  

In code, this shows up as:

- kernels  
- weights  
- suppression  
- persistence rules  

---

## What’s included

### 📄 Paper

The formal definition of the Consciousness Hypergraph Model:

- process-based ontology  
- hypergraph dynamics  
- attention as regulation  
- explicit non-claims and boundaries  

The paper contains the math.  
The code does **not** require you to read it first.

---

### 📓 Examples

This repository includes an **explicit, runnable example of a hyperedge in four dimensions** under:

```

examples/

```

The example demonstrates:

- k-ary (non-pairwise) interaction  
- discrete global updates  
- emergent structure from random initial conditions  
- dynamics without training, labels, or objectives  

Nothing is optimized.  
Nothing is learned.  
The system is simply allowed to evolve.

---

## Why hyperedges instead of pairwise interactions?

Most models assume interactions like:

```

A → B

```

CHM works with interactions like:

```

(A, B, C, D) → collective update

````

This matters because:

- integration is not reducible to pairs  
- many-body effects are first-class  
- global coherence cannot be cleanly decomposed  

If pairwise graphs feel limiting, this is the alternative.

---

## What CHM is *not*

CHM explicitly does **not**:

- explain qualia or subjective experience  
- model beliefs, symbols, or semantics  
- claim biological realism  
- define meaning or purpose  
- optimize performance metrics  

These are **out of scope by design**.

CHM is a **structural and dynamical model**. Nothing more, nothing less.

---

## Running the code

### Requirements

- Python  
- NumPy / PyTorch  
- Matplotlib  
- (Optional) CUDA for acceleration  

### Clone the repository

```bash
git clone https://github.com/jorgerf05/chm.git
cd chm
````

Then open the notebooks or scripts and run them top-to-bottom.

* No training
* No configuration
* Just let the system evolve

---

## What to look for

Do **not** look for accuracy or task performance.

Look for:

* stabilization
* collapse
* symmetry
* metastable regimes
* recurring structures
* sensitivity to parameters

This is exploration, not benchmarking.

---

## How to think about CHM as a developer

If you come from:

* **Machine Learning** → think *pre-loss, pre-task dynamics*
* **Physics** → think *many-body systems with global rewrites*
* **Graphics / simulation** → think *emergent structure*
* **Systems** → think *synchronous kernel updates*

CHM lives **below** most abstractions we usually assume.

---

## Status

This is **research code**.

* Exploratory by nature
* Minimal by design
* Honest about its limits

If something breaks, that is information.

---

## License & usage

Use it.
Fork it.
Break it.
Run wild parameter sweeps.

If you build something interesting on top of it, that is the point.

---

## Final note

CHM is not asking you to believe anything.

It asks one question:

> **What happens if integration itself is the primitive operation?**

This repository is one concrete, executable answer expressed as code.

```
