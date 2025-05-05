---
title: "VCH overview"
format:
  revealjs: default
  pdf: default
  pptx: default
---



:::::::::::::: {.columns}
::: {.column width="50%"}
# Project Overview

<mark>📘 Lessons Learned:</mark>

- Structure matters more than ambition  
- Constraints reveal priorities  
- Students need working AI-tools, not systems
- Students need active support to work with tools, not a workshop.
- Failures teach if documented  
- Local infra works, but needs support  
- Collaboration drives progress

:::
::: {.column width="50%"}

<mark>🧠 Skills & What’s Working:</mark>

- Full AI stack deployment (OpenWebUI, Qdrant, n8n)  
- Reproducible R workflows (RStudio, Docker)  
- Real-use workshops + mentorship  
- Proposal writing and stakeholder engagement  
- Active collaborations gaining traction

:::
::::::::::::::

::: notes
From trial to traction: this project has turned lessons into systems, failures into frameworks, and ideas into infrastructure.
:::


## Current Workstreams and Collaborations

:::::::::::::: {.columns}
::: {.column width="50%"}

<mark>🔧 Infrastructure:</mark>  
- VCH LLM stack (OpenWebUI, Qdrant, n8n)  
- DAT Linux for reproducible setups  
- Nextcloud for shared docs  
- RStudio workflows in progress

<mark>📚 Education & Workshops:</mark>  
- AI workshops based on real failures  
- Mentoring students with ready-to-use tools  
- Focus on prompting over building  
- Toward an AI learning track

:::
::: {.column width="50%"}

<mark>🌐 R&D:</mark>  
- Tool testing (Far.AI, AI Scientist)  
- R-based reproducibility pilots  
- Mapping AI for research workflows

<mark>🤝 Collaborations:</mark>  
- AgUnity (Clearroots) Stefan   
- Thomas Mazuiri (VCH-Infra),
- Torsten Raudssus (Supplylens), Thomas Dik
- SCF NICE (grant/pilot)  Luka Westergeest


:::
::::::::::::::


::: notes
This slide shows that we're not just planning — we’re actively building. Technical systems are running, educational content is being delivered, and external partnerships are forming. We’re laying the groundwork for scale, credibility, and cross-disciplinary impact.
:::
---

## Agenda

1. VCH Infrastructure (LLM for Students)  
2. VCH Infrastructure (General Tooling)  
3. VCH Infrastructure (Reproducible Research)  
4. Practical AI Use Cases & Workshops  
5. AI-Supported Student Projects  
6. SupplyLens (formerly Knopenkoning)  
7. Experimental Tool Testing (AI Scientist, Far.AI)  
8. ClearRoots (SCF NICE Project)  
9. ClearPaper (SCF NICE Proposal)  
10. Key Collaborations  

---

## 1. VCH Infrastructure – LLM for Students

:::::::::::::: {.columns}
::: {.column width="50%"}

<mark>🎯 Goal:</mark>  
Enable students to use local LLMs for assignments, feedback, and learning.

<mark>🔒 Why:</mark>  
A local LLM stack enables:

- Secure research with real data
- No reliance on cloud services
- Independent student experimentation

<mark>✅ Accomplished:</mark>

- Running OpenWebUI-based LLM environment
- Hosted on a local-controlled server
- Integrated tools: Qdrant, n8n, pgvector, dashboards

<mark>🧠 Now Possible:</mark>

- Memory-enabled AI workflows

More info: 
- [VCH-Infra](https://github.com/Value-Chain-Hackers/VCH-Infra)

:::
::: {.column width="50%"}

<mark>🚀 Next Steps:</mark>

- Broader student adoption
- Classroom integration
- Real use case development

<mark>🆘 Help Needed:</mark>

- Budget for <mark>TOKENS</mark> to run larger models
- Personal costs are unsustainable
- Need focused hours to maintain and improve
- Requesting support and validation of direction

:::
::::::::::::::

::: notes
This project lays the technical foundation for responsible student-AI interaction. It reduces reliance on cloud services and enables advanced, privacy-safe research workflows. With a small investment, we can turn this into a standard part of classroom education.
:::
---

## 2. VCH Infrastructure – General Tools

:::::::::::::: {.columns}
::: {.column width="50%"}

<mark>🎯 Goal:</mark>  
Provide infrastructure with built-in tools so students can quickly ideate and prototype.

<mark>⚙️ Why:</mark>  
A seamless environment helps students move from ideas to experiments without technical barriers.
<mark>✅ Accomplished:</mark>

- AI stack fully deployed
- Nextcloud environment live
- DAT Linux system in full testing

:::
::: {.column width="50%"}

<mark>🚀 Next Steps:</mark>

- Tighter integration of AI tools with DAT Linux
- Enable AI features inside Nextcloud
- Launch a documentation server using Nextcloud

<mark>🆘 Help Needed:</mark>

- Hands-on testing of tools and flows
- Feedback on missing functionality
- Time to improve reliability
- Support to validate that this is the right direction

:::
::::::::::::::

::: notes
This setup is about lowering the threshold for student experimentation. We now have a local cloud, open AI tools, and a Linux-based desktop system under one roof. With testing and refinement, this becomes a plug-and-play environment for future student-driven supply chain solutions.
:::
---


## 3. VCH Infrastructure – Reproducible Research (incl. DAT Linux)

:::::::::::::: {.columns}
::: {.column width="50%"}

<mark>🎯 Goal:</mark>  
Enable researchers to build, test, and share repeatable experiments — including data, code, and results.

<mark>🔍 Why:</mark>

- Reproduce prior research
- Run simulations
- Build openly on others' work  
  AI is most useful in research when workflows are reproducible and verifiable.

<mark>✅ Accomplished:</mark>

- Stack deployable with DAT Linux, Docker, systemd
- RStudio Server tested and operational

:::
::: {.column width="50%"}

<mark>🚀 Next Steps:</mark>

- Develop integrated workflows with RStudio
- Learn and apply data stewardship practices

<mark>🆘 Help Needed:</mark>

- A real past project to rebuild and reproduce in R
- Time to prototype and document workflows
- Support to ensure this path aligns with our research goals

:::
::::::::::::::

::: notes
This is about making research replicable, auditable, and extensible. With this setup, students and researchers can package their work in a form that others can immediately reuse or rerun. It’s a key step toward making our lab academically credible and open-source ready.
:::
More info: 
- [VCH-Infra](https://github.com/Value-Chain-Hackers/VCH-Datasharing)


---

## 4. Practical AI Use Cases & Workshops


:::::::::::::: {.columns}
::: {.column width="50%"}

<mark>🎯 Goal:</mark>  
Teach students how to use AI tools effectively — with a clear understanding of their limitations.

<mark>⚠️ Why:</mark>  
AI is overhyped. In practice:

- It makes mistakes
- Lacks reasoning and contextual awareness
- Struggles with memory and coherence  
  Students must learn to test, verify, and control AI systems — not blindly trust them.

<mark>✅ Accomplished:</mark>

- Workshop repo created
- First sessions delivered
- Failures (e.g. Knopenkoning, Inchainge) revealed limitations

:::
::: {.column width="50%"}

<mark>🚀 Next Steps:</mark>

- Translate IBM-based workshop into practical applications
- Teach "data-to-reality" thinking
- Run an ongoing workshop series with feedback loops

<mark>🆘 Help Needed:</mark>

- Integration and network engineers
- Students and testers to challenge tools
- Regular AI meetups and testing sessions
- Hands-on collaborators to co-build use cases

:::
::::::::::::::
---

## 5. AI-Supported Student Projects
Examples: 
- [VCH-Lithium](https://value-chain-hackers.github.io/LiCycle-AI/)
- [VCH-BCM](https://github.com/Value-Chain-Hackers/LiCycle-AI)

:::::::::::::: {.columns}
::: {.column width="50%"}

<mark>🎯 Goal:</mark>  
Support student-led projects by giving them AI tools that just work — not expecting them to build infrastructure.

<mark>💡 Why:</mark>  
As Maxime correctly noted: most students can't build their own AI pipelines.  
Instead, we:

- Provide working, end-user-facing tools (not chatbots)
- Focus on prompting, saving, and processing
- Teach integration with commercial and internal systems  
  This approach delivers value — not confusion.

<mark>✅ Accomplished:</mark>

- Built 2 functional AI-driven websites
- Far surpassed what students could do solo
- Demonstrated how AI mentorship accelerates outcomes

:::
::: {.column width="50%"}

<mark>🚀 Next Steps:</mark>

- Showcase student outcomes
- Formalize an AI mentorship pathway
- Identify new use cases with real needs

<mark>🆘 Help Needed:</mark>

- Stop limiting expert-student interaction
- Start providing token budgets for large model usage
- Stop comparing this and Chris to OpenAI — that's unrealistic
- Start letting external experts interface (e.g. via Discord)
- Start treating Value Chain Hackers as a formal initiative: KvK, domain, mandate
- Start giving Chris a team of IT + business students to scale AI work

:::
::::::::::::::
 
---

## 6. SupplyLens (formerly Knopenkoning)

Examples: 
- [VCH-Supplylens](https://github.com/Value-Chain-Hackers/SupplyLens)
- [Presentation](https://rpubs.com/kamitor/Supplylens23)
:::::::::::::: {.columns}
::: {.column width="50%"}

<mark>🎯 Goal:</mark>  
Visualize complex supply chains using AI, ESG data, and graph technology.

<mark>📌 Why:</mark>

- Supports CSRD/CSDDD compliance
- Enables supply chain risk mapping
- Provides actionable insights into real complexity

<mark>⏳ Why Now:</mark>

- Lessons learned from previous attempt (Sebastien)
- Renewed clarity and realistic expectations
- Strong community interest
- A grounded, feasible new approach

<mark>✅ Accomplished:</mark>

- Architecture and direction redesigned
- Demo + repo available: 
  - GitHub
  - Demo

:::
::: {.column width="50%"}

<mark>🚀 Next Steps:</mark>

- Greenlight to begin ideation
- Hours allocated for focused development
- Permission to form a dedicated Scrum team

<mark>🆘 Help Needed:</mark>

- Approval to bring in trusted external contributors (free)
- Spin this off as its own initiative (KvK, domain, mandate)
- Budget (< €5K) for prototyping and infrastructure
- Space for experimentation with external partners

:::
::::::::::::::

---

## 7. Experimental Tool Testing – AI Scientist, Far.AI

:::::::::::::: {.columns}
::: {.column width="50%"}

<mark>🔬 Goal:</mark>  
Explore cutting-edge AI tools that support scientific workflows — including multi-step reasoning and automated experimentation.

<mark>🌐 Why:</mark>

- Keep Windesheim connected to frontier AI developments
- Investigate tools that can: 
  - Simulate cyber attacks
  - Assist in generating PhD-level content
  - Automate complex reasoning chains  
    These tools may redefine how we approach research workflows.

<mark>✅ Accomplished:</mark>

- Reviewed AI Scientist and Far.AI initiatives
- Identified high-potential capabilities
- Repository bookmarked: 
  - GitHub – AI Scientist (aci)

:::
::: {.column width="50%"}

<mark>🚀 Next Steps:</mark>

- Test 3 key tools to assess research potential
- Identify barriers, limitations, and integration opportunities

<mark>🆘 Help Needed:</mark>

- Budget for tokens to properly test and evaluate the tools

:::
::::::::::::::

::: notes
This initiative keeps us ahead of the curve in research tech. While not production-ready, these experimental tools offer a glimpse into how AI might eventually support fully automated or guided scientific inquiry. We should test now — and decide where to engage deeper.
:::

---
 
## 8. Project Proposal – ClearRoots
Examples: 
- [VCH-ClearRoots](https://github.com/Value-Chain-Hackers/ClearRoots)
:::::::::::::: {.columns}
::: {.column width="50%"}

<mark>🎯 Goal:</mark>  
Build a digital platform to help smallholder cooperatives and EU SME importers comply with EU sustainability laws (CSRD, CSDDD, EUDR).

<mark>⚙️ How It Works:</mark>

- Data collected via a multilingual, offline-capable mobile app
- Time-stamped data stored on AgUnity’s blockchain
- App guides users to complete EU-aligned documentation
- Importers receive ready-to-submit compliance dossiers

<mark>📍 Status:</mark>

- Core logic and user roles drafted
- Documentation flow + pilot framework outlined
- Initial partners: AgUnity, Windesheim, SCF NICE
- Pitch deck and 1-pager in first draft

:::
::: {.column width="50%"}

<mark>🌍 Why It Matters:</mark>

- EU laws demand documentation smallholders can’t provide
- Importers lack accessible tools for compliance
- This platform bridges the gap — without exclusion or greenwashing

<mark>🆘 Help Needed:</mark>

- Funding or co-development support
- Help turning this into a grant proposal
- A grant writer or partner to help push this forward

:::
::::::::::::::

::: notes
ClearRoots bridges regulatory pressure with practical tech. It empowers both sides of the supply chain with credible documentation — not token checklists. We're ready to move, and we’re aligned with real partners. What we need now is momentum and backing.
:::

---

## 9. Project Proposal – ClearPaper
Examples: 
- [VCH-ClearRoots](https://github.com/Value-Chain-Hackers/ClearPaper)
:::::::::::::: {.columns}
::: {.column width="50%"}

<mark>📄 Goal:</mark>  
Create practical, standardized templates to help cooperatives, importers, and other actors comply with EU sustainability laws (CSRD, CSDDD, EUDR).

<mark>🌍 Why It Matters:</mark>

- No shared definition of “compliant documentation”
- Uncertainty for importers
- Exclusion of smallholders without expert support
- ClearPaper enables trustable, scalable compliance

<mark>📍 Current Status:</mark>

- Legal mapping and validation discussions started with Windesheim and SCF NICE

:::
::: {.column width="50%"}

<mark>🛠️ How It Works:</mark>  
Each template would:

- Link directly to relevant EU legal clauses
- Be available in Word, LaTeX, and JSON formats
- Adapt to national implementations and local languages
- Optionally integrate with platforms like AgUnity

<mark>🆘 Help Needed:</mark>

- Collect feedback to strengthen a grant proposal
- Support turning this into a fundable project
- <mark>We need a grant writer</mark>

:::
::::::::::::::

::: notes
ClearPaper transforms legal ambiguity into usable tools. It empowers smallholders and de-risks compliance for importers. Without clear templates, compliance is guesswork. This project builds clarity, confidence
:::
---

## Bi-Ronald: Automated Survey Reporting Platform

:::::::::::::: {.columns}
::: {.column width="50%"}

<mark>🎯 Purpose:</mark>  
Streamline survey workflows by automating response collection, analysis, and personalized report generation using open-source tools on self-hosted infrastructure.

<mark>🛠️ How It Works:</mark>  
- Participants complete a multi-step survey.
- Responses are securely stored in a local database.
- Automated workflows generate customized reports (PDF/HTML).
- Reports are emailed to participants.
- Data is prepared for structured analysis via dashboards or custom analytics.

:::
::: {.column width="50%"}

<mark>💡 Why It Matters:</mark>  
- Eliminates manual data processing and report generation.
- Ensures data privacy by avoiding external cloud services.
- Enhances efficiency in research and educational settings.

<mark>🔗 Repository:</mark>  
- [GitHub – Bi-Ronald](https://github.com/Value-Chain-Hackers/Bi-Ronald)

:::
::::::::::::::

::: notes
Bi-Ronald offers a scalable solution for automating survey processes, providing immediate, personalized feedback to participants while maintaining data control and privacy.
:::


## 11. Key Collaborations

- [Thomas Dik](https://www.linkedin.com/in/thomas-dik-2538392b/) – AI tooling and cloud architecture  
- Ronald de Boer – Business Intelligence, Power BI integration  
- Luka Westgeest – SCF, ClearRoots & ClearPaper  
- Stefan Barrett (AG-Unity CTO) – Document processing logic  
- Iivo Salmi & Raul Raus – Trusted EU infrastructure research - Finland. 
