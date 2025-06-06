---
title: Science Doesn’t Belong in Just One Place
subtitle: The future of research communication is modular, remixable, and everywhere.
---

In an ideal world, scientific communication would flow directly from the research itself. Early ideas—whether data points, musings, exploratory figures, notebooks—would be shared openly, evolving over time into more formal results by remixing and composing the existing bits. This [continuous](xref:cs#term-continuous-science) approach aligns with how science actually works: iterating, refining, expanding on previous steps, building on and incorporating other peoples work and methods.

But today, this continuous approach faces a major roadblock: **as soon as research reaches a certain threshold of significance, the momentum breaks. Suddenly, your work has to be reshaped to fit a platform that discards the context and continuity of the work so far.**

## The Frustration of Fragmentation

Imagine you're an open-science researcher documenting your work online. You've been sharing many updates—small posts on your lab website, preliminary data on a project blog, a repository release, maybe even rallying a community of people to build on the work before it is "published". These early-stage artifacts are tailored to your close collaborators or specific communities, often informal and dynamic.

Then you reach a milestone. You've refined your analysis, solidified your methods, and developed a result worthy of broader attention. Suddenly, you're faced with a dilemma:

- Do you **rewrite and repackage** your work for a preprint server or journal, stripping away the rich context you've built?
- Do you **duplicate content**, creating multiple versions scattered across different platforms (blog, preprint, journal)?
- Do you **abandon your own site** entirely and point everyone to the preprint server or journal, leaving your evolving narrative disjointed and hollow?

This isn't just an inconvenience. It reflects a deeper structural problem: the systems we use to publish and discover research are designed around **fixed venues**, not **continuous content**. Journals, preprints, and repositories are slow and siloed—disconnected from how research actually unfolds.

When researchers are forced to switch platforms at key milestones, we lose something valuable:

- **Contextual threads** that show how the work evolved.
- **Cohesive narratives** that connect the small bits of research to give them context.
- **Discoverability and engagement** that could be driven by continuous interaction in _multiple_ places, rather than fragmented releases constrained to a single place.

Moreover, the need to publish content across venues creates **confusion for readers**, **extra work for researchers**, and **limits opportunities for innovation**.

:::{danger .dropdown} Fragmentation adds friction for everyone involved

For **readers**, fragmented publishing means jumping across journals, preprints, blogs, and repositories—each with different formatting, metadata, and levels of access. Too often, what's presented is a decontextualized story: **just the narrative, not the full science**. The data and methods may live elsewhere, unlinked or hard to trace. The cohesive whole becomes scattered, requiring readers to reassemble it themselves.

For **researchers**, it adds friction at every step:

- Reformatting papers to meet arbitrary style guides, USD$230 million spent on reformatting articles by scientists _before_ publication [@doi:10.1186/s12916-023-02882-y]
- Navigating redundant peer review loops across journals
- Being forced to strip context to fit a platform's limitations
- Maintaining multiple, unsynced versions of the same work across systems

And for **innovation**, this model centralizes control in ways that stifle progress. Most journals and platforms are **incentivized not to change**: they rely on prestige, owning the content, or other unaligned business models. Even when the will is there, they often lack the **funding, capacity, or technical infrastructure** to support the kinds of rich, connected, interactive research experiences modern science demands. Innovations like live code, linked data, and reproducible figures are pushed to the margins—**not because they aren't valuable, but because they don't fit.**

:::

It doesn't have to be this way. Science is already networked, iterative, and collaborative. **Our publishing infrastructure should reflect that—not constrain it.**

## A Better Way: Shared Formats, Flexible Views

What if, instead of moving and duplicating research across rigid platforms, we treated the _content_ itself as the durable thing—structured around **shared formats and identifiers**—and let it flow naturally across many places?

Your early work might live on a lab blog. A dataset could be deposited in a trusted repository. A figure might be included in a project update or internal notebook. And a polished analysis might be published more broadly _as well as_ shared on your project website. These artifacts don't need to be forced into a single container. **What they need is a shared structure that ties them together.**

The **legacy of print-era publishing** tells us otherwise. It assumes that each piece of research can—and should—have **only one “real” home**: a final PDF, hosted by a journal, stamped with authority and prestige: the Version of Record. This was necessary when physical distribution meant choosing a single place to publish.

This constraint does not apply in a networked world. **On the internet, a research artifact can live in many places—embedded, referenced, reused, remixed—_while still maintaining a consistent identity_.** The challenge isn't to centralize everything, but to **coordinate it**. To build an ecosystem where the same work can be viewed, interpreted, and reused across contexts without fragmentation or loss of fidelity.

This shift—from “one home per paper” to “many interoperable views over the same content”—requires a new mindset. Science doesn't need to be repackaged and relocated at every stage. It needs to be composable. Instead of containers, we need views—different ways of presenting the same core content. That means building with **shared identifiers**, **portable formats**, and **common standards** that work across platforms and communities. This limiting mindset—_“one home per paper”_—reinforces scarcity and underpins the status-quo publishing & business models that are poorly aligned with the process of science: abundance, remix, reuse, build upon.

A composable research ecosystem relies on three principles:

- **Persistent identifiers** that track contributions across platforms.
- **Portable formats** that represent [all parts](xref:cs#term-complete) of research—text, code, data.
- **Community standards** that ensure [interoperability](xref:cs#term-interoperable) and enable [reuse](xref:cs#term-reusable) and [versioning](xref:cs#term-versioned).

And critically, this isn't theoretical or even that far away. DOIs are a clear example: persistent identifiers that track content wherever it goes, making it discoverable and citable across systems but not enforcing that those systems are centralized. Journals, too, are starting to act less like final destinations and more like **curation and review layers**—views over an increasingly distributed body of content. With open, community standards like [MyST](https://mystmd.org)—which allow researchers to write in structured Markdown that includes citations, code, and figures—we also have the scaffolding to represent scientific content in a **structured, reusable way**. This infrastructure enables us to move beyond the outdated logic of static files and single-point publishing, and instead build a research ecosystem where content is **modular, portable, and remixable from day one.**

## Acknowledgements

Thank you to Kristen Ratan, Michele Avissar-Whiting, and Tracy Teal for providing conversations and feedback on these evolving ideas.
