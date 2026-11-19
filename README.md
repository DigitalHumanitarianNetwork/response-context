# response-context

**A country-first humanitarian overview for the Digital Humanitarian Network. Currently a design and interaction demo with real country names and fictional reporting.**

Live demo: <https://overview.digitalhumanitarians.com/>

> **DEMO: real countries, fictional content.** All situation details, figures, analysis, report titles, publishers, funding and edition dates are invented examples. Nothing on the demo is a real situation report or live feed.

## The idea

Countries are the entry point. Each country has a weekly overview, with humanitarian situations inside it and dated editions preserved in a history. GHO supplies the starting country list and a source to watch for future country additions; plans do not define the site navigation. A qualifying new disaster outside the starting coverage would add that country, with its situation inside it.

The current demo shows an **illustrative selection of six real countries** listed in the [GHO 2026 overview](https://humanitarianaction.info/overview/2026): Afghanistan, Haiti, Myanmar, Sudan, Ukraine and Yemen. This is not a complete or automatically maintained GHO membership list. Only country names and their inclusion in this illustrative selection are sourced; no real reporting or numerical data have been imported.

## Current demo

- A country directory leads to country-specific views with shareable hash URLs.
- Each country has three sample weekly editions. Older examples remain selectable.
- Fictional situations appear inside the country, with working situation and source-type filters.
- A quiet-week example shows no new evidence rather than manufacturing a change.
- Funding is optional and scoped. Two demo countries show a fictional country-level funding envelope; the others omit the entire block. Country-level funding must not be confused with funding for a particular situation, and commitments, contributions and pledges must stay distinct.
- All source items are invented placeholders and do not link to real reports.

## Status

This repository currently contains a **visual and interaction mockup only**:

- A single self-contained `index.html`, served by GitHub Pages.
- Real country names, with hard-coded fictional content and sample edition dates.
- No monitoring, automatic publishing schedule or live data connections. Real sources and data will be added piece by piece after the structure is agreed.
- A prominent DEMO banner, watermark and local fictional-content labels. The page also asks search engines not to index it.

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
