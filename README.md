<div align="center">

<img src="https://capsule-render.vercel.app/api?type=Rect&color=0:0D1117,100:0D1117&height=3&section=header" width="100%" />

```
┌─[bhavuk@dev]─[~]
└──╼ $ ssh bhavuk1409
```

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=900&color=39FF14&background=0D111700&center=true&vCenter=true&width=700&height=45&lines=connecting+to+bhavuk1409...;authenticating...;access+granted.;welcome+back%2C+operator." alt="typing" />

<sub>uptime: since 2023 · shell: zsh · status: <b style="color:#39FF14">online</b></sub>

</div>

<br>

```
bhavuk@dev:~$ whoami
```

```
Bhavuk Agrawal
B.Tech Computer Science, Bennett University (2023–2027) · CGPA 8.91/10
Based in Greater Noida, India

I build systems that have to hold up outside a notebook: multi-agent
pipelines that have to agree with each other, RAG that isn't allowed to
hallucinate, LLMs fine-tuned under a VRAM budget. Former ML intern at
NUS Singapore. Currently building Nipuna AI, a financial copilot for
Indian MSMEs.
```

```
bhavuk@dev:~$ cat education.log
```

```
[2023-08] ── ENROLLED   Bennett University · B.Tech CS
[  ...  ] ── COURSEWORK Machine Learning, Deep Learning, Generative AI,
                        Data Structures & Algorithms, Computer Networks,
                        Operating Systems
[2024-06] ── EXTERNAL   ML Intern, National University of Singapore
[2027-05] ── EXPECTED   Graduation
```

```
bhavuk@dev:~$ git log --oneline --all -- experience/
```

```
* 2024-07  (NUS · on-site)  deploy: served real-time predictions from
                             EC2 + S3-backed model endpoint
* 2024-07  (NUS · on-site)  eval: measured pipeline on precision /
                             recall / F1 against held-out medical reports
* 2024-06  (NUS · on-site)  feat: built TF-IDF + scikit-learn text
                             classification pipeline for medical NLP
* 2024-06  (NUS · on-site)  init: onboarded onto faculty research team,
                             supervised learning on structured medical data
```

<br>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0D1117&height=2&width=800" />
</div>

```
bhavuk@dev:~$ docker ps --format "table {{.Names}}\t{{.Status}}\t{{.Stack}}"
```

<table>
<thead>
<tr><th align="left">NAME</th><th align="left">STATUS</th><th align="left">STACK</th></tr>
</thead>
<tbody>
<tr><td><b>nipuna-ai</b></td><td>up · live</td><td>FastAPI · PostgreSQL · LangChain · RAG</td></tr>
<tr><td><b>intervia-backend</b></td><td>up · public</td><td>FastAPI · LangGraph · Groq · DeepFace</td></tr>
<tr><td><b>insurflow</b></td><td>up · public</td><td>FastAPI · PyTorch · YOLOv8 · TrOCR</td></tr>
<tr><td><b>r-search</b></td><td>exited (0) · trained</td><td>PyTorch · Transformers · LoRA</td></tr>
<tr><td><b>football-yolo</b></td><td>up · public</td><td>YOLOv8 · ByteTrack · OpenCV</td></tr>
<tr><td><b>speech-asl</b></td><td>up · public</td><td>Azure · Stanza · MoviePy · Gradio</td></tr>
</tbody>
</table>

<details open>
<summary><code>bhavuk@dev:~$ cat nipuna-ai/README.md</code></summary>
<br>

<img src="https://img.shields.io/badge/status-live-39FF14?style=flat-square&labelColor=0D1117" /> <img src="https://img.shields.io/badge/stack-FastAPI_·_LangChain_·_RAG-39FF14?style=flat-square&labelColor=0D1117" />

**Nipuna AI — AI Financial Copilot for MSMEs**

Omnichannel copilot unifying Tally ERP, Zoho Books, Gmail, WhatsApp, and
Instagram into one financial data layer for Indian MSMEs. Built a
schema-grounded Text-to-SQL + RAG framework specifically to eliminate
fabricated financial outputs, with live Tally sync via XML/TDL and ODBC,
and a credit-metered subscription tier priced over 90% below traditional
virtual CFO services.

`repo link: add here`

</details>

<details>
<summary><code>bhavuk@dev:~$ cat intervia-backend/README.md</code></summary>
<br>

<img src="https://img.shields.io/badge/status-public-39FF14?style=flat-square&labelColor=0D1117" /> <img src="https://img.shields.io/badge/stack-FastAPI_·_LangGraph_·_Groq-39FF14?style=flat-square&labelColor=0D1117" />

**Intervia — Multi-Agent AI Interview Evaluator**

Generates interview questions from a resume + job description,
transcribes candidate answers, reads facial and vocal emotion from
video, then runs it all through a LangGraph pipeline — Behavior,
Content, and Communication agents feeding a Judge agent — to produce a
structured hiring verdict.

[→ github.com/bhavuk1409/intervia-backend](https://github.com/bhavuk1409/intervia-backend)

</details>

<details>
<summary><code>bhavuk@dev:~$ cat insurflow/README.md</code></summary>
<br>

<img src="https://img.shields.io/badge/status-public-39FF14?style=flat-square&labelColor=0D1117" /> <img src="https://img.shields.io/badge/stack-FastAPI_·_PyTorch_·_YOLOv8-39FF14?style=flat-square&labelColor=0D1117" />

**InsurFlow — Multi-Agent Vehicle Insurance Claims System**

End-to-end claims processor coordinating 7 specialized agents — intake
validation, damage assessment (YOLOv8), OCR extraction (TrOCR), fraud
detection (Isolation Forest), policy matching, and decision logic —
behind a FastAPI backend with MCP-based tool calling for
database/payment integrations.

`repo link: add here`

</details>

<details>
<summary><code>bhavuk@dev:~$ cat r-search/README.md</code></summary>
<br>

<img src="https://img.shields.io/badge/HotpotQA-%2B27%25_accuracy-39FF14?style=flat-square&labelColor=0D1117" /> <img src="https://img.shields.io/badge/VRAM-%E2%88%9235%25-39FF14?style=flat-square&labelColor=0D1117" />

**R-Search — RL-Enhanced LLM Reasoning**

Fine-tuned a 7B-parameter LLM with GRPO reinforcement learning for
multi-hop reasoning. Composite reward balances semantic coherence with
format compliance; retrieval-grounded inference via the Exa search API.
+27% accuracy on HotpotQA over the base model, −35% VRAM via LoRA/PEFT.

`repo link: add here`

</details>

<details>
<summary><code>bhavuk@dev:~$ cat football-yolo/README.md</code></summary>
<br>

<img src="https://img.shields.io/badge/status-public-39FF14?style=flat-square&labelColor=0D1117" /> <img src="https://img.shields.io/badge/stack-YOLOv8_·_ByteTrack_·_OpenCV-39FF14?style=flat-square&labelColor=0D1117" />

**Football Match Analysis with YOLOv8**

Detects players, referees, and the ball in match footage; tracks them
with ByteTrack; clusters shirt color into two teams; estimates ball
possession and camera-corrected player speed/distance.

[→ github.com/bhavuk1409/Object-Detection-Using-Yolo](https://github.com/bhavuk1409/Object-Detection-Using-Yolo)

</details>

<details>
<summary><code>bhavuk@dev:~$ cat speech-asl/README.md</code></summary>
<br>

<img src="https://img.shields.io/badge/status-public-39FF14?style=flat-square&labelColor=0D1117" /> <img src="https://img.shields.io/badge/stack-Azure_·_Stanza_·_Gradio-39FF14?style=flat-square&labelColor=0D1117" />

**Speech-to-ASL Sign Language Converter**

Converts spoken Gujarati audio into ASL video: Azure transcribes and
translates the speech, Stanza lemmatizes the resulting English text,
and MoviePy concatenates the matching pre-recorded ASL clips.

[→ github.com/bhavuk1409/speech-asl](https://github.com/bhavuk1409/speech-asl)

</details>

<br>

```
bhavuk@dev:~$ pip list --format=freeze | grep -v "^#"
```

<table>
<tr>
<td valign="top" width="25%">

**languages**

<img src="https://img.shields.io/badge/-Python-39FF14?style=flat-square&logo=python&logoColor=0D1117&labelColor=0D1117" /><br>
<img src="https://img.shields.io/badge/-C++-39FF14?style=flat-square&logo=cplusplus&logoColor=0D1117&labelColor=0D1117" /><br>
<img src="https://img.shields.io/badge/-Java-39FF14?style=flat-square&logo=openjdk&logoColor=0D1117&labelColor=0D1117" /><br>
<img src="https://img.shields.io/badge/-SQL-39FF14?style=flat-square&logo=postgresql&logoColor=0D1117&labelColor=0D1117" />

</td>
<td valign="top" width="25%">

**ml / ai**

<img src="https://img.shields.io/badge/-PyTorch-39FF14?style=flat-square&logo=pytorch&logoColor=0D1117&labelColor=0D1117" /><br>
<img src="https://img.shields.io/badge/-TensorFlow-39FF14?style=flat-square&logo=tensorflow&logoColor=0D1117&labelColor=0D1117" /><br>
<img src="https://img.shields.io/badge/-Transformers-39FF14?style=flat-square&logo=huggingface&logoColor=0D1117&labelColor=0D1117" /><br>
<img src="https://img.shields.io/badge/-LoRA_%2F_PEFT-39FF14?style=flat-square&labelColor=0D1117" />

</td>
<td valign="top" width="25%">

**orchestration**

<img src="https://img.shields.io/badge/-LangChain-39FF14?style=flat-square&labelColor=0D1117" /><br>
<img src="https://img.shields.io/badge/-LangGraph-39FF14?style=flat-square&labelColor=0D1117" /><br>
<img src="https://img.shields.io/badge/-FastAPI-39FF14?style=flat-square&logo=fastapi&logoColor=0D1117&labelColor=0D1117" /><br>
<img src="https://img.shields.io/badge/-OpenCV-39FF14?style=flat-square&logo=opencv&logoColor=0D1117&labelColor=0D1117" />

</td>
<td valign="top" width="25%">

**infra / tools**

<img src="https://img.shields.io/badge/-Docker-39FF14?style=flat-square&logo=docker&logoColor=0D1117&labelColor=0D1117" /><br>
<img src="https://img.shields.io/badge/-Git-39FF14?style=flat-square&logo=git&logoColor=0D1117&labelColor=0D1117" /><br>
<img src="https://img.shields.io/badge/-AWS_EC2-39FF14?style=flat-square&logo=amazonaws&logoColor=0D1117&labelColor=0D1117" /><br>
<img src="https://img.shields.io/badge/-PostgreSQL-39FF14?style=flat-square&logo=postgresql&logoColor=0D1117&labelColor=0D1117" />

</td>
</tr>
</table>

```
bhavuk@dev:~$ cat achievements.txt
```

```
[x] AWS Certified AI Practitioner
[x] DeepLearning.AI — Neural Networks Specialization
[x] 350+ DSA problems solved (LeetCode)
[x] Active hackathon / coding competition participant
```

<br>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0D1117&height=2&width=800" />
</div>

```
bhavuk@dev:~$ curl -s api.github.com/users/bhavuk1409/stats | jq
```

<div align="center">
<img src="https://github-stats-extended.vercel.app/api?username=bhavuk1409&show_icons=true&hide_border=true&bg_color=0D1117&title_color=39FF14&text_color=C9D1D9&icon_color=39FF14&count_private=true" alt="stats" height="165" />
<img src="https://github-stats-extended.vercel.app/api/top-langs/?username=bhavuk1409&layout=compact&hide_border=true&bg_color=0D1117&title_color=39FF14&text_color=C9D1D9" alt="top langs" height="165" />
</div>

<div align="center">
<img src="https://streak-stats.demolab.com?user=bhavuk1409&hide_border=true&background=0D1117&stroke=39FF14&ring=39FF14&fire=39FF14&currStreakLabel=39FF14&currStreakNum=39FF14&sideLabels=C9D1D9&sideNums=C9D1D9&dates=8B949E" alt="streak" width="80%" />
</div>

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=bhavuk1409&bg_color=0D1117&color=39FF14&line=39FF14&point=C9D1D9&area=true&hide_border=true&custom_title=commit%20activity" width="98%" alt="activity graph" />
</div>

```
bhavuk@dev:~$ cat /etc/contact.conf
```

```
email     bhavukagrawal1409@gmail.com
linkedin  linkedin.com/in/bhavukagrawal1409
github    github.com/bhavuk1409
```

<div align="center">

```
bhavuk@dev:~$ █
```

<img src="https://capsule-render.vercel.app/api?type=Rect&color=0:0D1117,100:0D1117&height=3&section=footer" width="100%" />

</div>
