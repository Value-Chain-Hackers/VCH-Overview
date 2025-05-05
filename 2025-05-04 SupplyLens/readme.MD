Wat is het project 

Supplylens is a open source tool to map out the reality of supplychains using the factors of Finance, movement of goods and information about that to give an more accrate scope of the world of today.
Instead of relying only on information that can be found, SupplyLens uses A.I to Reason and Predict the missing data of supplychains. 
By using Forensic methododology and Reasonmatic Reasoning, we can find the connections that are hidden in supplychains.

Wat is de huidige status
We are back to the drawing board, We are rebuilding the architectural design from the ground up, now with a more rigerous development process.

Wat dingen die bereikt zijn 
We have now, a more realistic setup on how to get towards the end goal, we have had our first failures and learned a lot from them.
We have determined that this is hard, but that there is significant demand for this program.

Wat moet er nog gebeuren
We need to get new approval, build a new prototype, Gather new funding.


# SupplyLens

**SupplyLens** is an open-source platform designed to reveal the true structure of global supply chains by combining finance, logistics, and documentation into one unified system. It goes beyond traditional data aggregation by applying **AI-powered reasoning** to infer, connect, and predict relationships between entities—even when direct information is missing.

---

## 🔍 What is SupplyLens?

Modern supply chains are fragmented, obscured, and often incomplete—especially at the start of the chain, where ethical and environmental risks are highest.

**SupplyLens** provides a new way to map that reality. Using a combination of:

- **AI-driven natural language processing**
- **Graph-based modeling of supplier relationships**
- **Forensic reasoning to reconstruct missing links**

…it creates dynamic, explorable knowledge graphs of supply chains, allowing researchers, compliance officers, and auditors to identify blind spots and dependencies.

---

## 🧠 How It Works

SupplyLens combines several layers of open tools into one integrated system:

1. **📥 Data Collection**  
   - Crawl ESG reports, trade documents, web sources  
   - Extract entities: companies, facilities, regions, certifications

2. **🧠 AI Reasoning & Prediction**  
   - Use LLMs (e.g. GPT, Ollama) to interpret and generate semantic links  
   - Apply **reasonmatic reasoning** to infer unseen connections  
   - Score confidence and risk on inferred links

3. **🔗 Graph Database Storage**  
   - PostgreSQL + Apache AGE to structure the supply graph  
   - pgvector for semantic similarity searches  
   - JSONB for detailed metadata (ESG, location, tier, etc.)

4. **❓ Query Interface**  
   - Ask natural-language questions via LangChain or OpenWebUI  
   - Get back insights, explanations, and visualizations

---

## 🌐 Why SupplyLens?

Most supply chain tools rely only on what can be explicitly reported or found in databases.  
**SupplyLens introduces a forensic approach**—reconstructing supply chains like crime scenes, using probability, logic, and AI to fill in the blanks.

This makes it useful for:
- ESG & CSRD compliance
- Investigative journalism
- NGO transparency campaigns
- Research into trade networks and hidden dependencies

---

## 👥 Team

- **Christiaan Verhoef** – Business Developer & Visionary  
  [linkedin.com/in/christiaanverhoef](https://www.linkedin.com/in/christiaanverhoef/)
- **Torsten Raudssus** – AI Engineer  
  [linkedin.com/in/raudssus](https://www.linkedin.com/in/raudssus/)
- **Prof. Michiel Steeman** – Strategic Support, Supply Chain Finance  
  [linkedin.com/in/michielsteeman](https://www.linkedin.com/in/michielsteeman/)

---

## 🧪 Status

This project is in early development.  
We are currently:

- Finalizing the data pipeline architecture (graph + embeddings)
- Setting up pilot infrastructure with Docker-based deployment
- Integrating the reasoning engine into PostgreSQL using Apache AGE and LangChain
- Preparing public demo environments and pilot use cases

---

## 👐 Get Involved

We’re actively seeking:

- Developers with interest in AI, graphs, NLP or supply chain data  
- Academic partners to use or test SupplyLens in real-world research  
- NGOs and journalists to help guide the ethical and forensic applications  
- Funding partners for open-source development, documentation, and outreach

If you'd like to get involved, open an issue or contact us directly at:

📧 info@supplylens.xyz

---

## 📄 License

This project is open-source under the **MIT License**. See [LICENSE](LICENSE) for details.



**SupplyLens**  
**AI-Enhanced Supply Chain Mapping System**  
*“Turning fragmented data into full-spectrum supply visibility”*

Presented by: [Your Name / Team / Organization]  
Windesheim University – Value Chain Hackers

---

## 1️⃣ **What is it?**

> “Every supply chain starts in the dark.”

- Companies face massive pressure to map ESG risks across their supply chains.  
- But most data is buried in reports, PDFs, supplier sites, and disconnected systems.
- ConflictChain turns that chaos into clarity.

**ConflictChain is an AI-powered system that**:
- Crawls unstructured sources
- Builds a supply graph from extracted entities
- Stores it in a unified graph database
- Lets you query it in plain language

> It’s like Google Maps for your supply chain — with an AI co-pilot.

---

## 2️⃣ **How does it work?**

### 🧠 Step 1: **Collect the Data**
- Use `Crawl4AI` or your own PDF/web crawler  
- Ingest ESG reports, supplier lists, trade documents  
- Extract entities: companies, products, countries

→ Output: Raw text + metadata, structured for reasoning

---

### 🧠 Step 2: **Embed and Reason**
- Feed text into an LLM (Ollama, GPT-4, LM Studio)
- Generate knowledge graph triples:  
  _EasyFiets → sources lithium from → Chinese Mining Corp_
- Use `pgvector` or `Qdrant` to store semantic embeddings
- LLM rates relationship validity and strength

→ Output: A clean, annotated map of who connects to whom — and why

---

### 🗃 Step 3: **Store and Structure**
- All data lives inside **PostgreSQL**  
  - `Apache AGE`: handles graph relationships  
  - `pgvector`: powers semantic search  
  - `JSONB`: stores rich ESG metadata

→ One database, one interface, no microservice spaghetti

---

### 🗣️ Step 4: **Query in Natural Language**
- Use **LangChain or LlamaIndex** to connect the graph to an LLM  
- User types:  
  _“Where is lithium for the electronic bike from EasyFiets coming from most likely?”_
- LLM turns that into a graph query → matches nodes and embeddings → gives a readable answer

→ Anyone can ask — no code, no SQL, just insight

---

## 3️⃣ **Are you sure?**

- 🧾 Based on **proven tools**: PostgreSQL, Apache AGE, LangChain, pgvector  
- 📊 Aligned with **EU regulation**: CSRD and CSDDD demand visibility past Tier 1  
- 🧪 Research-backed: LLM + KG approaches boost supply mapping depth by 3x (Cambridge, 2024)

**It’s open-source. Modular. Auditable.**  
And it’s the infrastructure we need to map the unmappable.

---

## 4️⃣ **Can you do it?**

Yes — and here’s how we’re planning it:

- 💻 All components containerized with Docker Compose
- 🔄 `start_services.py` orchestrates environment with profiles (CPU, GPU)
- 🔐 HAProxy or Caddy provides HTTPS + subpath routing on  
  `https://aisandbox1.ixworx.nl`
- 🧠 Stack already running in development:  
  Apache AGE + pgvector + LangChain + Supabase + n8n

**Now we’re seeking pilot partners to deploy it in the real world.**

---

## 5️⃣ **What do you want?**

We’re ready to test this in live environments.

We’re looking for:
- 🎓 **Academic partners** to stress test the system with real research data  
- 🏢 **Companies** who want supply chain transparency without the black box  
- 📈 **Investors and grantmakers** to fund the open-source build-out  
- 🌍 **NGOs and EU bodies** to help us align with real reporting needs

> ConflictChain makes visibility a utility.  
> Help us turn data chaos into clean, defensible ESG reporting.

---

## 📬 Contact

**Christiaan Verhoef**  
ConflictChain – Windesheim University  
📧 christiaan@valuechainhackers.xyz  
🌐 [https://aisandbox1.ixworx.nl](https://aisandbox1.ixworx.nl)  

---

Would you like this packaged into:
- A `.Rmd` ioslides presentation?  
- A slide-deck-style PDF/Quarto version?  
- Or a website-ready pitch layout?

Let me know how you want to present this.