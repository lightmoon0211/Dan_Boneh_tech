# Journal of Intelligent Manufacturing: article analysis and manuscript alignment

Checked against the journal website and four published research PDFs on 11 September 2026.

The revised manuscript follows the journal's author–year citation system and the unnumbered headings observed in these articles. This is a focused comparison of relevant research papers, not a systematic survey of the journal. Current submission instructions take precedence over conventions seen in an individual published article.

## Published papers examined

| Paper | Method and evidence | Presentation pattern relevant to this manuscript |
|---|---|---|
| [Qin and Lu (2025)](https://doi.org/10.1007/s10845-024-02494-0), *Knowledge graph-enhanced multi-agent reinforcement learning for adaptive scheduling in smart manufacturing*, 36, 5943–5966; 24 pages | Machine scheduling knowledge informs reinforcement learning; factory records support the manufacturing setting. | Defines the scheduling problem before graph construction and learning components; follows with experiments and interpretation. Equations have independent numbering. Contributions and the introduction's roadmap are explicit. |
| [Massouh et al. (2025)](https://doi.org/10.1007/s10845-025-02740-z), *Safe and efficient multi-agent planning for human–integrated smart manufacturing*; online publication, 17 pages | Graph-based skill planning and agent negotiation incorporate human safety; evaluation uses manufacturing simulations. | Moves from architecture to mathematical planning, negotiation, execution, and evaluation. Symbols are explained beside equations, and algorithmic actions are presented sequentially. |
| [Kaven et al. (2024)](https://doi.org/10.1007/s10845-023-02309-8), *Multi agent reinforcement learning for online layout planning and scheduling in flexible assembly systems*, 35, 3917–3936; 20 pages | Cooperative reinforcement learning connects layout and scheduling agents to a discrete-event simulator. | Introduces foundations and prior work before the proposed system; separates learning components from experimental setup and performance analysis. The bibliography is alphabetical and unnumbered. |
| [Seitz et al. (2026)](https://doi.org/10.1007/s10845-026-02904-5), *Synthetic process modeling for ring rolling via physics-guided GANs and analytical transfer learning*; online publication, 34 pages | Synthetic process modeling is grounded in experimental and finite-element information. | Separates the physical/modeling basis, proposed method, results, discussion, and conclusion; places detailed pseudocode in an appendix. Its synthetic data do not replace external grounding. |

All four PDFs use unnumbered displayed section headings. Their main bodies use the publisher's two-column layout, with full-width front matter and selected wide objects. Article lengths differ substantially; this sample does not establish a mandatory manuscript length.

## Conventions applied

The requirements below follow the [current author guidelines](https://link.springer.com/journal/10845/submission-guidelines); the table also identifies presentation choices observed in the PDFs.

| Element | Applied treatment |
|---|---|
| Citations | Author–year: “Qin and Lu (2025)” or “(Qin & Lu, 2025)”; three or more authors use “et al.” in the text. |
| References | Alphabetical, unnumbered, hanging indent; italic publication titles and volume; full DOI links where available. Only cited works enter the manuscript bibliography. |
| Headings | Two levels, unnumbered; a choice supported by all sampled PDFs. Guidelines allow at most three levels. |
| Equations | Native editable Word mathematics, numbered (1)–(8); nearby definitions and ordered cross-references. |
| Figures | Fig. 1–Fig. 3, cited in order; captions below, bold figure label, regular caption text, no final punctuation; separate EPS artwork supplied. |
| Tables | Table 1–Table 6, native Word tables, captions above; restrained horizontal rules match the sample's presentation. |
| Algorithm | Algorithm 1 has explicit inputs, indented loop and conditional steps, and outputs. Line numbers are local to the algorithm. |
| Front matter | Informative title; 224-word abstract; six keywords; author, affiliation, email, and ORCID fields retained for completion. |
| End matter | Statements and Declarations, data/code availability, substantive AI-use disclosure, and Online Resource 1. |
| Submission file | Editable Word, plain serif body, automatic page numbers, embedded figures; no publisher branding or invented publication metadata. |

## Changes to the research narrative

The introduction now gives three explicit contributions and a roadmap. The environment begins with the decision problem, information boundary, and evaluation targets. The method opens with an offline/online overview before presenting costs, specialists, belief updates, and acquisition. It defines symbols, tie handling, and missing-response behavior, and distinguishes the cost-normalized heuristic from an exact optimization solution. The invariance statements now have separate propositions and proofs. The complexity description accounts for the implementation's cached searches for individual specialists.

Three directly relevant JIM studies—Qin and Lu, Massouh and colleagues, and Kaven and colleagues—were added to the manuscript, bringing its bibliography to 17 entries. Their roles are distinguished from this study's evidence-access graph. Seitz and colleagues inform this style and evidence comparison; their paper is not inserted into the manuscript merely because it appeared in the target journal.

The numerical findings, data, and executed experiment remain unchanged. Tables and figures are regenerated from the retained outputs. In particular, the standard-condition cost reduction remains 2.74%, and the noisy-condition secondary accuracy interval remains positive; the other three adaptive accuracy intervals include zero.

## Submission layout and remaining author work

The Word file is a clean, single-column submission manuscript. Published two-column pagination, journal logos, received/accepted dates, copyright lines, and assigned article identifiers belong to the publisher's production process and are not requirements reproduced here.

Before uploading, complete the actual authorship, affiliations, corresponding-author details, funding, competing interests, and contribution statements in both manuscript and supplement, and review the scientific content. Style alignment does not establish sufficient novelty or industrial validity for acceptance: this study uses probabilistic agents and an assumed simulation, without LLM-agent experiments or physical-factory validation.
