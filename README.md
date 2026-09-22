# Pin Dev Notes

The Pinterest API is five products under one name, and only one of them lets you start today without an app review. Here is which one, and what the others ask for.

**Read the full page:** https://pinterest-api.github.io/

This is worth the integration work if you are an advertiser who needs server-side conversion tracking, or a product that genuinely creates Pins and boards on behalf of users, because those paths are documented and supported. It is the wrong tool if what you actually want is to post to Pinterest on a schedule alongside your other channels, since you would be building a publishing tool from primitives. The detail most people miss: a Pinterest Business account gets you the Conversions API immediately with no app ID, but it does not grant access to the wider API. If scheduling is the real job, Supapush covers it across ten networks without any of this.

## What's here

- **Five products wearing one name** — Pinterest's developer platform presents a single API, but the use cases it lists are effectively separate products with separate access paths. Conversions cover
- **The one door that opens without approval** — Here is the detail buried in Pinterest's help documentation and absent from most write-ups. The Conversions API does not require an application or a valid app I
- **What a conversions integration actually involves** — Pinterest offers two routes. A third-party partner integration works if you already use one of its partner platforms, and a direct integration gives the most co
- **Getting onto the wider platform** — Everything outside Conversions starts at the developer account setup flow, which you reach with a Pinterest business login rather than a personal one. Pinterest
- **When the API is not the answer** — A lot of people searching for this API want something simpler than an integration: get a week of Pins scheduled, keep Pinterest in step with the other channels,

**Try Supapush:** [supapush.com](https://supapush.com?utm_source=github&utm_medium=ugc&utm_campaign=pinterest-api&utm_content=readme-top&utm_term=tier-b)

---

*This is an independent page about a third-party product, with no affiliation to or endorsement from Pinterest; all trademarks belong to their respective owners.*

_Last reviewed: 2026-09-22_
