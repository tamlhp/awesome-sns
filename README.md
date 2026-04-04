# Awesome Social Network Simulation: From Small Worlds to Agentic AI

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/tamlhp/awesome-sns?style=social)](https://github.com/tamlhp/awesome-sns/stargazers)
![visitors](https://visitor-badge.laobi.icu/badge?page_id=tamlhp.awesome-sns)
<img src="https://img.shields.io/badge/Contributions-Welcome-278ea5" alt="Contrib"/>

A collection of academic articles, published methodology, and datasets on the subject of **Social Network Simulation** from classical models to LLM-based agentic simulation.

<!-- This README follows the manuscript structure directly: five paradigm sections with one paper table per paradigm, followed by dedicated dataset/benchmark and evaluation-metric sections. The survey spans 97 papers across 1951-2026, five application domains, 38 implementations, 21 benchmarks/datasets, and 22 evaluation metrics. -->

<!-- The manuscript metadata currently still contains placeholder ACM DOI and venue fields, so this repository intentionally avoids unverified publication claims until a public paper link is finalized. -->

- [Taxonomy](#taxonomy)
- [Network Models](#network-models)
- [Information Diffusion](#information-diffusion)
- [Opinion Dynamics](#opinion-dynamics)
- [Rule-Based Agent-Based Models](#rule-based-agent-based-models)
- [LLM-Based Agentic Simulation](#llm-based-agentic-simulation)
- [Datasets and Benchmarks](#datasets-and-benchmarks)
- [Evaluation Metrics](#evaluation-metrics)
- [Contributing](#contributing)

<!-- ## Citation

If you use this repository, please cite the survey manuscript. A public DOI or finalized venue entry will be added once the paper metadata is finalized.

```bibtex
@misc{pham2026social-network-simulation,
  title = {A Survey of Social Network Simulation: From Small Worlds to Agentic AI},
  author = {Pham, Trinh and Nguyen, Quoc Viet Hung and Yin, Hongzhi and Nguyen, Thanh Tam},
  year = {2026},
  note = {Survey manuscript},
  url = {https://github.com/tamlhp/awesome-sns}
}
``` -->

## Taxonomy

![Hierarchical taxonomy of social network simulation](figs/sns-matrix.png)

The survey organizes the field into five paradigm families:

- **Network Models**: topology generation and structural analysis for synthetic social graphs.
- **Information Diffusion**: epidemic, cascade, influence, rumor, and control models.
- **Opinion Dynamics**: averaging, bounded-confidence, polarization, and echo-chamber models.
- **Rule-Based Agent-Based Models**: heterogeneous bottom-up simulation with explicit agent rules.
- **LLM-Based Agentic Simulation**: persona-grounded, memory-enabled, language-driven social agents.

Each table below is grounded in the manuscript citations and keeps the paper title, year, category, venue, and repository or project link visible for quick scanning. Paper titles link to official publication or publisher pages when confidently resolved.

## Network Models

| Paper | Year | Category | Venue | Code |
| --- | --- | --- | --- | --- |
| [Homophily in An Artificial Social Network of Agents Powered By Large Language Models](https://doi.org/10.21203/rs.3.rs-3096289/v1) | 2023 | Attribute-driven generators | Br. J. Psychol. | - |
| Network segregation in a model of misinformation and fact-checking | 2016 | Attribute-driven generators | JCSS | - |
| [Social network analysis and agent-based modeling in social epidemiology](https://doi.org/10.1186/1742-5573-9-1) | 2012 | Exponential random graph models (ERGMs) | Epidemiol. Perspect. Innov. | - |
| [Maximizing the Spread of Influence through a Social Network](https://doi.org/10.1145/956750.956769) | 2003 | Scale-Free Networks | KDD | - |
| [The Structure and Function of Complex Networks](https://doi.org/10.1137/s003614450342480) | 2003 | Random Graph Models | SIAM Review | - |
| [Emergence of Scaling in Random Networks](https://doi.org/10.1126/science.286.5439.509) | 1999 | Scale-Free Networks | Science | - |
| [Collective dynamics of `small-world' networks](https://doi.org/10.1038/30918) | 1998 | Small-World Networks | Nature | - |
| [Social Network Effects on the Extent of Innovation Diffusion: A Computer Simulation](https://doi.org/10.1287/orsc.8.3.289) | 1997 | Attribute-driven generators | Organ. Sci. | - |
| [The Small World Problem](https://doi.org/10.1037/e400002009-005) | 1967 | Small-World Networks | Psychology Today | - |
| [Diffusion of Innovations](https://books.google.com/books/about/Diffusion_of_Innovations.html?id=9U1K5LjUOwEC) | 1962 | Attribute-driven generators | Free Press | - |
| On Random Graphs I | 1959 | Random Graph Models | Publ. Math. Debrecen | - |

## Information Diffusion

| Paper | Year | Category | Venue | Code |
| --- | --- | --- | --- | --- |
| [CSRT rumor spreading model based on complex network](https://doi.org/10.1002/int.22365) | 2021 | Epidemic Compartment Models | IJIS | - |
| [Dynamical behaviors and control measures of rumor-spreading model in consideration of the infected media and time delay](https://doi.org/10.1016/j.ins.2021.02.047) | 2021 | Competitive and Rumor Dynamics | Inf. Sci. | - |
| [Users' mobility enhances information diffusion in online social networks](https://doi.org/10.1016/j.ins.2020.07.061) | 2021 | Cascade Models: Independent Cascade and Linear Threshold | Inf. Sci. | - |
| [Rumor Spreading Model Considering Individual Activity and Refutation Mechanism Simultaneously](https://doi.org/10.1109/access.2020.2983249) | 2020 | Competitive and Rumor Dynamics | IEEE Access | - |
| [The stochastic evolution of a rumor spreading model with two distinct spread inhibiting and attitude adjusting mechanisms in a homogeneous social network](https://doi.org/10.1016/j.physa.2020.125321) | 2020 | Epidemic Compartment Models | Physica A | - |
| [Dynamical analysis of a IWSR rumor spreading model with considering the self-growth mechanism and indiscernible degree](https://doi.org/10.1016/j.physa.2019.04.176) | 2019 | Epidemic Compartment Models | Physica A | - |
| [Global dynamics analysis and control of a rumor spreading model in online social networks](https://doi.org/10.1016/j.physa.2019.04.139) | 2019 | Competitive and Rumor Dynamics | Physica A | - |
| [ILSR rumor spreading model with degree in complex network](https://doi.org/10.1016/j.physa.2019.121807) | 2019 | Epidemic Compartment Models | Physica A | - |
| Optimal Control of Rumor Spreading Model on Homogeneous Social Network with Consideration of Influence Delay of Thinkers | 2019 | Competitive and Rumor Dynamics | DEDS | - |
| [The impact of group propagation on rumor spreading in mobile social networks](https://doi.org/10.1016/j.physa.2018.04.038) | 2018 | Competitive and Rumor Dynamics | Physica A | - |
| [The Spread of True and False News Online](https://doi.org/10.1126/science.aap9559) | 2018 | Competitive and Rumor Dynamics | Science | - |
| [SEIR Model of Rumor Spreading in Online Social Network with Varying Total Population Size](https://doi.org/10.1088/0253-6102/68/4/545) | 2017 | Epidemic Compartment Models | Commun. Theor. Phys. | - |
| [Stability analysis and control models for rumor spreading in online social networks](https://doi.org/10.1142/s0129183117500619) | 2017 | Competitive and Rumor Dynamics | Int. J. Mod. Phys. C | - |
| Network segregation in a model of misinformation and fact-checking | 2016 | Competitive and Rumor Dynamics | JCSS | - |
| [A SIMULATION-BASED APPROACH TO ANALYZE THE INFORMATION DIFFUSION IN MICROBLOGGING ONLINE SOCIAL NETWORK](https://doi.org/10.1109/wsc.2013.6721550) | 2013 | Cascade Models: Independent Cascade and Linear Threshold | - | - |
| [How to Identify an Infection Source With Limited Observations](https://doi.org/10.1109/jstsp.2014.2315533) | 2013 | Cascade Models: Independent Cascade and Linear Threshold | IEEE JSTSP | - |
| [INFORMATION DIFFUSION IN FACEBOOK-LIKE SOCIAL NETWORKS UNDER INFORMATION OVERLOAD](https://doi.org/10.1142/s0129183113500472) | 2013 | Cascade Models: Independent Cascade and Linear Threshold | Int. J. Mod. Phys. C | - |
| [Information diffusion model for spread of misinformation in online social networks](https://doi.org/10.1109/icacci.2013.6637343) | 2013 | Competitive and Rumor Dynamics | ICACCI | - |
| [Measuring trustworthiness of information diffusion by risk discovery process in social networking services](https://doi.org/10.1007/s11135-013-9837-1) | 2013 | Competitive and Rumor Dynamics | Qual. Quant. | - |
| [Influential Neighbours Selection for Information Diffusion in Online Social Networks](https://doi.org/10.1109/icccn.2012.6289230) | 2012 | Cascade Models: Independent Cascade and Linear Threshold | ICCCN | - |
| [SIHR rumor spreading model in social networks](https://doi.org/10.1016/j.physa.2011.12.008) | 2012 | Epidemic Compartment Models | Physica A | - |
| A game theoretical approach to broadcast information diffusion in social networks | 2011 | Cascade Models: Independent Cascade and Linear Threshold | SpringSim | - |
| Simulation Investigation of Rumor Propagation in Microblogging Community | 2011 | Epidemic Compartment Models | Computer Engineering | - |
| [Maximizing the Spread of Influence through a Social Network](https://doi.org/10.1145/956750.956769) | 2003 | Cascade Models: Independent Cascade and Linear Threshold | KDD | - |
| [A Theory of Fads, Fashion, Custom, and Cultural Change as Informational Cascades](https://doi.org/10.1086/261849) | 1992 | Cascade Models: Independent Cascade and Linear Threshold | JPE | - |
| [Threshold Models of Collective Behavior](https://doi.org/10.1086/226707) | 1978 | Cascade Models: Independent Cascade and Linear Threshold | Am. J. Sociol. | - |
| [Diffusion of Innovations](https://books.google.com/books/about/Diffusion_of_Innovations.html?id=9U1K5LjUOwEC) | 1962 | Information Diffusion | Free Press | - |

## Opinion Dynamics

| Paper | Year | Category | Venue | Code |
| --- | --- | --- | --- | --- |
| [Extending the Hegselmann-Krause Model of Opinion Dynamics to include AI Oracles](https://arxiv.org/abs/2502.19701) | 2025 | Averaging Models: French-DeGroot and Friedkin-Johnsen | arXiv | - |
| [Opinion Dynamics and Collective Risk Perception: An Agent-Based Model of Institutional and Media Communication About Disasters](https://doi.org/10.18564/jasss.4479) | 2021 | Extensions and Modern Directions | JASSS | - |
| [Modeling Public Opinion Polarization in Group Behavior by Integrating SIRS-Based Information Diffusion Process](https://doi.org/10.1155/2020/4791527) | 2020 | Bounded Confidence: Deffuant and Hegselmann-Krause | Complexity | - |
| [Progressive Information Polarization in a Complex-Network Entropic Social Dynamics Model](https://doi.org/10.1109/access.2019.2902400) | 2019 | Bounded Confidence: Deffuant and Hegselmann-Krause | IEEE Access | - |
| Spiral of Silence in the Social Media Era: A Simulation Approach to the Interplay Between Social Networks and Mass Media | 2019 | Discrete and Stochastic Models | Communication Research | - |
| Opinion dynamics and bounded confidence: models, analysis and simulation | 2002 | Bounded Confidence: Deffuant and Hegselmann-Krause | JASSS | - |
| [Mixing beliefs among interacting agents](https://doi.org/10.1142/s0219525900000078) | 2000 | Bounded Confidence: Deffuant and Hegselmann-Krause | Adv. Complex Syst. | - |
| [Social Influence and Opinions](https://doi.org/10.1080/0022250x.1990.9990069) | 1990 | Averaging Models: French-DeGroot and Friedkin-Johnsen | J. Math. Sociol. | - |
| [Reaching a Consensus](https://doi.org/10.1080/01621459.1974.10480137) | 1974 | Averaging Models: French-DeGroot and Friedkin-Johnsen | JASA | - |
| [A formal theory of social power](https://doi.org/10.1037/h0046123) | 1956 | Averaging Models: French-DeGroot and Friedkin-Johnsen | Psychol. Rev. | - |

## Rule-Based Agent-Based Models

| Paper | Year | Category | Venue | Code |
| --- | --- | --- | --- | --- |
| [The (Mis)Information Game: A social media simulator](https://doi.org/10.3758/s13428-023-02153-x) | 2024 | Other ABM diffusion studies | Behav. Res. Methods | [Code](https://github.com/TheMisinformationGame/MisinformationGame) |
| [Effect of Seeding Strategy on the Efficiency of Brand Spreading in Complex Social Networks](https://doi.org/10.3389/fpsyg.2022.879274) | 2022 | Other ABM diffusion studies | Front. Psychol. | - |
| [Utilizing Python for Agent-Based Modeling: The Mesa Framework](https://doi.org/10.1007/978-3-030-61255-9_30) | 2020 | Implementation Frameworks | SCS | [Code](https://github.com/projectmesa/mesa) |
| WES: Agent-based User Interaction Simulation on Real Infrastructure | 2020 | Other ABM diffusion studies | ICSEW | - |
| [Agent Based Simulation of Bot Disinformation Maneuvers in Twitter](https://doi.org/10.1109/wsc40007.2019.9004942) | 2019 | Bot-driven disinformation | WSC | - |
| [Discrete Event System Specification-based framework for modeling and simulation of propagation phenomena in social networks: application to the information spreading in a multi-layer social network](https://doi.org/10.1177/0037549718776368) | 2019 | DEVS-based scheduling | SIMULATION | - |
| [Simulating and evaluating generative modeling and collaborative filtering in complex social networks](https://doi.org/10.65109/vmiv4632) | 2019 | Other ABM diffusion studies | CCS | - |
| [Policy simulation for promoting residential PV considering anecdotal information exchanges based on social network modelling](https://doi.org/10.1016/j.apenergy.2018.04.028) | 2018 | Other ABM diffusion studies | Appl. Energy | - |
| [A Survey of Agent-Based Approach of Complex Networks](https://doi.org/10.5455/ey.35900) | 2016 | Implementation Frameworks | Ekonomik Yaklasim | - |
| [Which Models Are Used in Social Simulation to Generate Social Networks? A Review of 17 Years of Publications in JASSS](https://doi.org/10.1109/wsc.2015.7408556) | 2015 | Implementation Frameworks | WSC | - |
| [An Agent-Based Model of Urgent Diffusion in Social Media](https://doi.org/10.2139/ssrn.2297167) | 2013 | Urgent diffusion | JASSS | - |
| [Complex adaptive systems modeling with Repast Simphony](https://doi.org/10.1186/2194-3206-1-3) | 2013 | Implementation Frameworks | Complex Adapt. Syst. Model. | [Code](https://github.com/Repast/repast.simphony) |
| [Large-Scale Multi-agent-Based Modeling and Simulation of Microblogging-Based Online Social Network](https://doi.org/10.1007/978-3-642-54783-6_2) | 2013 | Other ABM diffusion studies | mAbs | - |
| [Social network analysis and agent-based modeling in social epidemiology](https://doi.org/10.1186/1742-5573-9-1) | 2012 | Real-infrastructure simulation | Epidemiol. Perspect. Innov. | - |
| [Why Do People Use Social Media? Agent-Based Simulation and Population Dynamics Analysis of the Evolution of Cooperation in Social Media](https://doi.org/10.1109/wi-iat.2012.191) | 2012 | Other ABM diffusion studies | WI-IAT | - |
| [The Spread of Behavior in an Online Social Network Experiment](https://doi.org/10.1126/science.1185231) | 2010 | Complex contagion | Science | - |
| [MASON: A Multiagent Simulation Environment](https://doi.org/10.1177/0037549705058073) | 2005 | Implementation Frameworks | Simulation | [Code](https://github.com/eclab/mason) |
| [NetLogo](https://ccl.northwestern.edu/netlogo/) | 1999 | Implementation Frameworks | - | [Code](https://github.com/NetLogo/NetLogo) |
| [Collective dynamics of `small-world' networks](https://doi.org/10.1038/30918) | 1998 | Complex contagion | Nature | - |
| [Growing Artificial Societies: Social Science from the Bottom Up](https://mitpress.mit.edu/9780262550253/growing-artificial-societies/) | 1996 | Sugarscape | MIT Press | - |
| [Micromotives and Macrobehavior](https://wwnorton.com/books/9780393092677) | 1978 | Schelling segregation | W. W. Norton & Company | - |

## LLM-Based Agentic Simulation

| Paper | Year | Category | Venue | Code |
| --- | --- | --- | --- | --- |
| [Ahead of the Spread: Agent-Driven Virtual Propagation for Early Fake News Detection](https://arxiv.org/abs/2601.02750) | 2026 | Misinformation and bot dynamics | arXiv | - |
| [Towards Simulating Social Media Users with LLMs: Evaluating the Operational Validity of Conditioned Comment Prediction](https://doi.org/10.18653/v1/2026.wassa-1.16) | 2026 | Language-grounded cognition | - | - |
| [VIRENA: Virtual Arena for Research, Education, and Democratic Innovation](https://arxiv.org/abs/2602.12207) | 2026 | Platform-level systems | - | - |
| [AgentSociety: Large-Scale Simulation of LLM-Driven Generative Agents Advances Understanding of Human Behaviors and Society](https://arxiv.org/abs/2502.08691) | 2025 | Toward artificial societies | arXiv | [Code](https://github.com/tsinghua-fib-lab/AgentSociety) |
| AI Metropolis: Scaling Large Language Model-based Multi-Agent Simulation with Out-of-order Execution | 2025 | Multi-Agent Coordination and Communication | MLSys | - |
| [Attention Mechanism for LLM-based Agents Dynamic Diffusion under Information Asymmetry](https://arxiv.org/abs/2502.13160) | 2025 | Platform-level systems | arXiv | - |
| [BotSim: LLM-Powered Malicious Social Botnet Simulation](https://doi.org/10.1609/aaai.v39i13.33575) | 2025 | Action spaces | AAAI | [Code](https://github.com/QQQQQQBY/BotSim) |
| [Can Generative Agent-Based Modeling Replicate the Friendship Paradox in Social Media Simulations?](https://doi.org/10.1145/3717867.3717895) | 2025 | Network structure emergence | WebSci | - |
| [Can LLMs Simulate Social Media Engagement? A Study on Action-Guided Response Generation](https://arxiv.org/abs/2502.12073) | 2025 | Language-grounded cognition | arXiv | - |
| [Can We Fix Social Media? Testing Prosocial Interventions using Generative Social Simulation](https://arxiv.org/abs/2508.03385) | 2025 | Prosocial interventions and political opinion | arXiv | - |
| Decoding Echo Chambers: LLM-Powered Simulations Revealing Polarization in Social Networks | 2025 | Echo-chamber metrics | COLING | - |
| [Extending the Hegselmann-Krause Model of Opinion Dynamics to include AI Oracles](https://arxiv.org/abs/2502.19701) | 2025 | Reproducing and extending classical phenomena | arXiv | - |
| [GA-S3: Comprehensive Social Network Simulation with Group Agents](https://doi.org/10.18653/v1/2025.findings-acl.468) | 2025 | Multi-Agent Coordination and Communication | Findings of ACL | [Code](https://github.com/AI4SS/GAS-3) |
| [Large Language Model Driven Agents for Simulating Echo Chamber Formation](https://arxiv.org/abs/2502.18138) | 2025 | LLM as a drop-in replacement for classical update rules | arXiv | - |
| [LLM-Based Multi-Agent Systems are Scalable Graph Generative Models](https://doi.org/10.18653/v1/2025.findings-acl.78) | 2025 | Scalable agent coordination | ACL | - |
| [MegaAgent: A Large-Scale Autonomous LLM-based Multi-Agent System Without Predefined SOPs](https://doi.org/10.18653/v1/2025.findings-acl.259) | 2025 | Scalable agent coordination | Findings of ACL | [Code](https://github.com/Xtra-Computing/MegaAgent) |
| [MTOS: A LLM-Driven Multi-topic Opinion Simulation Framework for Exploring Echo Chamber Dynamics](https://arxiv.org/abs/2510.12423) | 2025 | Multi-topic opinion dynamics with bounded confidence | arXiv | - |
| [Network Formation and Dynamics Among Multi-LLMs](https://doi.org/10.1093/pnasnexus/pgaf317) | 2025 | Emergent networks | PNAS Nexus | - |
| [RumorSphere: A Framework for Million-scale Agent-based Dynamic Simulation of Rumor Propagation](https://arxiv.org/abs/2509.02172) | 2025 | Hybrid topology with adaptive role switching | - | - |
| [Simulating Rumor Spreading in Social Networks using LLM Agents](https://arxiv.org/abs/2502.01450) | 2025 | Platform-level systems | - | - |
| [User Behavior Simulation with Large Language Model-based Agents](https://doi.org/10.1145/3708985) | 2025 | Persona and Identity Grounding | TOIS | - |
| Affordable Generative Agents | 2024 | Cost-efficient inference | TMLR | [Code](https://github.com/AffordableGenerativeAgents/Affordable-Generative-Agents) |
| [Can Large Language Model Agents Simulate Human Trust Behavior?](https://doi.org/10.52202/079017-0501) | 2024 | Emergent social phenomena | NeurIPS | - |
| [ElectionSim: Massive Population Election Simulation Powered by Large Language Model Driven Agents](https://arxiv.org/abs/2410.20746) | 2024 | Persona and Identity Grounding | arXiv | [Code](https://github.com/amazingljy1206/ElectionSim) |
| Emergence of Social Norms in Generative Agent Societies: Principles and Architecture | 2024 | Norm emergence | IJCAI | - |
| [Exploring Collaboration Mechanisms for LLM Agents: A Social Psychology View](https://doi.org/10.18653/v1/2024.acl-long.782) | 2024 | Multi-Agent Coordination and Communication | ACL | - |
| From skepticism to acceptance: simulating the attitude dynamics toward fake news | 2024 | Misinformation and bot dynamics | IJCAI | [Code](https://github.com/LiuYuHan31/FPS) |
| [Large Language Model-driven Multi-Agent Simulation for News Diffusion Under Different Network Structures](https://arxiv.org/abs/2410.15557) | 2024 | Exogenous static networks | arXiv | - |
| [Oasis: Open agent social interaction simulations with one million agents](https://arxiv.org/abs/2411.11581) | 2024 | Planning and Goal-Directed Action | arXiv | [Code](https://github.com/camel-ai/oasis) |
| [Project Sid: Many-agent simulations toward AI civilization](https://arxiv.org/abs/2411.00114) | 2024 | Toward artificial societies | arXiv | - |
| [Shall We Team Up: Exploring Spontaneous Cooperation of Competing LLM Agents](https://doi.org/10.18653/v1/2024.findings-emnlp.297) | 2024 | Emergent social phenomena | EMNLP | - |
| [Simulating Opinion Dynamics with Networks of LLM-based Agents](https://doi.org/10.18653/v1/2024.findings-naacl.211) | 2024 | Multi-Agent Coordination and Communication | Findings of NAACL | [Code](https://github.com/yunshiuan/llm-agent-opinion-dynamics) |
| Sotopia: Interactive evaluation for social intelligence in language agents | 2024 | Emergent social phenomena | ICLR | [Code](https://github.com/sotopia-lab/sotopia) |
| [The Stepwise Deception: Simulating the Evolution from True News to Fake News with LLM Agents](https://doi.org/10.18653/v1/2025.emnlp-main.1330) | 2024 | Misinformation and bot dynamics | EMNLP | [Code](https://github.com/LiuYuHan31/FUSE) |
| [Unveiling the Truth and Facilitating Change: Towards Agent-based Large-scale Social Movement Simulation](https://doi.org/10.18653/v1/2024.findings-acl.285) | 2024 | Prosocial interventions and political opinion | ACL | [Code](https://github.com/xymou/HiSim) |
| [Very Large-Scale Multi-Agent Simulation in AgentScope](https://arxiv.org/abs/2407.17789) | 2024 | Cost-efficient inference | arXiv | [Code](https://github.com/modelscope/agentscope) |
| [Y Social: an LLM-powered Social Media Digital Twin](https://arxiv.org/abs/2409.07925) | 2024 | Memory: Episodic, Semantic, and Reflective | arXiv | [Code](https://github.com/YSocialTwin/YSocial) |
| [Emergence of Scale-Free Networks in Social Interactions among Large Language Models](https://arxiv.org/abs/2312.06619) | 2023 | Emergent networks | arXiv | - |
| [Generative agents: Interactive simulacra of human behavior](https://doi.org/10.1145/3586183.3606763) | 2023 | Agent Architecture for Social Simulation | UIST | [Code](https://github.com/joonspk-research/generative_agents) |
| [Homophily in An Artificial Social Network of Agents Powered By Large Language Models](https://doi.org/10.21203/rs.3.rs-3096289/v1) | 2023 | Emergent networks | Br. J. Psychol. | - |
| [Humanoid Agents: Platform for Simulating Human-like Generative Agents](https://doi.org/10.18653/v1/2023.emnlp-demo.15) | 2023 | Persona and Identity Grounding | EMNLP | [Code](https://github.com/HumanoidAgents/HumanoidAgents) |
| [S3: Social-network Simulation System with Large Language Model-Empowered Agents](https://arxiv.org/abs/2307.14984) | 2023 | Memory: Episodic, Semantic, and Reflective | arXiv | - |
| [Simulating Social Media Using Large Language Models to Evaluate Alternative News Feed Algorithms](https://arxiv.org/abs/2310.05984) | 2023 | Multi-Agent Coordination and Communication | arXiv | - |
| [Theory of Mind for Multi-Agent Collaboration via Large Language Models](https://doi.org/10.18653/v1/2023.emnlp-main.13) | 2023 | Planning and Goal-Directed Action | EMNLP | - |
| [War and peace (waragent): Large language model-based multi-agent simulation of world wars](https://arxiv.org/abs/2311.17227) | 2023 | Planning and Goal-Directed Action | arXiv | [Code](https://github.com/agiresearch/WarAgent) |
| [Social Simulacra: Creating Populated Prototypes for Social Computing Systems](https://doi.org/10.1145/3526113.3545616) | 2022 | Agent Architecture for Social Simulation | UIST | - |
| [Growing Artificial Societies: Social Science from the Bottom Up](https://mitpress.mit.edu/9780262550253/growing-artificial-societies/) | 1996 | Toward artificial societies | MIT Press | - |
| [Micromotives and Macrobehavior](https://wwnorton.com/books/9780393092677) | 1978 | Norm emergence | W. W. Norton & Company | - |

## Datasets and Benchmarks

The survey catalogues 21 published datasets and benchmarks for validating structural fidelity, temporal dynamics, behavioral realism, and platform-scale effects. The table below highlights the main benchmark families surfaced in the paper appendix.

| Benchmark / Dataset | Category | Platform | Evaluation Task | Used In |
| --- | --- | --- | --- | --- |
| [PPE Benchmark](https://github.com/amazingljy1206/ElectionSim) | Political Behavior and Elections | Twitter | Voter preference prediction | ElectionSim |
| ANES 2020 | Political Behavior and Elections | Survey | Demographic calibration | ElectionSim |
| ITA-ELECTION-22 | Political Behavior and Elections | Twitter | Political conversation simulation | SOSMC |
| Vaccination Engagement | User Behavior and Engagement | X | Action-guided engagement | CLSSM |
| CCP-DE | User Behavior and Engagement | X | Comment prediction (DE) | TSSMU |
| CCP-EN | User Behavior and Engagement | X | Comment prediction (EN) | TSSMU |
| CCP-LU | User Behavior and Engagement | RTL | Comment prediction (LU) | TSSMU |
| [Y Social traces](https://github.com/YSocialTwin/YSocial) | User Behavior and Engagement | Synthetic | Digital-twin validation | Y Social |
| Rumor Event Suite | Misinformation and Rumor | Twitter | Temporal rumor dynamics | RumorSphere |
| [BotSim-24](https://github.com/QQQQQQBY/BotSim) | Misinformation and Rumor | Reddit | Adversarial bot simulation | BotSim |
| [FPS Fake-News](https://github.com/LiuYuHan31/FPS) | Misinformation and Rumor | Synthetic | Attitude dynamics to fake news | FPS |
| [FUSE Mutation](https://github.com/LiuYuHan31/FUSE) | Misinformation and Rumor | Synthetic | Stepwise news deception | FUSE |
| Gender Discrimination | Controversial-Topic Propagation | Weibo | Emotion and event propagation | S3 |
| Nuclear Energy | Controversial-Topic Propagation | Weibo | Attitude-change propagation | S3 |
| [LLM Opinion Dynamics](https://github.com/yunshiuan/llm-agent-opinion-dynamics) | Opinion Dynamics and Echo Chambers | Synthetic | Opinion convergence | SODNL |
| [OASIS Twitter-like](https://github.com/camel-ai/oasis) | Opinion Dynamics and Echo Chambers | Synthetic | Group polarization | OASIS |
| [OASIS Reddit-like](https://github.com/camel-ai/oasis) | Opinion Dynamics and Echo Chambers | Synthetic | Herd effect and misinformation | OASIS |
| [SNAP Collection](https://snap.stanford.edu/data/) | Network Structure | Multi | Network analysis and topology generation | NetworkX, igraph |

## Evaluation Metrics

The survey groups 22 evaluation metrics into seven core evaluation goals. The table below summarizes the metric families that recur throughout the paper.

| Category | Representative Metrics | What They Measure |
| --- | --- | --- |
| Structural Fidelity | Degree distribution, clustering coefficient, average path length, assortativity | Whether generated graphs resemble real social-network topology. |
| Dynamic and Temporal Fidelity | Pearson correlation, DTW, DeltaBias, DeltaDiversity | How closely simulated cascades and trajectories match empirical time series. |
| Opinion and Polarization | Polarization `P_z`, global disagreement, neighbour correlation index, spectral gap | Consensus, fragmentation, echo chambers, and convergence speed. |
| Diffusion and Influence | Reproduction number `R_0`, influence spread, cascade size | Whether and how widely content spreads through the network. |
| Behavioral Alignment | Micro-F1, action-distribution KL/JS divergence, cosine similarity, state-level accuracy | Whether agent actions and content align with observed human behavior. |
| Efficiency and Scalability | Confusion index, token reduction, wall-clock cost | Cost-fidelity trade-offs in large-scale simulation systems. |
| Adversarial Robustness | Detector accuracy drop | Robustness against LLM-driven bots and adversarial social agents. |

## Disclaimer

Feel free to contact us if you have any queries or exciting news on social network simulation. In addition, we welcome all researchers to contribute to this repository and further contribute to the knowledge of social network simulation fields. It would be great if contributions keep the repository aligned with the survey taxonomy

If you have some other related references, please feel free to create a Github issue with the paper information. We will glady update the repos according to your suggestions. (You can also create pull requests, but it might take some time for us to do the merge)

<!-- ## Contributing

Contributions are welcome if they keep the repository aligned with the survey taxonomy.

- Add papers under the correct paradigm section and keep the `Paper`, `Year`, `Category`, and `Source` columns populated.
- Add datasets with platform and evaluation-task details, and add metrics with a clear description of what they measure.
- Prefer official paper, code, and dataset links when available.
- Do not add unverified publication status, DOI claims, or speculative code links. -->


-----------
**Backup Statistics**

![Visitors](https://margherita-gustatory-zane.ngrok-free.dev/badge/tamlhp%2Fawesome-sns.svg?ngrok-skip-browser-warning=true)
