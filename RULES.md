# Resume Editing Rules

- Keep resume content public-safe. Do not mention internal service names, internal config systems, internal environments, access keys, PSMs, or unreleased project names.
- Prefer generic technical wording for internal systems:
  - Use "distributed caching" instead of naming internal cache services.
  - Use "distributed storage" instead of naming internal storage services.
  - Use "multimodal video analysis" instead of naming specific internal model/client integrations.
  - Use "test runs" or "benchmark runs" instead of naming internal test environments.
- It is fine to mention public company names and public technologies, such as TikTok, Go, Python, Thrift, RPC, Kafka, Flink, Hive, Elasticsearch, PostgreSQL, AWS, and Google Cloud.
- Keep bullets achievement-oriented and concise. Preserve measurable scope where possible, such as RPC count, benchmark count, or latency/testing coverage.
- When editing any `.tex` resume source, rebuild the corresponding PDF with `latexmk -pdf`.
- Apply wording consistently across both resume variants when the same experience is described:
  - `Resume_Shengran_Jin.tex` (default, backend-focused)
  - `Resume_Shengran_Jin_Systems.tex`
