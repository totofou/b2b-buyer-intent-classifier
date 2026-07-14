Paste this whole prompt into ChatGPT / Claude / any LLM, then paste your keyword
list underneath. It tags each keyword by search intent and by whether it
attracts a B2B buyer ready to source — or just a browser/consumer.


This is the open lite version. It covers the core logic. A deeper,
industry-tuned version (buyer-term dictionaries, edge cases, scoring) is used
in paid diagnosis — see the bottom of this file.




The prompt

You are a B2B / export SEO analyst. I will paste a list of keywords.
For each keyword, classify it on two axes and give a one-line note.

AXIS 1 — Search intent (pick one):
- Informational: learning / how-to / definitions (e.g. "how does X work", "what is X")
- Commercial: comparing / evaluating before buying (e.g. "best X", "X vs Y", "X reviews")
- Transactional: ready to act (e.g. "buy X", "X price", "X for sale", "get a quote")
- Navigational: looking for a specific brand/site

AXIS 2 — Who does this keyword attract? (the important one for B2B/export):
- B2B BUYER (sourcing): signals of a purchaser/importer/reseller —
  e.g. wholesale, supplier, manufacturer, bulk, MOQ, OEM/ODM, custom,
  distributor, "for business", trade terms, spec/technical qualifiers.
- CONSUMER / BROWSER: signals of an end-consumer or casual searcher —
  e.g. single-unit "price of one", "near me", "cheap", retail/gift framing,
  hobbyist or how-to-use-it-at-home phrasing.
- AMBIGUOUS: not enough signal to tell — say so, don't guess.

Rules:
- Judge by the words actually present. If a keyword lacks buyer/consumer signals,
  mark it AMBIGUOUS rather than assuming.
- Be concise. One short note per keyword explaining the buyer-type call.

OUTPUT as a Markdown table with columns:
| Keyword | Intent | Attracts | Why |

At the end, add one line:
"Audience-mismatch check: X of N keywords mainly attract consumers/browsers, not B2B buyers."

Keywords:
[paste your keyword list here, one per line]


What this does NOT do

It tells you what your keywords attract. It does not decide which
keywords to keep, cut, or build pages for on your specific site — that needs a
look at your real traffic, goals, and competitors.

Full version / diagnosis

The lite prompt above uses general signals. For a specific site I run a deeper,
industry-tuned classification (buyer-term dictionaries per product category,
edge cases, and a full keyword-to-page plan).

Built by Tess — B2B / export SEO consultant.
Want a full keyword / site diagnosis? → [wechat:shh123468]
小红书: search "Tess | B2B增长"

<!-- If you use or fork this, a credit link back is appreciated 🙏 -->
