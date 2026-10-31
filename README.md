# Awesome-Search-Engine-Optimization-SEO-Tools

## Top Search Engine Optimization (SEO) Tools Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Keyword Research, Rank Tracking & Self-Hosted SEO Intelligence*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Search Engine Optimization (SEO) Tools**. These tools enable marketers, agencies, and site owners to research keywords, audit technical health, track rankings, analyze backlinks, and monitor visibility in both traditional search engines and AI-powered answer engines.



**Examples** include HubSpot Search Engine Optimization (SEO), Semrush, Ahrefs, Moz Pro, Surfer SEO, BrightEdge, Conductor, SE Ranking, SpyFu, and Ubersuggest (the category leaders).



**Open-source emphasis**: SEO Tools is a domain where open-source tooling has **matured significantly but carries an honest caveat about data costs**. **OpenSEO** is the leading open-source Semrush/Ahrefs alternative—covering keyword research, rank tracking, backlinks, site audits, and AI visibility—but it relies on **DataForSEO**, a paid API with pay-as-you-go pricing, so it is not completely free to run . **SerpBear** focuses purely on rank tracking for unlimited keywords and domains, with free Google Search Console integration, though it requires a SERP API provider for live position data . **Scrawly** is the strongest free technical audit tool—250 checks including GEO/AI-search readiness, no account required, MIT licensed . **SEONaut** and **LibreCrawl** provide free Screaming Frog alternatives for site crawling . The critical caveat: **backlink index depth and historical data remain commercial moats**—Ahrefs and Semrush still lead on years of accumulated link data that open-source tools cannot replicate .



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[HubSpot Search Engine Optimization (SEO)](https://www.hubspot.com/)**  

  SEO tools within HubSpot's Marketing Hub; topic clusters, content strategy, and on-page optimization tied to CRM data and marketing workflows.



- **[Semrush](https://www.semrush.com/)**  

  Comprehensive SEO suite with massive keyword database, competitive analysis, backlink audit, site audit crawler, and position tracking. The benchmark for keyword and competitive data depth.



- **[Ahrefs](https://ahrefs.com/)**  

  Industry-leading backlink index and keyword research platform; Site Audit crawler, Rank Tracker, and Content Explorer. The standard for backlink analysis.



- **[Moz Pro](https://moz.com/)**  

  SEO toolset with Domain Authority metric, keyword research, link building, and site audits; strong for local SEO and brand monitoring.



- **[Surfer SEO](https://surferseo.com/)**  

  Content optimization platform focused on on-page SEO and content briefs; analyzes top-ranking pages to recommend content structure and keywords.



- **[BrightEdge](https://www.brightedge.com/)**  

  Enterprise SEO and content performance platform with AI-powered recommendations, competitive intelligence, and CMS integrations.



- **[Conductor](https://www.conductor.com/)**  

  Enterprise SEO platform focused on content intelligence, organic visibility tracking, and workflow automation for large marketing teams.



- **[SE Ranking](https://seranking.com/)**  

  All-in-one SEO platform with rank tracking, keyword research, site audits, and competitor analysis at mid-market pricing.



- **[SpyFu](https://www.spyfu.com/)**  

  Competitive intelligence tool for spying on competitors' keywords and ad history; focused on PPC and SEO overlap.



- **[Ubersuggest](https://neilpatel.com/ubersuggest/)**  

  Budget-friendly SEO tool from Neil Patel; keyword research, site audits, and rank tracking with a generous free tier.



## Open-Source GitHub Projects



### All-in-One SEO Platforms (Semrush/Ahrefs Alternatives)



- **[OpenSEO](https://github.com/every-app/open-seo)**  

  The most complete open-source **Semrush/Ahrefs alternative** (MIT, 2,100+ GitHub stars) . Covers **keyword research** (volume, difficulty, CPC, intent, trends), **rank tracking** with position history stored on your server, **domain overview** and competitor research, **backlink analysis** (referring domains, new/lost links), **site audits** with grouped technical issues, **AI visibility tracking** and Prompt Explorer, and **Google Search Console integration** . Includes an **MCP server and nine Agent Skills** for Claude Code, Cursor, and Codex—letting AI agents query SEO data directly . **Critical cost caveat**: OpenSEO is free to self-host, but **all search data comes from DataForSEO**, a paid API billed per request with your own key (new accounts get $1 free credit; minimum top-up $50) . Docker or Cloudflare Workers deployment. **Best for teams wanting a full SEO workflow without per-seat SaaS fees**—budget for the DataForSEO usage, not the software.



### Rank Tracking (Dedicated)



- **[SerpBear](https://github.com/towfiqi/serpbear)**  

  The leading open-source **rank tracking** tool (2,000+ GitHub stars) . Tracks **unlimited keywords for unlimited domains**; supports **eight SERP API providers** with different cost/functionality tradeoffs so you can choose based on budget . Features: **email notifications** for keyword position changes, **REST API** for marketing tools and data reporting, **Google Search Console integration** for real clicks/impressions data, **Keyword Research** feature (requires Google Ads API approval), and PWA mobile app . Docker deployment; can run free on Fly.io or mogenius . **Best for teams wanting focused rank tracking** without the full OpenSEO stack—but you pay per SERP request to your chosen provider .



### Technical SEO Crawlers & Audits



- **[Scrawly](https://github.com/IliasSami/scrawly-seo-crawler)**  

  The strongest **free, open-source technical SEO crawler** available (MIT, released October 2026) . Runs **250 checks across 23 areas** including crawlability, redirects, titles/meta, canonicals, content quality, structured data, internal linking, Core Web Vitals, **AI search readiness (GEO)** —AI crawler access, llms.txt, citation readiness—and **agentic web** checks for how well AI agents can read your site . Features: JavaScript rendering, custom extraction, saved crawl profiles, 3D site graph, crawl-to-crawl comparison, scheduled audits with regression alerts, **GSC and GA4 integration**, branded HTML/PDF reports, AI writer for titles/meta (bring your own key), and an **MCP server** for AI assistant integration . **For WordPress sites, can apply safe, reversible fixes** . **Desktop app—no account, no page limit**. **The best free alternative to Screaming Frog and Sitebulb** with explicit AI-search checks.



- **[SEONaut](https://github.com/steven-tey/seonaut)**  

  Open-source **Screaming Frog alternative** for technical SEO (717 GitHub stars) . Self-hosted web app (Docker) with a hosted version available; crawls sites, audits on-page SEO, and surfaces issues like broken links . **No paid data provider required**—one of the cheapest tools to run . **Best for teams wanting a web-based crawler** without a paid licence.



- **[LibreCrawl](https://github.com/librecrawl/librecrawl)**  

  Open-source **desktop or web crawler** (681 GitHub stars) for site crawling and SEO audits . Analyzes links and exports SEO data; no paid data provider required . **Best for teams wanting a free, lightweight crawler** without Docker infrastructure.



### Keyword Research & Content (CLI / Library)



- **[ZensInk](https://pypi.org/project/zens-ink/)**  

  Open-source **SEO toolkit for indie builders** (pure Python, zero dependencies, 20 CLI tools) . Covers the full workflow: **keyword_research** (Google Autocomplete, no API), **keyword_cluster** (semantic topic clustering), **kd** (keyword difficulty via SERP structure, free Serper key), **keyword_volume** (Bing Webmaster API, free key), **domain_rating** (Ahrefs free API), **search_intent** classification, **competitor_gap** (compare multiple competitor sitemaps), **site_audit** (30 technical + GEO checks), **llms_gen** (generate llms.txt), **ai_crawler_audit**, **rank_tracker** (SQLite-backed), and **search_performance** (GSC) . Works as an **AI agent skill** and ships an **MCP stdio server** . **Best for developers and technical SEOs** wanting scriptable, reproducible SEO analysis without paid APIs—some features require free API keys (Serper, Bing, Ahrefs), but core tools work without any .



### Backlink Discovery (Free Alternative)



- **[mcp-common-crawl](https://github.com/arturseo-geo/mcp-common-crawl)**  

  Open-source **MCP server for backlink discovery** using Common Crawl's free web archive (MIT) . Provides a free alternative to Ahrefs/Semrush backlink APIs ($100+/month) . Tools: **discover_backlinks** (find backlinks to any domain across 3 CC indexes), **find_expired** (expired/parked domain discovery), **check_domain** (live/expired/parked + CC page count), and **competitor_gap** (domains linking to competitors but not you) . **No API keys, no rate limits, no paid tiers** . **Best for teams wanting free backlink discovery** via MCP—but it queries Common Crawl's archive rather than a live link index, so coverage and freshness differ from commercial backlink databases .



### Additional Strong Open-Source Options



- **All-In-One-Free-SEO-Tool (IamRamgarhia)** — Open-source self-hosted SEO tool claiming **99 tools** including site audits, rank tracking, keyword research, AI search visibility (ChatGPT, Perplexity, Gemini, AI Overviews), content briefs, backlinks, local SEO, white-label reports, and an agent that applies fixes; **no paid APIs required** (MIT) . **Early-stage/verify claims**—but the scope is ambitious if the functionality matches .

- **SerpX SEO Tools** — Open-source Python package for **on-page technical audits, small site crawling, and offline CSV keyword gap analysis**; no scraping Google, no fabricated volumes . **Best for reproducible CLI workflows** with your own data exports .



**Frameworks for building custom systems**: For **full SEO workflow with keyword research, backlinks, and audits**, OpenSEO (budgeting for DataForSEO usage) . For **rank tracking only**, SerpBear (choosing a SERP provider) . For **free technical audits with AI-search checks**, Scrawly . For **scriptable keyword and content analysis**, ZensInk . For **free backlink discovery**, mcp-common-crawl . No open-source project replicates **Ahrefs' backlink index depth or Semrush's historical data**—those remain commercial moats .



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- SEO tools handling site data and search performance must comply with search engine guidelines; **crawlers must respect robots.txt and rate limits**, and scraping search results may violate provider terms of service.

- **Open-source SEO tools are mature for audits and rank tracking but not for data depth**—OpenSEO and SerpBear rely on paid APIs for search volume, SERP positions, and backlinks, so they are **not completely free to run** . **Scrawly provides the strongest free technical audit** with no data provider dependency . **Backlink index depth and historical data remain commercial moats**—Ahrefs and Semrush still lead on years of accumulated link data that open-source tools cannot replicate .

- Verify license terms for commercial use; OpenSEO uses MIT , Scrawly uses MIT , and SerpBear is open-source .



---



**Made for SEO specialists, technical marketers, content strategists, and developers building SEO tooling.**  

Let's make SEO tools more open, but with clear eyes about the data costs and backlink index moats that commercial platforms still hold.
