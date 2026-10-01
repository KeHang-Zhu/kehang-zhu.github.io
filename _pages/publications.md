---
layout: archive
title: "Works"
permalink: /works/
author_profile: false
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
      <div class="pub-title"><a href="https://arxiv.org/abs/2507.09083">LLM Bidders Preserve the Mechanism-Level Orderings of Human Bidders</a></div>
      <div class="pub-authors">With Anand Shah, Yanchen Jiang, Jeffrey Wang, Arif K. Dayi, John Horton, and David Parkes.</div>
      <div class="pub-venue"><strong>NeurIPS 2024</strong> (Workshop), <strong>EC 2024</strong> (Poster).</div>
      <div class="pub-links"><button type="button" class="paper-btn" data-abstract-toggle="abs-benchmarking">Abstract</button> <a href="https://arxiv.org/abs/2507.09083" class="paper-btn">PDF</a> <button type="button" class="paper-btn" data-bibtex-toggle="bib-benchmarking" data-bibtex-name="shah2025llmbidders">Bibtex</button> <a href="https://github.com/KeHang-Zhu/llm-auction" class="paper-btn">Code</a></div>
      <div class="pub-abstract" id="abs-benchmarking" hidden>Training on vast amounts of human-generated data has motivated growing interest in using large language models (LLMs) to simulate human behavior. We ask which features of human behavior general-purpose models preserve when used out of the box in auctions, where multiple bidders interact under explicit rules and incentives. We evaluate five LLMs across seven laboratory settings against human benchmarks reconstructed from published experiments, with uncertainty bands for the private-value comparisons. Our main focus is on three large models without extended test-time reasoning: GPT-4o, Claude 3.5 Haiku, and Gemini 2.0 Flash. LLM and human deviations from theory differ in magnitude and often in direction: humans overbid in second-price auctions, whereas most models that deviate underbid. Surprisingly, without task-specific fine-tuning or calibration to human bids, the three non-reasoning large models robustly preserve key orderings of auction formats by deviation from theory. First-price auctions are harder than second-price, and ascending clocks reduce deviations relative to sealed bids wherever data are adequate. Kendall's $\tau_b$ between the human and GPT-4o difficulty rankings is $0.60$ and positive in every joint bootstrap draw. The reasoning model bids almost at equilibrium in the observed private-value settings, leaving little variation in errors to compare; the small model's large errors yield an inverted ranking. All five models nevertheless reproduce the stronger first-price winner's curse. Clock framing improves bidding for two of the three non-reasoning large models, and GPT-4o recovers the ordering of last-minute bidding across closing rules in an eBay-style marketplace.</div>
      <script type="application/x-bibtex" id="bib-benchmarking">
@inproceedings{shah2025llmbidders,
  title         = {LLM Bidders Preserve the Mechanism-Level Orderings of Human Bidders},
  author        = {Shah, Anand and Zhu, Kehang and Jiang, Yanchen and Wang, Jeffrey G. and Dayi, Arif K. and Horton, John J. and Parkes, David C.},
  year          = {2025},
  note          = {NeurIPS 2024 Workshop; ACM EC 2024 (poster)},
  eprint        = {2507.09083},
  archivePrefix = {arXiv},
  primaryClass  = {cs.GT},
  url           = {https://arxiv.org/abs/2507.09083}
}
</script>
    </div>

    <div class="pub">
      <div class="pub-title"><a href="https://drive.google.com/file/d/1K8-kDB-FGx3ihhdEdmu7toSKVA_ZO-fZ/view?usp=sharing">Designing Behavioral Profiles for Language Model Simulation of Out-of-Distribution Human Behavior</a></div>
      <div class="pub-authors">With Robin Na, Logan Cross, and Michiel A. Bakker.</div>
      <div class="pub-venue"><strong>NeurIPS 2026</strong> (UserSim Workshop).</div>
      <div class="pub-links"><button type="button" class="paper-btn" data-abstract-toggle="abs-profiles">Abstract</button> <a href="https://drive.google.com/file/d/1K8-kDB-FGx3ihhdEdmu7toSKVA_ZO-fZ/view?usp=sharing" class="paper-btn">PDF</a> <button type="button" class="paper-btn" data-bibtex-toggle="bib-profiles" data-bibtex-name="na2026profiles">Bibtex</button></div>
      <div class="pub-abstract" id="abs-profiles" hidden>Large language models (LLMs) are increasingly used to simulate human behavior, but which descriptions of people improve prediction when experimental designs change remains unclear. We develop a framework that draws candidate behavioral features from the literature and constructs profiles from earlier human experiments. A profile-generation LLM assigns feature values from observed actions, messages, and surveys; a separate LLM simulates behavior using these profiles. By comparing simulated and observed outcomes in the learning data, we select profile contents through forward feature selection, adding features while they improve prediction. We then evaluate the selected contents without modification against outcomes from new participants under new designs. Across 616 public-goods games, 144 multi-party bargaining games, and 1,480 generalized 11–20 money-request designs, leading one-feature profiles predict human outcome distributions better than no profile or general-purpose personas. Profiles with more features provide no clear additional benefit, and features' relative predictive value largely persists across learning and validation. Using profiles from one game family to simulate another produces uneven gains and can make predictions less accurate than simulations without profiles. The framework makes the choice of behavioral information a testable part of simulation design, helping researchers assess which descriptions remain useful as experimental conditions change.</div>
      <script type="application/x-bibtex" id="bib-profiles">
@inproceedings{na2026profiles,
  title     = {Designing Behavioral Profiles for Language Model Simulation of Out-of-Distribution Human Behavior},
  author    = {Na, Robin and Zhu, Kehang and Cross, Logan and Bakker, Michiel A.},
  year      = {2026},
  note      = {NeurIPS 2026 UserSim Workshop},
  url       = {https://drive.google.com/file/d/1K8-kDB-FGx3ihhdEdmu7toSKVA_ZO-fZ/view}
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
      <div class="pub-title"><a href="https://arxiv.org/abs/2609.36365">Engineering Simplicity: Simple Mechanism Interfaces Steer LLM Agents</a></div>
      <div class="pub-authors">With Anand Shah and David Parkes.</div>
      <div class="pub-links"><button type="button" class="paper-btn" data-abstract-toggle="abs-engineering">Abstract</button> <a href="https://arxiv.org/abs/2609.36365" class="paper-btn">PDF</a> <button type="button" class="paper-btn" data-bibtex-toggle="bib-engineering" data-bibtex-name="zhu2026engineering">Bibtex</button></div>
      <div class="pub-abstract" id="abs-engineering" hidden>Can interaction formats and textual scaffolds help large language model (LLM) agents make better decisions, and do better decisions come with better explanations? We study these questions in auctions and matching, multi-agent environments with explicit rules and known optimal strategies. These settings let us vary how a decision problem is presented while retaining a benchmark for evaluating behavior. Drawing on human-motivated theories of simplicity, we compare interfaces that elicit a complete bid or ranking with sequential interfaces that make safe choices easier to identify. We then hold the interaction format fixed and vary reasoning scaffolds and rule descriptions. Across four model families, the ascending auction interface substantially reduces bid deviations. The matching comparison also shows why sequential responses require different error accounting from complete rankings. Laying out payoff contingencies and explaining why truth-telling is safe also improve choices, whereas prompts to plan through matching rounds or form beliefs about opponents worsen play overall. In auctions, these behavioral gains are not accompanied by corresponding improvements in measured verbal indicators of strategic understanding in the agents' short stated plans. Other prompts change those indicators without improving bids. Our findings suggest that human-motivated theories of simplicity can inform the design of decision environments for artificial agents. They also show why scaffolds should be evaluated through realized choices as well as explanations: improvements in one need not appear in the other.</div>
      <script type="application/x-bibtex" id="bib-engineering">
@misc{zhu2026engineering,
  title         = {Engineering Simplicity: Simple Mechanism Interfaces Steer LLM Agents},
  author        = {Zhu, Kehang and Shah, Anand and Parkes, David C.},
  year          = {2026},
  eprint        = {2609.36365},
  archivePrefix = {arXiv},
  primaryClass  = {cs.AI},
  url           = {https://arxiv.org/abs/2609.36365}
}
</script>
    </div>

  </div>
</div>
