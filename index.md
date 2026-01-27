---
layout: about
permalink: /
profile:
  align: right
  image: profile.jpeg
published: true
---

<div class="intro-section">
  <p class="lead-text">
    I am a Ph.D. Candidate in Electrical & Computer Engineering at the University of Southern California, working with <a href="https://www.avestimehr.com/" target="_blank">Prof. Salman Avestimehr</a>.  My research focuses on the intersection of federated learning and graph generative models, and AI4Science. Recently, I have a keen interest in  <a href="https://www.youtube.com/watch?v=o0Ju9NQa5Ko" target="_blank">generative flow networks</a>. I have been selected as a 2025 North America Finalist at <a href="https://www.qualcomm.com/research/university-relations/innovation-fellowship/2025-north-america" target="_blank">the Qualcomm Innovation Fellowship</a>.
  </p>

 <div class="highlight-box">
    <br>
    - Looking for postdoctoral researcher and/or research scientist/enginner positions.

  </div>


  <div class="research-topics">
    <h3>Research Topics</h3>
    <div class="topic-grid">
      <div class="topic-item">Federated Learning</div>
      <div class="topic-item">GFlowNets</div>
      <div class="topic-item">Graph Neural Networks</div>
      <div class="topic-item">Uncertainty Estimation</div>
      <div class="topic-item">Probabilistic Modeling</div>
      <div class="topic-item">AI For Science</div>
      <div class="topic-item">Conformal Prediction</div>
      <div class="topic-item">LLM Reasoning</div>
    </div>
  </div>



 <div class="my-contributions" style="margin-top: 2em; ">
    <h3 id="contributions-toggle" style="cursor: pointer; text-align: center; color: #d3d3d3; display: block; border-bottom: 1px solid #d3d3d3; padding-bottom: 5px; user-select: none; font-size: 1em; font-weight: 500; margin: auto;">
      My Contributions
      <span id="contributions-icon" style="color: #d3d3d3; font-size: 0.8em;">+</span>
    </h3>
    <div id="contributions-content" style="display: none; text-align: left;">
      <p>
        As AI systems are increasingly deployed in complex tasks across decentralized real-world applications, I believe it's vital to build foundations of ML fro graphs over federated settings. My work has introduced the federated training of graph neural networks and continues to pursue applications required for collaborative and decentralized science with the coexistence of AI.  
      </p>
      <p>
        Currently, I'm focused on the theory and applications of GFlowNets to tackle more complex problems. My overall goal is to improve the reliability, efficiency, and reasoning capabilities of AI systems, particularly in scenarios that demand robust decision-making under uncertainty. For this goal, I am collaborating with  <a href="https://la7.lu/" target="_blank">Salem Lahlou</a> and  <a href="https://www.ee.iitm.ac.in/faculty/profile/saurav" target="_blank">Saurav Prakash</a>.
      </p>
      <p>
        Application-wise, my current focuses are automated analog circuit design and semiconductor physics using tools such as GNNs, LLMs and Bayesian Optimization to tackle  complex problems in the aforementioned domains. For this goal, I am collaborating with  <a href="https://engineering.uci.edu/users/hamidreza-aghasi" target="_blank">Hamidreza Aghasi</a> and  <a href="https://viterbi.usc.edu/directory/faculty/Kapadia/Rehan" target="_blank">Rehan Kapadia</a>.
      </p>
    </div>
  </div>
</div>

<div class="news" style="margin-top: 2em;">
<h2>Recent News</h2>
<ul>
<li><span class="news-date">Jan 2026</span> - I gave an invited talk titled "Three Modern Pillars of AI4Science with Graphs:
Federation, Domain Knowledge, and Discovery
" at California Institute of Technology CMS Department, </li>
  <li><span class="news-date">Oct 2025</span> - Selected as a Top Reviewer at <a href="https://neurips.cc/Conferences/2025/ProgramCommittee#top-reviewer">NeurIPS'25!</a>, </li>
  <li><span class="news-date">Sep 2025</span> - Our work, <a href="https://arxiv.org/abs/2505.21923">FALCON</a>, has been accepted to NeurIPS'25!</li>
  <li><span class="news-date">Sep 2025</span> - Officially, a Ph.D. candidate!</li>
   <li><span class="news-date">May 2025</span> - <a href="https://arxiv.org/abs/2505.21923">FALCON</a>,  an end-to-end ML framework for analog circuit design (including topology selection, layout-aware parameter selection, and performance prediction) is out!</li>
  <li><span class="news-date">February 2025</span> - Became a finalist at <a href="https://www.qualcomm.com/research/university-relations/innovation-fellowship/2025-north-america">the 2025 Qualcomm Innovation Fellowship</a>.</li>
   <li><span class="news-date">February 2025</span> - Awarded with Travel Grant for <a href="https://www.siam.org/conferences-events/siam-conferences/sdm25/">the SIAM-SDM'25 conference, a top-tier conference in ML & data-mining.</a>.</li>
  <li><span class="news-date">January 2025</span> - Became a semi-finalist at <a href="https://www.qualcomm.com/research/university-relations/innovation-fellowship/2025-north-america">the 2025 Qualcomm Innovation Fellowship </a>.</li>
  <li><span class="news-date">December 2024</span> - FedGrAINS, first GFlowNet paper to improve subgraph federated learning has been accepted to <a href="https://www.siam.org/conferences-events/siam-conferences/sdm25/">the SIAM-SDM'25 conference</a>. Preprint is available  <a href="https://arxiv.org/abs/2501.12592">in this link</a>.  </li>
</ul>
</div>

<div style="margin-top: 2em;">
  <p>
    Ultimately, I am driven by a deep interest in understanding and defining intelligence, whether it's in animals or artificial systems. While I'm excited about the potential of AI, I'm also mindful of its limitations and potential pitfalls – I'm definitely not a technosolutionist.
  </p>
  <p>
    Before my current role, Before joining USC, I received my MSc and BSc degrees from  <a href="https://ee.bilkent.edu.tr/en/" target="_blank">the Electrical Engineering at Bilkent University</a>  in 2018 and 2020 respectively.
  </p>
</div>

<script>
  const contributionsToggle = document.getElementById('contributions-toggle');
  const contributionsContent = document.getElementById('contributions-content');
  const contributionsIcon = document.getElementById('contributions-icon');

  contributionsToggle.addEventListener('click', () => {
    if (contributionsContent.style.display === 'none') {
      contributionsContent.style.display = 'block';
      contributionsIcon.textContent = '-';
    } else {
      contributionsContent.style.display = 'none';
      contributionsIcon.textContent = '+';
    }
  });
</script>