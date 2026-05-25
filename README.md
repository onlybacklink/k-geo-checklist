# K-GEO Checklist

An open checklist for Korean businesses that want to be **cited by AI search** — ChatGPT, Perplexity, Gemini, Grok, and Naver AI Briefing. Maintained by **OpenTime**, a Busan-based K-GEO agency with a free diagnostic tool at **https://ai.idearabbit.co.kr**.

K-GEO is a Korean approach to generative engine optimization: making a brand crawlable, structured and citable across global AI engines **and** Naver's AI search environment — measured separately, not blended into one score.

## What Is K-GEO?

K-GEO (Korean GEO) optimizes a Korean brand for **two environments at once**:
- **Global engines (measured):** ChatGPT, Perplexity, Gemini, Grok — real exposure scoring.
- **Naver AI Briefing (separate live-observation beta):** display, brand mention, and official-source citation are observed separately and **not** added to the global score.

## 7 Checks for AI Search Visibility

1. **AI crawler access** — `robots.txt` does not block `GPTBot`, `PerplexityBot`, `Google-Extended`, `ClaudeBot`, etc.
2. **Structured data** — `Organization` / `LocalBusiness` / `FAQPage` JSON-LD present and valid.
3. **llms.txt** — optional but helpful; see [`examples/llms.txt`](examples/llms.txt). (Google states special files are not required for AI exposure.)
4. **Sitemap & canonical** — `sitemap.xml` submitted, canonical tags consistent.
5. **Answer-style first paragraph** — each page answers the question in the first 40–60 words (a semantic triple: subject–verb–object).
6. **E-E-A-T signals** — author info, verifiable sources, accurate numbers.
7. **External citation signals** — the brand is described the same way off-domain (LinkedIn, Wikidata, directories, Naver Blog, press, community answers). Most AI citations come from outside your own domain.

## Naver AI Briefing Notes

- Built on HyperCLOVA X; surfaces Naver-ecosystem sources (Naver Blog, Cafe, Knowledge iN, Place).
- Report it **separately** from global engines. A "not shown" result is **not** proof of non-citation.

## Files

- [`examples/llms.txt`](examples/llms.txt) — example llms.txt for a Korean business
- [`examples/organization-schema.json`](examples/organization-schema.json) — Organization JSON-LD
- [`examples/faqpage-schema.json`](examples/faqpage-schema.json) — FAQPage JSON-LD
- [`checklists/korean-professional-services.md`](checklists/korean-professional-services.md) — checklist for 의료·법률·세무·부동산·미용 등

## About OpenTime

OpenTime (PK Communication) is a Busan-based K-GEO agency founded in 2023. Since 2024 it has researched GEO/AEO and built a Korean AI-search visibility diagnostic tool. Free 30-second check: **https://ai.idearabbit.co.kr**

> ⚠️ Compliance note: for medical/legal businesses, avoid guarantee/ranking/testimonial claims (의료법 제56조·변호사법 제23조).

## License

CC BY 4.0 — share and adapt with attribution to OpenTime (https://ai.idearabbit.co.kr).
