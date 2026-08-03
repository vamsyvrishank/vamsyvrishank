<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&width=700&lines=Data+Engineer+%7C+AI+Engineer+%7C+Quant+Adjacent;800TB+migrated.+200M%2B+profiles+consolidated.;Financial+Engineering+%40+Stevens+%7C+Ex-PayPal;Paranormally+Distributed+%3B%29" alt="Typing SVG" />

<br/>

[![Website](https://img.shields.io/badge/vamsy.org-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://vamsy.org)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vamsyvrishank/)
[![SSRN](https://img.shields.io/badge/SSRN-Working%20Paper-8B0000?style=for-the-badge)](https://vamsy.org)
![Profile Views](https://komarev.com/ghpvc/?username=vamsyvrishank&style=for-the-badge&color=58A6FF)

</div>

---

I build the data infrastructure that machine learning models sit on top of, and I also build the models. Three and a half years at PayPal on the Customer Data Platform and Enterprise Data Infrastructure teams, now finishing an MFE at Stevens with an algorithmic trading specialization. Undergrad was Metallurgy at NIT Trichy, which is a strange path into distributed systems and I am fine with that.

Most of what lives here falls into three buckets: derivatives pricing and market microstructure, streaming data pipelines, and agentic LLM systems.

<div align="center">

### Click any section below to open it

</div>

---

<details>
<summary><b>Quick facts</b></summary>

<br/>

| | |
|---|---|
| **Currently** | MFE candidate at Stevens Institute of Technology, graduating May 2026 |
| **Previously** | Software / Data Engineer at PayPal (Customer Data Platform, Enterprise Data Infra) |
| **Focus areas** | Distributed data systems, LLM and RAG pipelines, execution algorithms, market microstructure |
| **Languages** | Python, C++, SQL, Java, q/kdb+ |
| **Reading now** | Papers on volatility regime switching and execution cost modeling |
| **Ask me about** | Kafka exactly once semantics, Flink state, Snowflake cost tuning, why poker is applied Bayesian inference |

</details>

<details>
<summary><b>Tech stack</b></summary>

<br/>

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Data and streaming**

![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Flink](https://img.shields.io/badge/Apache%20Flink-E6526F?style=flat-square&logo=apacheflink&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

**ML and AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini%202.0%20Flash-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Infra**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

</details>

---

## Projects

<details>
<summary><b>Derivatives Pricing Engine</b> &nbsp;·&nbsp; C++ &nbsp;·&nbsp; analytic, tree, and Monte Carlo pricing</summary>

<br/>

A modular pricing library covering analytic formulas, lattice methods, and Monte Carlo across a range of payoffs. Built around Strategy, Factory, and Decorator patterns so payoffs and pricing methods compose independently of each other.

Includes trinomial trees for barrier options, finite difference schemes (explicit, implicit, Crank Nicolson with the Rannacher modification for the discontinuity at the strike), and Hull White for rates.

`C++17` `Design Patterns` `Numerical Methods` `Monte Carlo`

[**Open repo →**](https://github.com/vamsyvrishank/Derivatives-Pricing-Engine)

</details>

<details>
<summary><b>Adaptive Volatility Regime Based Execution and Risk Framework</b> &nbsp;·&nbsp; published on SSRN</summary>

<br/>

Co-authored working paper with Shreejit Verma. A hidden Markov model classifies volatility regimes, HAR-RV-J handles the realized volatility forecast with a jump component, and execution aggressiveness adapts to the regime the market is currently in.

The result worth pointing at: **Sortino of 2.41 against a Sharpe of 1.57**. The gap between those two numbers is the whole argument of the paper. Downside deviation and total deviation are not the same risk, and execution frameworks that optimize for the second one leave money on the table.

`Python` `HMM` `HAR-RV-J` `Execution Algorithms` `Regime Detection`

[**Open repo →**](https://github.com/vamsyvrishank/Adaptive-Volatility-Regime-Based-Execution-and-Risk-Framework)

</details>

<details>
<summary><b>StoryForge</b> &nbsp;·&nbsp; multi agent pipeline on Google ADK</summary>

<br/>

A multi agent narrative generation system running on Google's Agent Development Kit with Gemini 2.0 Flash. FastAPI backend streams tokens over SSE, deployed on Cloud Run.

The part I care about most is the evaluation loop. Rubric based sampling scores generations across dimensions instead of relying on a single quality proxy, which is what makes iteration on agent prompts tractable rather than vibes based.

`Python` `Google ADK` `Gemini 2.0 Flash` `FastAPI` `SSE` `Cloud Run`

[**Open repo →**](https://github.com/vamsyvrishank)

</details>

<details>
<summary><b>Distributed Log Aggregation Pipeline</b> &nbsp;·&nbsp; Kafka to Flink to Elasticsearch</summary>

<br/>

End to end streaming pipeline for log ingestion and search. Fluent Bit ships logs into Kafka, PyFlink handles windowed aggregation and enrichment in flight, Elasticsearch stores the output, Kibana renders it. The whole thing runs locally under Docker Compose.

Built to work through the parts of streaming that only show up in practice: watermarks and late arriving events, checkpoint tuning, and what exactly you give up when you choose at least once over exactly once.

`Fluent Bit` `Kafka` `PyFlink` `Elasticsearch` `Kibana` `Docker Compose`

[**Open repo →**](https://github.com/vamsyvrishank)

</details>

<details>
<summary><b>IAQF 2026: Stablecoin Market Microstructure</b> &nbsp;·&nbsp; 1.8M+ ticks</summary>

<br/>

A liquidity study across stablecoin pairs built on a pipeline processing over 1.8 million ticks. Estimates Kyle's lambda for price impact, Amihud illiquidity, and the Roll effective spread.

The SVB collapse is used as a natural experiment. A depeg event gives you an exogenous shock to a supposedly pegged asset, which is about as clean an identification strategy as crypto markets ever hand you.

`Python` `Market Microstructure` `Kyle's Lambda` `Amihud` `Roll Spread` `Tick Data`

[**Open repo →**](https://github.com/vamsyvrishank)

</details>

<details>
<summary><b>Dynamic Beta Hedging Model</b> &nbsp;·&nbsp; single stock exposure offset</summary>

<br/>

A full framework for building, analyzing, and rebalancing a beta hedged portfolio against a concentrated single stock position, using Apple as the working case. Covers rolling beta estimation, rebalance frequency tradeoffs, and the transaction cost drag that eats the hedge if you rebalance too often.

`Python` `Portfolio Construction` `Rolling Beta` `Risk Management`

[**Open repo →**](https://github.com/vamsyvrishank/Dynamic-Beta-Hedging-Model)

</details>

<details>
<summary><b>Cross Asset Volatility Arbitrage</b> &nbsp;·&nbsp; equities, rates, FX</summary>

<br/>

Tests one hypothesis: relative mispricing of implied volatility across economically linked asset classes is temporary and mean reverting. Builds the cross asset vol surface comparison, defines the dislocation signal, and checks whether the reversion is real or just a story that fits the sample.

`Python` `Implied Volatility` `Statistical Arbitrage` `Cross Asset`

[**Open repo →**](https://github.com/vamsyvrishank/Cross-Asset-Volatility-Arbitrage-Equities-Rates-FX-)

</details>

<details>
<summary><b>ArchitectIQ</b> &nbsp;·&nbsp; system design practice tool</summary>

<br/>

A client side React and Vite application for practicing system design interviews. Everything runs in the browser with no backend, so state stays local and there is nothing to deploy or pay for.

`React` `Vite` `TypeScript` `Client Side`

[**Open repo →**](https://github.com/vamsyvrishank)

</details>

<details>
<summary><b>QuantJobs Scraper</b> &nbsp;·&nbsp; ~75 firms, config driven</summary>

<br/>

A Python and Flask application that pulls postings from roughly 75 quant and fintech firms. Handles Greenhouse and Lever APIs, plus HTML and JSON scrapers for the firms that roll their own boards. Config driven through a `firms.json` file, with per domain rate limiting and deduplication across sources.

Built it because manually checking 75 career pages is exactly the kind of thing that should not be manual.

`Python` `Flask` `BeautifulSoup` `Playwright` `Rate Limiting`

[**Open repo →**](https://github.com/vamsyvrishank)

</details>

---

<details>
<summary><b>What I did at PayPal</b></summary>

<br/>

**Enterprise Data Infrastructure**

- Migrated **800TB** of data to GCP across the warehouse estate
- Built **ETLJobsServ**, a centralized Spring Boot connection pooling service on HikariCP that replaced per pipeline database connections. Adopted across **300+ concurrent Airflow pipelines**
- Optimized Braintree BigQuery workloads through partitioning, clustering, and query rewrites on a schema ported from Redshift

**Customer Data Platform**

- Consolidated **200M+ customer profiles** into golden records across Venmo, Braintree, Hyperwallet, PayPal, and GoPay
- Entity resolution and MDM at a scale where the interesting problems are all about conflict resolution rules, not the matching algorithm

</details>

<details>
<summary><b>Off the clock</b></summary>

<br/>

⚽ Manchester United, which is less a hobby and more a recurring test of emotional resilience

♠️ Competitive poker. The closest thing to a live fire drill for probabilistic reasoning under incomplete information that I have found

♟️ Chess

🎮 Open world games. GTA V and Red Dead Redemption 2 sit at the top

📺 Anime. Jujutsu Kaisen and Classroom of the Elite

🎵 Music, constantly

</details>

---

<div align="center">

### Stats

<img height="165" src="https://github-readme-stats.vercel.app/api?username=vamsyvrishank&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub Stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vamsyvrishank&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=vamsyvrishank&theme=tokyonight&hide_border=true" alt="Streak" />

<br/><br/>

<img src="https://github-profile-trophy.vercel.app/?username=vamsyvrishank&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8" alt="Trophies" />

</div>

---

<div align="center">

**Open to conversations about data engineering, AI engineering, and quant technology roles.**

[![Website](https://img.shields.io/badge/vamsy.org-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://vamsy.org)
[![LinkedIn](https://img.shields.io/badge/Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vamsyvrishank/)

<sub>👒 Paranormally Distributed ;)</sub>

</div>
