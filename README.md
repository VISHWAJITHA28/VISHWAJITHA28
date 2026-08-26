<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&duration=2800&pause=800&color=22D3EE&center=true&vCenter=true&width=700&height=45&lines=Byru+Vishwajitha;Agentic+%26+Generative+AI;RAG+pipelines+%7C+Computer+Vision;prototype+-%3E+production;01100011+01101111+01100100+01100101" alt="Byru Vishwajitha — agentic and generative AI" />

<br />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vishwajithabyru28/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:byruvishwajitha@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/VISHWAJITHA28)
![Views](https://komarev.com/ghpvc/?username=VISHWAJITHA28&style=flat-square&color=22d3ee&label=visitors)

</div>

<br />

## `~/` whoami

```
$ whoami
byru-vishwajitha

$ cat ./now.txt
Generative AI Intern @ Ve Lyra Labs.
B.Tech CSE (AIML), Kakatiya Institute of Science and Technology, 2026.

$ cat ./focus.txt
Agentic and generative AI in clinical settings — where being wrong matters.
An assistant that must not invent a citation. A model that must say what it
doesn't know. A record that must not cross a hospital boundary.
```

I build AI/ML systems and take them the whole way — prototype through to production, including the CI/CD that gets them there. Mostly **Python, FastAPI, and Azure**.

The through-line is **grounding**: making a model cite its source instead of guessing, and making a system prove who is asking before it answers.

<br />

## `~/` toolbox

<div align="center">

<img src="https://skillicons.dev/icons?i=py,java,fastapi,flask,pytorch,sklearn,tensorflow,opencv,azure,gcp,docker,postgres,mysql,git,github,vscode&perline=8" alt="Python, Java, FastAPI, Flask, PyTorch, scikit-learn, TensorFlow, OpenCV, Azure, GCP, Docker, PostgreSQL, MySQL, Git, GitHub, VS Code" />

</div>

<div align="center">

`LangChain` · `RAG` · `Agentic Workflows` · `ChromaDB` · `RDKit` · `HL7 FHIR R4` · `DICOM` · `Gemini` · `MedGemma` · `Streamlit`

</div>

<br />

## `~/` skill radar

<div align="center">

<img src="./radar-skills.svg" width="47%" alt="Technical competencies radar" />
&nbsp;&nbsp;
<img src="./radar-languages.svg" width="47%" alt="Language proficiency radar" />

</div>

<br />

## `~/` contribution calendar

<div align="center">

<img src="./profile-3d-contrib/profile-night-rainbow.svg" alt="3D contribution calendar" />

<br />

<img src="https://raw.githubusercontent.com/VISHWAJITHA28/VISHWAJITHA28/output/snake.svg" alt="Snake eating my contributions" />

</div>

<br />

## `~/` the numbers

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=VISHWAJITHA28&show_icons=true&hide_border=true&count_private=true&theme=transparent&title_color=22d3ee&icon_color=34d399&text_color=8b949e" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=VISHWAJITHA28&layout=compact&hide_border=true&langs_count=8&theme=transparent&title_color=22d3ee&text_color=8b949e" />

<br />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=VISHWAJITHA28&hide_border=true&background=00000000&stroke=8b949e&ring=22d3ee&fire=34d399&currStreakLabel=22d3ee&sideLabels=8b949e&dates=8b949e" />

</div>

<br />

## `~/` experience

**Generative AI Intern** · *Ve Lyra Labs* · Mar 2026 – present

Building an enterprise healthcare-AI platform, now scaling into a multi-tenant B2B service. Core modules: a **HL7 FHIR R4** electronic health record, a **DICOM** diagnostic AI tool, an agentic clinical research assistant, and hospital intelligence dashboards.

```
impact/   cut clinician scan-review time by 85%
          citation-backed answers from PubMed, FDA, NIH, WHO
          ~30s response at 90% accuracy

built/    schema-per-tenant isolation in PostgreSQL, routed at runtime
          per-module JWT auth with a verified module claim
          role-based portals: patient, doctor, admin, pharmacy
          azure CI/CD, prototype through to a live production service

found/    an unauthenticated endpoint returning full patient rows —
          password hashes and live OTPs. a complete takeover path, closed.
          cross-tenant access on the FHIR routes, closed — answering 404
          not 403, so a guessed UUID can't become an oracle.
```

**Machine Learning Intern** · *SDK Technologies* · Jan – Jun 2025
MobileNetV2 + TensorFlow Lite vision system recognising 40+ produce classes at **98% accuracy**, with OpenCV pipelines for real-time preprocessing and on-device inference.

**System Infrastructure Automation Intern** · *Abhyasana Technologies* · May – Jul 2025
Server-client architecture, web server setup, load balancing, and cloud deployment strategies.

<br />

## `~/` selected work

### 🧬 [Drug_discovery](https://github.com/VISHWAJITHA28/Drug_discovery) — agentic workflow
An agentic multi-agent LLM pipeline for pre-clinical screening that narrows **thousands of compounds down to 10 candidate leads** for cancer treatment — automating preprocessing, molecular analysis, and result synthesis. LLM agents coordinate each stage against cheminformatics tooling, so results come back reproducible and structured rather than as prose.
`Python` · `PyTorch` · `RDKit` · `LangChain` · `Multi-agent LLM`

### 🩻 [diagnostic-decision-support](https://github.com/VISHWAJITHA28/diagnostic-decision-support) · *Ve Lyra Labs, open sourced*
Multi-agent clinical decision support — chest X-ray analysis with TorchXRayVision, ICD-10 differentials, and PubMed-cited evidence through a hybrid FAISS + BM25 index. Orchestrator, vision, retrieval, diagnosis and safety agents are separate, so the safety pass can veto an output.
`FastAPI` · `PyTorch` · `LLaMA-3 70B` · `FAISS` · `Docker`

### 📚 [medresearch-agent](https://github.com/VISHWAJITHA28/medresearch-agent)
Medical paper analyzer — plain-language summaries, evidence-quality scoring, and synthesis across several papers at once. The chatbot answers only from the uploaded documents and cites them.
`FastAPI` · `Gemini` · `ChromaDB` · `pdfplumber`

| more | | |
|---|---|---|
| **[fitness-plan-generator](https://github.com/VISHWAJITHA28/fitness-plan-generator)** | Training plans that adapt to health conditions — arthritis, asthma, diabetes — not just goals | `Flask` `React` |
| **[Credit_Score](https://github.com/VISHWAJITHA28/Credit_Score)** | ML credit scoring (0–1000) for DeFi wallets from Aave V2 history | `scikit-learn` `pandas` |
| **[Wallet_Risk_Scoring](https://github.com/VISHWAJITHA28/Wallet_Risk_Scoring)** | Risk scoring for Ethereum wallets from Compound V2 lending via The Graph | `Python` `The Graph` |
| **[Trader-bot](https://github.com/VISHWAJITHA28/Trader-bot)** | Binance Futures testnet CLI — REST signing written by hand, no trading library | `Python` `requests` |

<br />

## `~/` credentials

- **B.Tech — CSE (AIML)**, Kakatiya Institute of Science and Technology · 2026
- **Certified AgentForce Specialist** — Salesforce AI Agents · Aug 2025

<br />

<div align="center">

```
01110011 01110100 01100001 01111001  01100011 01110101 01110010 01101001 01101111 01110101 01110011
```

<sub>built things I wanted to exist · <a href="mailto:byruvishwajitha@gmail.com">say hello</a></sub>

</div>
