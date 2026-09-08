## Artem Bilozor — Senior SDET (Java / Kotlin)

Kyiv, Ukraine · 11 years in QA and test automation · currently in iGaming

I treat automation as an engineering discipline, not as a pile of test suites. Most of what I build is
infrastructure and reusable libraries that other engineers adopt — currently used across a QA
organization of 50+ engineers and managers.

### What I work on

| | |
|---|---|
| **Computer vision for untestable UI** | HTML5 Canvas games expose nothing to the DOM, so there is nothing to locate. I built a YOLO-based detection pipeline — dataset collection, model training, framework integration — with an Ollama vision-model fallback. **1,000+ games across 5+ brands** validated automatically, replacing ~4 hours of manual checks per game. |
| **Test infrastructure at scale** | Nightly validation of ~50 game suppliers on GKE, split per supplier to kill pod evictions. **~30 CI pipelines** migrated from Jenkins/Bitbucket to GitHub Actions, cutting trigger-to-execution time by **~30%**. |
| **Engineering enablement** | Reusable internal libraries and standards, ADRs, design reviews, technical sessions. An internal mobile device farm (5 iOS / 3 Android, Appium 2 → 3). An internal AI memory / MCP tool built for non-technical adoption. |

### Older experiments

Everything above lives in private repositories. What is public here is a set of small experiments and
teaching examples from earlier years — kept for reference, not maintained, and not representative of
what I build now.

- **[junit5-selenide-atlas-allure](https://github.com/ArtBi/junit5-selenide-atlas-allur)** — JUnit 5 + Atlas page objects + Allure reporting.
- **[github-actions-selenide-allure](https://github.com/ArtBi/github-actions-selenide-allure)** — a UI suite wired into GitHub Actions with published Allure reports.
- **[swagger_test_coverage](https://github.com/ArtBi/swagger_test_coverage)** — measuring API test coverage against a Swagger spec.
- **[java_mentoring](https://github.com/ArtBi/java_mentoring)** — materials I used while mentoring engineers into automation.

### Stack

`Java` `Kotlin` `Playwright` `Selenide` `REST Assured` `Appium` `JUnit`
`YOLO` `Ollama` `Tesseract` `Docker` `Jenkins` `GitHub Actions` `GKE / GCP` `ReportPortal` `PostgreSQL` `GraphQL`

### Reach me

[LinkedIn](https://www.linkedin.com/in/artem-bilozor) · [theartbi@gmail.com](mailto:theartbi@gmail.com)

Open to test automation consulting and collaboration.
