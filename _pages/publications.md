---
layout: archive
title: "Works"
permalink: /works/
author_profile: true
---

<div class="pub-group">
  <div class="pub-group-title">Working Papers</div>
  <div class="pub-group-items">

    <div class="pub">
      <div class="pub-title"><a href="https://arxiv.org/abs/2404.11794">Automated Social Science: Language Models as Scientist and Subjects</a></div>
      <div class="pub-authors">With Benjamin Manning and John Horton.</div>
      <div class="pub-venue">Reject and Resubmit at the <strong>Quarterly Journal of Economics</strong>.<br>Extended abstract at the <strong>ACM Conference on Economics &amp; Computation (EC '26)</strong>.</div>
      <div class="pub-award"><span class="award-btn">EC '26 Exemplary Paper Award</span></div>
      <div class="pub-links"><button type="button" class="paper-btn" data-abstract-toggle="abs-automated">Abstract</button> <a href="https://arxiv.org/abs/2404.11794" class="paper-btn">PDF</a> <button type="button" class="paper-btn" data-bibtex-toggle="bib-automated" data-bibtex-name="manning2024automated">Bibtex</button> <a href="https://marginalrevolution.com/marginalrevolution/2024/03/its-happening-economic-science-edition.html" class="paper-btn">Press: Marginal Revolution</a> <a href="https://futureofbeinghuman.com/p/can-ai-be-used-to-automate-social" class="paper-btn">Press: The Future of Being Human</a> <a href="https://www.oneusefulthing.org/p/four-singularities-for-research" class="paper-btn">Press: One Useful Thing</a></div>
      <div class="pub-abstract" id="abs-automated" hidden>We present an approach for automatically generating and testing, in silico, social scientific hypotheses. This automation is made possible by recent advances in large language models (LLM), but the key feature of the approach is the use of structural causal models. Structural causal models provide a language to state hypotheses, a blueprint for constructing LLM-based agents, an experimental design, and a plan for data analysis. The fitted structural causal model becomes an object available for prediction or the planning of follow-on experiments. We demonstrate the approach with several scenarios: a negotiation, a bail hearing, a job interview, and an auction. In each case, causal relationships are both proposed and tested by the system, finding evidence for some and not others. We provide evidence that the insights from these simulations of social interactions are not available to the LLM purely through direct elicitation. When given its proposed structural causal model for each scenario, the LLM is good at predicting the signs of estimated effects, but it cannot reliably predict the magnitudes of those estimates. In the auction experiment, the in silico simulation results closely match the predictions of auction theory, but elicited predictions of the clearing prices from the LLM are inaccurate. However, the LLM's predictions are dramatically improved if the model can condition on the fitted structural causal model. In short, the LLM knows more than it can (immediately) tell.</div>
      <script type="application/x-bibtex" id="bib-automated">
@techreport{manning2024automated,
  title       = {Automated Social Science: Language Models as Scientist and Subjects},
  author      = {Manning, Benjamin S. and Zhu, Kehang and Horton, John J.},
  institution = {National Bureau of Economic Research},
  type        = {Working Paper},
  series      = {Working Paper Series},
  number      = {32381},
  year        = {2024},
  month       = {April},
  doi         = {10.3386/w32381},
  url         = {https://www.nber.org/papers/w32381}
}
</script>
    </div>

    <div class="pub">
      <div class="pub-title"><a href="https://arxiv.org/abs/2602.12089">Choose Your Agent: Tradeoffs in Adopting AI Advisors, Coaches, and Delegates in Multi-Party Negotiation</a></div>
      <div class="pub-authors">With Nithum Thain, Vivian Tsai, James Wexler, and Crystal Qian.</div>
      <div class="pub-venue">Submitted to <strong>CSCW</strong>.<br><strong>AAMAS 2026 ES Workshop</strong>.</div>
      <div class="pub-links"><button type="button" class="paper-btn" data-abstract-toggle="abs-choose">Abstract</button> <a href="https://arxiv.org/abs/2602.12089" class="paper-btn">PDF</a> <button type="button" class="paper-btn" data-bibtex-toggle="bib-choose" data-bibtex-name="zhu2026choose">Bibtex</button></div>
      <div class="pub-abstract" id="abs-choose" hidden>As AI usage becomes more prevalent in social contexts, understanding agent-user interaction is critical to designing systems that improve both individual and group outcomes. We present an online behavioral experiment (N=243) in which participants play three multi-turn bargaining games in groups of three. Each game, presented in randomized order, grants access to a single LLM assistance modality: proactive recommendations from an Advisor, reactive feedback from a Coach, or autonomous execution by a Delegate. All three modalities are powered by an LLM with super-human performance within this negotiation setting. On each turn, participants privately decide whether to act manually or use the AI modality available in that game. We document a preference-performance misalignment: participants strongly prefer the higher-control Advisor (44%) over the Delegate (19%), yet groups only significantly increase collective surplus under Delegate access. Adjusting for voluntary non-compliance, delegating to the AI yields suggestive individual welfare gains, roughly 1.5x the intent-to-treat estimate. A mechanism analysis traces this gap to a human filter: AI-generated proposals create more joint surplus than manual proposals across all conditions, but in the Advisor and Coach modes users modify, override, or ignore the AI's suggestions, reverting toward human-baseline trade patterns. The Delegate advantage arises not from a different AI capability but from bypassing this filtering step altogether. Realizing these welfare gains depends not only on model capability, but on the interaction structure through which that capability is delivered. We argue that assistance modalities should be designed as mechanisms with endogenous participation; adoption-compatible interaction rules are a prerequisite to improving welfare with automated assistance.</div>
      <script type="application/x-bibtex" id="bib-choose">
@inproceedings{zhu2026choose,
  title         = {Choose Your Agent: Tradeoffs in Adopting AI Advisors, Coaches, and Delegates in Multi-Party Negotiation},
  author        = {Zhu, Kehang and Thain, Nithum and Tsai, Vivian and Wexler, James and Qian, Crystal},
  year          = {2026},
  note          = {AAMAS 2026 ES Workshop},
  eprint        = {2602.12089},
  archivePrefix = {arXiv},
  primaryClass  = {cs.GT},
  url           = {https://arxiv.org/abs/2602.12089}
}
</script>
    </div>

    <div class="pub">
      <div class="pub-title"><a href="https://drive.google.com/file/d/1mvl8tgwak2fnBWhTh-slHqTSU_lyviDa/view?usp=sharing">Benchmarking LLM Bidding Against Human Experimental Data</a></div>
      <div class="pub-authors">With Anand Shah, Jeffery Wang, Arif K. Dayi, Yanchen Jiang, John Horton, and David Parkes.</div>
      <div class="pub-venue"><strong>NeurIPS 2024</strong> (Workshop), <strong>EC 2024</strong> (Poster).</div>
      <div class="pub-links"><button type="button" class="paper-btn" data-abstract-toggle="abs-benchmarking">Abstract</button> <a href="https://drive.google.com/file/d/1mvl8tgwak2fnBWhTh-slHqTSU_lyviDa/view?usp=sharing" class="paper-btn">PDF</a> <button type="button" class="paper-btn" data-bibtex-toggle="bib-benchmarking" data-bibtex-name="shah2024benchmarking">Bibtex</button> <a href="https://github.com/KeHang-Zhu/llm-auction" class="paper-btn">Code</a></div>
      <div class="pub-abstract" id="abs-benchmarking" hidden>This paper investigates the behavior of large language models (LLMs) in auctions, introducing a novel synthetic data-generating process to help facilitate the study and design of auctions. We use the method of moments to estimate human bidding strategies in the results of different experiments reported in the economics literature, for first-price and second-price auction formats and different value environments. We also consider empirical benchmarks from field studies of eBay-style proxy-bidding auctions. In comparing LLMs and humans, we find that LLMs reproduce several qualitative regularities emphasized in the auctions literature—systematic departures from equilibrium in IPV sealed-bid auctions, susceptibility to the winner's curse in common-value settings, and bid sniping under hard-close rules in eBay-style environments—and that LLM behavior is highly responsive to how the incentive mechanisms are presented: describing a strategy-proof sealed-bid auction via an ascending-clock threshold process makes bidding substantially more truthful. We further find that seemingly small design changes—such as moving from sealed-bid to clock-style implementations or modifying the closing rule—induce large and systematic shifts in LLM behavior (as with humans). However, even while summary statistics of LLM bids are similar to those of human bids, the bid distributions diverge in salient ways, revealing where human-likeness breaks down. In this way, we identify regimes in which LLM behavior resembles human behavior and where it does not—offering a methodological template for future work using LLMs as proxies for human behavior in auctions. We release the framework as a reproducible, open-source standard for evaluating economic reasoning in LLMs, flexible enough to run auction experiments with many different models and across a wide range of auction designs.</div>
      <script type="application/x-bibtex" id="bib-benchmarking">
@misc{shah2024benchmarking,
  title  = {Benchmarking LLM Bidding Against Human Experimental Data},
  author = {Shah, Anand and Zhu, Kehang and Wang, Jeffery and Dayi, Arif K. and Jiang, Yanchen and Horton, John J. and Parkes, David C.},
  year   = {2024},
  note   = {NeurIPS 2024 Workshop; ACM EC 2024 (poster)},
  url    = {https://github.com/KeHang-Zhu/llm-auction}
}
</script>
    </div>

  </div>
</div>

<div class="pub-group">
  <div class="pub-group-title">Peer-reviewed Conference Proceedings</div>
  <div class="pub-group-items">

    <div class="pub">
      <div class="pub-title"><a href="https://arxiv.org/pdf/2509.09071">Strategic Tradeoffs Between Human and AI Agents in Bargaining Games</a></div>
      <div class="pub-authors">With Crystal Qian, Vivian Tsai, James Wexler, Nithum Thain, John Horton, and Benjamin Manning.</div>
      <div class="pub-venue">Accepted at <strong>IUI 2026</strong>.</div>
      <div class="pub-links"><button type="button" class="paper-btn" data-abstract-toggle="abs-strategic">Abstract</button> <a href="https://arxiv.org/pdf/2509.09071" class="paper-btn">PDF</a> <button type="button" class="paper-btn" data-bibtex-toggle="bib-strategic" data-bibtex-name="qian2026strategic">Bibtex</button> <a href="https://www.prolific.com/resources/how-google-deepmind-is-advancing-multi-party-ai-research-with-deliberate-lab" class="paper-btn">Press: Prolific</a></div>
      <div class="pub-abstract" id="abs-strategic" hidden>Markets increasingly accommodate large language models (LLMs) as autonomous decision-making agents. As this transition occurs, it becomes critical to evaluate how these agents behave relative to their human and task-specific statistical predecessors. In this work, we present results from an empirical study comparing humans (N=216), multiple frontier LLMs, and customized Bayesian agents in dynamic multi-player bargaining games under identical conditions. Bayesian agents extract the highest surplus with aggressive trade proposals that are frequently rejected. Humans and LLMs achieve comparable aggregate surplus within their groups, but exhibit different trading strategies. LLMs favor conservative, concessionary proposals that are usually accepted by other LLMs, while humans propose trades that are consistent with fairness norms but are more likely to be rejected. These findings highlight that performance parity — a common benchmark in agent evaluation — can mask substantive procedural differences in how LLMs behave in complex multi-agent interactions.</div>
      <script type="application/x-bibtex" id="bib-strategic">
@inproceedings{qian2026strategic,
  title         = {Strategic Tradeoffs Between Human and AI Agents in Bargaining Games},
  author        = {Qian, Crystal and Zhu, Kehang and Horton, John and Manning, Benjamin S. and Tsai, Vivian and Wexler, James and Thain, Nithum},
  booktitle     = {Proceedings of the 2026 ACM Conference on Intelligent User Interfaces (IUI '26)},
  year          = {2026},
  eprint        = {2509.09071},
  archivePrefix = {arXiv},
  primaryClass  = {cs.AI},
  url           = {https://arxiv.org/abs/2509.09071}
}
</script>
    </div>

    <div class="pub">
      <div class="pub-title"><a href="/files/reading-between-pixels.pdf">Reading Between the Pixels: Investigating the Barriers to Visualization Literacy</a></div>
      <div class="pub-authors">With Carolina Nobre, Eric Mörth, Hanspeter Pfister, and Johanna Beyer.</div>
      <div class="pub-venue"><strong>CHI 2024</strong>.</div>
      <div class="pub-links"><button type="button" class="paper-btn" data-abstract-toggle="abs-reading">Abstract</button> <a href="/files/reading-between-pixels.pdf" class="paper-btn">PDF</a> <button type="button" class="paper-btn" data-bibtex-toggle="bib-reading" data-bibtex-name="nobre2024reading">Bibtex</button> <a href="https://doi.org/10.1145/3613904.3642760" class="paper-btn">ACM</a></div>
      <div class="pub-abstract" id="abs-reading" hidden>In our current visual-centric digital age, the capability to interpret, understand, and produce visual representations of data—termed visualization literacy—is paramount. However, not everyone is adept at navigating this visual terrain. This paper explores the barriers that individuals who misread a visualization encounter, aiming to understand their specific mental gaps. Utilizing a mixed-method approach, we administered the Visualization Literacy Assessment Test (VLAT) to a group of 120 participants drawn from diverse demographic backgrounds, which provided us with 1774 task completions. We augmented the standard VLAT test to capture quantitative and qualitative data on participants' errors. We collected participant sketches and open-ended text about their analysis approach, providing insight into users' mental models and rationale. Our findings reveal that individuals who incorrectly answer visualization literacy questions often misread visual channels, confound chart labels with data values, or struggle to translate data-driven questions into visual queries. Recognizing and bridging visualization literacy gaps not only ensures inclusivity but also enhances the overall effectiveness of visual communication in our society.</div>
      <script type="application/x-bibtex" id="bib-reading">
@inproceedings{nobre2024reading,
  title     = {Reading Between the Pixels: Investigating the Barriers to Visualization Literacy},
  author    = {Nobre, Carolina and Zhu, Kehang and M{\"o}rth, Eric and Pfister, Hanspeter and Beyer, Johanna},
  booktitle = {Proceedings of the 2024 CHI Conference on Human Factors in Computing Systems (CHI '24)},
  year      = {2024},
  publisher = {Association for Computing Machinery},
  doi       = {10.1145/3613904.3642760},
  url       = {https://doi.org/10.1145/3613904.3642760}
}
</script>
    </div>

  </div>
</div>

<div class="pub-group">
  <div class="pub-group-title">Selected Work in Progress</div>
  <div class="pub-group-items">

    <div class="pub">
      <div class="pub-title"><a href="https://drive.google.com/file/d/1V5Gkuu8RiZS17NSwKPe3SmUlMmXQDh4m/view?usp=sharing">Engineering Simplicity for LLM Agents</a></div>
      <div class="pub-authors">With Anand Shah and David Parkes.</div>
      <div class="pub-links"><button type="button" class="paper-btn" data-abstract-toggle="abs-engineering">Abstract</button> <a href="https://drive.google.com/file/d/1V5Gkuu8RiZS17NSwKPe3SmUlMmXQDh4m/view?usp=sharing" class="paper-btn">PDF</a> <button type="button" class="paper-btn" data-bibtex-toggle="bib-engineering" data-bibtex-name="shah2026engineering">Bibtex</button></div>
      <div class="pub-abstract" id="abs-engineering" hidden>The theory of simplicity in economic design makes a claim about minds: that certain strategic problems are intrinsically hard to reason about, and that simple design can improve reasoning and recover good outcomes. Large language models (LLMs) represent a new kind of intelligence—neither human nor superhuman—and offer a rare opportunity: to test whether the cognitive constraints that drive simplicity in economic design are specific to humans or reflect something deeper. Existing results establish that LLM agents make mistakes participating in strategy-proof auctions such as the second-price sealed-bid auction, but improve play in simpler, obviously strategy-proof designs; we extend these findings across model families and to two-sided matching, and take this as evidence that the representation of a mechanism—how a game is presented, not just what it implements—shapes LLM reasoning in the same direction it shapes human reasoning. To understand where these cognitive constraints bind, we systematically test prompt-based interventions along three axes from this theory—contingent reasoning, forward planning, and belief formation—as well as descriptions of the mechanisms themselves to make their incentive properties transparent. We find that scaffolding for contingent reasoning, and making incentive properties transparent, substantially improve play, while prompting models to plan forward or to reason about others' beliefs consistently worsens it. The conceptual vocabulary of simple mechanism design, it appears, also describes the limits of an intelligence we did not build the theory for. Understanding why will matter as artificial agents enter economic life.</div>
      <script type="application/x-bibtex" id="bib-engineering">
@misc{shah2026engineering,
  title  = {Engineering Simplicity for LLM Agents},
  author = {Shah, Anand and Zhu, Kehang and Parkes, David C.},
  year   = {2026},
  note   = {Working paper},
  url    = {https://drive.google.com/file/d/1V5Gkuu8RiZS17NSwKPe3SmUlMmXQDh4m/view}
}
</script>
    </div>

  </div>
</div>
