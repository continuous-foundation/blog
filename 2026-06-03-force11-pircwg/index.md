---
title: Preserving Interactive Research Content
subtitle: Graceful degradation as a framework for balancing innovation and longevity in research communication.
description: |
  Modern research is increasingly computational and interactive, yet scholarly communication remains stuck in the print era. The FORCE11 PIRC Working Group proposes graceful degradation — a tiered strategy where interactive research objects fall back through levels of decreasing interactivity rather than breaking catastrophically. The Open Exchange Architecture (OXA) shows how this comes to life as a community-adoptable standard.
date: 2026-06-03
abstract: |
  Research is often more than text — it includes the software and computational environments needed to reproduce work. The [FORCE11 PIRC Working Group](https://force11.org/group/preserving-executable-research-content-challenges-frameworks-and-best-practices/) introduces Graceful Degradation, a tiered preservation strategy where a fully interactive "ideal" version of a research object is published alongside fallback formats of decreasing interactivity, so the scientific record endures even as underlying technologies inevitably change.
---

::::{tip} FORCE11 PIRC Working Group
:::{iframe #talk-video} https://www.loom.com/embed/86d9f36ecb424c3785211e420fb3b861
:placeholder: video-presentation.png
:width: 100%
FORCE11 PIRC Working Group Lighting Talk at FORCE11, 2026. Watch the [overview online](https://www.loom.com/share/86d9f36ecb424c3785211e420fb3b861).
:::
::::

Modern research is increasingly computational and interactive. From data-heavy simulations to AI-driven analyses, scientists rely on code, data, and interactive tools to interrogate and produce results. Yet scholarly communication remains largely stuck in the print era — the static PDF research paper. Even online, most papers are essentially digital facsimiles of print, disconnected from the underlying code, data, and execution environments.

These shortcomings "needlessly limit, inhibit and undermine effective knowledge transfer" [@Bourne2012] — impeding discoverability, reuse, verification, and long-term access to the full scientific record. As the 2011 FORCE11 Manifesto noted, "online versions of 'scholarly outputs' have tended to replicate print forms, rather than exploit the additional functionalities afforded by the digital terrain."

> Science has changed. The way we communicate it has not kept up.

Today, we increasingly see rich interactive formats, where a published scientific narrative provides frictionless access to data and interactive research outputs. Readers might zoom into a large-scale microscopy image, adjust a simulation's parameters and rerun results within the narrative, experiment with embedded Jupyter notebooks, or explore time-series visualizations to see patterns beyond the author's chosen times or locations. Interactive research outputs are a demonstration of the work's reproducibility and its connection to source materials — and **frictionless reproducibility** [@Donoho2024] extends this further, transforming research into a continuously verifiable process.

## Two barriers to adoption

In our discussions with stakeholders and early adopters, we typically hear about two main barriers to adoption:

1. The need for **better tools** to author executable and interactive content.
2. The challenge of **preserving** these formats for the long term.

In recent years, many platforms — such as Jupyter Notebooks, R Markdown, Quarto, Jupyter Book, [MyST Markdown](https://mystmd.org), and Manubot — have significantly improved the authoring experience. High-profile initiatives over the past six years ([eLife](https://elifesciences.org/labs/dc5acbde/welcome-to-a-new-era-of-reproducible-publishing), [AGU Notebooks Now](https://notebooks.agu.org), the [Microscopy Society of America](https://elementalmicroscopy.org), [DistillPub](https://distill.pub)) have also attempted aspects of interactivity. Yet uptake within traditional scholarly publishing remains limited.

We believe the second barrier is the one holding back the first. Many researchers,institutions, journals, and repositories hesitate to commit to formats such as executable notebooks or interactive visualizations because they worry the content may not be runnable in a few years. This uncertainty discourages experimentation, even when the tools hold great promise for transparency and reproducibility. If publishers and tool developers had robust preservation strategies — ensuring that interactive research objects could be reliably archived, cited, and re-executed as well as allow the content to gracefully degrade when ultimately does not — these organizations would feel more confident that their work would endure.

> Better frameworks for preservation will incentivize adoption.

## What is Graceful Degradation?

Graceful degradation refers to software decay management practices that ensure the core value of a digital product continues to be delivered even as its underlying technology becomes out of date. It is both a technique and a philosophy that emphasizes a long-term mindset and designing products that age well. Systems designed with Graceful Degradation techniques are modular, include redundancy and failsafes, minimize or isolate external dependencies, and ensure value delivery over the long term — even at the cost of upfront additional requirements.

In the context of interactive scholarly content, the most important aspect of Graceful Degradation is the need for a **variety of output formats**. Research outputs start with interactive, computationally rich features — live visualizations, linked data, executable code — but retain value even if those layers degrade over time. Instead of binary outcomes (working vs. broken), Graceful Degradation enables a spectrum: from fully interactive environments to recorded demos, static images, and structured metadata.

A few reasons graceful degradation matters:

- **Interactive environments are fragile.** They break. Dependencies shift. Servers go down. But if we plan for that, we can leave behind something useful — a static version, a recording, a snapshot.
- **We preserve more context.** Even degraded, a bundle of narrative, data, and code is more valuable than a PDF alone.
- **Innovation needs room to fail.** New approaches face the refrain, "It won't work in five years." That may be true — but the fallback still contains the data, the code, and the execution intent. You can often make it work again if needed.
- **Preservation is not one-size-fits-all.** Most research has a short relevance window. But some projects matter for decades. Graceful Degradation lets us store enough to make that determination later, rather than prematurely flattening everything to a static snapshot.

> The goal is not perfection or permanence. It's resilience.

Decay is not the same as graceful degradation — decay just happens, whereas Graceful Degradation is a _response_ to decay. Importantly, explicit curation may not always be required: existing or future infrastructure might degrade gracefully by design. A document that invokes a web service to retrieve content, but maintains a local cache to fall back to when the live service is offline, degrades gracefully without anyone curating it.

## A framework for Graceful Degradation

To make this concrete, the PIRC Working Group proposed a framework that pairs **increasing interactivity** (which we want to encourage) with **graceful degradation** (the safety net that makes that encouragement risk-free). Interactivity moves up; graceful degradation falls back down.

:::{figure #fig-dial} ./pirc-dial.png
The graceful degradation dial — from Information (no interactivity), through Exploration (customizable style and view), to Modification (customizable content and analysis). Fallbacks on the left, increasing interactivity on the right.
:::

The framework defines three levels of interactivity, each of which can degrade into the level below it:

- **Level 3 — Open-ended.** The work as the published object, fully interactive. Created by the researcher, it presents as an open-ended, unfettered exploration of data, code, visualization, and environment — explorable explanations, online interactive papers, and multiverse analyses. This opens up new models of collaboration, sharing, and reuse.
- **Level 2 — Predefined.** A partially decayed version with limited, set interactions. Interaction is maintained within pre-established parameters — figures, up-to-date metadata on references and citations — but presentation-only controls do not affect the underlying data.
- **Level 1 — Static.** A fully decayed version. The object is no longer computationally interactive, but still includes data and code citations or links following appropriate standards. Content is fixed, but marked and tagged for accessibility.

:::{figure #fig-framework} ./pirc-framework.png
The PIRC framework. Three levels of interactivity (rows) across five components (columns): Text, Visualizations, Data, Code, and Environment. Progressive interactivity rises on the left; graceful degradation falls on the right.
:::

At each level, five **columns** represent the components of a research output. Although there is some fluidity among them, it helps to think of them separately because they degrade in different ways:

- **Text** — navigation, highlighting, hyperlinks, in-text evaluations and equation updates, and bounded LLM responses.
- **Visualizations** — zoom and pan, brushing and linked selections, faceting and overlays, custom encodings, annotation, and time-series scrubbing.
- **Data** — filtering, sorting, aggregation, joining, and deriving new columns. As we move from L3 to L2 we lose direct query access in the execution environment but can still download and query locally; at L1 only a derivative representation remains.
- **Code** — editing and re-execution, widgets and sliders for direct manipulation, debugging and runtime inspection, and checkpoint/share for reproducibility.
- **Environment** — configuration and dependency management: swapping libraries, managing versions, upgrading dependencies.

Crucially, modern interactive tools should **seamlessly generate these fallback versions** during their build, export, or publication processes — so the burden does not fall on authors. Many of the technologies needed already exist: package managers, containers, and virtual machines capture dependencies; compilation tools build binaries from source; hosting tools such as MyBinder, Google Colab, GitHub Pages, [Curvenote](https://curvenote.com) make work easy to share; and workflow managers (Snakemake, WholeTale, ReproZip) make replication easier. No technology is immune to obsolescence, which is exactly why a tiered strategy matters.

## How this comes to life: the Open Exchange Architecture

A framework is only useful if the community can adopt it. The graceful degradation model needs a concrete way to **package** a research object so that its interactive layers, its fallbacks, and the provenance connecting them all travel together. This is exactly what the [Open Exchange Architecture](https://oxa.dev) (OXA) is designed to do.

OXA is a new community standard for modular and composable scientific content — an open, JSON-based, extensible schema where everything is typed, interoperable, modular, and composable. Rather than [gluing a paper together into a single static trophy](https://articles.continuousfoundation.org/articles/towards-modular-science), OXA represents a research object as connected, navigable components: a figure that knows where it came from, a dataset that knows which figure it supports, a notebook that carries its execution intent.

That structure is what makes graceful degradation tractable in practice:

- Because components are **modular and typed**, a build or export process can emit Level 2 and Level 1 fallbacks for each component automatically — a static image alongside the live visualization, a data citation alongside the queryable dataset. These can be handled by the content tools (e.g. MyST, Quarto, Stencila, Curvenote etc.) and support best-practices from the start with minimal effort from researchers.
- Because provenance is **inherited and travels with the object**, even a fully degraded Level 1 artifact retains its data and code citations, its attribution, and its links back to source — preserving context that a PDF alone would lose.
- Because the schema is **open and community-driven** — built on practices from the Python ecosystem, with RFCs, steering councils, and governance — the preservation strategy is not owned by any single tool or vendor. There is also an [AT Proto](https://atproto.com) representation to support distributed annotation.

The ambition is shared across the ecosystem — from authoring tools like [MyST Markdown](https://mystmd.org) and [Quarto](https://quarto.org), to platforms like [Curvenote](https://curvenote.com) and [Stencila](https://stencila.io), to publishers like [eLife](https://elifesciences.org) and [openRxiv](https://openrxiv.org), and standards bodies like [Creative Commons](https://creativecommons.org). OXA gives this shared ambition a common substrate, so that interactive research content can be authored richly _and_ preserved reliably.

## Adopting better practices, gradually

Preserving interactive research content — not just code or data in isolation — means capturing the integrated environments and narratives that underpin computational science. This is essential for reproducibility, transparency, and educational value.

PIRC takes a higher-level mindset: adopt better practices **gradually** through progressive enhancement, adding computation, data, and interactivity in, and then defining how we gracefully "fall back" to today's baseline. We must support a spectrum of preservation strategies — from fully interactive environments, to readable static export formats, to archived artifacts with embedded provenance.

The goal is not to flatten everything to a snapshot, nor to bet everything on infrastructure that may not survive the decade. It is to build tools and workflows that support modern scientific practices without sacrificing long-term preservation — and, in doing so, give researchers the confidence to adopt them.

## Acknowledgements

This work and framework came out of the FORCE11 Preserving Interactive Research Content (PIRC) Working Group: led by Sam Teplitzky and Rowan Cockett with contributions from Catherine Jones, Roly Perera, Virginia Scarlett, Manuela Pallotto Strickland, and Kirstie Whitaker. For a full writeup of the FORCE11 PIRC Working Group, see <https://force11.github.io/pircwg/>.
