# Awesome-AI-Red-Teaming-Platform

## Top AI Red Teaming Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on LLM Jailbreak Testing, Prompt Injection Probes, Adversarial Evaluation, Agent Attack Simulation & Continuous AI Security Testing*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Red Teaming**. These systems systematically attack models and agents—jailbreaks, prompt injection, data leakage, toxicity elicitation, tool abuse—to find weaknesses before adversaries do, and to feed findings into evals and guardrails.



**Examples** include Lakera, HiddenLayer, Robust Intelligence, Protect AI, SplxAI, Mindgard, CalypsoAI, Patronus AI, Zenity, Promptfoo, Aporia, NVIDIA NeMo Guardrails, Microsoft AI Red Team tooling, Virtue AI, Gray Swan AI, and Trail of Bits AI (the category leaders and adjacent practitioners).



**Open-source emphasis**: Red teaming has outstanding open tools. **garak**, **PyRIT**, **Promptfoo**, and related frameworks enable automated, CI-friendly adversarial testing. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Lakera, HiddenLayer, Protect AI, Robust Intelligence](https://www.lakera.ai/)**  

  AI security platforms offering adversarial testing, model risk assessment, and continuous red-team-style evaluation of LLMs and applications.



- **[CalypsoAI, Patronus AI, Aporia, Mindgard, SplxAI, Virtue AI, Gray Swan AI](https://www.calypsoai.com/)**  

  Platforms focused on LLM security testing, evaluation, jailbreak detection, and safety scoring for production AI systems.



- **[Zenity](https://zenity.io/)**  

  Security and governance oriented toward AI agents and copilots in enterprise environments, including attack-surface analysis.



- **[Promptfoo (Cloud / enterprise)](https://www.promptfoo.dev/)**  

  Hosted and enterprise offerings built on the open Promptfoo red-teaming and eval framework.



- **[NVIDIA & Microsoft AI Red Team ecosystems](https://www.nvidia.com/)**  

  Guardrails, research tooling, and enterprise security practices from major AI vendors (paired with open projects like garak and PyRIT).



- **[Trail of Bits & specialist AI security firms](https://www.trailofbits.com/)**  

  Expert-led AI security assessments and tooling used alongside automated red-team platforms.



- **[Other commercial AI red teaming platforms](https://www.lakera.ai/)**  

  Additional solutions for continuous adversarial testing and security reporting.



## Open-Source GitHub Projects



- **[garak (NVIDIA)](https://github.com/NVIDIA/garak)**  

  Leading open-source LLM vulnerability scanner—probe-based testing for jailbreaks, injection, leakage, toxicity, and dozens of failure modes; CLI-friendly and CI-ready (Apache 2.0).



- **[PyRIT (Microsoft)](https://github.com/Azure/PyRIT)**  

  Open-source Python Risk Identification Toolkit for generative AI—orchestrated, multi-turn, adaptive red-team campaigns used by Microsoft’s AI Red Team.



- **[Promptfoo](https://github.com/promptfoo/promptfoo)**  

  Open-source (MIT) eval and red-teaming framework—YAML-driven adversarial test generation, OWASP LLM coverage, agent/tool attacks, and CI gates.



- **[DeepTeam & report-oriented scanners](https://github.com/search?q=DeepTeam+LLM+OR+OWASP+LLM+red+team)**  

  Open tools that map findings to OWASP LLM Top 10, NIST, and MITRE ATLAS for audit-friendly reporting.



- **[HarmBench, JailbreakBench & academic harnesses](https://github.com/centerforaisafety/HarmBench)**  

  Open benchmarks and attack corpora for reproducible jailbreak and harm evaluation research.



- **[LLM Guard & defensive scanners](https://github.com/protectai/llm-guard)**  

  Open input/output scanners often used both as defenses and as signals in red-team pipelines.



- **[NeMo Guardrails (test against rails)](https://github.com/NVIDIA/NeMo-Guardrails)**  

  Open guardrail framework—red teams use it as a target to verify whether policy rails hold under attack.



- **[Custom attack libraries & TAP/Crescendo implementations](https://github.com/search?q=jailbreak+OR+prompt+injection+attack+LLM+open+source)**  

  Community implementations of multi-turn and automated jailbreak strategies for advanced testing.



### Additional Strong Open-Source Options



- **Broad scan**: garak for fast, wide vulnerability coverage.

- **Adaptive multi-turn**: PyRIT for campaign-style attacks on agents and chat apps.

- **CI red team**: Promptfoo for config-driven adversarial suites in every PR.

- **Benchmarks**: HarmBench/JailbreakBench for comparable scores across models.

- **Composable stacks**: garak/Promptfoo in CI + PyRIT for deep dives + findings → eval datasets.

- Commercial platforms still lead in managed threat intel, continuous scanning, and enterprise reporting.



**Frameworks for building custom systems**:  

**garak**, **PyRIT**, and **Promptfoo** are the core open red-teaming toolkit.  

Feed successful attacks into evaluation datasets and harden with **NeMo Guardrails** / **LLM Guard**.  

Commercial platforms (Lakera, HiddenLayer, Protect AI, CalypsoAI, Patronus, etc.) provide continuous testing and specialist expertise.  

Best practice: open tools for automated regression; commercial or expert red teams for periodic deep assessments. Fully open red-team pipelines are production-viable for continuous security testing.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Only red-team systems you own or have explicit authorization to test. Adversarial prompts can produce harmful content—handle outputs carefully and comply with law and platform policies.

- Passing a red-team suite does not prove a system is safe. Combine automated testing with human expertise, guardrails, and monitoring. Open-source tools require you to interpret and act on findings; commercial platforms shift some operational burden to the vendor.



---



**Made for AI security engineers, red teams, and builders hardening LLMs and agents.**  

Let's expand open, rigorous AI red teaming while recognizing the continuous coverage and expertise that leading commercial platforms deliver.
