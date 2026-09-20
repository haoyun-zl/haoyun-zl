# 💼 Internship Experience

**[中文](../Internship.md) | English**

[← Back to Home](README.md)

## 🧭 Experience Map

| Area | Company & Business |
| :--- | :--- |
| 🤖 AI Product | Alibaba Taotian |
| 📈 Ads Strategy | ByteDance TikTok Shop |
| 🛒 E-commerce Operations | JD Jingxi |
| 💊 Marketing Analytics | AstraZeneca |

---

## 🤖 Alibaba Taotian
### AI Product Intern

Worked on an intelligent product review system, redesigning a multi-role serial manual workflow into a process with **parallel AI review plus human fallback**.

#### What I Did

- **Process definition**: Broke down business rules and decision criteria across **8 review dimensions** and organized the full review workflow.
- **Review module design**: For tax review, worked on a two-stage **RAG** approach that combined precise matching by category ID, **HyDE** semantic retrieval as fallback, and hard-rule post-processing. For category review, used **HyDE** to reduce the gap between colloquial product descriptions and standard category terms.
- **Modular design**: Helped abstract a `BaseAuditor` base class and a unified `AuditResult` structure, supporting independent iteration for each review dimension through `pre_process → audit → post_process`.
- **Evaluation and iteration**: Designed an evaluation setup based on manual annotation and consistency checks, tracking consistency rate, miss rate, and false positive rate. Bad cases were fed back into the **Milvus** knowledge base to support prompt, rule, and confidence-threshold optimization.

#### Impact

- Covered **8 review dimensions** and achieved **100% AI review coverage** for products.
- End-to-end review time for one product across all dimensions was **under 30 seconds**.
- Improved review efficiency by **more than 10x** compared with manual review.

`AI Product` · `RAG` · `HyDE` · `Evaluation` · `Workflow Design`

---

## 📈 ByteDance TikTok Shop
### Ads Strategy Intern

Worked on **AIGC** creative strategy, campaign performance monitoring, and automated data workflows for advertising optimization.

#### What I Did

- **Creative tiering strategy**: Managed creative delivery and budget allocation for hero products, new products, and potential breakout products, and analyzed tests across creators, creatives, and audiences to summarize reusable strategy takeaways.
- **Automated data workflow**: Helped shift routine campaign data collection and consolidation from manual extraction to automated output, supporting efficiency monitoring and strategy iteration.
- **Campaign optimization**: Participated in optimizing bidding approaches and scaling rhythm, and followed campaign performance in the **US** and **MX** markets.
- **Special projects**: Coordinated with industry, creative, and external agency teams on new-customer **DNC** strategy and **RPG/RPD** stabilization.
- **Tool migration**: Worked with the team on the migration to the **ROI2** tool, including strategy-level delivery data analysis and planning support.

#### Impact

- Helped keep hero-product **ROAS** stable at **5.2**.
- Contributed to increasing the share of GMV from US daily ad spend by **4 percentage points**.
- Contributed to increasing the share of GMV from MX ad spend by **2 percentage points**.
- New-customer **DNC** share reached **20.9%**.
- Reduced repetitive manual data handling through AI tools and automated workflows.

`AIGC` · `Ads Strategy` · `ROAS` · `Automation` · `Cross-functional Collaboration`

---

## 🛒 JD Jingxi
### E-commerce Operations

Worked across product selection, cold start operations, subsidy programs, on-site advertising, and coupon operations.

#### What I Did

- **Owned the "Add-on Purchase" section**: Optimized product selection, cold start, and price-gap strategy; coordinated with new merchants in categories such as cured meat products and beef shank; and helped move products from selection and listing to marketing promotion.
- **Super Subsidy program**: Took part in submission, routine maintenance, and data analysis; coordinated with suppliers to improve sell-through; and built a multi-dimensional monitoring setup to identify the risk of products going offline.
- **On-site advertising analysis**: Conducted daily checks and SKU-level attribution analysis, then supported implementation of optimization actions.
- **Coupon operations**: Worked with category merchandising and sourcing teams to optimize coupon strategy and improve product sales and sell-through.

#### Impact

- The "Add-on Purchase" section contributed **179,000 orders** and **794,000 GMV** in a single quarter, up **790%** and **517%** quarter over quarter.
- A high-ticket beef rib product contributed **3,270 orders** and **202,000 GMV**.
- The Super Subsidy group maintained **180+** live SKUs with **80,000+ average daily GMV**.
- Improved on-site advertising **ROI** from **7** to **10.5**.
- Coupon operations drove **169%** quarter-over-quarter GMV growth, **89%** order growth, and a **9.45 percentage point** increase in sell-through rate.

`Product Selection` · `SKU Operations` · `Advertising ROI` · `Coupon Strategy`

---

## 💊 AstraZeneca
### Marketing Intern

Supported pharmaceutical market analysis, brand planning, and cross-functional project execution.

#### What I Did

- **Data analysis**: Organized business data, conducted market analysis, and prepared reports, including monthly processing and pivot analysis for **5,000+ hospital accounts**.
- **Brand data support**: Consolidated nationwide market access data for the TAVO brand and prepared monthly reports and volume-evaluation materials.
- **Project support**: Assisted with projects including a resistance-consensus roadshow, distributor conferences, and product market access work, as well as strategy discussion support, material organization, and presentation preparation.
- **Cross-functional collaboration**: Worked with sales, medical, and commercial teams, coordinated with external vendors, and followed project execution and internal compliance operations.

#### Outputs

- Hospital data organization, pivot analysis, and monthly reports.
- Nationwide market access data summaries and volume-evaluation materials for the brand.
- Execution support for brand strategy and key projects.

`Market Analysis` · `Brand Support` · `Reporting` · `Project Coordination`

---

## 🧩 Skills Built Through Experience

| Capability | Practice |
| :--- | :--- |
| Problem Framing | Breaking business problems into workflows, rules, and executable tasks |
| Data Thinking | Using data to monitor performance, analyze issues, and validate strategies |
| AI Application | Embedding AI tools and evaluation mechanisms into business workflows |
| Business Analysis | Analyzing e-commerce, advertising, and market performance metrics |
| Collaboration | Working with business teams, suppliers, and external partners to move projects forward |
