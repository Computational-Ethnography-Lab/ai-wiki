# Everything You Wanted to Know About AI (in social science)
_(But Were Afraid to Ask)_

<p align="center">
  <img src="https://github.com/Computational-Ethnography-Lab/Computational-Ethnography-Lab.io/raw/e7ab5b2af6e8b92efa2120b6a12a9176ad3b2944/images/ciisr.png" alt="CIISR" width="100%">
</p>

A curated collection of resources for understanding artificial intelligence—from technical foundations to societal implications.

> **About this wiki**: Companion resource for the "Everything You Wanted to Know About AI But Were Afraid to Ask" event hosted by [CIISR](https://ciisr.rice.edu/)
> Very much in progress...
> Contributions welcome via pull request.
---

## Table of Contents

- [Getting Started: What is AI?](#getting-started-what-is-ai)
- [Dueling Perspectives: AI Optimism vs. Criticism](#dueling-perspectives-ai-optimism-vs-criticism)
- [Sociological & Methodological Perspectives](#sociological--methodological-perspectives)
  - [Attitudes Toward AI](#attitudes-toward-ai)
  - [LLM-Focused Methods](#llm-focused-methods)
  - [Qualitative & Computational Text Analysis Methods](#qualitative--computational-text-analysis-methods)
  - [Computational Text Analysis (Broader Context)](#computational-text-analysis-broader-context)
  - [Additional Resources](#additional-resources)
- [Social Science Workflow with AI](#social-science-workflow-with-ai)
- [Responsible AI & Ethics](#responsible-ai--ethics)
- [AI Governance & Regulation](#ai-governance--regulation)
- [AI Incidents & Failures](#ai-incidents--failures)
- [Domain Applications](#domain-applications)
- [Courses & Learning Resources](#courses--learning-resources)
- [Institutional AI Guidelines](#institutional-ai-guidelines)

---

## Getting Started: What is AI?

> **On Terminology** (Abramson et al. 2026, p. 5):
> 
> "*Artificial intelligence (AI) refers to technologies designed to mimic human performance on tasks that historically required human intelligence. This can include recognizing patterns, extracting text from .pdf files, classifying images, summarizing interviews, or generating synthetic content such as manipulated images or text. Some subfields commonly used in qualitative research workflows include machine learning (ML) for analyzing behaviors and cases, natural language processing (NLP) for parsing language data, and computer vision for analyzing images. Large language models (LLMs)—deep learning systems trained on mass-scale text data to predict and/or generate language (GPT is a commercial example)—are a subset of AI.*"
> See Abramson et al. (2026), [Qualitative Research in an Era of AI](https://arxiv.org/abs/2509.12503), Table 1 for a full typology.
> Today the term is often used synonymously with generative Large Language Models (LLMs) like ChatGPT, Claude, and Gemini.

Short, accessible introductions to large language models and AI fundamentals.

- [What is a Large Language Model?](https://www.cloudflare.com/learning/ai/what-is-large-language-model/) — Cloudflare's accessible technical overview
- [What are Large Language Models?](https://www.ibm.com/think/topics/large-language-models) — IBM's introduction to LLMs
- [A Very Gentle Introduction to LLMs without the Hype](https://mark-riedl.medium.com/a-very-gentle-introduction-to-large-language-models-without-the-hype-5f67941fa59e) — Mark Riedl (Georgia Tech); balanced, jargon-free overview
- [A Guide to Understanding AI as Normal Technology](https://www.normaltech.ai/p/a-guide-to-understanding-ai-as-normal) — Narayanan & Kapoor (2025); demystifying AI hype

### Practical Guides

- [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering) — Official best practices for GPT models
- [Anthropic Claude Prompt Engineering](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview) — Official guide for Claude models
- [Gemini Prompt Engineering Guide](https://ai.google.dev/gemini-api/docs/prompting-strategies) — Official guide for Gemini models
- [Context Engineering Guide](https://www.datacamp.com/blog/context-engineering) — DataCamp; beyond prompts: designing full information flows for AI
- [Ollama Quickstart Guide](https://docs.ollama.com/quickstart) — Run open-source models locally—installation, first model, API basics
- [Context Engineering with Agents](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents) — Anthropic (2024); managing context windows for AI agents beyond prompt engineering
- [Responsible AI at Stanford](https://uit.stanford.edu/security/responsibleai) — "Best practices" for AI use in academic settings

### Prompts
- [ChatGPT Prompts for University Educators](https://chatgpt.com/use-cases/university-educators) - Faculty from a dozen disciplines shared prompts they use for teaching and research

---

## Dueling Perspectives: AI Optimism vs. Criticism

Contrasting viewpoints to help you form your own position.

### The Optimist Case

- [One Useful Thing](https://www.oneusefulthing.org/) — Ethan Mollick; AI as collaborative partner; practical applications for knowledge work
- *Co-Intelligence* (2024) — Ethan Mollick; book-length treatment of human-AI collaboration

### The Critical Case

- [I Set Out to Study Which Jobs Should Be Done by AI](https://www.theguardian.com/commentisfree/article/2024/jun/09/study-which-jobs-ai-human-answer) — Allison Pugh; human connection has limits that AI cannot cross
- *The Last Human Job* (2024) — Allison Pugh; why certain work requires irreplaceable human qualities

### The "It's Complicated" Case

- [AI Snake Oil](https://www.aisnakeoil.com/) — Narayanan & Kapoor; separating genuine capabilities from hype
- [A Guide to Understanding AI as Normal Technology](https://www.normaltech.ai/p/a-guide-to-understanding-ai-as-normal) — Narayanan & Kapoor; AI as evolving technology, not magic

### The Pragmatic Case: Considered Use

- [From Carbon Paper to Code: Crafting Sociology in an Age of AI](https://contexts.org/blog/soc-ai/) — Corey M. Abramson; AI tools are part of our world now, for better or worse—but they can be repurposed with sociological imagination

---

## Sociological & Methodological Perspectives

How social scientists are thinking about AI.

- [The Society of Algorithms](https://doi.org/10.1146/annurev-soc-090820-020800) — Burrell & Fourcade (2021), *Annual Review of Sociology*. How algorithms mediate social life.
- [Qualitative Research in an Era of AI](https://arxiv.org/abs/2509.12503) — Abramson et al. (2026), *Annual Review of Sociology*. Large review of uses, examples, workflow, cautions in social science; includes traditional and large-scale qualitative examples; concludes with discussion of technological change and implications.
- [Can Generative AI Improve Social Science?](https://www.pnas.org/doi/10.1073/pnas.2314021121) — Bail (2024), *PNAS*. Review of AI applications across survey, experiments, content analysis, agent-based models.
- [Start Generating: Harnessing GAI for Sociological Research](https://doi.org/10.1177/23780231241259651) — Davidson (2024), *Socius*. Overview of GAI applications: text classification, image analysis, synthetic media.
- [A Sociological Approach to Analyzing Satellite and Streetscape Imagery with Generative AI Tools](https://doi.org/10.1177/00491241251339673) — Law & Roberto (2025), *SMR* 54(3). Using generative AI for image analysis in social science research.
- [Updating "The Future of Coding"](https://doi.org/10.1177/00491241251339188) — Than, Fan, Law, Nelson & McCall (2025), *SMR* 54(3):849-888. Systematic comparison of LLM coding approaches to human coding.
- [LLM Social Simulations Are a Promising Research Method](https://arxiv.org/abs/2504.02234) — Anthis, Kozlowski, Evans et al. (2025), *ICML 2025*. Using LLMs to simulate human research subjects—challenges and possibilities.
- [Simulating Subjects](https://doi.org/10.1177/00491241251337316) — Kozlowski & Evans (2025), *SMR* 54(3):1017-1073. Promise and peril of using LLMs to simulate human subjects and social interactions.

### Attitudes Toward AI

- [Generative AI in Sociological Research: State of the Discipline](https://doi.org/10.15195/v13.a3) ([preprint](https://arxiv.org/abs/2511.16884)) — Alvero, Stoltz, Stuhler & Taylor (2025), *Sociological Science*. Survey of authors across 50 sociology journals on GenAI use and attitudes. Finds sociologists primarily use GenAI for writing tasks; low trust in outputs regardless of expertise; few differences between computational and non-computational scholars.
- [Is it OK for AI to Write Science Papers? Nature Survey Shows Researchers Are Split](https://doi.org/10.1038/d41586-025-01463-8) — Kwon (2025), *Nature* 641. Survey of ~5,000 researchers worldwide; sharp divisions on ethical acceptability of AI in manuscript preparation; perception-practice gap where few disclose AI use despite broad acceptance.
- [Introducing Anthropic Interviewer: What 1,250 Professionals Told Us About Working with AI](https://www.anthropic.com/research/anthropic-interviewer) — Handa et al. (2025), Anthropic Research. AI-conducted qualitative interviews with 1,250 professionals (general workforce, scientists, creatives). Notable for using AI to do qualitative research at scale; finds optimism alongside stigma concerns (69%), displacement anxiety (55%), and low trust among scientists for core research tasks. [Public dataset](https://huggingface.co/datasets/Anthropic/AnthropicInterviewer).

### LLM-Focused Methods

- [Integrating Generative AI into Social Science Research](https://doi.org/10.1177/00491241251339184) — Davidson & Karell (2025), *SMR* 54(3):775-793. Introduction to SMR special issue; discusses measurement, prompting, and simulation themes across ten contributed articles.
- [From Codebooks to Promptbooks](https://doi.org/10.1177/00491241241227968) — Stuhler, Ton & Ollion (2025), *SMR* 54(3):794-848. Extracting information from text with generative LLMs.
- [LLMs for Text Classification: Zero-Shot to Instruction-Tuning](https://doi.org/10.1177/00491241251325243) — Chae & Davidson (2025), *Sociological Methods & Research*. Comparing 10 LLMs across prompting, fine-tuning, and instruction-tuning.
- [Scaling Hermeneutics](https://doi.org/10.1140/epjds/s13688-025-00548-8) — Dunivin (2025), *EPJ Data Science* 14(1):28. Hybrid approach preserving interpretive depth while scaling qualitative coding with LLMs; includes codebook adaptation workflow and intercoder reliability benchmarks.
- [Utilizing AI to Facilitate Qualitative Surgical Research](https://pubmed.ncbi.nlm.nih.gov/40557355/) — Farber, Abramson & Reich (2025), *Annals of Surgery Open* 6(2):e577. AI and qualitative in medicine: uses, cautions, challenges.

### Qualitative & Computational Text Analysis Methods

- [Contextual Text Coding](https://doi.org/10.1177/0049124120986191) — Lichtenstein & Rucks-Ahidiana (2023), *SMR* 52(2):606-641. Mixed-methods approach for large-scale textual data with context-specific meanings.
- [Flexible Coding of In-depth Interviews](https://doi.org/10.1177/0049124118799377) — Deterding & Waters (2018), *SMR*. Twenty-first-century approach to flexible coding.
- [The Living Codebook](https://doi.org/10.1177/0049124120986185) — Reyes et al. (2021), *SMR*. Documenting the process of qualitative data analysis.
- [Computational Grounded Theory](https://doi.org/10.1177/0049124117729703) — Nelson (2020), *SMR* 49(1):3-42. Foundational three-step workflow (pattern detection, refinement, confirmation) for computational text analysis.
- [Qualitative Coding in the Computational Era](https://osf.io/preprints/socarxiv/gpr4n_v1) — Li, Dohan & Abramson (2021), *Socius* 7. BERT example using local ML and human review for interview text classification. Appendix deals with false positives versus negatives in qualitative analysis. [Related blog](https://cmabramson.com/resources/f/using-machine-learning-with-ethnographic-interviews).
- [Ethnography and Machine Learning](https://arxiv.org/abs/2412.06087) — Li & Abramson (2025), *Oxford Handbook of the Sociology of Machine Learning*, pp. 245-272. Workflow with ML, local models, updated benchmarks for offline systems runnable on consumer hardware; also discusses file naming for QDA.
- [Inequality in the Origins and Experiences of Pain](https://www.rsfjournal.org/content/10/5/34) — Abramson et al. (2024), *RSF* 10(5):34-65. Simplified semantic networks using ML to subset text and visualize alongside in-depth reading.

### Computational Text Analysis (Broader Context)

- [The Promises of Computational Ethnography](https://doi.org/10.1177/1466138117725340) — Abramson et al. (2018), *Ethnography* 19(2):254-284. Broader case for triangulation and engagement with computation in in-depth qualitative data using data science/computational approaches.
- [Meaning in Hyperspace](https://doi.org/10.1146/annurev-soc-090324-024027) — Boutyline & Arseniev-Koehler (2025), *ARS* 51:89-107. Word embeddings as tools for cultural measurement; contains examples, good overview, links to pieces on measurement and similarity. Relevant to AI (embeddings are a key layer increasingly used in and outside of AI).
- [Computational Analysis for Qualitative Data: Workflow and Visualization Resources](https://github.com/Computational-Ethnography-Lab/teaching) — Computational Ethnography Lab. Comprehensive teaching repository with workflow summaries, Python toolkits, bibliography, and practical resources for integrating computational text analysis with qualitative research.

### Additional Resources (adjacent)

- [De-jargoning Qualitative Coding](https://cmabramson.com/resources/f/qualitative-coding-simplified?blogcategory=Analysis) — Academic resource simplifying qualitative coding concepts (academic cite in Li & Abramson 2025)
- [Sub-setting Qualitative Data for Machine Learning](https://cmabramson.com/resources/f/sub-setting-qualitative-data-for-machine-learning) — Guide to creating comparison sets in QDA
- [From Carbon Paper to Code](https://contexts.org/blog/soc-ai/) — Abramson (2024). Short, simple argument for how AI can be part of triangulation—repurposing language models as a sociological tool. This is what the field has done since Mills used a filing cabinet to write about the power elite, and Du Bois used data visualization to debunk myths about Black Americans.
- [Using Machine Learning with Ethnographic Interviews](https://cmabramson.com/resources/f/using-machine-learning-with-ethnographic-interviews) — Blog companion to Li, Dohan & Abramson (2021)

---

## Social Science Workflow with AI

Adapted from Abramson et al. (2026), [Qualitative Research in an Era of AI](https://arxiv.org/abs/2509.12503), *Annual Review of Sociology*, Table 2:

|  | Assistive | Automated | Agentic |
|---|-----------|-----------|---------|
| **Research Design** | Citation management, project records, version control | Readability checks, data-assisted sampling, simulating sample-size | Literature review synthesis |
| **Data Collection** | Participant/site tracking, hyperlink field artifacts, e-consent capture, digital diary, cloud backup | Multi-media aggregation, sensor/geospatial logging, timestamping, live transcription | Adaptive or event-based SMS prompts |
| **Data Processing** | Interview transcription, transcript editing, file-format normalization, data versioning | Scanned docs/images to text, A/V speech-to-text pipelines, de-identification workflows, metadata tagging, quality checks | Adaptive or event-based reminders |
| **Data Analysis** | Human coding, quote retrieval, memo writing | List/regex scripts coding, inter-coder reliability tests, pattern examination, visualizing patterns, counterfactual checks, network overlays | LLM-assisted coding, LLM-assisted memos, ML classifiers, ML embeddings, augmented retrieval, semantic Q&A |
| **Writing & Presentation** | Triangulation, consistency checks, real-time writing collaboration | Retrieval of analytic products, generating visuals, citation formatting, plain-language summaries, accessibility audits | Assisted writing, assisted editing |
| **Sharing & Preservation** | Replication code, notebooks, codebooks, DOI archiving, long-term preservation | Containerized analytic spaces, interactive data portals/APIs, tiered access controls, encryption for sensitive data | Simulated participants |

> **Key Insight**: "AI assists but does not replace researcher judgment. The most effective workflows maintain human oversight at decision points while leveraging AI for repetitive or scale-dependent tasks." (Abramson et al. 2026)

---

## Responsible AI & Ethics

Frameworks for thinking about AI ethics and responsibility.

### Foundational Documents

| Framework | Organization | Link |
|-----------|--------------|------|
| AI Risk Management Framework (2023) | NIST | [nist.gov](https://www.nist.gov/itl/ai-risk-management-framework) |
| EU AI Act (2024) | European Union | [artificialintelligenceact.eu](https://artificialintelligenceact.eu/) |
| Recommendation on the Ethics of AI (2021) | UNESCO | [unesco.org](https://www.unesco.org/en/artificial-intelligence/recommendation-ethics) |
| Ethically Aligned Design | IEEE | [ethicsinaction.ieee.org](https://ethicsinaction.ieee.org/) |
| Code of Ethics | ACM | [acm.org](https://www.acm.org/code-of-ethics) |

---

## AI Governance & Regulation

Tracking how governments and institutions are responding to AI.

| Resource | Type | Coverage |
|----------|------|----------|
| [AI Watch: Global Regulatory Tracker](https://www.whitecase.com/insight-our-thinking/ai-watch-global-regulatory-tracker) | Tracker | 30+ jurisdictions (EU, US, China, UK, etc.) |
| [Stanford AI Index Report 2025](https://hai.stanford.edu/ai-index/2025-ai-index-report) | Annual Report | Comprehensive data on AI trends, investment, policy |
| [Stanford STS 14/CS 134: AI Governance](https://web.stanford.edu/class/sts14/index.html) | Course | Graduate syllabus with readings on governance |

---

## AI Incidents & Failures

Learning from what goes wrong.

- [AI Incident Database](https://incidentdatabase.ai/) — Searchable database of AI failures and harms
- [Optimizing for the Wrong Metric](https://doi.org/10.1016/j.patter.2022.100476) — Thomas & Uminsky (2022), *Patterns*. When metric optimization causes harm.

---

## Domain Applications

AI in specific fields.

### Sports

- [AI for Sports: Technologies and Applications](https://doi.org/10.1016/j.ish.2025.05.001) — Li et al. (2025), *Intelligent Sports and Health*

### Medicine & Health

- [A Guide to Deep Learning in Healthcare](https://doi.org/10.1038/s41591-018-0300-7) — Esteva et al. (2019), *Nature Medicine*

### Software & Society

- [A Silicon Cage?: Qualitative Research in the Era of AI](https://www.cultureofmedicine.org/blog/a-silicon-cage-qualitative-research-in-the-era-of-ai) — Abramson (2023), *Medical Cultures Lab*. Weber's "iron cage" meets AI tools.

---

## Courses & Learning Resources

Structured learning paths for AI governance, ethics, and computational text analysis.

- [Stanford STS 14/CS 134](https://web.stanford.edu/class/sts14/index.html) — Graduate; AI Governance: full syllabus with readings
- [Computational Analysis for Qualitative Data](https://github.com/Computational-Ethnography-Lab/teaching) — Computational Ethnography Lab; workflow, Python toolkits, visualization, bibliography, and practical resources for integrating computational text analysis with qualitative research

---

## Institutional AI Guidelines

University-specific policies for responsible AI use.

| Institution | Resource |
|-------------|----------|
| Rice University | [AI Usage Guidelines](https://oit.rice.edu/ai-usage-guidelines) |
| Stanford University | [Responsible AI](https://uit.stanford.edu/security/responsibleai) |

---

## Contributing

To suggest additions:
1. Fork this repository
2. Add your resource to the appropriate section
3. Include: Title, URL, Author/Year, and 1-sentence description
4. Submit a pull request

---
*Last updated: February 2026*
> Some content in this repository was edited and formatted with assistance from Claude Opus 4.6 (Anthropic).
---

<p align="center">
  <a href="https://github.com/Computational-Ethnography-Lab" target="_blank">
    <img src="https://github.com/Computational-Ethnography-Lab/.github/raw/95529a5a1ffa938274ac5b4b912dbf99e26fd572/profile/images/lab_banner.jpg" alt="Computational Ethnography Lab Banner" width="100%">
  </a>
</p>


