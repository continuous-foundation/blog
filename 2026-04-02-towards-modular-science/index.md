---
title: Towards Modular Open Science
subtitle: A keynote on the modular science movement and the Open Exchange Architecture.
description: |
  Science is trapped in a paper-shaped box. In this talk at the ATProto community, Rowan Cockett introduces the structural states of scientific components — the floor, the buckets, and the shelf — and makes the case for a second wave of modular science where modularity emerges from packaging rather than being imposed as a precondition. The talk introduces the Open Exchange Architecture (OXA), a new standard for modular and composable scientific content.
date: 2025-04-02
authors:
  - rowan
tags:
  - presentation
  - open-science
  - modular-science
  - oxa
thumbnail: thumbnail.png
downloads:
  - title: Download Slides
    file: ./slides.pdf
abstract: |
  In this talk at the ATProto community, Rowan Cockett introduces the structural states of scientific components — the floor, the buckets, and the shelf — and makes the case for a second wave of modular science where modularity emerges from packaging rather than being imposed as a precondition. The talk introduces the Open Exchange Architecture (OXA), a new standard for modular and composable scientific content.
---

::::{tip} At-Science Keynote Talk
:::{iframe} https://www.loom.com/embed/8a6aced82b2544308b857875e1bde252
:width: 100%
:::
::::

---

I am Rowan Cockett from the [Continuous Science Foundation](https://continuousfoundation.org) and [Curvenote](https://curvenote.com), and I'm excited to talk about the movement towards modular open science and some of the work that we are doing.

## Science is trapped in a paper-shaped box

:::{figure} ./slide-02.png
Science trapped inside static, paper-shaped containers.
:::

Today, science is trapped in a paper-shaped box. We are communicating our discoveries using print-era concepts that constrain the way we communicate, evaluate, and ultimately build scientific progress. All of the data sets, code, protocols, and computational pieces are really constrained inside of that box. But the science that is being produced has changed massively — large data sets, large-scale collaborations, continuous sharing of open notebooks. The way we communicate science has really not kept up to that change.

> "Science has changed. The way we communicate it has not kept up."

Our mission at the Continuous Science Foundation is to help move the open science movement from the sole focus on reading and open access to a future that is focused more on **utility and reuse** — built on these foundations of openness and designed for modern discovery patterns where code, data, protocols, and methods are all available, interconnected, and modular, supporting the remixing and importing of other people's work.

:::{figure} ./slide-04.png
Moving from today's Reading & Access era to tomorrow's Utility & Reuse era.
:::

## The Necker Cube of Modular Science

:::{figure} ./slide-05.png
The Necker Cube, first published by Louis Albert Necker in 1832.
:::

There's an illusion that was published by Louis Albert Necker in 1832, a crystallographer. This is the Necker Cube — twelve lines on a page. If you stare at the bottom left, it pops into one orientation. If you look at the top of the cube, it sort of flips. It's this perceptual reversal: the same underlying data, but different interpretations, different stories and narratives that you can tell while fitting the same data points.

This is really the way that I like to think about modular science. We have these Lego bricks, these modules of science — the components, the figures, methods, equations, data sets, visualization routines, protocols, questions, claims, evidence.

## Structural States of Scientific Components

:::{figure} ./slide-06.png
The three structural states of scientific components: the floor, the buckets, and the shelf.
:::

They can live in these different spaces. They can be scattered on **the floor**, sorted into **the buckets**, or assembled onto **the shelf** and published as a paper. The assembly into a paper tells a story — it introduces a new concept, it changes minds, it changes a field. The components of scientific discourse are bundled together into that narrative.

### The Shelf

:::{figure} ./slide-07.png
**The shelf** — composed artifacts, like Lego trophies, glued together.
:::

That composed artifact — the paper, the story. But our scientific sharing industry, and the standards that are available today, demands that you **glue together** that "trophy" when you share it.

The eight pages, with four figure panels, and a zip file supplement, fused together. If you want to reuse a figure or a dataset, you must chisel out that figure, take a screenshot, copy that dataset. And as soon as you take it out of the paper, **that figure gets amnesia** — it forgets its attribution, its trust, its licensing. It loses all of its context, all of that rich metadata that our scientific commons is designed to support.

### The Buckets — The First Wave

> The 2010's prescription \
> Break research into parts, share each one first.

These challenges prompted the first wave of modular science. Many people recognized that it's not enough to share the advertisement of the experiment — you should share that data, share the method, share the code underlying it. The prescription in the 2010s was pretty simple: break your research and put it into buckets, put it in the appropriate repository.

:::{figure} ./slide-10.png
**The buckets** — digital repositories organized by type.
:::

Protocols.io for your protocols, [Figshare](https://figshare.com) for your figures, [Software Heritage](https://www.softwareheritage.org) for the code, a specialized data repository for your field's genomic or microscopy data, and [Zenodo](https://zenodo.org) to take care of the rest.

> The **first wave** built excellent buckets for modular components.

These digital repositories for archiving, tagging, and organizing your protocols, figures, and code — they are excellent. They exist for science. But they are also largely designed for **after the work is done**. You tidy up your workspace, you put your blocks away, you point to them from your glued-together trophy on the shelf.

> Structured, Organized, Tidy.

They're structured, organized, and they strive to be these tidy, curated spaces. You fill out your intake form, specify your authors, your licenses, descriptions. It's a very high bar to share work. And if some of the visualization code, or a scratch script that you know is the secret for how your analysis hangs together, but it isn't really at that state for sharing — all those things get lost. They don't fit on the shelf with that glued-together trophy, and they don't really amount to enough to justify the investment to formally request bucket status.

In aggregate, all of that lost scientific workflow — this is where all of that **tacit knowledge** of science lives, in the workflows and the scripts.

### The Floor

Research isn't always as structured as the scientific method — it's more fluid, more serendipitous. You need to access all of the pieces to build a new thing. You dump the buckets out on the floor so that you can remix them. This is where you're building, you're experimenting, you're supporting that serendipity — maybe your equivalent of Fleming leaving a Petri dish out and discovering penicillin in 1928.

> Fluid, Serendipity, Remix.

:::{figure} ./slide-14.png
**The floor** — Lego scattered everywhere, ready for building.
:::

The goal is to have access to all of these pieces, to be able to readily build, to pull from someone else's data bucket in Tokyo and pull a protocol from Germany and remix them with your ideas to build something new, to learn something new, to discover something new.

### Flipping between states

These are the three states of scientific components and modularity — **on the floor** (chaos, serendipity, remix), **in the buckets** (organized by type, structured, organized, tidy), or **on the shelf** (composed as a scientific artifact).

**All of these are right.** They're just different signs of that Necker Cube illusion, of what pops out to you at the right time — whether it's time for you to teach, to learn, to discover, to browse, or to build.

## The Next Wave

So what is the next wave of modular science? The core philosophy is **not** breaking it apart to share it first, not separating it into different spaces to deposit it. It's not about disconnected pieces that are lost or manually added. Where the buckets are right now, it's a very high bar for the researcher to share, and it ends in disconnection — a constellation of research artifacts where you have to tell a fable and imagine how it's all connected together. That's what a constellation is: an imagining of how things are connected.

:::{table #tab-next-wave} Fragments to Continuous Systems — comparing the first and second wave of modular science.

<table style="width: 100%; border-collapse: collapse; font-family: sans-serif; border: 1px solid #e0e0e0;">
  <thead>
    <tr style="text-align: left;">
      <th style="background-color: #d3d3d3; padding: 12px; border-bottom: 2px solid #e0e0e0; width: 25%;">Dimension</th>
      <th style="background-color: #d3d3d3; padding: 12px; border-bottom: 2px solid #e0e0e0; width: 37.5%;">First Wave</th>
      <th style="background-color: #6236ff; color: white; padding: 12px; border-bottom: 2px solid #e0e0e0; width: 37.5%;">Second Wave</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 12px; border-bottom: 1px solid #e0e0e0; font-weight: bold;">Core Philosophy</td>
      <td style="padding: 12px; border-bottom: 1px solid #e0e0e0; border-left: 1px solid #e0e0e0;">Break apart to share</td>
      <td style="padding: 12px; border-bottom: 1px solid #e0e0e0; border-left: 1px solid #e0e0e0;">Package and compose</td>
    </tr>
    <tr>
      <td style="padding: 12px; border-bottom: 1px solid #e0e0e0; font-weight: bold;">Researcher Action</td>
      <td style="padding: 12px; border-bottom: 1px solid #e0e0e0; border-left: 1px solid #e0e0e0;">File separate deposits</td>
      <td style="padding: 12px; border-bottom: 1px solid #e0e0e0; border-left: 1px solid #e0e0e0;">Work natively, modularity emerges</td>
    </tr>
    <tr>
      <td style="padding: 12px; border-bottom: 1px solid #e0e0e0; font-weight: bold;">Output State</td>
      <td style="padding: 12px; border-bottom: 1px solid #e0e0e0; border-left: 1px solid #e0e0e0;">Disconnected pieces</td>
      <td style="padding: 12px; border-bottom: 1px solid #e0e0e0; border-left: 1px solid #e0e0e0;">Connected, navigable graphs</td>
    </tr>
    <tr>
      <td style="padding: 12px; border-bottom: 1px solid #e0e0e0; font-weight: bold;">Provenance</td>
      <td style="padding: 12px; border-bottom: 1px solid #e0e0e0; border-left: 1px solid #e0e0e0;">Lost or manually added</td>
      <td style="padding: 12px; border-bottom: 1px solid #e0e0e0; border-left: 1px solid #e0e0e0;">Inherited and travels with object</td>
    </tr>
    <tr>
      <td style="padding: 12px; font-weight: bold;">System Result</td>
      <td style="padding: 12px; border-left: 1px solid #e0e0e0;">Floor covered in Lego bricks</td>
      <td style="padding: 12px; border-left: 1px solid #e0e0e0;">Multiplicative, compounding progress</td>
    </tr>
  </tbody>
</table>
:::

The second wave of modular science is about improving that path — attaching experience, working with the researcher as they're on the floor, where that modularity actually emerges. You don't write a manuscript from top to bottom in 10,000 unbroken words start to finish. You iterate on the figures, one panel at a time, one script at a time, asking for feedback and building up that modular work.

It's connected in graphs of discourse and computational narratives, supported by modern tooling like [Obsidian](https://obsidian.md) or [MyST Markdown](https://mystmd.org), or [Discourse Graphs](https://discoursegraphs.com). You can define the content with data that travels with it. The result is a multiplicative, compounding effect.

:::{figure} ./slide-18.png
Compositions on the shelf — not glued-together trophies, but modular artifacts you can take apart. There is a meta-study just calling out here on teapot use in the scientific discipline.
:::

The compositions are still the point of science, but maybe we should aspirationally have them be less like trophies polished and glued together on a shelf over a year, but shared a little bit earlier, a little bit more continuously. And if they're not glued together, you can grab the components out of the composition and do something new.

:::{figure} ./slide-19.png
A syntax shift from forced disaggregation to emergent modularity.
:::

There's a structural shift here. In the first wave, importing a figure meant severing its context. In the second wave, you **import a figure from a paper** — the figure retains its provenance, it carries its context. Modularity emerges from the packaging and is not a precondition imposed on the author upfront.

## Syntax of the Second Wave.

If the components of science are built to fit together — without glue — then we can actually support a whole lot more in this ecosystem. And so that's one of the initiatives that the Continuous Science Foundation is working on through the Open Exchange Architecture.

:::{figure} ./slide-21.png
Standards: if we don't build it to fit, it won't. No glue allowed.
:::

## The Open Exchange Architecture

The [Open Exchange Architecture](https://oxa.dev), OXA is a new standard for modular and composable scientific content.

:::{figure} ./slide-22.png
The Open Exchange Architecture — new standards for modular and composable scientific content.
:::

The ambition is shared across many actors in this field — from the authoring side with [Posit](https://posit.co)'s Quarto and [MyST Markdown](https://mystmd.org) from the [Jupyter](https://jupyter.org) ecosystem, to [Curvenote](https://curvenote.com) and [Stencila](https://stencila.io) working on authoring tools, to publishers like [eLife](https://elifesciences.org), [PLOS](https://plos.org), and [openRxiv](https://openrxiv.org), as well as license advocates like [Creative Commons](https://creativecommons.org). Our goal is to build a more modern, computational, complete, modular, composable artifact that can work together to meet this shared ambition.

:::{figure} ./slide-23.png
Organizations converging on OXA — from authoring tools to publishers and standards bodies.
:::

### Principles for OXA

:::{figure} ./slide-24.png
Principles for OXA: Modular, Interactive, Composable.
:::

The principles for OXA are that it is a modular, interactive, composable framework — an open JSON-based schema that's extensible. It's composable so that you can bring in other people's work and import those pieces of science into your graph. Everything's typed, interoperable, modular, and composable. This is very much a community-driven effort, building on practices in the Python ecosystem — from RFCs, steering councils, and governance work that brings this standard to life in a much more iterative way.

And of course, there's also an [AT Proto](https://atproto.com) representation of this — not as the default representation (which is a structured nested tree), but a facet-based implementation that can support distributed annotations.

### Open & Community Driven

:::{figure} ./slide-25.png
The open, community-driven RFC process: Issue, Draft RFC, Active, Implementation.
:::

:::{figure} ./slide-26.png
The AT Proto and OXA schema representations side by side.
:::

## Demos: What this looks like in practice

### Elemental Microscopy

This is a journal that we work with called [Elemental Microscopy](https://elementalmicroscopy.org), part of the Microscopy Society of America. They're trying to reimagine what a modern journal looks like using composable, interactive, computational concepts for communicating very large-scale microscopy data.

:::{figure} ./microscopy-zoom.mp4
Zooming into a 1.5 TB microscopy dataset, the same way you would with Google Maps.
:::

**This is a terabyte and a half of data.** Traditionally, you'd have a panel, zoom into one piece, and show a screenshot. But on the web, you should just be able to zoom in — the same way you would with Google Maps — directly embedded in the narrative. And of course, this speaks to modularity and composability: that terabyte and a half is living in its own bucket, but the paper composes it in and brings that content directly into place.

### Reprocessing half a million openRxiv preprints

Another case study is a partnership between Curvenote and openRxiv where we're working to reprocess all of the half million preprints (424,949 bioRxiv preprints, 79,809 medRxiv preprints, 8.1 TB of data total) that have been published over the last decade — converting them into OXA.

:::{figure} ./curvenote-citations.mp4
Hover citations with inline figures, attribution and licensing information.
:::

This supports things like hovering over a figure and bringing that modular component to the foreground, zooming in for a better reading experience than a PDF-first narrative, and thinking about abbreviations, attributions, and annotations. You can hover over a reference to somebody else's citation and see their figures immediately — they come with their attribution, their licensing, and are shown in context. A much more integrated and fluid way of working, with new social experiences woven into the places of science.

## Rethinking how we share

Our concepts of how we publish research should maybe be less about that glued-together trophy that takes a year and a half to put on a shelf in a glass case for preservation, but more like **continuous artifacts** that you can string together and put up on a shelf, but that you can _also_ take down — you can pull those pieces apart and do new studies.

Lowering the barrier to entry to actually index and put these in a bucket, and supporting all of that rich, additional glue — the workflows, protocols, and scripts that don't fit in any of these buckets — should be able to be up on the shelf, just behind the scenes. And tools that support working on the floor, either through better ways of organizing knowledge or stitching it together or weaving in computational narratives.

:::{figure} ./slide-35.png
Towards Modular Open Science — from components on the floor, through buckets, to composed artifacts.
:::

What we think about modular science is flipping between all of these states — on the floor, in the buckets, or in these composed artifacts. And what is so exciting is that this is our next wave of modular science, and it is something that the people on the AT Proto side can influence completely.

> It is **our next wave**.

I am Rowan Cockett. I work at [Curvenote](https://curvenote.com) as CEO and I'm one of the co-founders of the [Continuous Science Foundation](https://continuousfoundation.org). You can find me at [\@row1.ca](https://bsky.app/profile/row1.ca). Thank you so much.
