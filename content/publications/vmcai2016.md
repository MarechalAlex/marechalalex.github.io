---
title: "Polyhedral Approximation of Multivariate Polynomials using Handelman's Theorem"
authors: "Alexandre Maréchal, Alexis Fouilhé, Tim King, David Monniaux, Michaël Périn"
pubtype: "Conference Paper"
publication: "International Conference on Verification, Model Checking, and Abstract Interpretation (VMCAI)"
doi: "10.1007/978-3-662-49122-5_8"
date: 2016-01-01
featured: false
description: "Convex polyhedra are commonly used in the static analysis of programs to represent over-approximations of sets of reachable states of numerical program variables. When the analyzed programs contain nonlinear instructions, they do not directly map to standard polyhedral operations: some kind of linearization is needed. Convex polyhe-dra are also used in satisfiability modulo theory solvers which combine a propositional satisfiability solver with a fast emptiness check for polyhedra. Existing decision procedures become expensive when nonlinear constraints are involved: a fast procedure to ensure emptiness of systems of nonlinear constraints is needed. We present a new linearization algorithm based on Handelman's representation of positive polynomials. Given a polyhedron and a polynomial (in)equality, we compute a polyhedron enclosing their intersection as the solution of a parametric linear programming problem. To get a scalable algorithm, we provide several heuristics that guide the construction of the Handelman's representation. To ensure the correctness of our polyhedral approximation , our Ocaml implementation generates certificates verified by a checker certified in Coq."
tags: ["convex polyhedra", "simplex algorithm", "result certification", "abstract interpretation", "linearization"]
link: "https://hal.archives-ouvertes.fr/hal-01223362"
weight: 400
sitemap:
  priority : 0.8
---
