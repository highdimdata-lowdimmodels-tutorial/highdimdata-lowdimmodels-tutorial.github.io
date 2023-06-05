---
layout: home
title: Home
nav_exclude: true
permalink: index.html
nav_order: 0
---

# Learning Nonlinear and Deep Low-Dimensional Representations from High-Dimensional Data: From Theory to Practice
### ICASSP 2023, Rhodes, Greece

{% assign instructors = site.speakers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Course Rationale

We are currently in the midst of a data
revolution. Massive and ever-growing datasets, arising in science, health, or
even everyday life, are poised to impact many areas of society. Many of these
datasets are not only large -- they are high-dimensional, in the sense that each
data point may consist of millions or even billions of numbers. To take an
example from imaging, a single image can contain millions of pixels or more; a
video may easily contain a billion "voxels". There are fundamental reasons
("curses of dimensionality") why learning in high-dimensional spaces is
challenging. A basic challenge spanning signal processing, statistics, and
optimization is to leverage lower-dimensional structures in high-dimensional
datasets. Low-dimensional signal modeling has driven developments both in
theory and in applications to a vast array of areas, from medical and
scientific imaging, to low-power sensors, to the modeling and interpretation of
bioinformatics data sets, just to name a few. However, massive modern datasets
pose an additional challenge: as datasets grow, data collection techniques
become increasingly uncontrolled, and it is common to encounter gross errors or
malicious corruptions, and nonlinearity. Classical techniques break down
completely in this setting, and new theories and algorithms are needed. 

To meet those challenges, there have been explosive developments in the study
of low-dimensional structures in high-dimensional spaces over the past two
decades. To a large extent, the geometric and statistical properties of
representative low-dimensional models (such as sparse and low-rank and their
variants and extensions) are now well understood. Conditions under which such
models can be effectively and efficiently recovered from (minimal amount of
sampled) data have been clearly characterized. Many highly efficient and
scalable algorithms have been developed for recovering such low-dimensional
models from high-dimensional data. The working conditions and data and
computational complexities of these algorithms have also been thoroughly and
precisely characterized. These new theoretical results and algorithms have
already revolutionized the practice of data science and signal processing, and
have had significant impacts on sensing, imaging, and information processing.
On the other hand, recently strong connections between deep neural networks and
low-dimensional models emerge at multiple levels, in terms of learning
representations, network architectures, and optimization strategies. Such
connections do not only help explain many intriguing phenomena in deep
learning, but also provide new guiding principles for better network design,
optimization, robustness, and generalization of deep networks in both
supervised and unsupervised scenarios.

As witnesses to such historical advancements, we believe that it is the right
time to deliver this new body of knowledge to the next generation of students and
researchers in the signal processing community. Through exciting research
developments over the past twenty years, the signal processing community has
witnessed the power of sparse and low-dimensional models. In the meantime,
however, the community is still in the transition of embracing the power of
modern machine learning, especially deep learning, with unprecedented new
challenges in terms of modeling and interpretability. In comparison to past
tutorials on compressed sensing, convex optimization and related topics, this
tutorial (and the associated book, exercises and course materials) is unique
in that it bridges fundamental mathematical models from signal processing to
contemporary topics in nonconvex optimization and deep learning. The goal is to
show how (i) these low-dimensional models and principles provide a valuable
lens for formulating problems and understanding the behavior of methods, and
(ii) how ideas from nonconvexity and deep learning help make these core models
*practical* for real-world problems with nonlinear data and observation
models, measurement nonidealities, etc. 

## Course Resources

The major reference is the following book:

John Wright and Yi Ma. "[High-Dimensional Data Analysis with Low-Dimensional
Models: Principles, Computation, and
Applications](https://book-wright-ma.github.io/){:target="_blank"} {::comment}__{:/comment}".  *Cambridge University
Press*, 2022.

A full pre-production edition of the book is available at this link.

## Course Overview

The course starts by introducing fundamental linear low-dimensional models
(e.g., basic sparse and low-rank models) and convex relaxation approaches with
motivating engineering applications, followed by a suite of scalable and
efficient optimization methods. Based on these developments, we introduce
nonlinear low-dimensional models for several fundamental learning and inverse
problems (e.g., dictionary learning and sparse blind deconvolution), and
nonconvex approaches from a symmetry and geometric perspective, followed by
their guaranteed correctness and efficient nonconvex optimization. Building
upon these results, we proceed to discuss strong conceptual, algorithmic, and
theoretical connections between low-dimensional structures and deep models,
providing new perspectives to understand state-of-the-art deep models, as well
as leading to new principles for designing deep networks for learning
low-dimensional structures, with both clear interpretability and practical
benefits.

## List of Lectures

{% for module in site.modules %}
{{ module }}
{% endfor %}

## Beyond the Course

A new conference is being organized -- the [Conference on Parsimony and
Learning](https://cpal.cc) -- with the aim of bringing together researchers
working on topics that we have touched on in the course and creating a venue
for the presentation and dissemination of outstanding research in these areas. 
Attendees are encouraged to consider submitting work and attending in the
future.

[![CPAL Logo]({{ site.baseurl }}/assets/images/logo_text.png)](https://cpal.cc)

