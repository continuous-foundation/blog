---
title: Reimagining Research as an Integrated Experience
subtitle: Preserve the Package, Not Just the Pieces
---

Research today is messy, dynamic, and computational. It involves data pipelines, notebooks, interactive visualizations, simulation environments, evolving codebases, patchwork scripts, and collaborative writing and presentations. But when it comes time to share that work with others, we're forced to squash it into static documents and scatter the supporting materials across a half-dozen platforms: a preprint server, a GitHub repo, a Zenodo archive, a supplementary ZIP file.

This mismatch—between how research is done and how it is communicated isn’t just inconvenient, it is a structural flaw that breaks reproducibility, hampers reuse, and wastes time and effort.

## Ideas don’t live in documents alone

A research idea is more than the papers, PDFs, and DOIs we assign to it. It lives in the interplay between narrative, code, data, and environment. Yet our infrastructure for scholarly communication treats these components as separate, optional, or out-of-scope.

Right now, even accessing a supplementary figure or video means clicking through broken links or downloading files and scrolling through unrelated pages. Accessing the actual data and code used in a study? That might involve matching DOIs to repository names, finding the right branch in a GitHub repo, and guessing at the correct package versions — _if you're lucky_.

This fractured ecosystem is a _terrible_ user experience; the _opposite_ of frictionless. It actively discourages people from engaging more deeply with published work, looking at that supplementary video or dataset or figure. And it severely limits the ability to _reuse_ research, whether for education, reproducibility, building new tools, or working towards new ideas.

## Preservation is _also_ about integration

Preserving research is not just about storing code or archiving data — it is about preserving the relationships between them. It is about capturing a version of the research that is coherent, complete, and navigable in the future. This is especially true for executable research content that only works in the intersection points between narrative, code and data. Preservation in this context requires not just dumping pieces in separate places, but maintaining a linked and understandable _whole_.

We need to make it possible to:

- View interactive, computational, and reproducible figures in context, as you read ([for example](xref:scipy2024#eg-interactivity)).
- Explore data and code alongside the narrative ([for example](xref:idr#fig-4495402)).
- Utilize computational environments without guesswork.
- Seamlessly navigate between research components without leaving the context behind.

These aren’t luxuries—they’re requirements for meaningful [reuse](xref:cs#term-reusable).

## Tools must meet researchers where they are

If this vision is going to take hold, the tools must be:

- Accessible to everyday researchers—not just developers or computational scientists.
- Integrated into existing research workflows—from writing and analysis to publishing.
- Sustainable for long-term preservation, with pathways to graceful degradation when full interactivity isn't feasible.

And above all, they must be easy to use. If the process of preserving and sharing executable content is too brittle or too complex, researchers won’t do it. If the process of preserving and sharing deviates from also providing value in day-to-day work, researchers won’t do it _and_ the shared outputs will necessarily not be the actual research.

## Why now?

We are at a crossroads. There’s growing interest — from researchers, funders, publishers, and communities — in making science more open, reproducible, interactive, and reusable. But without solving the problem of integration, we risk recreating the same silos we already have — just with more file formats, repositories, and fragmented experiences.

What is needed now is not just another repository, but a commitment to making research communication feel whole. That means rethinking preservation, not just as backup or compliance or satisfying principles[^data-citation], but as a pathway to reuse and understanding.

If we care about scientific knowledge being built upon, not just published, then it’s time to treat integration as a first-class goal.

[^data-citation]: For example, the fantastic data-citation principles [@doi:10.25490/a97f-egyk], which any integrated expression of this should absolutely follow.

## Acknowledgements

This articulation on the importance of "[integration](xref:cs#term-integrated)" as a core requirement of preserving executable research content came through two recent conversations: one with Arfon Smith in a lead up to the [Banff meeting on research communication](https://articles.continuousfoundation.org/articles/banff-meeting-future-of-research-communication) and a working session in the [PERC Working Group by FORCE11](https://force11.org/group/preserving-executable-research-content-challenges-frameworks-and-best-practices/) with Sam Teplitzky, Virginia Scarlett, Kirstie Whitaker, Roly Perera, Manuela Strickland, and Catherine Jones — where we are grappling with the scope of preservation in the context of executable research artifacts.
