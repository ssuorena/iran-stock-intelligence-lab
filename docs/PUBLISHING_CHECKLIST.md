# Release checklist / چک‌لیست انتشار

## Before creating the repository / پیش از ساخت ریپو

- [x] Repository created as `ssuorena/iran-stock-intelligence-lab` with private visibility.
- [ ] Suggested description: `An experimental n8n workflow for Iranian equity research: market data, rule-based scoring, AI explanations and Persian HTML reports.`
- [ ] Suggested topics: `n8n`, `workflow-automation`, `iran-stock-market`, `ai-agent`, `financial-analysis`, `persian`.
- [ ] Verify all folder contents and media in the online repository before changing visibility.
- [ ] Select a license deliberately; this pack does not grant an open-source license.
- [ ] Import the sanitized workflow and configure your own model credential. The workflow was packaged, not live-tested on a new n8n instance.
- [ ] Never commit credentials, API keys, account IDs, cookies, execution payloads or private portfolio information. Rotate any credentials previously shared publicly.
- [ ] Review third-party data terms and endpoint access before public or commercial deployment.

## Before recording or posting / پیش از ضبط و انتشار

- [ ] Run a fresh demo and verify symbol, timestamp, price units and missing values.
- [ ] Confirm report prices against the underlying historical close, not an assumed live quote.
- [ ] Check zero/invalid lows, shortened history, adjusted-price issues and scenario outputs across several symbols.
- [ ] Do not claim proven accuracy, profitability, full Codal statement analysis or autonomous trading.
- [ ] Label future estimates as experimental heuristic scenarios; confidence labels are not measured probabilities.
- [ ] Current risk/horizon inputs do not customize score formulas. Do not advertise that capability yet.
- [ ] The supplied saved ending HTML contains no usable analytic report body. Capture a fresh real report if you want a results screenshot; do not use a mock result as evidence.
- [ ] Screenshots and export may represent different iterations. Re-capture the imported final version if exact UI consistency matters.
- [ ] If you want public access, review the files and explicitly change repository visibility. A private repository URL is not accessible to LinkedIn readers.
- [ ] Add the repository URL to LinkedIn copy after the intended audience can access it. No LinkedIn post has been published by this pack.

## Scope of this package / دامنه این بسته

Presentation and documentation only. The original working workflow was not repaired or altered. The distributable copy removes instance/version metadata, pinned execution data and credential bindings, and remains inactive. Underlying calculations and UI logic are preserved, including the limitations documented in both READMEs.
