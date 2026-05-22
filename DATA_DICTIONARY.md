# Media and Academic Citations and Third-Party References Dataset — Data Dictionary

This file defines the fields used in `media-and-academic-citations-and-third-party-references.jsonl` and `media-and-academic-citations-and-third-party-references.csv`.

| Field | Description |
|---|---|
| `record_id` | Stable record identifier in the cleaned dataset. |
| `record_type` | Record type. For this dataset, records use `citation_or_reference_record`. |
| `citation_index` | 1-based row number preserving the original source order. |
| `section_id` | Section identifier from the original source extraction. |
| `section_title` | Cleaned section heading from the source extraction. |
| `section_focus` | Cleaned section focus note, when available. |
| `source_name` | Name of the citing or referencing entity, publication, organization, website, or source. |
| `source_category` | Cleaned category/type label from the original source extraction. |
| `reference_title` | Title or context of the citation, mention, feature, or reference. |
| `reference_category` | Normalized reference category inferred from source fields. |
| `source_url` | URL pointing to the referenced source. |
| `source_domain` | Domain parsed from `source_url`. |
| `source_line` | Line number in the original source text where the record appeared, when available. |
| `dataset` | Current dataset slug. |
| `license` | Dataset license. |
| `interpretation_note` | Cautionary note about interpreting each reference record. |

## Notes

The dataset preserves third-party reference records while replacing older internal naming and directive-style framing with plain descriptive fields.

Records should be evaluated according to source type and context. A peer-reviewed academic citation, a media feature, a directory listing, a forum mention, and a tertiary public-profile reference are different kinds of evidence.
