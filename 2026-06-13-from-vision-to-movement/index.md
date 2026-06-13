---
title: 'From Vision to Movement: A Year of Composable Science'
subtitle: A year after Banff, modularity moved from a shared idea to working infrastructure and real adoption.
short_title: From Vision to Movement
abstract: |
  A little over a year ago, a small group gathered in Banff to ask where scientific communication is headed. We left with a name for the future we wanted — composable science. This is a reflection on the year since: what we learned, what we built, and the inspiring people and organizations turning that vision into a movement.
---

When we [convened in Banff](https://articles.continuousfoundation.org/articles/csf-looks-towards-2026), we did not set out to solve everything. We set out to slow down, take stock, and give voice to a future that was already emerging — one where science is shared not only as the story, but as a more complete and reusable package of data, software, methods, and review. We named that future — composable science — and in the year since, a remarkable number of people joined us.

:::{iframe} https://www.youtube.com/embed/Y5uL9X3eGBI
:width: 100%
:placeholder: composable-science-youtube.png
Watch [_Composable Science_ on YouTube](https://www.youtube.com/watch?v=Y5uL9X3eGBI).
:::

## A Movement, Not a Milestone

The clearest thing we've learned this year is that composable science is not a product we ship or a milestone we cross. It's a movement — and movements are made of people willing to _move_ before they have permission.

The arc has been steady. In Banff, we aligned on a vision and then organized around _adoption_ through three working groups that emerged directly from those conversations. What excites us most isn't any single output. It's watching the network effects begin.

## Working Groups

We started with modularity, and three working groups carried it forward. Each tackled a different barrier to modularity, and each surprised us with how much energy was waiting to be channeled.

### Modular peer review, with PREreview

If science is modular — if we're sharing datasets, code, methods, and figures as first-class objects — then _review_ has to be modular too. Our [Modular Peer Review Working Group](https://articles.continuousfoundation.org/articles/modular-peer-review), a collaboration with [PREreview](https://prereview.org), set out to explore what it means to review components, not just complete papers.

What inspired us most was who showed up. Over **sixty participants** joined across continents and time zones — publishers, librarians, researchers, early-career scholars, infrastructure builders, funders, and community organizers, from 🇨🇦 🇺🇸 🇬🇧 🇪🇺 🇲🇽 🇨🇱 🇳🇬 🇮🇳 and beyond. What they shared was not a single solution, or even agreement on the problem. What they shared was a willingness to move: to be messy by design, human-first, and lean into the uncertainty.

Across five sessions the group moved from an exhaustive brainstorm of reviewable components, to a system map, to running **live reviews** of real preregistrations, datasets, and visualizations through a simple arc: Object → Function → Criteria → Signal → Capture.

Trust, evaluation, and feedback no longer have to be confined to a single object at a single moment in time.

### Modular reuse incentives, with Creative Commons

The current incentive structure rewards publishing papers, not creating reusable components. Our [Reuse Incentives Working Group](https://articles.continuousfoundation.org/articles/reuse-incentives), a collaboration with [Creative Commons](https://creativecommons.org), treated licensing not as legal paperwork but as **infrastructure for reuse and attribution**.

Between February and April, 2026, the group met five times and produced a preliminary set of **seven recommendations** for component-level licensing and attribution — built for both humans and machines. A few themes ran through every session and have stuck with us:

- **Licensing is infrastructure, not paperwork.** Clear open licensing is the _enabling layer_ that lets research objects travel across tools, labs, platforms — and AI systems — while carrying the signals needed for responsible reuse.
- **Attribution must work at the component level.** Citation practices built around whole papers fail to capture the reuse of a single figure, dataset, snippet of code, or even a sentence.
- **Metadata must travel with the object.** License and attribution information should survive copies, reuses, and AI ingestion — otherwise we incentivize stripping it.
- **The biggest surface is informal.** Most real-world reuse happens in lab meetings, social media, draft exchanges, and AI-assisted synthesis — outside formal publishing entirely.

And one design principle crystallized at the smallest level of a research object, a sentence we keep coming back to: **Compliant reuse must be easier than copy and paste**.

If giving credit is harder than extracting value, people will extract value. The goal of this work is to flip that — to **make it easier to give credit than to take it**.

### Standards and adoption

The third thread was standards. In San Diego, we built the [infrastructure and coalitions](https://articles.continuousfoundation.org/articles/from-tools-to-adoption) to make it real. Our standards working group asked a hard question: how do tools actually interoperate without a single platform controlling how knowledge circulates?

The major outcome was the [Open Exchange Architecture (OXA)](https://oxa.dev) — not a theoretical framework but code, schemas, and working implementations, designed as an interoperability layer that works with the infrastructure publishers already have.

Unbundling without shared standards produces fragments, not ecosystems. OXA is how the modular pieces gain shared meaning — and how they connect.

As we wrote in [_From Albums to Streams_](https://articles.continuousfoundation.org/articles/how-modularity-changes-systems), music didn't change because audiences suddenly wanted playlists. It changed because digital infrastructure made it possible to break apart bundled products, describe the pieces consistently, and reconnect them in new ways. Science is making the same structural shift — from modularity, to standards, to composability. This year was about laying that middle layer.

## OXA Is Being Adopted

A standard only matters if people adopt it, and this is where the year turned from inspiring to real.

OXA has drawn investment and implementation work from across the ecosystem — including [openRxiv](https://openrxiv.org), [Curvenote](https://curvenote.com), [Stencila](https://stencila.io), and [eLife](https://elifesciences.org). We've taken the case for modular, composable science onto the world stage, presenting on OXA at a **[PLOS](https://plos.org) meeting in Brussels**, in a [keynote](https://articles.continuousfoundation.org/articles/towards-modular-science) at the first **[AtProto Science workshop in Vancouver](https://oxa.dev/articles/oxa-on-at-proto)**, at the **[COAR](https://www.coar-repositories.org) Annual Meeting in Portugal**, at the **[FORCE11](https://force11.org) meeting in Singapore** — meeting repositories, publishers, developers, researchers, and funders where they are.

::::{tip} Watch the AtScience keynote
:::{iframe} https://www.loom.com/embed/8a6aced82b2544308b857875e1bde252
:width: 100%
:placeholder: banner.png
Watch the [keynote online](https://www.loom.com/share/8a6aced82b2544308b857875e1bde252).
:::
::::

The most concrete proof point is an early version of OXA demonstrated in the new **partnership between [openRxiv](https://openrxiv.org) and [Curvenote](https://curvenote.com)**, who recently launched [openRxiv Labs](https://openrxiv.org/labs-reader/) experiment. Over half a million preprint articles have been turned into [modular and addressable content](https://reader.openrxivlabs.org).

This is the transition we described in _From Albums to Streams_: the corpus has always been accessible, but accessibility only removes the lock. Making each article modular and addressable is what creates **mobility** — the ability for figures, datasets, methods, and claims to move across tools with their context and integrity intact, enabling reuse and composability at a scale that simply wasn't possible when research lived inside static containers.

> Access creates visibility. Standards create mobility.

## What We're Carrying Forward

A year on, the bottleneck is no longer ideas, it's not technology, it's not even adoption. It's coordination, governance, and sustained effort — and that's precisely what CSF exists to steward. The working groups continue. The recommendations are evolving into new proposals, educational activities, and adoption paths in tools researchers already use. The partnerships are turning this vision into **scaled demonstration of what composability unlocks**.

In early June 2026, Modular Interoperable Research Attribution ([MIRA](https://www.mira.science/about)), 22 participants prototyped interoperable frameworks for modular research attribution. CSF didn't run it, and that's the point: others are building on the ideas, extending them, and bringing modular and composable practices to new levels.

The most inspiring thing we learned this year is simple: the future of science won't be built by any single organization. It's being built by people who **decide not to wait** — publishers experimenting with modular review, researchers daring to share their work in a new way, technologists treating licensing as infrastructure, repositories enabling reuse at scale, and institutions changing their policies to encourage iteration and early sharing.

We named a movement in Banff. A year later, there is working infrastructure and a growing community moving forward together.

If you're building tools, standards, or community practices that connect to this vision, [get involved](https://continuousfoundation.org/contact).
