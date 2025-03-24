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
    I am a fourth PhD student in Electrical Engineering at the Universoty of Southern California, working with <a href="https://www.avestimehr.com/" target="_blank">Prof. Salman Avestimehr</a>. .  My research focuses on synergistic combination of computer vision and medical imaging to advance healthcare technologies by developing novel deep learning models for accelerated multi-contrast MRI synthesis, reconstruction and super-resolution as well as for the foremost computer vision problems utilizing supervised and unsupervised learning techniques.
  </p>



  <div class="research-topics">
    <h3>Research Topics</h3>
    <div class="topic-grid">
      <div class="topic-item">Federated Learning</div>
      <div class="topic-item">GFlowNets</div>
      <div class="topic-item">Graph Neural Networks</div>
      <div class="topic-item">Uncertainty Estimation</div>
      <div class="topic-item">Probabilistic Modeling</div>
      <div class="topic-item">AI For Science/Engineering</div>
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
        Currently, I'm focused on scaling GFlowNets to tackle more complex problems, using them to enhance Large Language Model reasoning, and developing even better uncertainty estimation methods. My overall goal is to improve the reliability, efficiency, and reasoning capabilities of AI systems, particularly in scenarios that demand robust decision-making under uncertainty.
      </p>
    </div>
  </div>
</div>

<div class="news" style="margin-top: 2em;">
<h2>News</h2>
<ul>
  <li><span class="news-date">February 2025</span> - Became a finalist at Qualcomm Innovation Fellowship"  <a href="https://www.qualcomm.com/research/university-relations/innovation-fellowship/2025-north-america"></a>.</li>
  <li><span class="news-date">January 2025</span> - Became a semi-finalist at Qualcomm Innovation Fellowship at <a href="https://um6p.ma/">UM6P, Ben Guerir</a>.</li>
  <li><span class="news-date">December 2024</span> - I gave a keynote talk titled "Advancing the Fourth Paradigm: Machine Learning Frameworks for Experimental Science" at the  the <a href="https://morocco.ai/events/conferences/MoroccoAI-Conference-2024/index.html">MoroccoAI 2024 conference</a>.</li>
  <li><span class="news-date">November 2024</span> - I attended the <a href="https://climb.berkeley.edu/climb-workshop/">CLIMB workshop</a>, and the <a href="https://simons.berkeley.edu/workshops/domain-adaptation-related-areas" target="_blank">Domain adaption and related areas workshop</a> at the Simon's institute, in University of California, Berkeley.</li>
  <li><span class="news-date">October 2024</span> - I am co-organizing the <a href="https://netys.org/" target="_blank">NETYS 2025</a> conference in Rabat, Morocco, in May 2025.</li>
  <li><span class="news-date">September 2024</span> - I joined MBZUAI as an Assistant Professor in the Machine Learning Department.</li>
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