---
title : "FC Community Day"
date : 2024-01-01
weight : 1
chapter : false
pre : "<b> 4.1. </b>"
---

### Event Objectives
* Update on advanced technology trends and solutions: **Cloud, Agentic System, Voice AI, AWS DevOps Agent, Amazon Q Business**.
* Share career development directions and adaptability skills in the AI era for students and tech engineers.
* Guide on infrastructure security and Private Connection solutions in enterprise environments.
* Create a networking space between students, the AWS community, and industry experts.

---

### Speakers
* **Steve Tran** - Founder @ Cloud Thinker (Former Solutions Architect at AWS, FPT)
* **Hieu Nghi** - Cloud Engineer @ Renova Cloud
* **Kiet** - Representative @ AWS Student Community Group
* **Trung Do** - Founder & CEO @ R AI
* **Nguyen Nguyen** - Cloud Engineer @ Cloud Kinetics
* **Bao** - Cloud Engineer @ Cloud Kinetics
* **Truong (Quen)** - AI Solution Shaper @ Noventic
* **Minh Anh** - Solution Shaper @ Noventic
* **Toan Nguyen** - AWS Security Builder

---

### Key Highlights

#### 1. Cloud & Agentic Platform in Infrastructure Operations
* **Current state of legacy application operations:** Microservices expansion increases complexity and tech debt. Enterprises adopt too many observability tools leading to bloated operations teams.
* **Labor market trends:** Hiring for traditional developers is declining; enterprises prioritize personnel who can collaborate effectively with AI.
* **Agentic Platform Solution (Cloud Thinker):**
  * Comparison of **Single Agent** (prone to context dilution, high cost on large systems) and **Multi-Agent / Specialist Agents** (narrower context window, RBAC support, and cost-effective).
  * **Core Features:** Incident Investigation (automated log/incident reading in minutes), Code Reviews, FinOps (Cloud cost optimization), and Penetration Testing.

#### 2. Building Voice AI for the Vietnamese Market
* **Technical Architecture:** Vietnamese is a low-resource language, hence the Speech-to-Speech model is not optimal yet. The current effective solution is a 3-step pipeline:  
  $$\text{Speech-to-Text (STT)} \rightarrow \text{LLM + Tool Calling} \rightarrow \text{Text-to-Speech (TTS)}$$
* **Real-world Challenges in the Banking Industry:**
  * Handling formal address (Mr./Ms.) based on gender detection.
  * Smart interruption handling and pause detection (when reading a sequence of ID/phone numbers).
  * Introducing 10–20% regional accent data into the STT/TTS training set.
  * Supporting a **Human-in-the-loop** mechanism (transferring calls to human operators for complex issues).

#### 3. Automating Monitoring and Incident Handling with AWS DevOps Agent
* **The MTTR (Mean Time to Resolution) Problem:** Fragmented telemetry monitoring data makes troubleshooting time-consuming for engineers.
* **6 Pillars of AWS DevOps Agent:** Context Learning (auto-draw Topology), Control (permission via Tag/Private Connection), Integration (expand via MCP), Collaboration (Slack/ServiceNow integration), Convenience (direct operations on Console), and Cost Effectiveness (charging $0.083/second of actual execution).
* **4-Step Process:** Classify & Collect Logs $\rightarrow$ Investigate & Hypothesize $\rightarrow$ Propose Mitigation Plan $\rightarrow$ Post-incident Improvement.
* **Safety Principle:** DevOps Agent only acts as **Recommendation Only**; approval and execution always remain with humans.

#### 4. The AI Era & Amazon Q Business Application in HR Management
* **HR Challenges:** Manual CV screening takes time (1–2 months), candidate evaluation is subjective, and public AI poses data privacy risks.
* **Amazon Q Business Solution:**
  * Specialized Custom Agent, workflow automation, and BI business data analytics.
  * Connects diverse data sources beyond a single ecosystem: Microsoft Workspace, Google Workspace, Amazon S3, Jira, Salesforce, GitHub...
* **HR Talent Review Assistant Demo Flow:** Automating Job Description (JD) generation $\rightarrow$ OCR & extracting CV data (PDF/Scan) $\rightarrow$ Scoring based on competency frameworks $\rightarrow$ Exporting candidate reports and suggesting salary benchmarks.

#### 5. Private Security Connection for Amazon Q Business with MCP Server
* **Enterprise Security Risks:** Connecting Amazon Q to third parties (Zalo, WhatsApp, Databases...) via MCP Server on Public Endpoints is vulnerable to DDoS, MITM, or data leaks.
* **Private Connection Architecture Model:**
  * Place MCP Server entirely within a **Private Subnet**.
  * Use **VPC Connection / Interface Endpoint** to connect directly from Amazon Q to the internal VPC.
  * Use **Application Load Balancer (ALB)** with TLS encryption combined with **Route 53 Resolver** for internal domain resolution.
  * Integrate **AWS Cognito** for Authentication/Authorization.

---

### Key Takeaways

#### Design Mindset
* **Human-in-the-loop:** AI is a skill amplifier tool; crucial decisions affecting production or enterprise systems still require human approval.
* **Business-first & Security-first:** Technology applications must stem from real enterprise business problems while ensuring security (Private Network, RBAC) from the design phase.

#### Technical Architecture
* **Multi-Agent Architecture:** Using Specialist Agents helps narrow the Context Window, reduce hallucinations, and optimize operational costs.
* **Hybrid Voice Pipeline:** The method combining STT $\rightarrow$ LLM $\rightarrow$ TTS allows better control over real-time text data stream and supports Tool Calling better for low-resource models.
* **Private Integration Pattern:** The private connection model for MCP Server via VPC Endpoint, ALB, and Route 53 Resolver ensures absolute safety for enterprise data.

#### Modernization Strategy
* Automate incident monitoring (DevOps) and department operations (HR/Sales) to reduce manual handling time and improve organizational productivity.
* Optimize cloud costs (FinOps) by combining AI tools and pay-as-you-go pricing models.

---

### Applying to Work
* **Optimize CV screening process:** Build standardized candidate assessment frameworks and apply AI tools for automated data extraction to reduce hiring time.
* **Experiment with AWS DevOps Agent & Amazon Q Business:** Evaluate the integration of Agents into alert monitoring and internal document query systems.
* **Apply private connection models (Private MCP):** Implement connections between AI Agents and internal systems via VPC Endpoints to ensure compliance with security standards.

---

### Event Experience

Attending the **FC Community Day** event was a highly practical experience, bringing deep insights from architectural theory to live demos on the AWS ecosystem:

* **Learning from Experts:** Listening to valuable insights from speakers with rich field experience at AWS, Cloud Kinetics, Renova Cloud, Noventic, and R AI.
* **Hands-on Technical Demos:** 
  * Observed a live demo of DDoS incident mitigation on ECS Task using **AWS DevOps Agent**.
  * Experienced the CV evaluation and automated report generation flow using **Amazon Q Business**.
  * Followed configuration steps for private queries via **VPC Connection & Route 53 Resolver**.
* **Networking & Exchange:** Opportunity to network, connect with the AWS community, speakers, and fellow students sharing career aspirations in Cloud & AI.

---

### LESSONS LEARNED
* AI Agents are actively transitioning from simple text generation to executing actionable tasks via Tool Calling.
* Private Connection security is a prerequisite when deploying Generative AI solutions in enterprise environments.
* Continuous self-improvement and developing a correct AI application mindset are key to adapting to the shifting IT labor market.

---

### 8. Google Drive Link
* [Google Drive Link](https://drive.google.com/drive/folders/1HFBn3O3yVfNxi-RjN88kXpvAUjCLCXKk)
