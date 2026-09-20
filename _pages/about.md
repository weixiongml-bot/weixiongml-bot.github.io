---
layout: about
title: Home
permalink: /
subtitle: Member of Technical Staff · OpenAI<br>RL / Frontier Team
profile:
  align: right
  image: wei-xiong.jpeg
  image_circular: false
selected_papers: false
social: false
announcements:
  enabled: false
latest_posts:
  enabled: false
---

<p class="profile-links"><a href="mailto:weixiongml@gmail.com">Email</a><span> / </span><a href="{{ '/assets/pdf/cv.pdf' | relative_url }}">CV</a><span> / </span><a href="https://scholar.google.com/citations?user=m2-OwQEAAAAJ&amp;hl=zh-CN">Google Scholar</a><span> / </span><a href="https://github.com/weixiongml-bot">GitHub</a></p>
<div class="home-content">

<p>I am a Member of Technical Staff on the RL Frontier team at OpenAI, working on reinforcement learning.</p>
<p>I received my Ph.D. in Computer Science from the <a href="https://cs.illinois.edu/">University of Illinois Urbana-Champaign</a> in 2026, where I worked with <a href="http://tongzhang-ml.org/">Prof. Tong Zhang</a> and <a href="http://nanjiang.cs.illinois.edu">Prof. Nan Jiang</a>. My doctoral research was supported by the Google PhD Fellowship.</p>
<p>Prior to this, I received a master's degree in mathematics in 2023 from The Hong Kong University of Science and Technology, where my study was supported by the Hong Kong PhD Fellowship. I enjoyed several fabulous years at the University of Science and Technology of China and obtained a B.S. in mathematics in 2021, where I worked closely with <a href="http://www.ece.virginia.edu/~cs7dt/home.html">Prof. Cong Shen</a>.</p>
<div class="profile-clear"></div><h2 id="research-highlights">Research</h2>
<p>My current work at OpenAI focuses on reinforcement learning algorithms to advance the capabilities of frontier AI models.</p>
<p>During my Ph.D. at UIUC, I studied reinforcement learning and its applications to LLM post-training, spanning theoretical foundations, algorithm design, and practical training methods. My work connected mathematical insights with large-scale experimentation and open-source implementations.</p>
<h3>Selected Prior Work</h3>
<ol>
<li><p><i>Online rejection-sampling fine-tuning</i> <a href="https://arxiv.org/pdf/2505.02391">[3]</a><a href="https://arxiv.org/pdf/2304.06767">[13]</a>; <a href="https://github.com/RLHFlow/Minimal-RL">[Code]</a></p>
<ol>
<li><p>a widely used and competitive algorithm for Llama and Qwen post-training;</p>
</li>
<li><p>a practical recipe that competes with GRPO and provides theoretical understanding of GRPO through its connection to rejection sampling;</p>
</li>
<li><p>introduces an elegant inference-budget allocation strategy motivated by the variance-reduction principle in gradient estimation.</p>
</li></ol>
</li>
<li><p><b><i>Reinforce-ada</i></b> <a href="https://arxiv.org/pdf/2510.04996">[1]</a>; <a href="https://github.com/RLHFlow/Reinforce-Ada">[Code]</a></p>
<ol>
<li><p>a simple yet scalable adaptive sampling framework that continuously reallocates sampling effort toward prompts with the greatest uncertainty or learning potential, addressing the signal-loss problem in GRPO training.</p>
</li></ol>
</li>
<li><p><i>Online DPO and RLHFlow</i> · <a href="https://github.com/RLHFlow/Online-RLHF">[Online DPO Code]</a> <a href="https://github.com/RLHFlow/RLHF-Reward-Modeling">[Reward Modeling Code]</a></p>
<p>I co-founded and lead RLHFlow, the open-source framework accompanying our work on online DPO (2,000 GitHub stars, 500 academic citations, 1M Hugging Face downloads).</p>
<ol>
<li><p>established the first convergence and refined logarithmic regret analyses of KL-regularized RL(HF), translating these theoretical insights into online DPO <a href="https://arxiv.org/pdf/2312.11456">[10]</a> <a href="https://arxiv.org/pdf/2502.07460">[4]</a> <a href="https://proceedings.neurips.cc/paper_files/paper/2024/file/94d13c2401fe119e57ba325b6fe526e0-Paper-Conference.pdf">[14]</a>;</p>
</li>
<li><p>released <b>the first open-source recipe for online DPO</b> as part of a complete post-training pipeline covering SFT, reward modeling, and online DPO, <b>with final models outperforming Meta's Llama-3-8B-it</b> <a href="https://arxiv.org/pdf/2405.07863">[7]</a>;</p>
</li>
<li><p>trained widely used open-source BT reward models and preference models for RLHF, and introduced <i>multi-head reward models</i> with <i>MoE-style aggregation</i> (ARMO <a href="https://arxiv.org/pdf/2406.12845">[8]</a>, with 200+ citations);</p>
</li>
<li><p>released <b>the first open-source recipe for <i>(generative) process reward</i></b> <a href="https://github.com/RLHFlow/RLHF-Reward-Modeling/tree/main/math-rm">[9]</a>.</p>
</li>
</ol>
</li>
</ol>
<p>Some older work in learning theory </p>
<ul>
<li><p>Learnability and regret analysis in multi-agent Markov games <a href="https://arxiv.org/pdf/2205.15512">[i]</a> <a href="https://proceedings.mlr.press/v162/xiong22b/xiong22b.pdf">[ii]</a> <a href="https://proceedings.mlr.press/v162/zhong22b/zhong22b.pdf">[iii]</a></p>
</li>
<li><p>A unified viewpoint of learnability and generalization in online decision making <a href="https://arxiv.org/pdf/2211.01962">[iv]</a> <a href="{{ '/assets/pdf/masterthesis.pdf' | relative_url }}">[v]</a> </p>
</li>
<li><p>Improved algorithm design and analysis in decentralized convex optimization <a href="https://arxiv.org/pdf/2012.15010">[vi]</a> </p>
</li>
</ul>
<h2 id="industry-experience">Industry Experience</h2>
<ul>
<li><p><b>Research Intern, Meta FAIR</b>, 2025.5 to 2025.8</p>
<ul>
<li><p>Taught LLMs to segment reasoning trajectories into coherent intermediate steps, improving interpretability and stability of reasoning.</p>
</li>
<li><p>Trained a generative process reward model via RL to evaluate and guide step-by-step reasoning.</p>
</li></ul>
</li>
<li><p><b>Student Researcher, Google Deepmind</b> (Gemini Post-Training Team), 2024.5 to 2025.4</p>
<ul>
<li><p>Formulated a multi-turn RL framework for agent tasks and developed a multi-turn variant of DPO for scalable online alignment. </p>
</li>
<li><p>Designed robust reward modeling techniques to mitigate reward hacking and improve reliability of RLHF training.</p>
</li>
<li><p>Contributed to internal thinking-LLM related projects.</p>
</li></ul>
</li>
<li><p><b>Research Intern, Microsoft Research Asia</b>, 2021.1 to 2021.6</p>
<ul>
<li><p>Developed RL-based bandwidth estimation algorithms for real-time communications in Microsoft Teams.</p>
</li>
<li><p>Conducted research on distributional reinforcement learning.</p>
</li>
</ul>
</li>
</ul>
<h2 id="honors-and-awards">Honors and Awards</h2>
<ol>
<li><p><b>Google PhD Fellowship</b> ($85,000 USD per year), 2025</p>
</li>
<li><p>Best Paper Award, Demo Track, NAACL, 2024</p>
</li>
<li><p>NeurIPS Travel Award and Best Reviewer, 2023</p>
</li>
<li><p>Hong Kong PhD Fellowship Scheme (HKPFS) (approx. $90,000 USD over two years), 2021 - 2023</p>
</li>
<li><p><b>Guo Moruo Scholarship, Finalist</b> (Highest honor for undergraduates at USTC), 2020</p>
</li>
</ol>
<h2 id="service">Service</h2>
<p><b>Conference Service</b></p>
<ul>
<li><p><b>Area Chair:</b> NeurIPS 2025 Workshop on Multi-Turn Interactions in Large Language Models.</p>
</li>
<li><p><b>Organizer:</b> NeurIPS 2025 Workshop on MATH-AI: The 5th Workshop on Mathematical Reasoning and AI.</p>
</li>
<li><p><b>Reviewer:</b> ICLR (2024-2025), NeurIPS (2022-2024, <b>Top Reviewer Award (Top 8%) 2023</b>), ICML (2022-2023, 2025), AISTATS (2023-2025), ARR (2024-2025)</p>
</li>
</ul>
<p><b>Journal Reviewer</b></p>
<ul>
<li><p>Journal of Machine Learning Research (JMLR), Transactions on Machine Learning Research (TMLR), Journal of the American Statistical Association (JASA)</p>
</li>
</ul>
<h2 id="service-and-recent-talks">Service and Recent Talks</h2>
<ol>
<li><p><a href="{{ '/assets/pdf/slidesimons.pdf' | relative_url }}">Iterative Preference Learning for Large Language Model Post Training </a></p>
<ol>
<li><p>Sep 2024 Talk at the Simons Institute Workshop: <a href="https://simons.berkeley.edu/workshops/emerging-generalization-settings">Emerging Generalization Settings,</a></p>
</li>
<li><p>Sep 2024 Talk at UIUC Machine Learning Seminar</p>
</li>
<li><p>Aug 2024 Talk at University of Waterloo</p>
</li>
<li><p>July 2024 Talk at Mila Alignment Seminar</p>
</li></ol>
</li>
<li><p><a href="{{ '/assets/pdf/slidemdpo.pdf' | relative_url }}">Building Math Agent by Iterative Preference Learning </a></p>
<ol>
<li><p>Jan 2025, Talk at UCLA Data Mining Group</p>
</li>
<li><p>Nov 2024, Talk at Amazon Rufus Group</p>
</li>
<li><p>Oct 2024, Talk at Informs Annual Meeting</p>
</li>
<li><p>Oct 2024, Talk at UIUC-NLP large group meeting</p>
</li>
<li><p>Aug 2024 Talk at Google Deepmind Sky Team, NYC</p>
</li></ol>
</li>
<li><p><a href="{{ '/assets/pdf/sliderlhf.pdf' | relative_url }}">Reinforcement Learning from Human Feedback: From Theory to Algorithm</a></p>
<ol>
<li><p>Dec 2024, Guest Lecture at University of Wisconsin-Madison for CS760 Machine Learning</p>
</li>
<li><p>Nov 2024, Guest Lecture at UVA for CS 4501 Natural Language Processing</p>
</li>
<li><p>June 2024 Talk at Google Multi-turn RLHF Workshop, MTV</p>
</li>
<li><p>May 2024 Talk at Google Learning Theory Seminar, NYC</p>
</li>
<li><p>Jan 2024 Talk at Microsoft Research Asia</p>
</li>
</ol>
</li>
</ol>
<h2 id="contact">Contact</h2>
<p>If you are interested in discussing with me, feel free to email me at <a href="mailto:weixiongml@gmail.com">weixiongml@gmail.com</a> or add my wechat wei_xiong2000 </p>

</div>
