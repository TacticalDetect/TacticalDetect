<!--
**TacticalDetect/TacticalDetect** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
Banner: replace the user-attachments URL below with assets/tacticaldetect_four_moves.png once the image is committed to this repo.
--->

<div align="center">
  <img src="https://github.com/user-attachments/assets/eb52b89a-3aa9-4d06-b552-d5d305581ab4" alt="TacticalDetect" width="100%"/>
</div>

<h2 align="center">🔍 Whoami</h2>
<p align="center">
  <samp>
  Lead Threat Hunter at an MDR firm, with 12+ years across military cyber operations and enterprise defense. I lead hunts across hundreds of client environments on Splunk-based SIEMs, and I write about the part most hunt reports skip. Most hunts end with nothing found. The hard part is knowing whether that means the environment is clean or the telemetry never showed you the answer.
  </samp>
  <br><br>
  <samp>Detection Engineering | Link Analysis | Unsupervised ML | Splunk | MITRE ATT&CK</samp>
  <br><br>
</p>
<hr>

<h2 align="center">🧭 How I Hunt</h2>
<p align="center">
  <samp>Author of a security analytics framework built on a 6W data model, a Four-Lens Visualization Grammar, and one principle. Hunt what the attacker cannot avoid. Identities rotate. Mechanisms persist.</samp>
</p>

<table>
<tr>
<td width="25%" align="center">

**📊 Statistical Lens**
<br>
Prevalence, rarity, and baselines that tell you how unusual a behavior is

</td>
<td width="25%" align="center">

**🕸️ Relationship Lens**
<br>
Property graphs that show what tables obscure

</td>
<td width="25%" align="center">

**🧩 Semantic Lens**
<br>
Behavioral clustering across low-fidelity observations

</td>
<td width="25%" align="center">

**⏱️ Temporal Lens**
<br>
Sequence and timing that turn clusters into an intrusion story

</td>
</tr>
</table>

<p align="center">
  <samp>The questions an analyst must answer drive the data model. Three or more behavior clusters start to tell an intrusion story. Investigations run from first harm signal forward to worst case, then backward to fill gaps until the narrative is complete.</samp>
</p>
<hr>

<h2 align="center">📉 Why Finding Nothing Is a Result</h2>

```mermaid
flowchart LR
    Q([Operator's<br>question]) --> M[Data model]
    M --> L[Four lenses]
    L --> C{Behavior<br>clusters?}
    C -->|three or more| S[Intrusion<br>story]
    C -->|none| N{{Nothing found}}
    N --> G{Could the<br>telemetry<br>show it?}
    G -->|yes| E[Clean]
    G -->|no| B[Blind spot]
    S --> V([Verdict<br>a person])
    E --> V
    B --> V
    B -.->|close the gap| M

    classDef fork fill:#42c767,stroke:#1a3a52,color:#101320,stroke-width:2px
    classDef base fill:#1a3a52,stroke:#1a3a52,color:#ffffff
    classDef blind fill:#ffffff,stroke:#e74c3c,color:#2d3436,stroke-dasharray:4 2
    class N fork
    class Q,M,L,C,S,G,E,V base
    class B blind
```

<p align="center">
  <samp>Most hunts end with nothing found. The hard part is knowing which branch you are on.</samp>
</p>
<hr>

<h2 align="center">🛠️ Tools of Trade</h2>

<h3 align="center">Security Platforms</h3>
<p align="center">
  <img src="https://img.shields.io/badge/Splunk%20-%23000000.svg?&style=for-the-badge&logo=splunk&logoColor=white" />&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/Microsoft_Sentinel%20-%230078D4.svg?&style=for-the-badge&logo=microsoft-azure&logoColor=white" />&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/CrowdStrike%20-%23E01F27.svg?&style=for-the-badge&logo=crowdstrike&logoColor=white" />&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/Google_Security_Operations%20-%234285F4.svg?&style=for-the-badge&logo=google-cloud&logoColor=white" />&nbsp;&nbsp;
</p>

<h3 align="center">Query Languages</h3>
<p align="center">
  <img src="https://img.shields.io/badge/SPL%20%2F%20SPL2%20(Splunk)-%23000000.svg?&style=for-the-badge&logo=splunk&logoColor=white" />&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/KQL%20(Kusto)-%230078D4.svg?&style=for-the-badge&logo=microsoftazure&logoColor=white" />&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/CQL%20(CrowdStrike)-%23E01F27.svg?&style=for-the-badge&logo=crowdstrike&logoColor=white" />&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/YARA--L%20(Google)-%234285F4.svg?&style=for-the-badge&logo=google&logoColor=white" />&nbsp;&nbsp;
</p>

<h3 align="center">Threat Intelligence & Analysis</h3>
<p align="center">
  <img src="https://img.shields.io/badge/MITRE_ATT%26CK-%231a3a52.svg?&style=for-the-badge&logoColor=white" />&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/VirusTotal-%23394EFF.svg?&style=for-the-badge&logo=virustotal&logoColor=white" />&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/OpenCTI-%231a3a52.svg?&style=for-the-badge&logoColor=white" />&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/STIX_2.1-%231a3a52.svg?&style=for-the-badge&logoColor=white" />&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/Shodan-%231a3a52.svg?&style=for-the-badge&logoColor=white" />&nbsp;&nbsp;
</p>

<h3 align="center">Development & Automation</h3>
<p align="center">
  <img src="https://img.shields.io/badge/Python-%233776AB.svg?&style=for-the-badge&logo=python&logoColor=white" />&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/PowerShell-%235391FE.svg?&style=for-the-badge&logo=powershell&logoColor=white" />&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/Docker-%232496ED.svg?&style=for-the-badge&logo=docker&logoColor=white" />&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/Vagrant-%231563FF.svg?&style=for-the-badge&logo=vagrant&logoColor=white" />&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/Ansible-%23EE0000.svg?&style=for-the-badge&logo=ansible&logoColor=white" />&nbsp;&nbsp;
</p>

<h3 align="center">Visualization & Analytics</h3>
<p align="center">
  <img src="https://img.shields.io/badge/Splunk_Network_Diagram_Viz-%231a3a52.svg?&style=for-the-badge&logoColor=white" />&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/D3.js-%23F68212.svg?&style=for-the-badge&logo=d3.js&logoColor=white" />&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/Vis.js-%234FC08D.svg?&style=for-the-badge&logoColor=white" />&nbsp;&nbsp;
</p>
<hr>

<h2 align="center">💡 Current Focus</h2>
<p align="center">
  <samp>
    🕸️ TacticalGraph, a property graph investigation layer built on Splunk Network Diagram Viz<br>
    📉 Confirmed negatives, or why finding nothing can mean the hunt worked<br>
    🧩 Role resolution, telling who participated in a behavior from who merely got mentioned<br>
    🤖 Where AI belongs in a hunt. The search does the math, AI helps plan and read, a person owns the verdict<br>
    🧰 A skill library for hunt mission planning, graph construction, SPL, SPL2, and KQL hunting<br>
  </samp>
</p>
<hr>

<h2 align="center">📝 Writing & Research</h2>
<p align="center">
  <samp>
    <b>Can't Hide in 3D</b> (THOR Collective Dispatch, Sep 2025)<br>
    <b>Trojan Packages</b> (Deepwatch, Oct 2025)<br>
    <b>Your Device Code Phishing Detection Probably Doesn't Work</b> (Deepwatch, May 2026)<br>
    <b>Five Ideas, One Hunt</b> (TacticalDetect Substack, Oct 2026)<br>
    <br>
    "Can't Hide in 3D" is among the first practical SPL implementations of MITRE's Time-Terrain-Behavior framework. Featured in Detection Engineering Weekly's "State of the Art" and extended in <i>Advanced Cyber Threat Intelligence and Hunting</i> (Tiepolo and Sorensen, Packt, 2026).<br>
    Expert commentary cited across the Wall Street Journal, CSO Online, Dark Reading, SC World, MSSP Alert, and PCMag. 14 citations across 10 publications.
  </samp>
</p>
<p align="center">
  <a target="_blank" href="https://tacticaldetect.substack.com/about"><img src="https://img.shields.io/badge/TacticalDetect_Blog-%2342c767.svg?&style=for-the-badge&logo=substack&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;
  <a target="_blank" href="https://tacticaldetect.substack.com/p/five-ideas-one-hunt"><img src="https://img.shields.io/badge/Five_Ideas,_One_Hunt-%234a9fd8.svg?&style=for-the-badge&logoColor=white" /></a>
</p>
<hr>

<h2 align="center">🔍 Projects & Tools</h2>
<p align="center">
  <a href="https://github.com/TacticalDetect/TTB_BOTS_v2">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=TacticalDetect&repo=TTB_BOTS_v2&theme=dark" />
  </a>
</p>
<p align="center">
  <samp>The SPL behind "Can't Hide in 3D", MIT licensed.</samp>
</p>
<hr>

<h2 align="center">📫 Connect</h2>
<p align="center">
  <a target="_blank" href="https://www.linkedin.com/in/certisf/"><img src="https://img.shields.io/badge/LinkedIn-%231a3a52.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;&nbsp;
</p>
<hr>

<p align="center">
  <samp><i>I am an employee of Deepwatch. All comments, posts, and thoughts are my own and do not necessarily reflect the positions, strategies, or opinions of the company.</i></samp>
</p>
