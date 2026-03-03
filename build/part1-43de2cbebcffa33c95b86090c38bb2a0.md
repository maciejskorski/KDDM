## Knowledge Discovery Process

The foundations of knowledge discovery were laid by {cite}`fayyad1996kdd`, who framed
it as a pipeline: select data, clean it, transform it, mine it, interpret the results —
with feedback loops allowing earlier steps to be revisited as understanding grows.

:::{figure} https://www2.cs.uregina.ca/~dbd/cs831/notes/kdd/kdd.gif
:name: fig-kdd-process
:width: 85%

From raw data to actionable knowledge: the KDD pipeline with feedback {cite}`fayyad1996kdd`.
:::

The model is data-centric and influential, but shows its age {cite}`hofmann2003kdp`:

- **No business perspective** — stakeholder goals and domain knowledge are absent; a technically correct model can easily answer the wrong question.
- **Incomplete lifecycle** — deployment and monitoring are missing; patterns may never reach production.
- **No agility** — despite the feedback loops, the overall flow is linear; changing requirements means starting over.

This motivated more iterative approaches — from CRISP-DM (which added business
understanding and deployment) to fully agile models like ASD-DM and AgileKDD,
which treat analytics as uncertainty-driven and team-centric {cite}`alnoukari2012kdp`.
Even these, however, often lack explicit handling of data sources, human roles, and
deployment {cite}`rotondo2020evolution` — the field is still evolving.