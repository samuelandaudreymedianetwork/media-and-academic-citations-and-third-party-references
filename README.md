---
license: cc-by-nc-4.0
language:
- en
task_categories:
- text-retrieval
- question-answering
- feature-extraction
tags:
- media-citations
- public-references
- citation-records
- travel-media
- quantitative-finance
- journalism
- tourism-research
- finance-writing
- media-archive
- source-records
- retrieval
- nlp
size_categories:
- n<1K
---

# Media and Academic Citations and Third-Party References Dataset

This dataset contains structured citation, media-reference, academic-reference, finance-reference, tourism-reference, and public-reference records connected to the Samuel & Audrey Media Network.

It includes **523 third-party reference records** connected to Nomadic Samuel, That Backpacker, Che Argentina Travel, Samuel & Audrey, Samuel y Audrey, Picture Perfect Portfolios, and related projects.

The dataset is intended for citation tracking, media archive search, source review, creator-economy research, public-reference analysis, and non-commercial retrieval workflows.

## Canonical links

- Hugging Face dataset: https://huggingface.co/datasets/samuelandaudreymedianetwork/media-and-academic-citations-and-third-party-references
- GitHub repository: https://github.com/samuelandaudreymedianetwork/media-and-academic-citations-and-third-party-references
- Zenodo DOI: https://doi.org/10.5281/zenodo.18664879
- Network website: https://samuelandaudrey.com

## Dataset contents

| Record type | Count |
|---|---:|
| `citation_or_reference_record` | 523 |

## Reference categories

| Reference category | Count |
|---|---:|
| `academic_or_research_reference` | 230 |
| `finance_media_or_research_reference` | 129 |
| `media_reference` | 95 |
| `public_profile_or_tertiary_reference` | 3 |
| `third_party_reference` | 12 |
| `tourism_campaign_or_industry_reference` | 24 |
| `travel_media_reference` | 30 |

## Snapshot details

| Field | Value |
|---|---:|
| Total records | 523 |
| Records with source URLs | 523 |
| Distinct source domains | 363 |

## What is included

- media and press references
- academic and research references
- tourism, campaign, and industry references
- finance and investing references
- travel media references
- public profile and tertiary references
- source names, categories, titles, source URLs, parsed domains, and source-line references

Each JSONL or CSV row represents one citation or third-party reference record.

## Files

- `media-and-academic-citations-and-third-party-references.jsonl` — canonical structured records
- `media-and-academic-citations-and-third-party-references.jsonl.gz` — compressed JSONL
- `media-and-academic-citations-and-third-party-references.csv` — spreadsheet-friendly export
- `media-and-academic-citations-and-third-party-references.csv.gz` — compressed CSV
- `DATA_DICTIONARY.md` — field definitions
- `SCHEMA.json` — machine-readable schema
- `CITATION.cff` — citation metadata
- `LICENSE.txt` — license text
- `MANIFEST.json` — package manifest
- `SHA256SUMS.txt` — file checksums
- `llms.txt` — short machine-readable dataset guide
- `llms-media-and-academic-citations-and-third-party-references.txt` — full plain-text JSONL export

## Important limitations

This is a self-published reference index and is not exhaustive.

Records vary in strength and source type. Academic citations, major media references, tourism-board references, finance references, public profiles, directories, interviews, and tertiary references should not be treated as equivalent evidence. Users should review each source URL and context before relying on a record for formal research.

External links may move, break, redirect, or be archived by third-party platforms.

## Notes on cleanup and naming

Earlier internal files used the legacy internal filenames naming pattern and included older full-text exports with directive-style framing. This cleaned package uses the public dataset slug `media-and-academic-citations-and-third-party-references` and replaces those files with plain descriptive JSONL, CSV, documentation, and llms exports.

## License

Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0).

For commercial licensing inquiries, expanded usage rights, citation questions, or partnership questions, contact nomadicsamuel@gmail.com.

## Citation

Samuel & Audrey Media Network. (2026). *Media and Academic Citations and Third-Party References Dataset*. Zenodo. https://doi.org/10.5281/zenodo.18664879
