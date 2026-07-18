# Eren Gülmez

**Industrial Engineer · TURKEY** — I turn logistics & supply chain data into decisions.

- 🎯 I design the questions first: KPI architecture, delivery performance (OTIF), demand & inventory analytics
- 🛠️ I direct modern tooling — automation, analytics, AI — while the strategy, the methodology and the quality bar stay with me

## 🚩 Flagship — [erp-report-engine](https://github.com/gulmezeren2-byte/erp-report-engine)

[![A read-only SQL guard for AI agents you can actually prove: 28/28 attacks refused, vs 6/28 for a shape-only check](https://raw.githubusercontent.com/gulmezeren2-byte/erp-report-engine/main/docs/assets/social-card.png)](https://github.com/gulmezeren2-byte/erp-report-engine)

**A *provably* read-only SQL layer for AI agents — and weekly reports — over the database behind an ERP.** The agent queries canonical entities (`orders`), never the raw ERP tables (`LG_001_01_ORFICHE`), through a guard that checks the **statement itself** — and refuses the file reads, shell calls and write-escapes a shape-only check waves through (the class of bug behind the [archived Postgres MCP server](https://github.com/modelcontextprotocol/servers-archived/tree/HEAD/src/postgres) and the Supabase "lethal trifecta"). Not asserted — **measured**: a reproducible 28-attack benchmark and an in-browser "break it" playground running the real guard.

On [PyPI](https://pypi.org/project/erp-report-engine/) · listed on the official **MCP registry** · **[try to break the guard, live →](https://gulmezeren2-byte.github.io/erp-report-engine/playground.html)** · **[the benchmark →](https://gulmezeren2-byte.github.io/erp-report-engine/trust.html)**

## The measurement honesty series

*Metrics should describe reality, not decorate slides.*

<img src="https://raw.githubusercontent.com/gulmezeren2-byte/otif-analytics/main/charts/metric_ladder.svg" alt="The same deliveries, five definitions: 98% reported vs 59% OTIF" width="720">

1. **[otif-analytics](https://github.com/gulmezeren2-byte/otif-analytics)** — the reported on-time KPI says 98%; the customer feels 59%. The four definition choices that hide the gap.
2. **[forecast-accuracy-lab](https://github.com/gulmezeren2-byte/forecast-accuracy-lab)** — MAPE silently drops zero-demand months and flips model rankings; WMAPE, bias and FVA tell the truth.
3. **[abc-xyz-inventory](https://github.com/gulmezeren2-byte/abc-xyz-inventory)** — the safety-stock formula promises 95% and delivers 83% on volatile SKUs. Segment before you standardize.
4. **[auto-report-pipeline](https://github.com/gulmezeren2-byte/auto-report-pipeline)** — the capstone: honest metrics, computed the same way and delivered every Monday, untouched by hands.
5. **[forecast-autoresearch](https://github.com/gulmezeren2-byte/forecast-autoresearch)** — the live experiment: can an AI agent honestly beat naive forecasting? Sealed holdout, one editable file, a human-directed program. The bar was **+6.79**; two cycles and ten experiments later: **+8.13**.
6. **[erp-report-engine](https://github.com/gulmezeren2-byte/erp-report-engine)** — the series' enterprise culmination, now the **flagship above**: measurement honesty applied to an ERP's own database, for AI agents as much as for reports — read-only *proven*, not promised.

## For your AI agent

- 🛑 **[andon](https://github.com/gulmezeren2-byte/andon)** — the honesty block, turned on your AI. It re-checks the numbers an agent drafts — a report, a spreadsheet — against the data they came from, with arithmetic instead of another model: reconciliation, internal consistency and Excel integrity, stopping the line when they don't add up.
- 🤖 **[industrial-engineering-ai-skills](https://github.com/gulmezeren2-byte/industrial-engineering-ai-skills)** — the judgment layer of the series as a full method pack: 7 skills, 4 role agents, always-on data-hygiene rules and artifact templates. Pitfalls included.
- 🔧 **[opsaudit](https://github.com/gulmezeren2-byte/opsaudit)** — the engine room: a JSON-only CLI (OTIF, forecast backtests, ABC-XYZ, Pareto) where every result carries a mandatory honesty block. 8 end-to-end tests.
- 🛡️ **[readonly-sql-guard](https://github.com/gulmezeren2-byte/readonly-sql-guard)** — a provably read-only SQL guard for any MCP server or DB tool: it checks what a statement *calls*, not just its shape, and refuses the file reads and transaction escapes a shape-only check waves through. Measured against a 28-attack benchmark. The guard from erp-report-engine, extracted as a reusable primitive.

## Turkish public data, made queryable

*Public information that is public one document at a time — and impossible to reason across.*

- 🏛️ **[ihalent](https://github.com/gulmezeren2-byte/ihalent)** — every public tender in Turkey ends with a result notice: who won, for how much, at what discount, against how many bidders. ihalent turns tens of thousands of them into firm histories, discount (kırım) distributions and competition metrics — every number traceable back to its notice.

## Also

- 📚 Curator of **[awesome-industrial-engineering](https://github.com/gulmezeren2-byte/awesome-industrial-engineering)** — every entry hand-picked for practitioner value
- 🇹🇷 Curator of **[awesome-turkish-mcp](https://github.com/gulmezeren2-byte/awesome-turkish-mcp)** — MCP servers for Turkish data & domains (law, finance, government, academia, ERP)
- 📫 Reach me on [LinkedIn](https://www.linkedin.com/in/erengulmez)

## 🇹🇷 Türkçe

**Endüstri mühendisiyim (İstanbul).** Lojistik ve tedarik zinciri verisini karara çeviririm: önce doğru soruyu tasarlarım, sonra modern araçları — otomasyon, analitik, yapay zeka — yöneterek hayata geçiririm; yöntem, kalite çıtası ve iş yorumu her zaman bende kalır.

***Ölçüm dürüstlüğü* serim** — metrikler gerçeği anlatmalı, slaytları süslememeli:

1. **[otif-analytics](https://github.com/gulmezeren2-byte/otif-analytics)** — rapor edilen zamanında-teslimat %98 derken müşterinin yaşadığı %59; farkı gizleyen dört tanım tercihi. ([Türkçesi](https://github.com/gulmezeren2-byte/otif-analytics/blob/main/README.tr.md))
2. **[forecast-accuracy-lab](https://github.com/gulmezeren2-byte/forecast-accuracy-lab)** — MAPE sıfır talepli ayları sessizce düşürür ve model sıralamasını değiştirir; doğruyu WMAPE, yanlılık ve FVA söyler. ([Türkçesi](https://github.com/gulmezeren2-byte/forecast-accuracy-lab/blob/main/README.tr.md))
3. **[abc-xyz-inventory](https://github.com/gulmezeren2-byte/abc-xyz-inventory)** — emniyet stoku formülü %95 vaat eder, oynak ürünlerde %83 teslim eder. Standartlaştırmadan önce segmentlere ayırın. ([Türkçesi](https://github.com/gulmezeren2-byte/abc-xyz-inventory/blob/main/README.tr.md))
4. **[auto-report-pipeline](https://github.com/gulmezeren2-byte/auto-report-pipeline)** — final: dürüst metrikler, her Pazartesi aynı şekilde, el değmeden. ([Türkçesi](https://github.com/gulmezeren2-byte/auto-report-pipeline/blob/main/README.tr.md))
5. **[forecast-autoresearch](https://github.com/gulmezeren2-byte/forecast-autoresearch)** — canlı deney: bir yapay zeka ajanı naive tahmini dürüstçe yenebilir mi? Mühürlü holdout, tek düzenlenebilir dosya, insan-yönetimli program. Çıta **+6,79** idi; iki döngü ve on deney sonra: **+8,13**. ([Türkçesi](https://github.com/gulmezeren2-byte/forecast-autoresearch/blob/main/README.tr.md))
6. **[erp-report-engine](https://github.com/gulmezeren2-byte/erp-report-engine)** — serinin kurumsal doruğu, artık **amiral proje**: ölçüm dürüstlüğü ERP'nin kendi veritabanına uygulanmış — raporlar kadar AI ajanları için de. Salt-okunur *kanıtlanmış*, vaat edilmemiş; halka açık 28-saldırı benchmark'ı + tarayıcıda "kır beni" oyun alanı. PyPI'da + resmî MCP registry'de. ([Türkçesi](https://github.com/gulmezeren2-byte/erp-report-engine/blob/main/README.tr.md))

**Yapay zeka ajanınız için** — 🛑 **[andon](https://github.com/gulmezeren2-byte/andon)**: dürüstlük bloğunu yapay zekaya çevirir; bir ajanın hazırladığı raporu/Excel'i başka bir modele değil aritmetiğe denetletir (mutabakat, iç tutarlılık, Excel bütünlüğü) ve sayılar tutmuyorsa hattı durdurur. Ayrıca **[endüstri mühendisliği becerileri](https://github.com/gulmezeren2-byte/industrial-engineering-ai-skills)** method paketi.

**Türk kamu verisi, sorgulanabilir hale** — 🏛️ **[ihalent](https://github.com/gulmezeren2-byte/ihalent)**: her kamu ihalesi bir sonuç ilanıyla biter — kim, kaça, ne kırımla, kaç rakibe karşı kazandı. ihalent on binlerce ilanı firma geçmişlerine, kırım dağılımlarına ve rekabet metriklerine çevirir; her sayı kaynak ilanına kadar izlenebilir.

Ayrıca alanın ücretsiz kaynaklarını derlediğim **[awesome-industrial-engineering](https://github.com/gulmezeren2-byte/awesome-industrial-engineering)** ve Türkçe MCP ekosistemini derlediğim **[awesome-turkish-mcp](https://github.com/gulmezeren2-byte/awesome-turkish-mcp)** listelerinin küratörlüğü.
