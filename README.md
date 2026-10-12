# MD Humayun

**ML Engineer and Software Development Engineer**\
M.Tech Computer Science, Information Security & Privacy — SVNIT Surat · GATE CS 2025, 93.8 percentile

I work where machine learning meets systems engineering. Training a model is the
easy half; the interesting problems live in the pipeline around it — what
happens when the classifier is wrong, what it costs, and who can explain the
decision afterwards.

[Portfolio](https://mdhumayun7.github.io/MD-HUMAYUN-PORTFOLIO/) ·
[LinkedIn](https://www.linkedin.com/in/md-humayun-82051521a/) ·
[LeetCode](https://leetcode.com/u/mdhumayun7/) ·
md.humayun7777777@gmail.com

---

## What I am building

**[IPS-ML / ShieldNet](https://github.com/mdhumayun7/ips)** — my main machine
learning project, and the work I would most like to be asked about.

An inline intrusion prevention system is not a classifier with a nicer name. It
executes its own predictions: a false positive does not raise an alert for
somebody to dismiss, it drops a legitimate connection. So the whole thing is
evaluated as a control system — recall and false alarm rate as the headline
metrics, three outcomes instead of two, and a SHAP attribution written to an
append-only audit log beside every enforcement action.

Trained on 2,497,980 audited CICIDS2017 flows, evaluated on 749,394 held out.
Macro-F1 0.8814 at a 0.00135 false alarm rate, 0.432 ms median inference.
A model that predicts "benign" for everything scores 82.96% accuracy on the same
data and detects nothing, which is why accuracy is not the headline anywhere in
that repository.

**Hybrid AI-Based Autonomous Drone Swarm Navigation** — MeitY-sponsored research
at SVNIT Surat. Built BattleWorld, a multi-agent simulator wrapped as a
Gymnasium environment with a uniform 12-dimensional state interface, so seven
commander architectures could be benchmarked on identical input. The hybrid
LLM+PPO controller reached 67.9% action accuracy against 60.7% for the best
classical baseline. Paper under review at IEEE GSCON 2027.

---

## Selected work

| Project | What it demonstrates | Evidence |
| --- | --- | --- |
| [**ips**](https://github.com/mdhumayun7/ips) | Explainable ML in an enforcement path | 2.5M flows · macro-F1 0.8814 · FAR 0.00135 |
| [**Smart-Home-Automation**](https://github.com/mdhumayun7/Smart-Home-Automation) | ESP32 firmware whose failure behaviour is specified and tested | Dual-core FreeRTOS · 84 / 84 host test runs · CI-built for arduino-esp32 2.0.17 and 3.3.12 |
| [**job-agent**](https://github.com/mdhumayun7/job-agent) | Data pipelines built to degrade, not fail | 11 sources · 2,158 records · 793 → 357 after dedup |
| [**ddos-5g-sdn-project**](https://github.com/mdhumayun7/ddos-5g-sdn-project) | Detection and mitigation inside an SDN controller | 54.3 → 31 Gbps measured under flood |
| [**vae-aevb-reimplementation**](https://github.com/mdhumayun7/vae-aevb-reimplementation) | Reading a paper closely enough to reproduce it | SSIM 0.678 · PSNR 23.40 dB |
| [**medical-chatbot**](https://github.com/mdhumayun7/medical-chatbot) | Grounded retrieval that refuses when it should | 1,152-page corpus · local inference |
| [**Backend-System-design**](https://github.com/mdhumayun7/Backend-System-design) | Class-level design judgement | Spotify and Zomato, modelled from UML |

---

## How I work

Every claim in those repositories is traceable to something I can regenerate.
Where a result is weak I say so: the limitations sections are written before the
results, not after, and the deviation register in `ips` lists all thirteen
places the implementation departed from the plan, with impact ratings.

That habit is the thing I would want a reviewer to notice.

---

## Stack

**Languages** C++ · Python · SQL\
**Embedded and IoT** ESP32 · FreeRTOS · Arduino · MQTT · Home Assistant\
**ML** TensorFlow · Keras · scikit-learn · XGBoost · SHAP · LoRA · PPO\
**LLM and retrieval** LangChain · Pinecone · Ollama · RAG\
**Infrastructure** Docker · AWS (EC2, S3) · GitHub Actions · Linux\
**Networking** SDN · OpenFlow · Mininet · Scapy

---

## Currently

Sharpening C++ and system design for SDE interviews, and reading toward
cross-dataset validation for the intrusion prevention work — generalisation is
an objective there, not yet a result.

Outside coursework I run **NITIAN RAHI**, an engineering education community of
around 52,000 across YouTube, Facebook and Instagram, where I explain ML and
systems topics to students. Teaching a thing is the fastest way to find out
whether you understand it.
