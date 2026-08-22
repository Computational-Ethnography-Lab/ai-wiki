# Everything You Wanted to Know About AI (in social science)
_(But Were Afraid to Ask)_

<p align="center">
  <a href="https://ciisr.rice.edu/" target="_blank">
    <img src="https://github.com/Computational-Ethnography-Lab/Computational-Ethnography-Lab.io/raw/e7ab5b2af6e8b92efa2120b6a12a9176ad3b2944/images/ciisr.png" alt="CIISR" width="100%">
  </a>
</p>

A curated collection of resources for understanding artificial intelligence—from technical foundations to societal implications, and some practical guides.

> **About this wiki**: Companion resource for the "Everything You Wanted to Know About AI But Were Afraid to Ask" event hosted by [CIISR](https://ciisr.rice.edu/)
> Very much in progress...
> Contributions welcome via pull request.

---

## Table of Contents

- [Getting Started: What is AI?](#getting-started-what-is-ai)
- [Dueling Perspectives: AI Optimism vs. Criticism](#dueling-perspectives-ai-optimism-vs-criticism)
- [Social Science Perspectives](#social-science-perspectives)
  - [Overviews & Perspectives](#overviews--perspectives)
  - [Attitudes Toward AI](#attitudes-toward-ai)
  - [LLM-Focused Methods](#llm-focused-methods)
  - [LLM Simulation of Social Agents](#llm-simulation-of-social-agents)
  - [Qualitative Coding Methods (Broader Context)](#qualitative-coding-methods-broader-context)
  - [LLM-Assisted & Large-Scale Qualitative Analysis](#llm-assisted--large-scale-qualitative-analysis)
  - [Additional Resources (adjacent)](#additional-resources-adjacent)
- [Social Science Workflow with AI](#social-science-workflow-with-ai)
- [Responsible AI & Ethics](#responsible-ai--ethics)
- [AI Governance & Regulation](#ai-governance--regulation)
- [AI Incidents & Failures](#ai-incidents--failures)
- [Domain Applications](#domain-applications)
- [Courses & Learning Resources](#courses--learning-resources)
- [Institutional AI Guidelines](#institutional-ai-guidelines)
- [Lab Teaching Materials & Handouts](#lab-teaching-materials--handouts)
- [Key Terms](#key-terms)
  - [Agent & Tooling Terms](#agent--tooling-terms)

---

## Getting Started: What is AI?

> **On Terminology** (Abramson et al. 2026, p. 5):
>
> "*Artificial intelligence (AI) refers to technologies designed to mimic human performance on tasks that historically required human intelligence. This can include recognizing patterns, extracting text from .pdf files, classifying images, summarizing interviews, or generating synthetic content such as manipulated images or text. Some subfields commonly used in qualitative research workflows include machine learning (ML) for analyzing behaviors and cases, natural language processing (NLP) for parsing language data, and computer vision for analyzing images. Large language models (LLMs)—deep learning systems trained on mass-scale text data to predict and/or generate language (GPT is a commercial example)—are a subset of AI.*"
> See Abramson et al. (2026), [Qualitative Research in an Era of Artificial Intelligence](https://www.annualreviews.org/content/journals/10.1146/annurev-soc-011824-104836), Table 1 for a full typology.
> Today the term is often used synonymously with generative Large Language Models (LLMs) like ChatGPT, Claude, and Gemini.

Short, accessible introductions to large language models and AI fundamentals.

- [What is a Large Language Model?](https://www.cloudflare.com/learning/ai/what-is-large-language-model/) — Cloudflare's accessible technical overview
- [What are Large Language Models?](https://www.ibm.com/think/topics/large-language-models) — IBM's introduction to LLMs
- [A Very Gentle Introduction to LLMs without the Hype](https://mark-riedl.medium.com/a-very-gentle-introduction-to-large-language-models-without-the-hype-5f67941fa59e) — Mark Riedl (Georgia Tech); balanced, jargon-free overview

### Practical Guides

- [Claude 101](https://academy.claude.com/courses/claude-101) — Anthropic Academy. Official A–Z course: first conversation, prompting, projects, artifacts, skills, and connected tools.
- [Get started with Claude Cowork](https://support.claude.com/en/articles/13345190-get-started-with-claude-cowork) — Anthropic. Useful for general automations once authorized.
- [Get started with ChatGPT Work](https://learn.chatgpt.com/docs/get-started-with-work) — OpenAI. Delegate multi-step tasks with a reviewable output (decks, spreadsheets, recurring updates).
- [Gemini in Google Workspace](https://workspace.google.com/solutions/ai/) — Google. Gemini built into Gmail, Docs, Sheets, and Meet.

Cowork, ChatGPT Work, and Gemini in Google Workspace are general productivity resources, not guides for sensitive-data pipelines.

- [Best practices for Claude Code](https://code.claude.com/docs/en/best-practices) — Anthropic. Official guide for using Claude Code across files, commands, and parallel sessions.
- [OpenAI Prompt Engineering Guide](https://developers.openai.com/api/docs/guides/prompt-engineering) — Official best practices for GPT models
- [Anthropic Claude Prompt Engineering](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/overview) — Official guide for Claude models
- [Gemini Prompt Engineering Guide](https://ai.google.dev/gemini-api/docs/prompting-strategies) — Official guide for Gemini models
- [Context Engineering Guide](https://www.datacamp.com/blog/context-engineering) — DataCamp; beyond prompts: designing full information flows for AI
- [Ollama Quickstart Guide](https://docs.ollama.com/quickstart) — Run open-source models locally—installation, first model, API basics
- [Responsible AI at Stanford](https://uit.stanford.edu/security/responsibleai) — "Best practices" for AI use in academic settings, with lots of guides.
- [Artificial Intelligence Teaching Guide](https://teachingcommons.stanford.edu/teaching-guides/artificial-intelligence-teaching-guide) — Stanford Teaching Commons. How generative AI works in teaching, plus course policy and assignment design.

### Prompts

- [ChatGPT Prompts for University Educators](https://chatgpt.com/use-cases/university-educators) - Faculty from a dozen disciplines shared prompts they use for teaching and research

---

## Dueling Perspectives: AI Optimism vs. Criticism

Contrasting viewpoints to help you form your own position.

### The Optimist Case

- [One Useful Thing](https://www.oneusefulthing.org/) — Ethan Mollick; AI as collaborative partner; practical applications for knowledge work
- *[Co-Intelligence](https://www.penguinrandomhouse.com/books/741805/co-intelligence-by-ethan-mollick/)* (2024) — Ethan Mollick; book-length treatment of human-AI collaboration
- [AI agents are ‘aeroplanes for the mind’: five ways to ensure that scientists are responsible pilots](https://doi.org/10.1038/d41586-026-00665-y) — Wang (2026), *Nature*. Five practices for using AI agents in scientific work.

### The Critical Case

- [I Set Out to Study Which Jobs Should Be Done by AI](https://www.theguardian.com/commentisfree/2025/jan/21/ai-jobs-human-work-relationship-tech) — Allison Pugh; human connection has limits that AI cannot cross
- *[The Last Human Job](https://press.princeton.edu/books/hardcover/9780691240817/the-last-human-job)* (2024) — Allison Pugh; why certain work requires irreplaceable human qualities
- [Let AI Burn](https://www.wheresyoured.at/let-ai-burn/) — Ed Zitron (2026). The generative-AI industry is a bailout-seeking bubble and should be left to fail.

### The "It's Complicated" Case

- [AI Snake Oil](https://www.normaltech.ai/) — Narayanan & Kapoor; separating genuine capabilities from hype
- [A Guide to Understanding AI as Normal Technology](https://www.normaltech.ai/p/a-guide-to-understanding-ai-as-normal) — Narayanan & Kapoor; AI as evolving technology, not magic

### The Pragmatic Case: Considered Use

- [From Carbon Paper to Code: Crafting Sociology in an Age of AI](https://computationalethnography.org/writing/from-carbon-paper-to-code/) — Corey M. Abramson; AI tools are part of our world now, for better or worse—but they can be repurposed with sociological imagination
- [A Pragmatic Approach to AI in Qualitative Research](https://computationalethnography.org/writing/qualitative-research-in-an-era-of-ai/) — Corey M. Abramson. Short summary of the implications of Abramson et al. (2026), *Annual Review of Sociology*: AI is already in the research stack; a pragmatic approach asks what each tool makes possible and what it may distort, rather than treating use as a simple opt-in or opt-out.

---

## Social Science Perspectives

How social scientists are thinking about AI.

### Overviews & Perspectives

- [Can Generative AI Improve Social Science?](https://www.pnas.org/doi/10.1073/pnas.2314021121) — Bail (2024), *PNAS*. Review of AI applications across survey, experiments, content analysis, agent-based models.
- *[The Ordinal Society](https://www.hup.harvard.edu/books/9780674971141)* — Fourcade & Healy (2024), Harvard University Press. How pervasive measurement, scoring, and ranking by data-driven systems reshape markets, the public sphere, and the self.
- [Start Generating: Harnessing GAI for Sociological Research](https://doi.org/10.1177/23780231241259651) — Davidson (2024), *Socius*. Overview of GAI applications: text classification, image analysis, synthetic media.
- [Qualitative Research in an Era of Artificial Intelligence](https://www.annualreviews.org/content/journals/10.1146/annurev-soc-011824-104836) — Abramson, Prendergast, Li & Dohan (2026), *Annual Review of Sociology* 52(1):35–61. Uses, examples, workflow, and cautions for AI in social science. [doi:10.1146/annurev-soc-011824-104836](https://doi.org/10.1146/annurev-soc-011824-104836)
- [Large AI models are cultural and social technologies](https://doi.org/10.1126/science.adt9819) — Farrell, Gopnik, Shalizi & Evans (2025), *Science*. Treats large models as infrastructure that reshapes culture and social life.
- [Agentic AI and the next intelligence explosion](https://arxiv.org/abs/2603.20639) — Evans, Bratton & Agüera y Arcas (2026), *Science*. What follows if agentic systems start improving themselves.
- [The Society of Algorithms](https://doi.org/10.1146/annurev-soc-090820-020800) — Burrell & Fourcade (2021), *Annual Review of Sociology*. How algorithms mediate social life.

### Attitudes Toward AI

- [Generative AI in Sociological Research: State of the Discipline](https://sociologicalscience.com/articles-v13-3-45/) ([preprint](https://arxiv.org/abs/2511.16884)) — Alvero, Stoltz, Stuhler & Taylor (2025), *Sociological Science*. Survey of sociologists on GenAI use and attitudes.
- [Is it OK for AI to Write Science Papers? Nature Survey Shows Researchers Are Split](https://doi.org/10.1038/d41586-025-01463-8) — Kwon (2025), *Nature* 641. Survey of researchers on AI in manuscript writing; views split, few disclose.
- [Introducing Anthropic Interviewer: What 1,250 Professionals Told Us About Working with AI](https://www.anthropic.com/research/anthropic-interviewer) — Handa et al. (2025), Anthropic Research. AI-led interviews with 1,250 professionals on working with AI. [Public dataset](https://huggingface.co/datasets/Anthropic/AnthropicInterviewer).
- [We Reject the Use of Generative Artificial Intelligence for Reflexive Qualitative Research](https://doi.org/10.1177/10778004251401851) — Jowsey, Braun, Clarke, Lupton, Fine et al. (2025), *Qualitative Inquiry*. Statement that reflexive thematic analysis is a human practice and GenAI does not fit.
- [How latent and prompting biases in AI-generated historical narratives influence opinions](https://doi.org/10.1093/pnasnexus/pgag022) — Shu, Karell, Okura & Davidson (2026), *PNAS Nexus*. How biased AI histories shift readers’ opinions.
- [Generative AI Meets Open-Ended Survey Responses](https://osf.io/preprints/socarxiv/4esdp_v2) — Zhang, Xu & Alvero (2025), *Sociological Methods & Research* 54(3):1197–1242. Participant LLM use in open-ended surveys and the homogenization of responses.

### LLM-Focused Methods

- [Integrating Generative AI into Social Science Research](https://doi.org/10.1177/00491241251339184) — Davidson & Karell (2025), *SMR* 54(3):775-793. Introduction to SMR special issue; discusses measurement, prompting, and simulation themes across ten contributed articles.
- [From Codebooks to Promptbooks](https://doi.org/10.1177/00491241251336794) — Stuhler, Ton & Ollion (2025), *SMR* 54(3):794-848. Extracting information from text with generative LLMs.
- [Scaling Hermeneutics](https://doi.org/10.1140/epjds/s13688-025-00548-8) — Dunivin (2025), *EPJ Data Science* 14(1):28. Hybrid approach preserving interpretive depth while scaling qualitative coding with LLMs; includes codebook adaptation workflow and intercoder reliability benchmarks.
- [Utilizing AI to Facilitate Qualitative Surgical Research](https://doi.org/10.1097/as9.0000000000000577) — Farber, Abramson & Reich (2025), *Annals of Surgery Open* 6(2):e577. AI and qualitative in medicine: uses, cautions, challenges.
- [Large Language Models for Text Classification: From Zero-Shot Learning to Instruction-Tuning](https://doi.org/10.1177/00491241251325243) — Chae & Davidson (2025), *Sociological Methods & Research* 55(2):501-567. Finds that LLMs can code and classify text accurately given appropriate inputs, and that fine-tuned, purpose-built small language models are a competitive alternative—comparably accurate at substantially lower cost.
- [GPT as a Measurement Tool](https://www.nber.org/papers/w34834) — Asirvatham, Mokski & Shleifer (2026), NBER Working Paper 34834. Using GPT for large-scale social measurement. [Software](https://github.com/openai/GABRIEL).
- [Joint Text-and-Image Clustering for Social Science Research](https://hanzhang.xyz/files/Zhang%20and%20Leung%20-%202025%20-%20Joint%20Text-and-Image%20Clustering%20for%20Social%20Science%20Research%20accepted%20version.pdf) — Zhang & Leung (2025), *Sociological Methodology*. Clustering text–image pairs with shared embeddings.
- [AInterviewer](https://aclanthology.org/2026.acl-demo.12/) — Gårdhus, Vitsakis, Frederiksen, Rogers & Carlsen (2026), *ACL*. A platform for designing and running AI-led qualitative interviews.
- [SciSciGPT: advancing human–AI collaboration in the science of science](https://www.nature.com/articles/s43588-025-00906-6) — Shao, Wang, Qian, Pan, Liu & Wang (2025), *Nature Computational Science*. Human–AI system for science-of-science research. [GitHub](https://github.com/Northwestern-CSSI/SciSciGPT).
- [Values in the Wild](https://www.anthropic.com/research/values-wild) — Huang, Durmus, McCain, Handa et al. (2025), Anthropic Research. Values expressed in real-world language-model interactions. [arXiv](https://arxiv.org/abs/2504.15236).
- [Multimodal large language models can make context-sensitive hate speech evaluations aligned with human judgement](https://doi.org/10.1038/s41562-025-02360-w) — Davidson (2025), *Nature Human Behaviour*. Multimodal models for hate-speech judgments that track human context sensitivity.
- [A Turing test of whether AI chatbots are behaviorally similar to humans](https://doi.org/10.1073/pnas.2313925121) — Mei, Xie, Yuan & Jackson (2024), *PNAS*. Behavioral Turing tests of chatbot play in classic games.

### LLM Simulation of Social Agents

- [LLM Social Simulations Are a Promising Research Method](https://proceedings.mlr.press/v267/anthis25a.html) — Anthis, Kozlowski, Evans et al. (2025), *ICML 2025*. Using LLMs to simulate human research subjects—challenges and possibilities.
- [Simulating Subjects](https://doi.org/10.1177/00491241251337316) — Kozlowski & Evans (2025), *SMR* 54(3):1017-1073. Promise and peril of using LLMs to simulate human subjects and social interactions.
- [Machine Bias: How Do Generative Language Models Answer Opinion Polls?](https://doi.org/10.1177/00491241251330582) — Boelaert, Coavoux, Ollion, Petev & Präg (2025), *Sociological Methods & Research* 54(3):1156-1196. Generative LLMs give biased, non-representative answers when used to simulate opinion-poll responses.
- [Synthetic Replacements for Human Survey Data? The Perils of Large Language Models](https://doi.org/10.1017/pan.2024.5) — Bisbee, Clinton, Dorff, Kenkel & Larson (2024), *Political Analysis* 32(4):401-416. LLM-generated survey responses match some averages but distort variation and drift over time—cautioning against replacing human respondents.
- [LLM Agents Grounded in Self-Reports Enable General-Purpose Simulation of Individuals](https://arxiv.org/abs/2411.10109) — Park, Zou, Kamphorst, Egan, Shaw, Hill, Cai, Morris, Liang, Willer & Bernstein (2024). Interview- and survey-grounded agents for 1,052 people.
- [Finetuning LLMs for Human Behavior Prediction in Social Science Experiments](https://aclanthology.org/2025.emnlp-main.1530/) — Kolluri, Wu, Park & Bernstein (2025), *EMNLP*. Fine-tuning on 210 experiments to predict human responses.
- [Large language models can predict the results of social science experiments](https://osf.io/preprints/psyarxiv/3svep_v1) — Ashokkumar, Hewitt, Ghezae & Willer (2026), *Nature*. LLM forecasts of experimental results compared with later human trials.
- [Generative Personality Simulation via Theory-Informed Structured Interview](https://aclanthology.org/2026.eacl-long.82/) — Wang, Zou, Jiang, Chen, Sun, Yi, Xiao & Oswald (2026), *EACL*. Personality simulation from theory-informed interviews.
- [A theory of appropriateness](https://arxiv.org/abs/2412.19010) — Leibo, Vezhnevets, Diaz et al. (2024). Appropriateness as a guide for social behavior in multi-agent systems.

### Qualitative Coding Methods (Broader Context)

- [Computational Grounded Theory](https://doi.org/10.1177/0049124117729703) — Nelson (2020), *SMR* 49(1):3-42. Foundational three-step workflow (pattern detection, refinement, confirmation) for computational text analysis.
- [Flexible Coding of In-depth Interviews](https://doi.org/10.1177/0049124118799377) — Deterding & Waters (2018), *SMR*. Twenty-first-century approach to flexible coding.
- [The Living Codebook](https://doi.org/10.1177/0049124120986185) — Reyes et al. (2021), *SMR*. Documenting the process of qualitative data analysis.
- [Contextual Text Coding](https://doi.org/10.1177/0049124120986191) — Lichtenstein & Rucks-Ahidiana (2023), *SMR* 52(2):606-641. Mixed-methods approach for large-scale textual data with context-specific meanings.
- [Qualitative Coding in the Computational Era](https://osf.io/preprints/socarxiv/gpr4n_v1) — Li, Dohan & Abramson (2021), *Socius* 7. BERT example using local ML and human review for interview text classification. Appendix deals with false positives versus negatives in qualitative analysis. [Related blog](https://cmabramson.com/resources/f/using-machine-learning-with-ethnographic-interviews).
- [Meaning in Hyperspace](https://doi.org/10.1146/annurev-soc-090324-024027) — Boutyline & Arseniev-Koehler (2025), *ARS* 51:89-107. Word embeddings as tools for cultural measurement; contains examples, good overview, links to pieces on measurement and similarity. Relevant to AI (embeddings are a key layer increasingly used in and outside of AI).

### LLM-Assisted & Large-Scale Qualitative Analysis

- ["Conversing" with Qualitative Data: Enhancing Qualitative Research Through Large Language Models](https://doi.org/10.1177/16094069251322346) — Hayes (2025), *International Journal of Qualitative Methods*. Using LLMs as interactive analytic partners to work through qualitative data.
- [Updating "The Future of Coding"](https://doi.org/10.1177/00491241251339188) — Than, Fan, Law, Nelson & McCall (2025), *SMR* 54(3):849-888. Systematic comparison of LLM coding approaches to human coding.
- [A Sociological Approach to Analyzing Satellite and Streetscape Imagery with Generative AI Tools](https://doi.org/10.1177/00491241251339673) — Law & Roberto (2025), *SMR* 54(3). Using generative AI for image analysis in social science research.
- [Listening to the Voices of America](https://doi.org/10.7758/rsf.2024.10.5.01) — Edin, Fields, Grusky, Leskovec, Mattingly, Olson & Varner (2024), *RSF: The Russell Sage Foundation Journal of the Social Sciences*. Large-scale qualitative-interview infrastructure for studying American life, with attention to data collection, sharing, and reuse.
- [Inequality in the Origins and Experiences of Pain](https://doi.org/10.7758/rsf.2024.10.5.02) — Abramson et al. (2024), *RSF* 10(5):34-65. Simplified semantic networks using ML to subset text and visualize alongside in-depth reading.

### Additional Resources (adjacent)

- [De-jargoning Qualitative Coding](https://cmabramson.com/resources/f/qualitative-coding-simplified?blogcategory=Analysis) — Academic resource simplifying qualitative coding concepts (academic cite in Li & Abramson 2025)
- [Sub-setting Qualitative Data for Machine Learning](https://cmabramson.com/resources/f/sub-setting-qualitative-data-for-machine-learning) — Guide to creating comparison sets in QDA
- [Using Machine Learning with Ethnographic Interviews](https://cmabramson.com/resources/f/using-machine-learning-with-ethnographic-interviews) — Blog companion to Li, Dohan & Abramson (2021)
- [Ethnography, Data Transparency, and the Information Age](https://doi.org/10.1146/annurev-soc-090320-124805) — Murphy, Jerolmack & Smith (2021), *Annual Review of Sociology*. Reviews two decades of debate over how ethnographers record, anonymize, and share fieldnotes amid open-science mandates and data-repository requirements.
- [Computational Social Science and Sociology](https://doi.org/10.1146/annurev-soc-121919-054621) — Edelmann, Wolff, Montagne & Bail (2020), *Annual Review of Sociology*. Reviews how computational methods and large-scale digital data are reshaping sociological inquiry.
- [Deep Learning With DAGs](https://doi.org/10.1177/00491241251319291) — Balgi, Daoud, Peña, Wodtke & Zhou (2025), *Sociological Methods & Research*. Causal-graphical deep learning for theories represented as DAGs.
- [Causal Machine Learning](https://link.springer.com/content/pdf/10.1007/s11577-026-01053-0.pdf) — Jeon & Brand (2026), *Kölner Zeitschrift für Soziologie und Sozialpsychologie*. Deductive–inductive framework for causal machine learning in sociology.

---

## Social Science Workflow with AI

Adapted from Abramson et al. (2026), [Qualitative Research in an Era of Artificial Intelligence](https://www.annualreviews.org/content/journals/10.1146/annurev-soc-011824-104836), *Annual Review of Sociology*, Table 2:

|                            | Assistive                                                                                            | Automated                                                                                                                                                                   | Agentic                                                                    |
| -------------------------- | ---------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| **Research Design**        | Citation management, project records, version control                                                | Readability checks, data-assisted sampling, simulating sample-size                                                                                                          | Literature review synthesis                                                |
| **Data Collection**        | Participant/site tracking, hyperlink field artifacts, e-consent capture, digital diary, cloud backup | Multi-media aggregation, sensor/geospatial logging, timestamping, live transcription                                                                                        | Adaptive or event-based SMS prompts                                        |
| **Data Processing**        | Interview transcription, transcript editing, file-format normalization, data versioning              | Scanned docs/images to text, A/V speech-to-text pipelines, de-identification workflows, metadata tagging, quality checks                                                    | Adaptive or event-based reminders                                          |
| **Data Analysis**          | Human coding, quote retrieval, memo writing                                                          | List/regex scripts coding, inter-coder reliability tests, pattern examination, visualizing patterns, counterfactual checks, network overlays, ML classifiers, ML embeddings | LLM-assisted coding, LLM-assisted memos, augmented retrieval, semantic Q&A |
| **Writing & Presentation** | Triangulation, consistency checks, real-time writing collaboration                                   | Retrieval of analytic products, generating visuals, citation formatting, plain-language summaries, accessibility audits                                                     | Assisted writing, assisted editing                                         |
| **Sharing & Preservation** | Replication code, notebooks, codebooks, DOI archiving, long-term preservation                        | Containerized analytic spaces, interactive data portals/APIs, tiered access controls, encryption for sensitive data                                                         | Simulated participants                                                     |

> **Key Insight**: "AI assists but does not replace researcher judgment. The most effective workflows maintain human oversight at decision points while leveraging AI for repetitive or scale-dependent tasks." (Abramson et al. 2026)

For an example of end-to-end workflow and data schema, see [Teaching → Workflow Steps](https://github.com/Computational-Ethnography-Lab/teaching#workflow-steps-end-to-end).

- [A relational approach to agentic AI in social science research](https://rohanalexander.github.io/notes_on_the_future/09-Davidson.html) — Davidson, in Rohan Alexander, *Notes on the Future*. Hybrid human–AI roles and tasks in research projects.

---

## Responsible AI & Ethics

Frameworks for thinking about AI ethics and responsibility.

### Foundational Documents

| Framework                                   | Organization   | Link                                                                                                                               |
| ------------------------------------------- | -------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| AI Risk Management Framework 1.0 (2023)     | NIST           | [nist.gov](https://www.nist.gov/itl/ai-risk-management-framework)                                                                  |
| Generative AI Profile, NIST-AI-600-1 (2024) | NIST           | [nist.gov](https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-generative-artificial-intelligence) |
| EU AI Act (2024)                            | European Union | [artificialintelligenceact.eu](https://artificialintelligenceact.eu/)                                                              |
| Recommendation on the Ethics of AI (2021)   | UNESCO         | [unesco.org](https://www.unesco.org/en/artificial-intelligence/recommendation-ethics)                                              |
| Ethically Aligned Design / AIS              | IEEE           | [standards.ieee.org](https://standards.ieee.org/initiatives/autonomous-intelligence-systems/)                                      |
| Code of Ethics                              | ACM            | [acm.org](https://www.acm.org/code-of-ethics)                                                                                      |

- [The Global Landscape of AI Ethics Guidelines](https://doi.org/10.1038/s42256-019-0088-2) — Jobin, Ienca & Vayena (2019), *Nature Machine Intelligence*. Systematic review of 84 AI-ethics guidelines worldwide, mapping where principles converge (transparency, justice, non-maleficence) and where they diverge.

---

## AI Governance & Regulation

Tracking how governments and institutions are responding to AI.

| Resource                                                                                                                 | Type          | Coverage                                            |
| ------------------------------------------------------------------------------------------------------------------------ | ------------- | --------------------------------------------------- |
| [AI Watch: Global Regulatory Tracker](https://www.whitecase.com/insight-our-thinking/ai-watch-global-regulatory-tracker) | Tracker       | 30+ jurisdictions (EU, US, China, UK, etc.)         |
| [Stanford AI Index Report 2026](https://hai.stanford.edu/ai-index/2026-ai-index-report)                                  | Annual Report | Comprehensive data on AI trends, investment, policy |
| [Stanford STS 14/CS 134: AI Governance](https://web.stanford.edu/class/sts14/index.html)                                 | Course        | Graduate syllabus with readings on governance       |

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

- [A Guide to Deep Learning in Healthcare](https://doi.org/10.1038/s41591-018-0316-z) — Esteva et al. (2019), *Nature Medicine*
- [Dissecting Racial Bias in an Algorithm Used to Manage the Health of Populations](https://doi.org/10.1126/science.aax2342) — Obermeyer, Powers, Vogeli & Mullainathan (2019), *Science*. A widely deployed commercial health-care algorithm systematically underestimated illness severity in Black patients—a concrete case of how optimization targets can encode structural racism.

### Software & Society

- [Algorithmic Control in Platform Food-Delivery Work](https://doi.org/10.1177/2378023119870041) — Griesbach, Reich, Elliott-Negri & Milkman (2019), *Socius*. Empirical study of how delivery platforms use algorithmic management to direct and discipline labor.
- [When Being a Data Annotator Was Not Yet a Job](https://doi.org/10.1177/23780231241259617) — Li (2024), *Socius* 10. Traces the laboratory origins of "dispersible labor" — the hidden human image-labeling work behind computer-vision AI — showing how data annotation became a dispersed, low-status job.
- [From Conflict to Cohesion](https://osf.io/preprints/socarxiv/umh5n_v2) — Yeaton, Anshuman & Srivastava (2026), *American Journal of Sociology* 131(6):1397–1465. Structural similarity and uncivil discourse in polarized Reddit groups.
- [Artificial Intelligence at Work](https://purl.stanford.edu/rf958bq8885) — Karunakaran, Lebovitz, Narayanan & Rahman (2025), *Academy of Management Annals* 19(2):693–735. How AI changes workplace inequality.

---

## Courses & Learning Resources

Structured learning paths for AI governance, ethics, and computational text analysis.

- [Stanford STS 14/CS 134](https://web.stanford.edu/class/sts14/index.html) — Graduate; AI Governance: full syllabus with readings

---

## Institutional AI Guidelines

University-specific policies for responsible AI use.

| Institution         | Resource                                                          |
| ------------------- | ----------------------------------------------------------------- |
| Rice University     | [AI Usage Guidelines](https://tss.rice.edu/ai-usage-guidelines)   |
| Stanford University | [Responsible AI](https://uit.stanford.edu/security/responsibleai) |

---

## Lab Teaching Materials & Handouts

Computational Ethnography Lab materials and related publications, gathered in one place.

- [Computational Analysis for Qualitative Data](https://github.com/Computational-Ethnography-Lab/teaching) — Lab teaching repository: workflow, Python toolkits, visualization, and bibliography for integrating computational text analysis with qualitative research.
- [CMAP Visualization Toolkit](https://github.com/Computational-Ethnography-Lab/cmap_visualization_toolkit) — Open-source Python toolkit for visualizing patterns in qualitative text data: word clouds, t-SNE semantic maps, word/code heatmaps, and semantic networks. Runs locally (secure) or in Colab.
- [Qualitative Research in an Era of Artificial Intelligence](https://www.annualreviews.org/content/journals/10.1146/annurev-soc-011824-104836) — Abramson, Prendergast, Li & Dohan (2026), *Annual Review of Sociology* 52(1):35–61. Uses, examples, workflow, and cautions for AI in social science. [doi:10.1146/annurev-soc-011824-104836](https://doi.org/10.1146/annurev-soc-011824-104836)
- [The Promises of Computational Ethnography](https://doi.org/10.1177/1466138117725340) — Abramson, Joslyn, Rendle, Garrett & Dohan (2018), *Ethnography* 19(2):254–284. How computational tools extend ethnographic analysis.
- [Ethnography and Machine Learning: Synergies and New Directions](https://doi.org/10.1093/oxfordhb/9780197653609.013.36) — Li & Abramson (2025), in *The Oxford Handbook of the Sociology of Machine Learning*, pp. 245–272.

---

## Key Terms

Plain-language definitions of terms you encounter when using AI in research. Each term links a general reference plus an independent source.

> **Scope:** these Key Terms cover AI, machine-learning, and agent/tooling vocabulary. For methods vocabulary specific to computational qualitative analysis (e.g. computational ethnography, scaling up/down, HHMLA), see the [Teaching → Glossary](https://github.com/Computational-Ethnography-Lab/teaching#iv-glossary-selected).

**Foundations**

- **Model** — A mathematical system that maps inputs (text, images, numbers) to outputs such as labels, predictions, or generated text. ([Wikipedia](https://en.wikipedia.org/wiki/Machine_learning), [Snowflake](https://www.snowflake.com/en/artificial-intelligence/machine-learning/models/))
- **Training** — Adjusting a model using data so its outputs become more accurate or useful for a task. ([Wikipedia](https://en.wikipedia.org/wiki/Training,_validation,_and_test_data_sets), [Google](https://developers.google.com/machine-learning/intro-to-ml/what-is-ml))
- **Dataset** — A collection of examples used to train or evaluate a model. ([Wikipedia](https://en.wikipedia.org/wiki/Data_set), [Google](https://developers.google.com/machine-learning/crash-course/overfitting/dividing-datasets))
- **Parameters (weights)** — The internal values of a model, adjusted during training, that determine how it transforms inputs into outputs. ([Wikipedia](https://en.wikipedia.org/wiki/Neural_network_%28machine_learning%29), [Google](https://developers.google.com/machine-learning/glossary#weight))
- **Prediction** — The output a model produces, such as a category, number, probability, or piece of text. ([Wikipedia](https://en.wikipedia.org/wiki/Predictive_modelling), [Google](https://developers.google.com/machine-learning/glossary/fundamentals))
- **Inference** — Using a trained model to produce outputs or predictions on new inputs. ([Wikipedia](https://en.wikipedia.org/wiki/Inference_%28machine_learning%29), [IBM](https://research.ibm.com/blog/AI-inference-explained))

**Training & evaluation**

- **Training set / test set** — Data used to teach a model, versus separate data used to evaluate how well it performs on new, unseen examples. ([Wikipedia](https://en.wikipedia.org/wiki/Training,_validation,_and_test_data_sets), [Google](https://developers.google.com/machine-learning/crash-course/overfitting/dividing-datasets))
- **Overfitting** — When a model performs well on its training data but poorly on new data because it learned detail that does not generalize. ([Wikipedia](https://en.wikipedia.org/wiki/Overfitting), [Google](https://developers.google.com/machine-learning/crash-course/overfitting/overfitting))
- **Evaluation metric** — A quantitative measure of model performance, such as accuracy, precision, or recall. ([Wikipedia](https://en.wikipedia.org/wiki/Evaluation_of_binary_classifiers), [Google](https://developers.google.com/machine-learning/crash-course/classification/accuracy-precision-recall))

**Model types & architectures**

- **Neural network** — A model built from many connected layers of simple units, designed to learn complex patterns in data. ([Wikipedia](https://en.wikipedia.org/wiki/Neural_network_%28machine_learning%29), [MIT](https://news.mit.edu/2017/explained-neural-networks-deep-learning-0414))
- **Deep learning** — Machine learning based on neural networks with many layers. ([Wikipedia](https://en.wikipedia.org/wiki/Deep_learning), [AWS](https://aws.amazon.com/what-is/deep-learning/))
- **Transformer** — A neural-network architecture well suited to sequences such as text, and the basis of modern language models. ([Wikipedia](https://en.wikipedia.org/wiki/Transformer_%28deep_learning_architecture%29), [NVIDIA](https://blogs.nvidia.com/blog/what-is-a-transformer-model/))
- **Foundation model (base model)** — A general-purpose model trained on broad data before any task-specific fine-tuning or customization. ([Wikipedia](https://en.wikipedia.org/wiki/Foundation_model), [AWS](https://aws.amazon.com/what-is/foundation-models/))
- **Large language model (LLM)** — A deep-learning system trained on mass-scale text data to predict and/or generate language; a subset of AI. ([Wikipedia](https://en.wikipedia.org/wiki/Large_language_model), [IBM](https://www.ibm.com/think/topics/large-language-models))
- **Small language model (SLM)** — A language model with far fewer parameters than a large one, designed to run efficiently on modest or local hardware (e.g., a desktop or in-house server) at lower cost. ([Wikipedia](https://en.wikipedia.org/wiki/Small_language_model); Abramson et al. 2026 run local SLMs for secure coding, *[ARS](https://doi.org/10.1146/annurev-soc-011824-104836)*)
- **Attention / self-attention** — A mechanism that lets a model weigh which parts of a sequence matter most relative to each other; the core operation behind transformers. ([Wikipedia](https://en.wikipedia.org/wiki/Attention_%28machine_learning%29), [Google](https://developers.google.com/machine-learning/glossary#attention))

**Language-model terms**

- **Token** — A unit of text a language model processes, which may be a whole word, part of a word, or a symbol. ([Wikipedia](https://en.wikipedia.org/wiki/Byte-pair_encoding), [Google](https://developers.google.com/machine-learning/crash-course/llm))
- **Pretraining** — An initial training phase in which a model learns general patterns from a very large, broad dataset. ([Wikipedia](https://en.wikipedia.org/wiki/Generative_pre-trained_transformer), [Databricks](https://www.databricks.com/blog/llm-pre-training-and-custom-llms))
- **Fine-tuning** — Additional training on a more specific dataset to adapt a model to particular tasks or goals. ([Wikipedia](https://en.wikipedia.org/wiki/Fine-tuning_%28deep_learning%29), [OpenAI](https://developers.openai.com/api/docs/guides/model-optimization))
- **Temperature** — A setting that controls how random or conservative a model's outputs are; lower values are more predictable, higher values more varied. ([Wikipedia](https://en.wikipedia.org/wiki/Softmax_function), [Vellum](https://www.vellum.ai/llm-parameters/temperature))
- **Deterministic vs. stochastic output** — Deterministic: the same input always yields the same output. Stochastic: outputs can vary due to randomness in generation. ([Wikipedia](https://en.wikipedia.org/wiki/Deterministic_algorithm), [NIST](https://csrc.nist.gov/glossary/term/deterministic_algorithm))
- **Custom GPTs** — User-configured versions of a general model that bundle custom instructions, documents, or tools for a particular task. ([Wikipedia](https://en.wikipedia.org/wiki/ChatGPT), [MIT Sloan](https://mitsloanedtech.mit.edu/ai/tools/custom-gpts-at-mit-sloan-a-comprehensive-guide/))
- **GPT (generative pre-trained transformer)** — A transformer-based large language model trained to generate language (e.g., ChatGPT). ([Wikipedia](https://en.wikipedia.org/wiki/Generative_pre-trained_transformer), [Google](https://developers.google.com/machine-learning/crash-course/llm))
- **Quantization** — Reducing the numerical precision of a model's weights (e.g., 32-bit to 8-bit) to shrink memory use and speed up inference, often to run models on local or limited hardware. ([Wikipedia](https://en.wikipedia.org/wiki/Quantization_%28signal_processing%29), [Hugging Face](https://huggingface.co/docs/optimum/en/concept_guides/quantization))
- **Distillation (knowledge distillation)** — Training a smaller "student" model to reproduce the behavior of a larger "teacher" model, a common way small language models are built. ([Wikipedia](https://en.wikipedia.org/wiki/Knowledge_distillation), [Google Research](https://research.google/blog/distilling-step-by-step-outperforming-larger-language-models-with-less-training-data-and-smaller-model-sizes/))

**Prompts, context & interaction**

- **Prompt** — The input given to a model, such as a question or instruction, that guides its output. ([Wikipedia](https://en.wikipedia.org/wiki/Prompt_engineering), [Microsoft](https://learn.microsoft.com/en-us/dotnet/ai/conceptual/prompt-engineering-dotnet))
- **Prompt engineering** — The practice of designing prompts to get more useful, accurate, or reliable outputs from a model. ([Wikipedia](https://en.wikipedia.org/wiki/Prompt_engineering), [OpenAI](https://developers.openai.com/api/docs/guides/prompt-engineering))
- **System prompt (instruction)** — Special input that sets a model's role, behavior, or constraints (for example, "be concise" or "answer as a tutor"). ([Wikipedia](https://en.wikipedia.org/wiki/Large_language_model), [Google](https://firebase.google.com/docs/ai-logic/system-instructions))
- **Zero-shot / few-shot** — Asking a model to do a task with no examples (zero-shot) versus giving a few examples in the prompt to guide it (few-shot). ([Wikipedia](https://en.wikipedia.org/wiki/Prompt_engineering), [Microsoft](https://learn.microsoft.com/en-us/dotnet/ai/conceptual/zero-shot-learning))
- **Context / context window** — The information a model considers when generating a response (the prompt plus prior text), and the maximum amount it can hold at once; longer material may be truncated or summarized. ([Wikipedia](https://en.wikipedia.org/wiki/Context_window), [Google](https://ai.google.dev/gemini-api/docs/long-context))

**Limits & risks**

- **Hallucination** — When a model generates information that appears coherent but is incorrect or not grounded in its data. ([Wikipedia](https://en.wikipedia.org/wiki/Hallucination_%28artificial_intelligence%29), [TechTarget](https://www.techtarget.com/whatis/definition/AI-hallucination))
- **Bias** — Systematic patterns in a model's outputs that reflect biases in its data, labels, or design. ([Wikipedia](https://en.wikipedia.org/wiki/Algorithmic_bias), [NIST](https://www.nist.gov/news-events/news/2022/03/theres-more-ai-bias-biased-data-nist-report-highlights))
- **Alignment** — Efforts to ensure a model's behavior matches human intentions, values, or guidelines, often through added training and feedback. ([Wikipedia](https://en.wikipedia.org/wiki/AI_alignment), [IBM](https://research.ibm.com/blog/what-is-alignment-ai))

**Data & modalities**

- **Modality** — A type of data, such as text, images, audio, or video. ([Wikipedia](https://en.wikipedia.org/wiki/Multimodal_learning), [Label Studio](https://labelstud.io/learningcenter/understanding-data-modalities-a-guide-to-the-types-of-data-that-power-modern-ai/))
- **Multimodal model** — A model that can work with more than one type of data, such as text and images together. ([Wikipedia](https://en.wikipedia.org/wiki/Multimodal_learning), [NVIDIA](https://www.nvidia.com/en-us/glossary/vision-language-models/))

**Retrieval & external knowledge**

- **Retrieval-augmented generation (RAG)** — A setup where a model retrieves relevant information from a document collection or database and uses it when generating a response. ([Wikipedia](https://en.wikipedia.org/wiki/Retrieval-augmented_generation), [IBM](https://research.ibm.com/blog/retrieval-augmented-generation-RAG))
- **Embedding** — A numerical representation of text or images that captures meaning so similar items can be compared or searched. ([Wikipedia](https://en.wikipedia.org/wiki/Embedding_%28machine_learning%29), [Google](https://cloud.google.com/blog/topics/developers-practitioners/meet-ais-multitool-vector-embeddings))
- **Vector database** — A database designed to store and search embeddings, commonly used for semantic search and document retrieval. ([Wikipedia](https://en.wikipedia.org/wiki/Vector_database), [Microsoft](https://learn.microsoft.com/en-us/fabric/real-time-intelligence/vector-database))
- **Semantic search** — Searching by meaning rather than exact keywords, often using embeddings to find conceptually similar text. ([Wikipedia](https://en.wikipedia.org/wiki/Semantic_search), [Elastic](https://www.elastic.co/what-is/semantic-search))
- **Grounding** — Using specific external information (documents, databases) so outputs rest on known sources rather than only the model's internal patterns. ([Wikipedia](https://en.wikipedia.org/wiki/Retrieval-augmented_generation), [Google](https://cloud.google.com/blog/products/ai-machine-learning/how-vertex-ai-grounding-helps-build-more-reliable-models))

### Agent & Tooling Terms

More technical terms from agent-based and multi-agent tooling.

- **Agent** — A system that uses a model to decide what actions to take, sometimes over multiple steps, such as calling tools, searching, writing files, or asking follow-up questions. ([Wikipedia](https://en.wikipedia.org/wiki/AI_agent), [AWS](https://aws.amazon.com/what-is/ai-agents/))
- **Tool use (function calling)** — A setup where a model can trigger external tools — a calculator, database query, web search, or code execution — as part of completing a task. ([Wikipedia](https://en.wikipedia.org/wiki/Large_language_model), [OpenAI](https://developers.openai.com/api/docs/guides/function-calling))
- **Context engineering** — Deliberately choosing what information a model is given for a task, and what is kept out, so its limited working memory stays focused; it treats the context window as a scarce resource to curate rather than fill. ([Wikipedia](https://en.wikipedia.org/wiki/Prompt_engineering), [Elastic](https://www.elastic.co/search-labs/blog/context-engineering-overview))
- **Skills (agent skills)** — A reusable, packaged procedure an AI assistant loads on demand, turning a workflow you would otherwise re-explain each time into a named, repeatable capability stored as files. ([Microsoft](https://learn.microsoft.com/en-us/agent-framework/agents/skills), [Sysdig](https://www.sysdig.com/learn-cloud-native/what-are-agent-skills))
- **MCP (Model Context Protocol)** — An open standard that lets an AI assistant connect to outside tools and data through a common interface rather than a one-off integration per tool; a connected tool is an "MCP server." ([Wikipedia](https://en.wikipedia.org/wiki/Model_Context_Protocol), [OpenAI](https://openai.github.io/openai-agents-python/mcp/))
- **Subagent** — A separate, bounded AI worker that a lead agent delegates a focused piece of a task to, running in its own context so subtask detail does not clutter the main work. ([VS Code](https://code.visualstudio.com/docs/agents/run/subagents), [Gemini CLI](https://geminicli.com/docs/core/subagents/))
- **Orchestrator** — The lead agent, or person acting as one, that coordinates a task by restating the objective, delegating to subagents, then verifying and reconciling results, with the verifier kept separate from the builder. ([Wikipedia](https://en.wikipedia.org/wiki/AI_agent), [Microsoft](https://learn.microsoft.com/en-us/agents/architecture/multi-agent-orchestrator-sub-agent))
- **Harness (agent harness)** — The software scaffolding around a model that manages what context it sees, which tools it may use, when it pauses for human approval, and how its output is checked. ([DataCamp](https://www.datacamp.com/blog/agent-harness), [Hugging Face](https://huggingface.co/blog/agent-glossary))

---

## Contributing

To suggest additions:

1. Fork this repository
2. Add your resource to the appropriate section
3. Include: Title, URL, Author/Year, and 1-sentence description
4. Submit a pull request

---

*Last updated: August 2026*

> Some content in this repository was edited and formatted with assistance from Claude Opus 4.8 (Anthropic).

---

<p align="center">
  <a href="https://github.com/Computational-Ethnography-Lab" target="_blank">
    <img src="https://github.com/Computational-Ethnography-Lab/.github/raw/95529a5a1ffa938274ac5b4b912dbf99e26fd572/profile/images/lab_banner.jpg" alt="Computational Ethnography Lab Banner" width="100%">
  </a>
</p>
