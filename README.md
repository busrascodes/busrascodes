## Hi there 👋
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1120,55:14304A,100:1F6F8B&height=195&section=header&text=B%C3%BC%C5%9Fra%20G%C3%BCl&fontSize=58&fontColor=ffffff&fontAlignY=36&desc=busrascodes%20%C2%B7%20protocol%20security%20and%20systems%20tooling&descAlignY=59&descSize=17&animation=fadeIn" alt="Büşra Gül">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=2900&pause=900&color=67D4F5&center=true&vCenter=true&width=800&height=52&lines=OCPP+%2B+CAN+bus+security+simulation.;PRNGs+I+chi-square+test+before+trusting.;Python+tooling%2C+C%23+when+it+is+a+game.;Small+systems+stood+up%2C+attacked%2C+measured." alt="What I build">

<p>
  <b>I build simulations that show <i>why</i> a protocol fails.</b><br>
  Systems small enough to stand up locally, attack, and measure.
</p>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white" alt="Unity">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
  <br>
  <img src="https://img.shields.io/badge/OCPP-1.6J-1F6F8B?style=flat-square" alt="OCPP 1.6J">
  <img src="https://img.shields.io/badge/CAN_bus-vcan0-1F6F8B?style=flat-square" alt="CAN bus">
  <img src="https://img.shields.io/badge/MitM-testing-1F6F8B?style=flat-square" alt="MitM testing">
  <img src="https://img.shields.io/badge/Photon-multiplayer-1F6F8B?style=flat-square" alt="Photon">
</p>

</div>

## What I work on

My code sits where a network protocol meets hardware it was never built to
defend against. One repo loops a CSMS, a charge point and a `vcan0` bus
together, drops a man-in-the-middle proxy in and logs what both sides still
believe. Another asks a chi-square test whether an LCG's output is random
before anyone calls it a key. The third is the multiplayer half. Reproduce the
system in a few hundred lines, break it on purpose, keep the numbers.

## Selected work

| Project | What it is | Stack |
|---|---|---|
| [OCPP–CAN Security](https://github.com/busrascodes/OCPP-CANSecuritySimulation-MitMAnalysisFramework) | CSMS + charge point + OCPP→CAN bridge on `vcan0`; MitM proxy reroutes the station to port 8888, with a runnable security test suite, logs and a written report. | Python · `ocpp` 0.17 · `python-can` · Linux `vcan` |
| [Collatz](https://github.com/busrascodes/Collatz) | Bit generator on an LCG (`1103515245`, `12345`, mod 2³¹), validated with chi-square over 10⁴ bits: 0.0576 against a 3.841 critical value. | Python · statistics |
| [UnityBattleBus](https://github.com/busrascodes/UnityBattleBus) | Unity multiplayer prototype on Photon Realtime and Chat; the C# worth reading lives under `Assets/`. | C# · Unity · Photon PUN |

## Toolchain

| Area | Used for |
|---|---|
| Python | Protocol clients, simulation harnesses, log parsing, test scripts |
| C# / Unity | Game prototypes and their networking layer |
| Linux | `vcan0` setup, multi-terminal runs, venvs with pinned requirements |
| In-repo docs | Pseudocode, Mermaid flowcharts and attack reports beside the code |

## How I build

- **Local reproduction over theory** — a virtual CAN bus and three terminals beat a paragraph about a vulnerability.
- **Measure before claiming** — distributions get a statistic and a critical value, not an adjective.
- **Leave the reasoning in the repo** — pseudocode, flowcharts and logs ship with the source.

## Looking at

Next on the same rig: OCPP 2.0.1 security profiles, ISO 15118 plug-and-charge,
CAN-level intrusion detection.

## Elsewhere

<a href="https://www.linkedin.com/in/b%C3%BC%C5%9Fra-g%C3%BCl-13a451221/"><img src="https://img.shields.io/badge/LinkedIn-B%C3%BC%C5%9Fra%20G%C3%BCl-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="https://github.com/busrascodes"><img src="https://img.shields.io/badge/GitHub-busrascodes-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
