<div align="center">

![Banner](https://github.com/AbrarMuhtasim14/AbrarMuhtasim14/blob/main/Github_Banne.png)

<br/>

# ABRAR MUHTASIM

### Agentic AI Engineer &nbsp;•&nbsp; LLM Systems Builder &nbsp;•&nbsp; Multi-Agent Architect

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/syed-muhtasim-3308611a6)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/Abrar144)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@abrarm)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abrarmuhtasim400@gmail.com)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=abrarmuhtasim14&label=Profile+Views&color=6d28d9&style=flat-square)

</div>

---

<div align="center">

### I build AI systems that reason, route tasks, call tools, and deliver grounded outputs
**Agentic AI &nbsp;•&nbsp; Multi-Agent Orchestration &nbsp;•&nbsp; Tool Calling &nbsp;•&nbsp; LLM Fine-Tuning &nbsp;•&nbsp; AI Workflow Automation**

</div>

---

## About Me

I am an **Agentic AI Engineer** who builds production-grade AI systems where LLMs go beyond answering questions — they **plan, route tasks, call external tools, manage conversational context, verify outputs, and automate real business workflows**.

My strongest work is in:

- **Agentic AI Engineering** — designing multi-agent pipelines with role specialization, sequential orchestration, tool use, and query routing
- **LLM Engineering** — prompt design, output grounding, anti-hallucination systems, fine-tuning, and evaluation
- **AI Product Engineering** — turning agent prototypes into deployable systems with databases, dashboards, APIs, and automation layers

I care about building AI that is not just impressive in demos — but **reliable, verifiable, and genuinely useful in production**.

---

## Core Engineering Focus

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧠 Agentic AI Engineering</h3>
      <ul>
        <li>Multi-agent orchestration with specialized agent roles</li>
        <li>Sequential context chaining across agent handoffs</li>
        <li>Query routing and intent-based flow control</li>
        <li>Tool-calling agents using ReAct and native function calling</li>
        <li>Conversational memory using session and cache layers</li>
        <li>Anti-hallucination verification at the system level</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>⚙️ LLM Systems Engineering</h3>
      <ul>
        <li>LangChain, CrewAI, LiteLLM, OpenRouter</li>
        <li>Structured outputs, function calling, and tool schemas</li>
        <li>Redis for session memory and response caching</li>
        <li>Citation-grounded and retrieval-augmented generation</li>
        <li>QLoRA fine-tuning, dataset design, and model evaluation</li>
        <li>Gradio, Streamlit, HuggingFace Spaces, Render deployment</li>
      </ul>
    </td>
  </tr>
</table>

---

## Featured Projects

<table>
  <tr>
    <td width="33%" valign="top">
      <h3 align="center">⚖️ Multi-Agent Legal Research Pipeline</h3>
      <h4 align="center">Automated Case Law Retrieval, Statute Analysis and IRAC Memo Generation</h4>
      <p align="center">
        <a href="https://medium.com/@Abrarm/i-built-a-multi-agent-legal-ai-that-actually-doesnt-hallucinate-here-s-the-architecture-8c67a6a6f30d">
          <img src="https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white"/>
        </a>
      </p>
      <p>
        Takes raw client facts as input and outputs a fully structured, citation-verified legal memorandum — built for legal professionals who need reliable, grounded research at speed.
      </p>
      <ul>
        <li>Designed a <strong>5-agent CrewAI pipeline</strong> where each agent has a distinct role: intake, legal retrieval, statute analysis, synthesis, and citation verification — with structured output passed sequentially between agents</li>
        <li>Implemented <strong>query routing</strong> to classify incoming requests into full research, follow-up, refinement, or clarification flows before any agent is invoked</li>
        <li>Built a <strong>zero-trust citation system</strong> where no legal reference enters the final memo unless it has been retrieved and confirmed through CourtListener or Tavily tool calls</li>
        <li>Engineered a <strong>4-layer output verification system</strong> to catch hallucinated citations, unsupported claims, and incomplete IRAC structure before final delivery</li>
      </ul>
      <p>
        <strong>Skills Demonstrated:</strong> Multi-agent orchestration, tool calling, query routing, output grounding, memory management, anti-hallucination design
      </p>
      <p>
        <code>CrewAI</code> <code>LangChain</code> <code>Redis</code> <code>OpenRouter</code> <code>CourtListener API</code> <code>Tavily</code> <code>Gradio</code>
      </p>
    </td>
    <td width="33%" valign="top">
      <h3 align="center">📈 Citation-Grounded Financial Q&A System</h3>
      <h4 align="center">Domain Fine-Tuned LLM on SEC Filings with Hallucination Resistance</h4>
      <p align="center">
        <a href="https://github.com/AbrarMuhtasim14/sec-assistant-finqa">
          <img src="https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white"/>
        </a>
        <a href="https://huggingface.co/Abrar144/sec-assistant-phi3-finqa">
          <img src="https://img.shields.io/badge/Live_Model-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
        </a>
      </p>
      <p>
        Takes a financial question and an SEC filing excerpt as input and outputs a cited, evidence-grounded answer — or an explicit refusal when the filing does not contain sufficient evidence.
      </p>
      <ul>
        <li>Fine-tuned <strong>Phi-3-Mini (3.8B)</strong> using <strong>QLoRA + 4-bit quantization</strong> — completed in approximately 25 minutes at zero compute cost on free-tier GPU</li>
        <li>Designed the training dataset with a <strong>70/30 split</strong> — 70% matched question-context pairs and 30% deliberately mismatched pairs — to teach the model when NOT to answer</li>
        <li>Improved <strong>citation inclusion rate from 80% to 100%</strong> by making citation a structural requirement enforced through prompt format and training signal</li>
        <li>Improved <strong>answer rate from 45% to 100%</strong> on matched contexts while preserving correct refusal behavior on mismatched ones</li>
        <li>Trained and deployed a <strong>live HuggingFace Spaces demo</strong> with Gradio interface for interactive testing</li>
      </ul>
      <p>
        <strong>Skills Demonstrated:</strong> QLoRA fine-tuning, dataset engineering, hallucination resistance through training, model evaluation, HuggingFace deployment
      </p>
      <p>
        <code>Phi-3-Mini</code> <code>QLoRA</code> <code>BitsAndBytes</code> <code>TRL</code> <code>SFTTrainer</code> <code>HuggingFace</code> <code>Gradio</code>
      </p>
    </td>
    <td width="33%" valign="top">
      <h3 align="center">🏨 Conversational BI Platform</h3>
      <h4 align="center">Natural Language to SQL Interface Over 24 Hotel Performance KPIs</h4>
      <p align="center">
        <a href="https://github.com/AbrarMuhtasim14/chat-with-data">
          <img src="https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white"/>
        </a>
      </p>
      <p>
        Takes plain-English business questions as input and outputs SQL-backed KPI answers, anomaly alerts, and property health scores — built for hotel operations teams who need analytics without writing queries.
      </p>
      <ul>
        <li>Built an LLM agent with <strong>native function calling</strong> that routes natural language questions to specific SQL tool functions rather than generating raw SQL directly — preserving control and reliability</li>
        <li>Engineered a <strong>deterministic SQL engine covering 24 business KPIs</strong> including RevPAR, occupancy rate, ADR, cancellation rate, and booking channel mix — all with pre-validated query logic</li>
        <li>Implemented a <strong>4-layer anomaly detection system</strong> that flags statistical outliers in KPI data and assigns property-level health scores for executive reporting</li>
        <li>Unified the agent answer layer and the Streamlit dashboard through a <strong>single shared metrics engine</strong> — ensuring the agent and the dashboard always show the same numbers</li>
        <li>Used <strong>Supabase + PostgreSQL</strong> as the backend with <strong>Plotly</strong> for interactive chart rendering inside the Streamlit interface</li>
      </ul>
      <p>
        <strong>Skills Demonstrated:</strong> Function calling, tool schema design, deterministic SQL pipelines, anomaly detection, dashboard engineering, agent-UI integration
      </p>
      <p>
        <code>Python</code> <code>LiteLLM</code> <code>OpenRouter</code> <code>PostgreSQL</code> <code>Supabase</code> <code>Streamlit</code> <code>Plotly</code>
      </p>
    </td>
  </tr>
</table>

---

## Impact at a Glance

<table>
  <tr>
    <td align="center" width="25%">
      <h2>100%</h2>
      <strong>Citation Rate</strong><br/>
      <sub>Improved from 80%</sub>
    </td>
    <td align="center" width="25%">
      <h2>100%</h2>
      <strong>Answer Rate</strong><br/>
      <sub>Improved from 45%</sub>
    </td>
    <td align="center" width="25%">
      <h2>~90%</h2>
      <strong>Cost Reduction</strong><br/>
      <sub>Via model routing</sub>
    </td>
    <td align="center" width="25%">
      <h2>4</h2>
      <strong>Verification Layers</strong><br/>
      <sub>Anti-hallucination</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="25%">
      <h2>$0</h2>
      <strong>Fine-Tuning Cost</strong><br/>
      <sub>Free-tier GPU</sub>
    </td>
    <td align="center" width="25%">
      <h2>25 min</h2>
      <strong>Training Time</strong><br/>
      <sub>Phi-3-Mini QLoRA</sub>
    </td>
    <td align="center" width="25%">
      <h2>24</h2>
      <strong>Deterministic KPIs</strong><br/>
      <sub>SQL-backed metrics</sub>
    </td>
    <td align="center" width="25%">
      <h2>2</h2>
      <strong>Publications</strong><br/>
      <sub>IEEE + Acadlore</sub>
    </td>
  </tr>
</table>

---

## Technology Stack

<div align="center">

<p><strong>Agentic AI and LLM Frameworks</strong></p>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-FF4B4B?style=for-the-badge&logoColor=white)
![LiteLLM](https://img.shields.io/badge/LiteLLM-000000?style=for-the-badge&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-6366F1?style=for-the-badge&logoColor=white)

<p><strong>Fine-Tuning and Machine Learning</strong></p>

![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![QLoRA](https://img.shields.io/badge/QLoRA-EE4C2C?style=for-the-badge&logoColor=white)
![TRL](https://img.shields.io/badge/TRL-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![BitsAndBytes](https://img.shields.io/badge/BitsAndBytes-F97316?style=for-the-badge&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

<p><strong>Memory, Data and Infrastructure</strong></p>

![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

<p><strong>Apps, Deployment and Automation</strong></p>

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=for-the-badge&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## Additional Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🎁 BloomGift AI</h3>
      <p>AI-powered gift and event recommendation platform that personalizes suggestions based on recipient profile and occasion type.</p>
      <p>
        <a href="http://www.bloomgiftai.com/">
          <img src="https://img.shields.io/badge/Live_Product-FF6B9D?style=for-the-badge&logo=vercel&logoColor=white"/>
        </a>
      </p>
      <p><code>Lovable</code> <code>Supabase</code> <code>OpenRouter</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>💪 ThrivePath</h3>
      <p>AI wellness assistant that generates personalized meal plans and fitness routines based on user goals and dietary preferences.</p>
      <p>
        <a href="https://thrivepath.vercel.app/">
          <img src="https://img.shields.io/badge/Live_Product-4CAF50?style=for-the-badge&logo=vercel&logoColor=white"/>
        </a>
      </p>
      <p><code>Lovable</code> <code>Supabase</code> <code>OpenRouter</code></p>
    </td>
  </tr>
</table>

### Workflow Automation
- Built production AI automation workflows using **n8n** including automated email triage and an AI voice agent for appointment scheduling using **ElevenLabs** and **Google Calendar API**

### Analytics and Data Projects
- **[E-Commerce Web Analytics](https://medium.com/@Abrarm/sql-driven-data-analysis-illuminating-growth-strategies-in-the-retail-e-commerce-landscape-dd7a0a3a2193)** — SQL analysis surfacing 11% CTR improvement opportunity and 40% cart abandonment pattern
- **[Customer Segmentation and Churn Analysis](https://medium.com/@Abrarm/customer-segmentation-and-cohort-analysis-in-retail-using-excel-bigquery-and-looker-315ce2859445)** — K-means and RFM segmentation identifying 23% churn-risk customer cohort
- **[Hotel Revenue Insights](https://medium.com/@Abrarm/revenue-insights-for-a-chain-hotel-brand-in-power-bi-b0e6449aa24d)** — Power BI dashboard revealing 32% cancellation rate and 52% weekend occupancy patterns
- **[Hotel Booking Cancellation Prediction](https://medium.com/@Abrarm/a-python-data-analysis-project-to-understand-hotel-cancellations-fb3f0fee6eea)** — Random Forest classifier achieving 78.34% accuracy on booking cancellation prediction

---

## Research and Publications

- **[Optimizing Predictive Models for Drug-Induced Suicidal Risk](https://ieeexplore.ieee.org/document/11021794)** — IEEE Xplore, 2025
- **[Optimizing Decision-Making Through Customer-Centric Market Basket Analysis](https://www.acadlore.com/article/JOSA/2024_2_2/josa020201)** — Acadlore, 2024

---

## GitHub Analytics

<div align="center">

![](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=abrarmuhtasim14&theme=github_dark)

</div>

<div align="center">

![](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=abrarmuhtasim14&theme=github_dark)
![](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=abrarmuhtasim14&theme=github_dark)

</div>

<div align="center">

![](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=abrarmuhtasim14&theme=github_dark)
![](https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=abrarmuhtasim14&theme=github_dark&utcOffset=6)

</div>

---

## Education and Certifications

**B.Sc. in Computer and Communication Engineering**
International Islamic University Chittagong — CGPA 3.39 / 4.00

**Certifications**
- 365 Data Science — Data Analyst Career Track
- Data Science using Python A-Z for Machine Learning
- PostgreSQL Bootcamp: Beginner to Advanced
- IELTS — Overall Band 6.5

---

## Currently Exploring

- Advanced agentic workflow patterns including parallel agent execution and hierarchical delegation
- Production memory design for long-horizon multi-turn AI conversations
- Fine-tuning and alignment strategies for domain-specific reliable outputs
- AI workflow automation at scale with n8n and API integration layers

---

## Let's Connect

<div align="center">

**Open to Agentic AI Engineer, LLM Engineer, AI Product Engineer, and Applied ML roles**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/syed-muhtasim-3308611a6)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/Abrar144)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@abrarm)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abrarmuhtasim400@gmail.com)

</div>

---

<div align="center">

![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer&text=Agentic%20AI%20Engineer%20%7C%20Building%20Reliable%20LLM%20Systems&fontSize=20&fontColor=fff&animation=twinkling&fontAlignY=70)

</div>
