---
title: "VCH overview"
format:
  revealjs: default
  pdf: default
  pptx: default
---

# Project Overview  
## Current Workstreams and Collaborations

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

<mark>Goal:</mark> Enable students to use local LLMs for assignments, feedback, and learning.

<mark>Why:</mark> A local LLM stack lets students perform advanced supply chain research securely and independently, using real data without relying on external cloud services.

<mark>Accomplished:</mark>
- Fully running OpenWebUI-based LLM environment  
- Hosted on our own local-controlled server  
- Integrated tools: Qdrant, n8n, pgvector, dashboards

<mark>Now Possible:</mark> We can create automated flows with memory.

<mark>Next Steps:</mark>
- Broader student adoption  
- Classroom integration  
- Develop real use cases

<mark>Help Needed:</mark>
- Budget for <mark>TOKENS</mark> so we can run large models  
- Current costs are being covered personally  
- Time allocation is needed to maintain and grow the stack  
- Confirmation that this is a supported, strategic direction

::: notes
This project lays the technical foundation for responsible student-AI interaction. It reduces reliance on cloud services and enables advanced, privacy-safe research workflows. With a small investment, we can turn this into a standard part of classroom education.
:::

---

## 2. VCH Infrastructure – General Tools

<mark>Goal:</mark> Provide infrastructure with built-in tools so students can quickly ideate and prototype.

<mark>Why:</mark> A seamless environment helps students move from ideas to experiments without technical barriers.

<mark>Accomplished:</mark>
- AI stack fully deployed  
- Nextcloud environment live  
- DAT Linux system in full testing

<mark>Next Steps:</mark>
- Integrate AI tools more tightly with the DAT Linux OS  
- Enable AI-enhanced features inside Nextcloud  
- Launch a Nextcloud-based documentation server

<mark>Help Needed:</mark>
- Hands-on testing of all tools and automations  
- Feedback on what’s missing or broken  
- I need *hours* to improve reliability  
- I need support to validate that this infrastructure path makes sense

::: notes
This setup is about lowering the threshold for student experimentation. We now have a local cloud, open AI tools, and a Linux-based desktop system under one roof. With testing and refinement, this becomes a plug-and-play environment for future student-driven supply chain solutions.
:::
---


## 3. VCH Infrastructure – Reproducible Research (incl. DAT Linux)

<mark>Goal:</mark> Enable researchers to build, test, and share repeatable experiments — including data, code, and results.

<mark>Why:</mark> This supports frictionless academic collaboration:  
- Reproduce prior research  
- Run simulations  
- Build openly on each other’s work  
AI has narrow, specific uses in research — but reproducibility unlocks real value.

<mark>Accomplished:</mark>
- Full stack is deployable using DAT Linux, Docker, and systemd  
- RStudio Server tested and running

<mark>Next Steps:</mark>
- Develop integrated research workflows in RStudio  
- Study and apply data stewardship best practices

<mark>Help Needed:</mark>
- I need a real past research project to rebuild as a reproducible R workflow  
- I need *hours* to prototype and document it properly  
- I need confirmation that this direction aligns with our goals

::: notes
This is about making research replicable, auditable, and extensible. With this setup, students and researchers can package their work in a form that others can immediately reuse or rerun. It’s a key step toward making our lab academically credible and open-source ready.
:::

---

## 4. Practical AI Use Cases & Workshops

<mark>Goal:</mark> Teach students how to use AI tools effectively, with a focus on real-world limitations.

<mark>Why:</mark>  
AI is massively overhyped. In reality:
- It makes frequent mistakes  
- Lacks reasoning and context awareness  
- Struggles with memory, coherence, and truthfulness  
Students must understand how to test, verify, and contain AI — not blindly trust it.

<mark>Accomplished:</mark>
- Workshop repository created  
- First sessions completed  
- Practical failures (e.g. Knopenkoning, Inchainge) revealed major AI limitations

<mark>Next Steps:</mark>
- Translate IBM-based workshop into applied, real-world format  
- Teach data translation: from models to operational reality  
- Embed these lessons into ongoing workshop series

<mark>Help Needed:</mark>
- Manpower: integration engineers, network engineers, workshop co-builders  
- Testers to challenge tools and give feedback  
- Regular, scheduled workshops and hands-on AI meetups

::: notes
This project is about critical thinking. We’re not selling AI — we’re building fluency in when and how to use it. These workshops teach students to confront the gap between theoretical AI performance and actual system behavior. That’s where deep learning happens — and where trust is earned.
:::

---

## 5. AI-Supported Student Projects

<mark>Goal:</mark> Support student-led projects by giving them access to AI tools that just work — instead of expecting them to build or understand AI infrastructure from scratch.

<mark>Why:</mark>  
As Maxime correctly pointed out, most students are not equipped to build models or flows.  
Chris worked with "What he had and what he was working with", but that doesnt work;
Instead, we:
- Provide working - End-user faceing tools; not chatbots. 
- Focus on prompting, saving, processing  
- Teach integration with commercial and internal systems  
This approach boosts their real output — it’s more valuable than sandbox experiments.

<mark>Accomplished:</mark>
- Built 2 fully working websites and concepts using AI  
- Far beyond what students could build on their own  
- Proved that AI mentorship unlocks creativity and output

<mark>Next Steps:</mark>
- Showcase project results  
- Formalize AI mentorship offerings  
- Identify new student use cases

<mark>Help Needed:</mark>
- **Stop** restricting expert-student interactions — students need direct support to accelerate  
- **Start** giving token budgets so we can run large models when needed  
- **Stop** comparing local setups to billion-dollar AI clouds  
- **Start** allowing external experts to connect with our lab (e.g. via Discord or open sessions)  
- **Start** recognizing Value Chain Hackers as a serious initiative: give it a KvK, a domain, and a mandate  
- **Start** giving Chris a dedicated team of IT and business students to build applied AI solutions

::: notes
This slide is a call to shift from theory to empowerment. Students thrive when given working tools and mentorship. The current model is burning energy on trying to teach what can’t be learned in a crash course. Instead, let's supercharge them — and learn from what breaks.
:::

## 6. SupplyLens (formerly Knopenkoning)

<mark>Goal:</mark> Visualize complex supply chains using a combination of AI, ESG data, and graph technology.

<mark>Why:</mark>  
- Supports CSRD/CSDDD compliance  
- Enables risk mapping, transparency, and actionable insights  
- Real use for real complexity

<mark>Why Now:</mark>  
- Lessons learned from previous attempt (Sebastien encounter)  
- Renewed clarity, realism, and enthusiasm  
- Ongoing interest from the AI community to contribute  
- Chris has developed a new, feasible approach

<mark>Accomplished:</mark>
- New direction and architecture defined  
- GitHub + live demo prepared:
  - [GitHub](https://github.com/Value-Chain-Hackers/SupplyLens)  
  - [Demo](https://rpubs.com/kamitor/Supplylens23)

<mark>Next Steps:</mark>
- Greenlight to begin ideation  
- Allocation of focused working hours  
- Approval to form a dedicated Scrum team

<mark>Help Needed:</mark>
- Permission to proceed and bring in trusted external contributors (free) 
- Split this off from Value Chain Hackers as it's own initiative, with a kvk, domain etc. 
- Minimal prototype budget (< €5K) for infrastructure and testing  
- Space to experiment and iterate with a core team, allow chris to work with externals.

::: notes
SupplyLens brings together sustainability, transparency, and AI to address a real need: supply chain visibility. After a difficult first iteration, this new approach is grounded, collaborative, and well-scoped. With a small budget and a bit of trust, we can show fast progress.
:::


## 7. Experimental Tool Testing – AI Scientist, Far.AI

<mark>Goal:</mark> Explore emerging AI tools that support scientific workflows — from multi-step reasoning to automated experimentation.

<mark>Why:</mark>  
- Keep Windesheim connected to the frontier of AI development  
- Investigate tools that can:  
  - Automate cyber attack simulation  
  - Assist in generating PhD-level research  
  - Handle complex multi-step processing  
These tools could reshape the way academic research is conducted.

<mark>Accomplished:</mark>
- Reviewed AI Scientist and Far.AI projects  
- Identified promising capabilities and applications  
- Repository bookmarked:  
  - [GitHub – AI Scientist (aci)](https://github.com/aipotheosis-labs/aci)

<mark>Next Steps:</mark>
- Actively test 3 tools to evaluate research potential  
- Identify barriers and integration opportunities

<mark>Help Needed:</mark>
- Token budget required to run and evaluate these tools properly

::: notes
This initiative keeps us ahead of the curve in research tech. While not production-ready, these experimental tools offer a glimpse into how AI might eventually support fully automated or guided scientific inquiry. We should test now — and decide where to engage deeper.
:::


## 8. Project Proposal – ClearRoots

<mark>Goal:</mark> Build a digital platform to help smallholder cooperatives and EU SME importers comply with EU sustainability laws (CSRD, CSDDD, EUDR).

<mark>How It Works:</mark>
- Cooperatives enter data via a multilingual, offline-capable mobile app  
- Data is time-stamped and stored on AgUnity’s blockchain for traceability  
- System guides users through EU-aligned documentation workflows  
- Importers receive ready-to-submit compliance dossiers for each shipment

<mark>Why It Matters:</mark>
- EU rules now require sustainability documentation that smallholders can’t easily produce  
- Importers lack practical tools to meet compliance requirements  
- This platform enables both sides to comply — without exclusion or greenwashing

<mark>Current Status:</mark>
- Drafted core logic, roles, and compliance flow  
- Identified pilot framework and documentation logic  
- Initial partners: AgUnity, Windesheim, SCF NICE  
- First pitch deck and 1-pager created

<mark>Help Needed:</mark>
- Funding or co-development support to move into implementation  
- Support turning this into a grant proposal  
- A grant writer or strategic partner to help secure next steps

::: notes
ClearRoots bridges regulatory pressure with practical tech. It empowers both sides of the supply chain with credible documentation — not token checklists. We're ready to move, and we’re aligned with real partners. What we need now is momentum and backing.
:::

## 9. Project Proposal – ClearPaper

<mark>Goal:</mark> Create practical, standardized templates to help cooperatives, importers, and other actors comply with EU sustainability laws (CSRD, CSDDD, EUDR).

<mark>How It Works:</mark>
Each template would:
- Be directly linked to specific EU legal clauses  
- Come in Word, LaTeX, and JSON formats  
- Adapt to national implementations and local languages  
- Optionally integrate with tools like AgUnity for semi-automated input

<mark>Why It Matters:</mark>
- There’s no common definition of what “compliant documentation” looks like  
- This creates risk for importers and barriers for smallholders  
- ClearPaper provides a transparent, usable foundation for scalable compliance

<mark>Current Status:</mark>
- Begun legal mapping and validation discussions with Windesheim and SCF NICE

<mark>Help Needed:</mark>
- Collect feedback to shape a strong grant proposal  
- Turn this into a fundable project — give us a grant writer!

::: notes
ClearPaper translates EU regulation into usable formats. It reduces ambiguity and levels the playing field. Without shared templates, even honest actors are at risk of non-compliance. This project builds trust into the documentation process.
:::

---

## 10. Key Collaborations

- [Thomas Dik](https://www.linkedin.com/in/thomas-dik-2538392b/) – AI tooling and cloud architecture  
- Ronald de Boer – Business Intelligence, Power BI integration  
- Luka Westgeest – SCF, ClearRoots & ClearPaper  
- Stefan Barrett (AG-Unity CTO) – Document processing logic  
- Iivo Salmi & Raul Raus – Trusted EU infrastructure research - Finland. 
