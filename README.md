# response-context

**An automated emergency overview page for the Digital Humanitarian Network. Currently a design mockup with fictional data.**

Live demo: <https://digitalhumanitariannetwork.github.io/response-context/>

> **Everything on the demo page is invented.** Every emergency, place, number, source and date is fictional, shown only to demonstrate the design. It is not a real report, carries no live data, and links to no real situation information.

## The idea

When a crisis escalates, information arrives scattered across many organisations: alerts, situation reports, datasets and funding announcements. That is true in the first hours of a sudden disaster, but also when an ongoing or slow-onset crisis changes materially, for example a drought tipping into famine conditions or a conflict displacing a new wave of people. Responders, donors and journalists piece the picture together by hand, and the picture keeps changing.

The concept behind this project is a single page per emergency that:

1. **Detects**: checks an alert feed for new events and major changes on a timer.
2. **Gathers**: pulls the matching reports, datasets and funding records from trusted sources.
3. **Snapshots**: writes a dated edition for each emergency, so "what did we know, and when" is preserved.
4. **Publishes**: rebuilds a static page and keeps the edition history, so anyone can read the latest or step back through earlier editions.

The demo page shows what one such page could look like: an emergency and edition selector, headline figures, a stylised map, a funding tracker block, a filterable list of source items (each labelled by source type), a timeline, and the difference between editions.

Two design choices worth noting:

- **Funding is optional and scoped.** The financial section can be hidden entirely for an emergency where no suitable funding data exists. Where it does appear, it must state its scope: funding for one event is distinct from the broader country or response-plan context, and reported, pledged and paid amounts are different things, often late and sometimes double counted.
- **Sources stay visible.** Every item carries its source type so readers can weigh it, rather than blending everything into unattributed prose.

## Status

This repository currently contains a **visual and interaction mockup only**:

- A single self-contained `index.html`, served by GitHub Pages.
- All content is hard-coded fictional sample data; the selectors, filters and edition switching work, but against invented entries.
- None of the automation steps above exist yet. There are no live feeds, and access to real data sources still has to be arranged.
- The page asks search engines not to index it, so the fictional content is less likely to surface as if it were real reporting.

## How this was built

This project is a collaboration between [Andrej Verity](https://veritythink.com/) and his [Instinct](https://instinct.com/) agent.

Andrej set the direction: the concept, the choice of the Digital Humanitarian Network as the framing, the brand assets (logo, background artwork, favicon and style guide, which he supplied for this demo), and review of each iteration. The Instinct agent did the hands-on work: it studied the supplied brand guidelines, designed and built the page, embedded the brand assets, and published it to GitHub Pages, including the fictional safeguards (the striped demo banner, the DEMO watermark and the "invented" labels on every data block).

It is a small example of a person and their agent building something together: the person brings judgement, context and the final say; the agent does the production work in between.

## Brand and design notes

- The design follows the DHN style guide supplied for this demo: the network grey (#434341) with the red, orange, teal and yellow accent palette, bold uppercase headings and square-cornered cards.
- The guide's brand fonts (BetaSans Bold and Clan OT) are commercial and were not available for this demo, so the page uses a system sans-serif stack as a stand-in.
- The favicon and header artwork are embedded directly in the page as data URIs, keeping the demo to one file.

## The original mockup

This page is a rebrand of an earlier design exercise Andrej and his Instinct agent built for a fictional "situation room". The original remains at <https://veritythink.github.io/av_instinctagent/situation-room/>.
