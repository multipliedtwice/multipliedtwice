# TalentProfile case study

## Iglu · Full-Stack Engineer

**Dec 2022–Present**

At Iglu, I architected and built [TalentProfile.net](https://talentprofile.net), a multi-tenant employment platform that manages more than 150,000 job records. My work spans the public site, candidate and employer applications, background workers, and a Chrome Manifest V3 autofill extension.

The platform handles job ingestion and enrichment, matching, CV and job-description parsing, ATS adapters, contextual answer reuse, and cover-letter generation. Its RAG retrieval uses BGE-M3 and pgvector to ground content in external, company, and job sources. The content workflow includes quality checks, revision, deduplication, linking, and publishing.

For multilingual application-form question classification, I built local ONNX/WASM inference. I also trained and evaluated a model candidate with PyTorch, LLM supervision, grouped evaluation, calibration, and ONNX export. On 3,986 held-out examples, the evaluated candidate accepted 51.4% of predictions (coverage), achieving 98.3% precision on those accepted predictions, and abstained on the remainder.

