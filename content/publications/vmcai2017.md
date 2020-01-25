---
title: "Efficient Elimination of Redundancies in Polyhedra by Raytracing"
authors: "Alexandre Maréchal, Michaël Périn"
pubtype: "Conference Paper"
publication: "International Conference on Verification, Model Checking, and Abstract Interpretation (VMCAI)"
doi: "10.1007/978-3-319-52234-0_20"
date: 2017-01-12
featured: false
description: "A polyhedron can be represented as constraints, generators or both in the double description framework. Whatever the representation, most polyhedral operators spend a significant amount of time to maintain minimal representations. To minimize a polyhedron in constraints-only representation, the redundancy of each constraint must be checked with respect to others by solving a linear programming (lp) problem. We present an algorithm that replaces most lp problem resolutions by distance computations. It consists in launching rays starting from a point within the polyhedron and orthogonal to its bounding hyperplanes. A face first encountered by one of these rays is an irredundant constraint of the polyhedron. Since this procedure is incomplete, lp problem resolutions are required for the remaining undetermined constraints. Experiments show that our algorithm drastically reduces the number of calls to the simplex, resulting in a considerable speed improvement. To follow the geometric interpretation, the algorithm is explained in terms of constraints but it can also be used to minimize generators."
tags: ["convex polyhedra","simplex algorithm","raytracing", "algorithm"]
link: "https://hal.archives-ouvertes.fr/hal-01385653"
weight: 400
sitemap:
  priority : 0.8
---
