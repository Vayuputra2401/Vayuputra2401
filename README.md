<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img alt="Pathikreet Chowdhury — ML engineer, researcher, founder" src="assets/header-light.svg" width="100%">
</picture>

I take machine learning from the paper to production. By day I run the data lakehouse I built from scratch at **Flipkart (Cleartrip)**, serving 200+ TB. Before that I built neuro-symbolic agents at **Siemens** that shipped to production and became patents. The rest of the time goes to research — two papers under review at WACV 2027 — and three products of my own.

[Portfolio](https://vayuputra2401.github.io/Personal-Portfolio/) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/pathikreet-chowdhury-489b77234/) &nbsp;·&nbsp; [Kaggle](https://www.kaggle.com/pathikreet) &nbsp;·&nbsp; [Email](mailto:pathikreetofficial@gmail.com)

<br>

### Building now

<table>
<tr>
<td width="230" valign="top"><b>Akasha.ai</b> <br><sub>IN&nbsp;DESIGN&nbsp;·&nbsp;2026</sub></td>
<td valign="top">The operational intelligence layer for Indian enterprises. Existing cameras become typed events at the edge (raw video never leaves the site), events land in one Postgres memory with pgvector and an entity graph, and LangGraph agents act on them. Designed to go from camera to WhatsApp in about 20 seconds, with no human in the loop.</td>
</tr>
<tr>
<td width="230" valign="top"><b>Chef.ai</b> <br><sub>IN&nbsp;PRODUCTION&nbsp;BUILD</sub></td>
<td valign="top">Scan your fridge, get dinner. A 7-node LangGraph DAG fuses pgvector retrieval with fresh generation over a ~7,000-recipe corpus, and ChefGPT — a streaming agent with 9 tools — stays with you at the stove. The LLM only ever rewrites prose; allergies and diets are enforced in code.</td>
</tr>
<tr>
<td width="230" valign="top"><b>Artemis</b> <br><sub>FOUNDER&nbsp;&amp;&nbsp;CEO</sub></td>
<td valign="top">On-device personal safety. Every 1.5 seconds a threat engine on the phone fuses Silero VAD, a YAMNet audio classifier and ECAPA-TDNN speaker embeddings with motion signals. A deterministic rule engine, never the LLM, decides when to raise an SOS.</td>
</tr>
</table>

<br>

### Research

<table>
<tr>
<td width="300" valign="top"><b>Anatomy is Free:</b> zero-parameter structural priors for efficient skeleton action recognition <br><sub>WACV 2027 · UNDER REVIEW · <a href="https://github.com/Vayuputra2401/anatomy-is-free">CODE</a></sub></td>
<td valign="top">Two shift operators route joint features across body regions by pure tensor indexing — no weights, no FLOPs. 88.8% on NTU RGB+D 60 with 281K parameters and 7× fewer FLOPs than EfficientGCN-B0; 90.4% after distillation, at 25 ms on a desktop CPU.</td>
</tr>
<tr>
<td width="300" valign="top"><b>Aligned but Inert:</b> concept bottlenecks in dense prediction, and how to make them causal <br><sub>WACV 2027 · UNDER REVIEW · <a href="https://github.com/Vayuputra2401/AMBETS">CODE</a></sub></td>
<td valign="top">A brain-tumour segmentation bottleneck can track clinical concepts at 0.96 alignment while the model ignores it — rerouting changes 1.1% of voxels. Making routing an additive term of the output raises causal control from 0.001 to 0.636 for about one Dice point.</td>
</tr>
<tr>
<td width="300" valign="top"><b>Federated learning for privacy-preserving face and activity recognition</b> <br><sub>ICIT 2025 · <a href="https://github.com/Vayuputra2401/FL-Face">CODE</a></sub></td>
<td valign="top">Adaptive aggregation with pruning and quantisation cut bandwidth by 65%; differential privacy and adversarial disentanglement hold up against membership inference.</td>
</tr>
<tr>
<td width="300" valign="top"><b>Brain tumour classification and segmentation with a custom CNN, U-Net and XAI</b> <br><sub>ICPR 2024 · <a href="https://github.com/Vayuputra2401/ICPR-XAI-2024">CODE</a></sub></td>
<td valign="top">99.6% accuracy on MRI, plus metrics that put a number on LIME and Grad-CAM explanations.</td>
</tr>
<tr>
<td width="300" valign="top"><b>Patents</b> <br><sub>SIEMENS</sub></td>
<td valign="top">A physics-informed neural network enhanced by symbolic regression and LLMs, with balanced loss optimisation — granted. DANA, a neuro-symbolic LLM agent for industrial chiller anomaly detection — filed.</td>
</tr>
</table>

<br>

### Work

<table>
<tr>
<td width="150" valign="top"><b>Flipkart</b> (Cleartrip)</td>
<td width="190" valign="top">SDE 1 · Data engineering</td>
<td valign="top">Built the lakehouse on GCP: Hudi and Iceberg over GCS, Trino, Metabase. CDC with Kafka Connect and Debezium into Hudi, real-time clickstream into Apache Doris. 40% lower ingestion latency, 30% faster pipelines, 25% lower cloud cost.</td>
</tr>
<tr>
<td width="150" valign="top"><b>Siemens</b></td>
<td width="190" valign="top">Research engineer · Foundational AI</td>
<td valign="top">DANA, a BDI agent on LangGraph, deployed to production. PINNs fused with symbolic regression (52% fewer outliers on industrial data); LLMs in the loop of multi-agent symbolic regression.</td>
</tr>
<tr>
<td width="150" valign="top"><b>Matrice.ai</b></td>
<td width="190" valign="top">Machine learning engineer</td>
<td valign="top">SAM, GroundingDINO, CLIP and YOLO-World in production video pipelines (+30% accuracy); core architecture of the Matrice Python package on PyPI.</td>
</tr>
<tr>
<td width="150" valign="top"><b>IIT Kanpur</b></td>
<td width="190" valign="top">SURGE researcher</td>
<td valign="top">Controllable neural symbolic regression over 230M equations; few-shot font diffusion with Monotype, 40% faster.</td>
</tr>
</table>

<br>

### Selected projects

**[AP Commander](https://github.com/Vayuputra2401/AP-Clerk-Financial-Agent)** — a multi-agent RL environment for enterprise accounts payable on Meta OpenEnv. Qwen2.5-7B trained with GRPO against live rewards: mean reward 0.535 → 0.746. Top 100 of 75,000 teams.

**[ReLoop](https://github.com/Radhika1124/ReLoop)** — closed-loop returns and resale for HackOn with Amazon 6.0, built in 48 hours. SAM2 masks make product grades auditable instead of guessed.

**[TransformoDocs](https://github.com/Vayuputra2401/TransformoDocs)** — agentic document intelligence with HyDE RAG. National finalist, Smart India Hackathon 2024.

**[MoleculeForge](https://github.com/Vayuputra2401/MoleculeForge)** · **[Eir](https://github.com/Vayuputra2401/Eir)** · **[LegalVoice.ai](https://github.com/Vayuputra2401/LegalVoice.ai)** — molecule generation, federated healthcare, and legal help by voice in 8 Indian languages.

<br>

### Tools I reach for

<table>
<tr><td width="90" valign="top"><sub>DATA</sub></td><td>Hudi · Iceberg · Trino · Doris · Spark · Kafka · Debezium · BigQuery · Azkaban</td></tr>
<tr><td width="90" valign="top"><sub>ML</sub></td><td>PyTorch · Hugging Face · LoRA / QLoRA · GRPO (TRL) · ONNX Runtime · OpenCV · LangGraph</td></tr>
<tr><td width="90" valign="top"><sub>CLOUD</sub></td><td>GCP · Docker · Kubernetes · AWS SageMaker · Grafana · MCP servers</td></tr>
<tr><td width="90" valign="top"><sub>CODE</sub></td><td>Python · Java · C++ · TypeScript · SQL · React · Next.js · FastAPI</td></tr>
</table>

<br>

<sub>Off the keyboard: winger or centre forward, FC Barcelona through everything, international chess, and a cat called Jim Beam. Open to hard problems, research collaborations, and people who want to build with me.</sub>
