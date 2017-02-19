Quantifying over epistemic updates
==================================

[Download (PDF)](https://github.com/jameshales/phd-thesis/releases/tag/final)

This thesis was presented to the School of Computer Science and Software
Engineering for the degree of Doctor of Philosophy from The University of
Western Australia in May 2016.

Abstract
--------

Dynamic epistemic logics reason about the knowledge belonging to a collection
of agents and how that knowledge changes in response to epistemic updates,
events that provide agents with additional information.  Previous work in
dynamic epistemic logic, such as public announcement logic and action model
logic, introduced models for epistemic updates and logics for reasoning about
the effects of specific epistemic updates using these models.  However many
natural questions about epistemic updates are not questions about specific
epistemic updates.  For example, given a desired change in knowledge we might
ask "Is there an epistemic update that results in the desired change in
knowledge?", and if there is we might also ask "What is a specific epistemic
update that results in the desired change in knowledge?".  More recent works in
dynamic epistemic logic, such as arbitrary public announcement logic and group
announcement logic, have considered logics for quantifying over epistemic
updates. In principle these logics allow us to answer such questions using
model-checking or satisfiability procedures, although these particular logics
are undecidable, and quantify over relatively restricted forms of epistemic
updates.

In the present work we consider logics for quantifying over very general forms
of epistemic updates: arbitrary action model logic, which quantifies over
action models; and refinement modal logic, which quantifies over refinements,
which have a partial correspondence with the results of action models, but are
more general.  We present sound and complete axiomatisations, expressivity
results, and decidability results for these logics in various multi-agent modal
settings.

Building
--------

Requirements:

- TeX Live 2015 or later
- LaTeXmk
- GNU Make

Simply run `make`.
