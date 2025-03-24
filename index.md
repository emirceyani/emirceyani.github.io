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
    I am a fourth year PhD student in Electrical Engineering at the Universoty of Southern California, working with <a href="https://www.avestimehr.com/" target="_blank">Prof. Salman Avestimehr</a>.  My research focuses on the intersection of federated learning and graph machine learning. Recently, I have a keen interest in  <a href="https://www.youtube.com/watch?v=o0Ju9NQa5Ko" target="_blank">generative flow networks</a> and <a href="https://www.youtube.com/watch?v=nql000Lu_iE&t=19s" target="_blank">conformal prediciton</a>. I have been selected as a 2025 North America Finalist at <a href="https://www.qualcomm.com/research/university-relations/innovation-fellowship/2025-north-america" target="_blank">the Qualcomm Unnovation Fellowship</a>.
  </p>



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
        As AI systems are increasingly deployed in complex tasks and real-world applications, I believe it's crucial to understand and improve their reasoning and reliability. My work addresses challenges like quantifying uncertainty, performing efficient search and sampling, and ensuring reliable reasoning, all of which are fundamental for safe and effective AI deployment.
      </p>
      <p>
        One major focus has been the development of Generative Flow Networks (GFlowNets), a framework that connects reinforcement learning and probabilistic modeling. I've worked on establishing the theoretical foundations of GFlowNets, demonstrating their effectiveness in Bayesian inference of discrete and continuous structures, and showing their ability to handle multimodal distributions better than traditional variational methods. I also created and released <a href="https://github.com/GFNOrg/torchgfn" target="_blank">torchgfn</a>, an open-source software framework, to make GFlowNets more accessible for both discrete and general applications.
      </p>
      <p>
        Beyond GFlowNets, I've also contributed to uncertainty estimation through a method called DEUP (Direct Epistemic Uncertainty Prediction). DEUP addresses model misspecification in interactive learning settings by using a secondary predictor trained on the main model's errors. This results in more reliable uncertainty estimates for decision-making in downstream tasks.
      </p>
      <p>
        Currently, I'm focused on the theory and applications of GFlowNets to tackle more complex problems, using them to enhance Large Language Model reasoning, and developing even better uncertainty estimation methods. My overall goal is to improve the reliability, efficiency, and reasoning capabilities of AI systems, particularly in scenarios that demand robust decision-making under uncertainty. For this goal, I am collaborating with  <a href="https://la7.lu/" target="_blank">Salem Lahlou</a> and  <a href="https://www.ee.iitm.ac.in/faculty/profile/saurav" target="_blank">Saurav Prakash</a>.
      </p>
    </div>
  </div>
</div>

<div class="news" style="margin-top: 2em;">
<h2>News</h2>
<ul>
  <li><span class="news-date">February 2025</span> - Became a finalist "  <a href="https://www.qualcomm.com/research/university-relations/innovation-fellowship/2025-north-america">at the 2025 Qualcomm Innovation Fellowship /a>.</li>
  <li><span class="news-date">January 2025</span> - Became a semi-finalist at 2025 Qualcomm Innovation Fellowship  <a href="https://www.qualcomm.com/research/university-relations/innovation-fellowship/2025-north-america">UM6P, Ben Guerir</a>.</li>
  <li><span class="news-date">December 2024</span> - FedGrAINS, GFlowNet paper to improve subgraph federated learning has been accepted at the <a href="https://www.siam.org/conferences-events/siam-conferences/sdm25/">the SIAM-SDM'25 conference</a>.</li>
</ul>
</div>

<div style="margin-top: 2em;">
  <p>
    Ultimately, I am driven by a deep interest in understanding and defining intelligence, whether it's in animals or artificial systems. While I'm excited about the potential of AI, I'm also mindful of its limitations and potential pitfalls – I'm definitely not a technosolutionist.
  </p>
  <p>
    Before my current role, Before joining USC, I received my MSc and BSc degrees from  <a href="https://ee.bilkent.edu.tr/en/" target="_blank">the Electrical Engineering at Bilkent University</a> as a Senior Researcher in 2018 and 2020 respectively.
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