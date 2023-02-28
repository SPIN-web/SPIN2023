---
layout: home
---

# Invited speakers

We are honored to have an excellent line-up of invited speakers at SPIN 2023.

### [Simon Gay](http://www.dcs.gla.ac.uk/~simon/) (University of Glasgow)

#### Model-Checking Quantum Computing Systems

Large investments by governments and industry, and an increasing research activity, mean that quantum computing is moving closer to practical reality - indeed, there are already some commercial quantum computing services. We can hope to apply formal methods to this new domain. There are significant challenges, especially the fact that the whole point of quantum computing is that it should be difficult to simulate with classical computers. In this talk I will describe some work on model-checking quantum computing systems and give an invitation to future challenges.

### [Joost-Pieter Katoen](https://people.utwente.nl/j.p.katoen) (RWTH Aachen & University of Twente)

#### The Probabilistic Model Checker Storm

Probabilistic model checking amounts to verify quantitative properties on probabilistic models such discrete- and continuous-time variants of both Markov chains and Markov decision processes. The field originated 40 years ago and mature software tools exist for more than two decades.

This talk will focus on the rationales, features, and performance of Storm (see stormchecker.org), the probabilistic model checker that dominated the last (and only) two competitions among similar tools. We will describe its modular set-up in which solvers and symbolic engines can easily be exchanged, and show how its python API enabled rapid prototyping of various other tools by encapsulating Storm’s algorithms.

We conclude the talk by discussing several recent extensions of Storm and future development plans.

### [Raúl Pardo](https://raulpardo.net) (IT University of Copenhagen)

#### Formal Verification of Privacy Policies for Social Networks

Online Social Networks (OSNs) are ubiquitous, with more than 70% of internet users being part of them. The pervasive nature of OSNs brings many threats and challenges; privacy being one of them. One mechanism to protect user privacy is to allow users to define privacy policies. These policies define who can know the information of the user. To this end, "the logic of knowledge" (epistemic logic) is a good candidate.

In this talk, I will present a formal framework, based on epistemic logic, to define and reason about privacy policies in OSNs. The framework is generic and can be used to instantiate real OSNs such as Facebook or Twitter. Furthermore, we can express novel types of privacy policies that are not present in existing OSNs. For instance, we can capture implicit disclosure of information, or evolving policies (i.e., policies that change over time). The framework relies on Social Networks Models (SNMs): social graphs enriched with knowledge bases containing the information that each user knows. I will discuss methods to formally verify and enforce privacy policies over execution traces---i.e., sequences of SNMs that capture the effect of the events that users execute. Finally, I will demonstrate a proof-of-concept implementation of this framework on the open-source OSN Diaspora.

### [Caterina Urban](https://caterinaurban.github.io/) (INRIA)

#### Interpretability-Aware Verification of Machine Learning Software

Machine learning (ML) software is increasingly being employed in high stakes or sensitive applications. This poses important safety, privacy, and non-discrimination challenges. As a consequence, research in ML verification rapidly gained popularity and demand for interpretable ML models is more and more pronounced. Interpretability and verification are typically seen as orthogonal concerns. Research in ML interpretability is mainly carried out in the ML community, while research in ML verification is mostly carried out in the formal methods community, without much communication and exchanges between these research areas. In this talk, we advocate for closing this gap by presenting our recent and ongoing work on interpretability-aware verification of ML software.
