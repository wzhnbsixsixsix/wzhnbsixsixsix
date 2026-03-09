## Hi there 👋

**🚀 AI Agent Developer | Full-Stack Engineer | CS Student @ University of Exeter**

Welcome to my GitHub! I am a passionate developer focusing on **LLM Agents**, **RAG systems**, and **Backend Architecture**. Currently pursuing my Computer Science degree in the UK, I have a strong track record of turning cutting-edge AI research into production-ready applications. 

### 💡 About Me

- 🔭 I’m currently working on **High-performance AI Agents**, **Multi-Agent Evaluation Systems**, and robust RAG pipelines.
- 🌱 I’m currently learning **Deep Learning & Advanced Data Science** at the University of Exeter.
- 👯 I’m looking to collaborate on **Open-source LLM frameworks (like AgentScope/LangChain)** and backend microservices.
- 💬 Ask me about **Python, Java/Spring Boot, Dify workflows, and Prompt Engineering**.
- 📫 How to reach me: [Personal Website](https://wzhnb666.win/) | 📧 w905840774@gmail.com
- ⚡ Fun fact: I am a heavy user of AI coding assistants (Claude Code, Cursor) building AI tools to empower other developers!

---

### 🛠️ Tech Stack

**Languages** `Python` `Java` `JavaScript/TypeScript` `SQL`

**AI & LLM Ecosystem** `Dify` `Coze` `LangChain` `LangGraph` `AgentScope` `OpenAI SDK`

**Backend & Architecture** `FastAPI` `Spring Boot` `Django` `RESTful API` `MyBatis-Plus` `JWT`

**Databases & Vector Stores** `MySQL` `PostgreSQL` `Redis (Stream/Redisson)` `Milvus` `ChromaDB` `AWS RDS`

**Engineering & Cloud** `Docker` `CI/CD` `AWS EC2/Amplify` `Nginx` `Linux` `PyTorch` `Keras`

---

### 🔥 Featured Projects & Experiences

#### [**CompanyCopilot**](https://github.com/wzhnbsixsixsix/CompanyCopilot)
*Enterprise Knowledge Base & Multi-Agent Research Copilot*

- Built a full-stack **AI Copilot platform** for enterprise research and knowledge management, integrating **Chatbot UI** frontend with an **AgentScope-based multi-agent backend**.
- Implemented **RAG-powered knowledge base QA**, enterprise background investigation, and rapid due-diligence reporting with **SSE streaming generation**.

- Designed the **RAG ingestion pipeline** supporting multi-format documents (PDF/Word/Excel/PPT/MD/CSV/images); applied **paragraph split + 512-token chunking** for text and multimodal captioning for images to balance semantic integrity and retrieval granularity.

- Optimized **embedding & retrieval architecture** using **DashScope qwen3-vl-embedding (2560-dim)** to unify text-image representations; deployed **Qdrant** with collection isolation per knowledge base and retrieval via **Top-K + score threshold**, enabling efficient cross-KB search and source traceability.

- Architected a **multi-agent workflow** using **AgentScope**, defining roles including **Researcher, Analyst, Compiler, and Guidance** to form a closed loop from **task routing → evidence collection → analysis → structured report generation**.

- Implemented **Function Calling + Skills + Slash Commands** via **ReActAgent + Toolkit**, enabling agents to trigger retrieval tools and external APIs; formalized an **8-dimension enterprise due-diligence workflow** in `SKILL.md` and mapped user intents to pipelines such as `/research` and `/due-diligence`.

- Integrated **external data augmentation** through **Firecrawl MCP search**, enabling the Researcher agent to perform parallel web discovery (official sites, news, products, funding data), improving factual grounding and coverage of generated reports.

#### [**Jury LLM**](https://github.com/wzhnbsixsixsix/Jury_LLM)
*Human-AI Mixed Alignment Multi-Role Evaluation System*
- Built a multi-dimensional "Jury + Human-in-the-loop" scoring system using **AgentScope**.
- Designed a dynamic human empowerment flow, directional debate engine, and anti-cheating blind voting mechanism.

#### [**Dianping Backend**](https://github.com/wzhnbsixsixsix/dianping)
*Distributed Review App Backend Service*
- Developed a high-concurrency backend with **Spring Boot & Redis**.
- Optimized flash sales using **Redisson** distributed locks, Lua scripts, and Redis Stream for asynchronous queuing.

#### **Professional Experiences**
- **LLM Agent Backend Intern** at **BGI (华大基因)**: Built high-performance Agent workflows in Dify, optimized PubMed API retrieval from 10 mins to 1 min, and deployed Milvus for RAG.
- **AI Agent Developer** at **Shengshi Film & TV (胜事影视)**: Created multi-million-word novel-to-script Agent workflows on Coze and engineered the RAG memory system for a smart companion chatbot (LumiLove).
