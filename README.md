# Hi, I'm Nguyen Quang Minh

Cool pickup lines I found:
 
- Still figuring out what I’m doing. I write about things I don’t understand so you don’t have to Google them.
- Acceptance criteria for my life: _PTSD_. Acceptance criteria for your product: already drafted, versioned, and color-coded.
Somehow, this exact chaos turned a vague brief into a multi-agent AI platform for Vinsmart Future (Vingroup).
 
Student at **FPT University**, Vietnam · Working where **AI, data, and business operations** meet: multi-agent systems, computer vision for retail, and B2B software for real clients.
 
- Focus: business analysis, product discovery, requirements & scoping, AI product design
- Growing into: AI engineering, building and shipping LLM-powered and multi-agent systems, not just scoping them

> Most of my best work lives in private repos owned by companies and project teams, locked away like a family recipe. So instead of the code, you get the director's commentary below.

---

## Highlight: c-AI — Multi-Agent Platform for Enterprise Operations
`Vinsmart Future (Vingroup) · AI Thực Chiến internship` · `Role: Business Analyst, with UI/UX & Backend contributions`

During my internship at Vinsmart Future, my team built **c-AI**, a multi-agent AI platform that supports operational decision-making for a business unit within Vingroup.

- **Problem:** Operational decisions require input from several departments, each holding its own data and priorities. Getting a balanced recommendation is slow and depends on manual coordination.
- **Solution:** Department-level AI agents each assess a proposed scenario from their own perspective, and an orchestrator agent consolidates their input into one recommended plan for management.
- **Key product decision:** Agents are fully isolated and only the orchestrator coordinates them. This keeps data boundaries clean, which matters for governance in an enterprise setting, and avoids fragile agent-to-agent dependencies.
- **My contribution:**
  - **Business:** Scoped the MVP, mapped the data each operational area required, and translated business needs into agent responsibilities and testable requirements
  - **UI/UX:** Contributed to the interface design for how managers review scenarios and recommendations
  - **Backend:** Helped build the mock-data API so the system could be tested without touching production data
- **What I learned:** Scoping AI products around a real pain point, designing for data governance in an enterprise, and bridging business and engineering.

> _Source code and business data are confidential and owned by Vinsmart Future / Vingroup._

---

## Other Projects

### RetailVision Edge — AI Computer Vision for Retail Analytics
`AI Thực Chiến program · Team project` · `Role: Product Manager / Product Owner` · `Team of 4`

A computer-vision system that helps retail stores and shopping malls understand foot traffic from existing CCTV cameras.

- **Problem:** Store operators lack reliable data on how many customers come in, where they go, and how long they stay.
- **What we built:** In/out people counting, dwell time, zone occupancy, hourly aggregation, heatmaps and alerts, using pretrained YOLO detection with object tracking (ByteTrack/DeepSORT) and zone/line-crossing logic, so it works without domain-specific training data.
- **My contribution:**
  - Defined the product scope and prioritised must-have features (counting, dwell time, occupancy) over nice-to-haves (demographics, face recognition)
  - Led architecture trade-off discussions (on-premise vs edge vs cloud) and worked around dataset constraints by using real café CCTV footage as a proof-of-concept
  - Built the business case: a hybrid on-premise B2B pricing model charged per camera, with unit economics and P&L/ROI across optimistic, base and pessimistic scenarios
- **Outcome:** A working proof-of-concept running on real CCTV footage, showing live detection, tracking IDs, in/out counts and dwell-time metrics, backed by a business model for B2B retail customers.

▶️ Video demo: https://youtu.be/VtzKFgC_Eo4

> _Private team repository._

### BBK Travel — B2B Management App for a Travel Business
`FPT University graduation project · Real client` · `Role: UI/UX Developer & Business Analyst` · `Team of 5`

A B2B operations management application built for BBK Travel, a real tour operator partnering with our team.

- **Problem:** The company's operational data was scattered across separate hotel, vehicle and service contracts, spreadsheets and email. Staff had to piece information together by hand every time they prepared a quote, which was slow and error-prone.
- **What we're building:** An all-in-one internal operations platform (CRM-style web app) that consolidates suppliers and contracts across hotels, vehicles, meals, tour tickets, passports and other services into one view, so staff can build quotes faster and more accurately.
- **My contribution:**
  - Designed the UI/UX and built the front-end for the core operational screens
  - Worked with the team on requirement analysis with the real client, keeping a requirements list aligned with the screen-first design approach
  - Created visuals that communicate the client's problem and the solution to stakeholders and the academic council
- **Status:** In progress, with ongoing feedback from the client and our supervisor.

> _Private team repository._

---

<p align="center"><i>Always open to conversations about product, AI, and building things that people actually use.</i></p>
