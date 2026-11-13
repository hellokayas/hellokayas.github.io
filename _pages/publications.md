---
title: "Publications"
permalink: /publications/
author_profile: true
---

<style>
/* Scoped to this page's publication list. Native ordered lists remain numbered.
   The CSS counter continues automatically across year sections when entries change. */
.publications-by-year {
  counter-reset: publication;
  font-size: 0.8em;
  line-height: 1.45;
}
.publications-by-year h2 {
  color: #78a22f;
  font-size: 1.35em;
  font-weight: 400;
  margin: 1.55em 0 0.65em;
  padding: 0;
  border: 0;
}
/*.publications-by-year ol {
  list-style-type: decimal;
  margin: 0;
  padding-left: 2.5em;
}
.publications-by-year li {
  counter-increment: publication;
  padding-left: 0.3em;
  margin: 0 0 1.15em;
}
.publications-by-year li::marker {
  content: counter(publication) ". ";
  color: #777;
  font-variant-numeric: tabular-nums;
}*/
.publications-by-year ol {
  list-style: none;          /* hide native numbers */
  margin: 0;
  padding-left: 2.5em;
}
.publications-by-year li {
  counter-increment: publication;
  position: relative;
  padding-left: 0.3em;
  margin: 0 0 1.15em;
}
.publications-by-year li::before {
  content: counter(publication) ".";
  position: absolute;
  right: 100%;               /* sits in the left gutter, right-aligned */
  margin-right: 0.3em;
  color: #777;
  font-variant-numeric: tabular-nums;
}
.publications-by-year .publication-title,
.publications-by-year .publication-authors,
.publications-by-year .publication-venue {
  display: block;
}
.publications-by-year .publication-venue {
  font-style: italic;
}
.publications-by-year .publication-title {
  color: #536dce;
  font-weight: 400;
}
.publications-by-year a {
  color: #536dce;
  text-decoration: none;
}
.publications-by-year a:hover,
.publications-by-year a:focus {
  text-decoration: underline;
}
.publications-by-year i a { color: inherit; }
.publications-by-year .publication-order {
  font-size: 0.9em;
  color: #777;
  margin-bottom: 1em;
}
@media (max-width: 600px) {
  .publications-by-year { font-size: 0.9em; }
  .publications-by-year ol { padding-left: 2.1em; }
}
</style>

<div class="publications-by-year">

<p class="publication-order">Publications by year, most recent first.</p>

<h2>Preprints and submitted papers</h2>

<ol start="1">
  <li>
    <span class="publication-title">An LLM-Powered Interactive Web-Based Registry Browser for Longitudinal Systemic Sclerosis Electronic Health Record Analysis</span>
    <span class="publication-venue">Paper Submitted</span>
  </li>
  <li>
    <span class="publication-title"><a href="https://arxiv.org/abs/2604.12337">Identifying and Mitigating Gender Cues in Academic Recommendation Letters: An Interpretability Case Study</a></span>
    <span class="publication-venue">Paper Submitted</span>
  </li>
</ol>

<h2>2026</h2>

<ol start="3">
    <li>
    <span class="publication-title">Beyond Dense Attention: Probabilistic Hyperedge Masks and Geometry-Mixed Manifold Attention for Sequential Recommendation</span>
    <span class="publication-authors">Sayak Chakrabarty, <a href="https://souradipp76.github.io/">Souradip Pal</a>, <a href="https://ibanerj750.github.io/">Imon Banerjee</a></span>
    <span class="publication-venue"><i><a href="https://icpram.scitevents.org/Home.aspx">16th International Conference on Pattern Recognition Applications and Methods (ICPRAM)</a></i></span>
  </li>
  <li>
    <span class="publication-title">XNano: Using XAI to Explain How Preprocessing Affects Nanoparticle Image Classification</span>
    <span class="publication-authors">Sayak Chakrabarty, <a href="https://www.linkedin.com/in/youjia-li-560ba7148/">Youjia Li</a>, <a href="https://www.linkedin.com/in/carolin-wahl-ab246537a/">Carolin Wahl</a>, <a href="https://robertodosreis.com/">Roberto dos Reis</a>, <a href="https://users.eecs.northwestern.edu/~wkliao/">Wei-Keng Liao</a>, <a href="https://chemistry.northwestern.edu/people/faculty/profiles/chad-mirkin.html">Chad Mirkin</a>, <a href="https://chemistry.northwestern.edu/people/faculty/profiles/vinayak-p-dravid.html">Vinayak Dravid</a>, <a href="https://www.eecs.northwestern.edu/~choudhar/">Alok Choudhary</a> & <a href="https://www.eecs.northwestern.edu/~ankitag/">Ankit Agrawal</a></span>
    <span class="publication-venue"><i><a href="https://ictai.computer.org/2026/">The 38th IEEE International Conference on Tools with Artificial Intelligence (ICTAI)</a></i></span>
  </li>
  <li>
    <span class="publication-title">The Type Theory of Stationary MDPs: Rare Events and Uncertainty Quantification</span>
    <span class="publication-authors"><a href="https://ibanerj750.github.io/">Imon Banerjee</a>, Sayak Chakrabarty, <a href="https://www.linkedin.com/in/ramkrishna-jyoti-samanta-84681a210/">Ramkrishna Jyoti Samanta</a>, <a href="https://scholar.google.com/citations?user=fdyRnbgAAAAJ&amp;hl=en">Riddhiman Bhattacharya</a></span>
    <span class="publication-venue"><i>The Fortieth Annual Conference on Neural Information Processing Systems (NeurIPS)</i></span>
  </li>
  <li>
    <span class="publication-title">Time is the Hidden Budget: Slate Optimization with Value and Policy Based Reinforcement Learning</span>
    <span class="publication-authors">Sayak Chakrabarty, <a href="https://souradipp76.github.io/">Souradip Pal</a></span>
    <span class="publication-venue"><i><a href="https://link.springer.com/series/558">Book Chapter to appear in the Lecture Notes in Computer Science. The expected publication date is December 14</a></i></span>
  </li>
  <li>
    <span class="publication-title"><a href="https://ieeexplore.ieee.org/abstract/document/11760958">Stable History, Better Rankings: Invariant Parent Selection with Geodesic Attention for Recommenders</a></span>
    <span class="publication-authors">Sayak Chakrabarty, <a href="https://souradipp76.github.io/">Souradip Pal</a>, <a href="https://ibanerj750.github.io/">Imon Banerjee</a></span>
    <span class="publication-venue"><i><a href="https://www.icmla-conference.org/icmla26/">25th International Conference on Machine Learning and Applications (ICMLA)</a></i></span>
  </li>
  <li>
    <span class="publication-title"><a href="https://ieeexplore.ieee.org/abstract/document/11760911">Can Vision-Language Models Predict Atomic Structures of 2D Materials?</a></span>
    <span class="publication-authors">Sayak Chakrabarty, <a href="https://engineering.jhu.edu/faculty/kamal-choudhary/">Kamal Choudhary</a>, <a href="https://www.nist.gov/people/daniel-wines">Daniel Wines</a>, <a href="https://www.linkedin.com/in/youjia-li-560ba7148/">Youjia Li</a>, <a href="https://scholar.google.com/citations?user=964aU-4AAAAJ&amp;hl=en">Vishu Gupta</a>, <a href="https://www.linkedin.com/in/mntalhakilic/">Muhammed Nur Talha Kilic</a>, <a href="https://scholar.google.com/citations?user=6nvFl5sAAAAJ&amp;hl=en">Alok Choudhary</a> & <a href="https://eecs.northwestern.edu/~ankitag/">Ankit Agrawal</a></span>
    <span class="publication-venue"><i><a href="https://www.icmla-conference.org/icmla26/">25th International Conference on Machine Learning and Applications (ICMLA)</a></i></span>
  </li>
  <li>
    <span class="publication-title"><a href="https://www.scitepress.org/Papers/2026/151392/151392.pdf">DeepSeekMath Meets Order Book: Group-Aware Policy Optimization for High-Frequency Directional Trading</a></span>
    <span class="publication-authors"><a href="https://souradipp76.github.io/">Souradip Pal</a>, Sayak Chakrabarty</span>
    <span class="publication-venue"><i><a href="https://data.scitevents.org/">The International Conference on Data Science, Technology and Applications (DATA)</a></i> <i><a href="https://github.com/hellokayas/DeepSeek-HFT">Our Code</a></i></span>
  </li>
  <li>
    <span class="publication-title"><a href="https://www.scitepress.org/Papers/2026/151341/151341.pdf">CITRUS: Screening the Past, Ranking the Future</a></span>
    <span class="publication-authors"><a href="https://souradipp76.github.io/">Souradip Pal</a>, Sayak Chakrabarty, <a href="https://ibanerj750.github.io/">Imon Banerjee</a></span>
    <span class="publication-venue"><i><a href="https://data.scitevents.org/">The International Conference on Data Science, Technology and Applications (DATA)</a></i></span>
  </li>
  <li>
    <span class="publication-title"><a href="https://iopscience.iop.org/article/10.1088/2632-2153/ae696b/pdf">Determinism Analysis in Hybrid-LLM-GNN Modeling for Materials Property Prediction</a></span>
    <span class="publication-authors"><a href="https://www.linkedin.com/in/youjia-li-560ba7148/">Youjia Li</a>, <a href="https://www.nist.gov/people/daniel-wines">Daniel Wines</a>, <a href="https://engineering.jhu.edu/faculty/kamal-choudhary/">Kamal Choudhary</a>, <a href="https://scholar.google.com/citations?user=964aU-4AAAAJ&amp;hl=en">Vishu Gupta</a>, <a href="https://www.linkedin.com/in/mntalhakilic/">Muhammed Nur Talha Kilic</a>, Sayak Chakrabarty, <a href="https://www.mccormick.northwestern.edu/research-faculty/directory/affiliated/liao-wei-keng.html">Wei Keng Liao</a>, <a href="https://scholar.google.com/citations?user=6nvFl5sAAAAJ&amp;hl=en">Alok Choudhary</a> & <a href="https://eecs.northwestern.edu/~ankitag/">Ankit Agrawal</a></span>
    <span class="publication-venue"><i><a href="https://iopscience.iop.org/journal/2632-2153">Machine Learning: Science and Technology</a></i></span>
  </li>
  <li>
    <span class="publication-title"><a href="https://arxiv.org/pdf/2506.22427">Personalized Federated Learning through Clustering of Loss Vector Embeddings</a></span>
    <span class="publication-authors"><a href="https://scholar.google.com/citations?user=Iia81jAAAAAJ&amp;hl=en">Randeep Bhatia</a>, <a href="https://scholar.google.com/citations?user=FtAx7CIAAAAJ&amp;hl=en">Nikos Papadis</a>, <a href="https://www.nokia.com/people/murali-kodialam/">Murali Kodialam</a>, <a href="https://scholar.google.com/citations?user=EzDbOKoAAAAJ&amp;hl=en">T. V. Lakshman</a>, Sayak Chakrabarty</span>
    <span class="publication-venue"><i><a href="https://icml.cc/">International Conference on Machine Learning (ICML)</a></i></span>
  </li>
  <li>
    <span class="publication-title"><a href="https://ieeexplore.ieee.org/document/11622311">Is Sliding Window All You Need? An Open Framework for Long-Sequence Recommendation</a></span>
    <span class="publication-authors">Sayak Chakrabarty, <a href="https://souradipp76.github.io/">Souradip Pal</a></span>
    <span class="publication-venue"><i><a href="https://rev-ai.org/">The (IEEE) International Conference on Revolutionary Artificial Intelligence and Future Applications (Rev-AI)</a></i></span>
  </li>
  <li>
    <span class="publication-title"><a href="https://openreview.net/pdf?id=FGBZ4q1HPZ">Adaptive Model Selection in Offline Contextual MDP&#x27;s without Stationarity</a></span>
    <span class="publication-authors"><a href="https://scholar.google.com/citations?user=fdyRnbgAAAAJ&amp;hl=en">Riddhiman Bhattacharya</a>, Sayak Chakrabarty, <a href="https://ibanerj750.github.io/">Imon Banerjee</a></span>
    <span class="publication-venue"><i><a href="https://jmlr.org/tmlr/">Transactions on Machine Learning Research (TMLR)</a></i></span>
  </li>
  <li>
    <span class="publication-title"><a href="https://pubs.rsc.org/en/content/articlelanding/2026/dd/d5dd00544b">Evaluating Large Language Models for Inverse Semiconductor Design</a></span>
    <span class="publication-authors"><a href="https://www.linkedin.com/in/mntalhakilic/">Muhammed Nur Talha Kilic</a>, <a href="https://www.nist.gov/people/daniel-wines">Daniel Wines</a>, <a href="https://engineering.jhu.edu/faculty/kamal-choudhary/">Kamal Choudhary</a>, <a href="https://scholar.google.com/citations?user=964aU-4AAAAJ&amp;hl=en">Vishu Gupta</a>, <a href="https://www.linkedin.com/in/youjia-li-560ba7148/">Youjia Li</a>, Sayak Chakrabarty, <a href="https://www.mccormick.northwestern.edu/research-faculty/directory/affiliated/liao-wei-keng.html">Wei Keng Liao</a>, <a href="https://scholar.google.com/citations?user=6nvFl5sAAAAJ&amp;hl=en">Alok Choudhary</a> & <a href="https://eecs.northwestern.edu/~ankitag/">Ankit Agrawal</a></span>
    <span class="publication-venue"><i><a href="https://www.rsc.org/publishing/journals/digital-discovery">Digital Discovery</a></i></span>
  </li>
  <li>
    <span class="publication-title"><a href="https://link.springer.com/chapter/10.1007/978-3-032-24810-7_46">PixRec: Leveraging Visual Context for Next-Item Prediction in Sequential Recommendation</a></span>
    <span class="publication-authors">Sayak Chakrabarty, <a href="https://souradipp76.github.io/">Souradip Pal</a></span>
    <span class="publication-venue"><i><a href="https://saiconference.com/Computing">Intelligent Computing Conference</a></i> <i>Book chapter (pp 763-775) of <a href="https://link.springer.com/book/10.1007/978-3-032-24810-7">Intelligent Computing</a>, part of the Book series <a href="https://link.springer.com/series/15179">Lecture Notes in Networks and Systems (volume 1951)</a>, the <a href="https://drive.google.com/file/d/1R4PUzWMGi_RPTdqnFNWXpqcnxPdEyItC/view?usp=sharing">eBook</a> ISBN 978-3-032-24810-7 and Print ISBN 978-3-032-24809-1</i></span>
  </li>
  <li>
    <span class="publication-title"><a href="https://www.scitepress.org/Papers/2026/142980/142980.pdf">Time-Constrained Recommendations: Reinforcement Learning Strategies for E-Commerce</a></span>
    <span class="publication-authors">Sayak Chakrabarty, <a href="https://souradipp76.github.io/">Souradip Pal</a></span>
    <span class="publication-venue"><i><a href="https://icpram.scitevents.org/Home.aspx">15th International Conference on Pattern Recognition Applications and Methods (ICPRAM)</a></i></span>
  </li>
</ol>

<h2>2025</h2>

<ol start="17">
  <li>
    <span class="publication-title"><a href="https://ieeexplore.ieee.org/document/11471533">AI-Driven Prediction of Material Deformation: Stress-Strain Curves Faster Than Crystal Plasticity Finite Element Simulation</a></span>
    <span class="publication-authors">Sayak Chakrabarty, <a href="https://scholar.google.com/citations?user=6FYL0Z0AAAAJ&amp;hl=en">Shahriyar Keshavarz</a>, <a href="https://scholar.google.com/citations?user=4SBeU1gAAAAJ&amp;hl=en">Yuwei Mao</a>, <a href="https://www.nist.gov/people/andrew-ce-reid">Andrew Reid</a>, <a href="https://scholar.google.com/citations?user=6nvFl5sAAAAJ&amp;hl=en">Alok Choudhary</a> & <a href="https://eecs.northwestern.edu/~ankitag/">Ankit Agrawal</a></span>
    <span class="publication-venue"><i><a href="https://www.icmla-conference.org/icmla25/index.php">International Conference on Machine Learning and Applications</a></i></span>
  </li>
  <li>
    <span class="publication-title"><a href="https://pubs.acs.org/doi/10.1021/acs.jpcc.5c04792">Predicting Lattice Parameters from Atomic-Scale Images of Two Dimensional (2D) Materials Using Deep Learning</a></span>
    <span class="publication-authors">Sayak Chakrabarty, <a href="https://engineering.jhu.edu/faculty/kamal-choudhary/">Kamal Choudhary</a>, <a href="https://www.nist.gov/people/daniel-wines">Daniel Wines</a>, <a href="https://www.linkedin.com/in/youjia-li-560ba7148/">Youjia Li</a>, <a href="https://scholar.google.com/citations?user=964aU-4AAAAJ&amp;hl=en">Vishu Gupta</a>, <a href="https://www.linkedin.com/in/mntalhakilic/">Muhammed Nur Talha Kilic</a>, <a href="https://scholar.google.com/citations?user=6nvFl5sAAAAJ&amp;hl=en">Alok Choudhary</a> & <a href="https://eecs.northwestern.edu/~ankitag/">Ankit Agrawal</a></span>
    <span class="publication-venue"><i><a href="https://pubs.acs.org/journal/jpccck">The Journal of Physical Chemistry C</a></i></span>
  </li>
  <li>
    <span class="publication-title"><a href="https://arxiv.org/pdf/2505.11725">Small Resamples, Sharp Guarantees: Convergence Rates for Resampled Studentized Quantile Estimators</a></span>
    <span class="publication-authors"><a href="https://ibanerj750.github.io/">Imon Banerjee</a>, Sayak Chakrabarty</span>
    <span class="publication-venue"><i>Thirty-ninth Annual Conference on Neural Information Processing Systems (NeurIPS)</i></span>
  </li>
  <li>
    <span class="publication-title"><a href="https://www.nature.com/articles/s41598-025-06894-x">An AI-driven framework for time-series processing-microstructure-property prediction</a></span>
    <span class="publication-authors"><a href="https://scholar.google.com/citations?user=4SBeU1gAAAAJ&amp;hl=en">Yuwei Mao</a>, Mahmudul Hasan, Md Maruf Billah, Youjia Li, Sayak Chakrabarty, Claire Songhyun Lee, Kewei Wang, Muhammed Nur Talha Kilic, Vishu Gupta, Wei-keng Liao, <a href="https://scholar.google.com/citations?user=6nvFl5sAAAAJ&amp;hl=en">Alok Choudhary</a>, Pinar Acar & <a href="https://eecs.northwestern.edu/~ankitag/">Ankit Agrawal</a></span>
    <span class="publication-venue"><i><a href="https://www.nature.com/srep/">Nature Scientific Reports</a></i></span>
  </li>
  <li>
    <span class="publication-title"><a href="https://www.theoj.org/joss-papers/joss.07489/10.21105.joss.07489.pdf">ReadmeReady: Free and Customizable Code Documentation with LLMs - A Fine-Tuning Approach</a></span>
    <span class="publication-authors">Sayak Chakrabarty, <a href="https://souradipp76.github.io/">Souradip Pal</a></span>
    <span class="publication-venue"><i><a href="https://joss.theoj.org/">The Journal of Open Source Software (JOSS)</a></i></span>
  </li>
  <li>
    <span class="publication-title"><a href="https://joss.theoj.org/papers/10.21105/joss.07783">MM-PoE: Multiple Choice Reasoning via. Process of Elimination using Multi-Modal Models</a></span>
    <span class="publication-authors">Sayak Chakrabarty, <a href="https://souradipp76.github.io/">Souradip Pal</a></span>
    <span class="publication-venue"><i><a href="https://joss.theoj.org/">The Journal of Open Source Software (JOSS)</a></i></span>
  </li>
  <li>
    <span class="publication-title"><a href="https://www.freepatentsonline.com/y2025/0111457.html">Judicial Support Tool Computing System</a></span>
    <span class="publication-authors"><a href="https://vssubrah.github.io/">V. S. Subrahmanian</a>, Sayak Chakrabarty, <a href="https://www.linkedin.com/in/maksim-bolonkin">Maksim Bolonkin</a>, <a href="https://scholar.google.com/citations?user=UdYMo0gAAAAJ&amp;hl=en">Cristian Molinaro</a></span>
    <span class="publication-venue">United States Patent Application 20250111457 (published April 3).</span>
  </li>
</ol>

<h2>2024</h2>

<ol start="24">
  <li>
    <span class="publication-title"><a href="https://link.springer.com/chapter/10.1007/978-3-031-76235-2_5">Judicial Support Tool: Finding the k Most Likely Judicial Worlds</a></span>
    <span class="publication-authors"><a href="https://www.linkedin.com/in/maksim-bolonkin">Maksim Bolonkin</a>, Sayak Chakrabarty, <a href="https://scholar.google.com/citations?user=UdYMo0gAAAAJ&amp;hl=en">Cristian Molinaro</a> & <a href="https://vssubrah.github.io/">V. S. Subrahmanian</a></span>
    <span class="publication-venue"><i>The 16th International Conference on Scalable Uncertainty Management (SUM)</i></span>
  </li>
</ol>

<h2>2023</h2>

<ol start="25">
  <li>
    <span class="publication-title"><a href="https://arxiv.org/pdf/2305.13560.pdf">Single-Pass Pivot Algorithm for Correlation Clustering. Keep it simple!</a></span>
    <span class="publication-authors">Sayak Chakrabarty, <a href="https://konstantin.makarychev.net/">Konstantin Makarychev</a></span>
    <span class="publication-venue"><i>Thirty-seventh Conference on Neural Information Processing Systems (NeurIPS)</i></span>
  </li>
  <li>
    <span class="publication-title"><a href="https://arxiv.org/pdf/2311.05046.pdf">On the Consistency of Maximum Likelihood Estimation of Probabilistic Principal Component Analysis</a></span>
    <span class="publication-authors"><a href="https://www.linkedin.com/in/arghya-d-66a450195/">Arghya Datta</a>, Sayak Chakrabarty</span>
    <span class="publication-venue"><i>Thirty-seventh Conference on Neural Information Processing Systems (NeurIPS)</i></span>
  </li>
  <li>
    <span class="publication-title"><a href="https://ieeexplore.ieee.org/abstract/document/10285721">SockDef: A Dynamically Adaptive Defense to a Novel Attack on Review Fraud Detection Engines</a></span>
    <span class="publication-authors"><a href="https://youzhi333.github.io/index.html">Youzhi Zhang</a>, Sayak Chakrabarty, <a href="https://www.linkedin.com/in/rui-liu-70b16081">Rui Liu</a>, <a href="https://sites.google.com/unical.it/andreapugliese">Andrea Pugliese</a>, <a href="https://vssubrah.github.io/">V. S. Subrahmanian</a></span>
    <span class="publication-venue"><i> IEEE Transactions on Computational Social Systems, September</i></span>
  </li>
</ol>

<h2>2022</h2>

<ol start="28">
  <li>
    <span class="publication-title"><a href="https://ieeexplore.ieee.org/abstract/document/9927814">A New Dynamically Changing Attack on Review Fraud Systems and a Dynamically Changing Ensemble Defense</a></span>
    <span class="publication-authors"><a href="https://youzhi333.github.io/index.html">Youzhi Zhang</a>, Sayak Chakrabarty, <a href="https://www.linkedin.com/in/rui-liu-70b16081">Rui Liu</a>, <a href="https://sites.google.com/unical.it/andreapugliese">Andrea Pugliese</a>, <a href="https://vssubrah.github.io/">V. S. Subrahmanian</a></span>
    <span class="publication-venue"><i><b><a href="https://drive.google.com/file/d/1CcPke3MNfNuAbr2ZxwhWI8w_0YWHitQF/view?usp=sharing">BEST PAPER AWARD</a></b> IEEE Intl Conf on Dependable, Autonomic and Secure Computing, Intl Conf on Pervasive Intelligence and Computing, Intl Conf on Cloud and Big Data Computing, Intl Conf on Cyber Science and Technology Congress (DASC/PiCom/CBDCom/CyberSciTech)</i></span>
  </li>
</ol>

<h2>2021</h2>

<ol start="29">
  <li>
    <span class="publication-title"><a href="https://media.pims.math.ca/pi_in_sky/pi22.pdf">A Number Guessing Game</a></span>
    <span class="publication-authors">Sayak Chakrabarty</span>
    <span class="publication-venue"><i>Pi in the Sky, Issue 22, Pacific Institute for the Mathematical Sciences, January</i></span>
  </li>
</ol>

<h2>2017</h2>

<ol start="30">
  <li>
    <span class="publication-title"><a href="https://www.researchgate.net/publication/316596873_The_Repeated_Divisor_Function_and_Possible_Correlation_with_Highly_Composite_Numbers">The Repeated Divisor Function and Possible Correlation with Highly Composite Numbers</a></span>
    <span class="publication-authors">Sayak Chakrabarty, <a href="https://www.linkedin.com/in/arghya-d-66a450195/">Arghya Datta</a></span>
    <span class="publication-venue"><i><a href="http://kmsuj.im.uj.edu.pl/workshop2017/index.php%3Faction=history.html">20th International Workshop for Young Mathematicians &quot;Number Theory&quot;</a>-The Zaremba Society of Mathematicians - Students of the Jagiellonian University, Krakow, Poland.</i></span>
  </li>
</ol>

</div>

<!-- 1. <b>An LLM-Powered Interactive Web-Based Registry Browser for Longitudinal Systemic Sclerosis Electronic Health Record Analysis</b><br>
Paper Submitted<br>

1. <b>XNano: Using XAI to Explain How Preprocessing Affects Nanoparticle Image Classification</b><br>
Sayak Chakrabarty, [Youjia Li](https://www.linkedin.com/in/youjia-li-560ba7148/), [Carolin Wahl](https://www.linkedin.com/in/carolin-wahl-ab246537a/), [Roberto dos Reis](https://robertodosreis.com/), [Wei-Keng Liao](https://users.eecs.northwestern.edu/~wkliao/), [Chad Mirkin](https://chemistry.northwestern.edu/people/faculty/profiles/chad-mirkin.html), [Vinayak Dravid](https://chemistry.northwestern.edu/people/faculty/profiles/vinayak-p-dravid.html), [Alok Choudhary](https://www.eecs.northwestern.edu/~choudhar/) & [Ankit Agrawal](https://www.eecs.northwestern.edu/~ankitag/)<br>
<i>[The 38th IEEE International Conference on Tools with Artificial Intelligence (ICTAI 2026)](https://ictai.computer.org/2026/)</i>

1. <b>[Identifying and Mitigating Gender Cues in Academic Recommendation Letters: An Interpretability Case Study](https://arxiv.org/abs/2604.12337)</b><br>
Paper Submitted<br>

1. <b>The Type Theory of Stationary MDPs: Rare Events and Uncertainty Quantification</b><br>
[Imon Banerjee](https://ibanerj750.github.io/), Sayak Chakrabarty, [Ramkrishna Jyoti Samanta](https://www.linkedin.com/in/ramkrishna-jyoti-samanta-84681a210/), [Riddhiman Bhattacharya](https://scholar.google.com/citations?user=fdyRnbgAAAAJ&hl=en)<br>
<i>The Fortieth Annual Conference on Neural Information Processing Systems (NeurIPS 2026)</i>

1. <b>Time is the Hidden Budget: Slate Optimization with Value and Policy Based Reinforcement Learning</b><br>
Sayak Chakrabarty,[Souradip Pal](https://souradipp76.github.io/)<br>
<i>[Book Chapter to appear in the Lecture Notes in Computer Science. The expected publication date is December 14, 2026](https://link.springer.com/series/558)</i><br>

1. <b>Stable History, Better Rankings: Invariant Parent Selection with Geodesic Attention for Recommenders</b><br>
Sayak Chakrabarty, [Souradip Pal](https://souradipp76.github.io/), [Imon Banerjee](https://ibanerj750.github.io/)<br>
<i>[25th International Conference on Machine Learning and Applications (ICMLA 2026)](https://www.icmla-conference.org/icmla26/)</i>

1. <b>Can Vision-Language Models Predict Atomic Structures of 2D Materials?</b><br>
Sayak Chakrabarty, [Kamal Choudhary](https://engineering.jhu.edu/faculty/kamal-choudhary/), [Daniel Wines](https://www.nist.gov/people/daniel-wines), [Youjia Li](https://www.linkedin.com/in/youjia-li-560ba7148/), [Vishu Gupta](https://scholar.google.com/citations?user=964aU-4AAAAJ&hl=en), [Muhammed Nur Talha Kilic](https://www.linkedin.com/in/mntalhakilic/), [Alok Choudhary](https://scholar.google.com/citations?user=6nvFl5sAAAAJ&hl=en) & [Ankit Agrawal](https://eecs.northwestern.edu/~ankitag/)<br>
<i>[25th International Conference on Machine Learning and Applications (ICMLA 2026)](https://www.icmla-conference.org/icmla26/)</i>

1. <b>[DeepSeekMath Meets Order Book: Group-Aware Policy Optimization for High-Frequency Directional Trading](https://www.scitepress.org/Papers/2026/151392/151392.pdf)</b><br>
[Souradip Pal](https://souradipp76.github.io/), Sayak Chakrabarty<br>
<i>[The International Conference on Data Science, Technology and Applications (DATA 2026)](https://data.scitevents.org/)</i><br>
<i>[Our Code](https://github.com/hellokayas/DeepSeek-HFT)</i>

1. <b>[CITRUS: Screening the Past, Ranking the Future](https://www.scitepress.org/Papers/2026/151341/151341.pdf)</b><br>
[Souradip Pal](https://souradipp76.github.io/), Sayak Chakrabarty, [Imon Banerjee](https://ibanerj750.github.io/)<br>
<i>[The International Conference on Data Science, Technology and Applications (DATA 2026)](https://data.scitevents.org/)</i>

1. <b>[Determinism Analysis in Hybrid-LLM-GNN Modeling for Materials Property Prediction](https://iopscience.iop.org/article/10.1088/2632-2153/ae696b/pdf)</b><br>
[Youjia Li](https://www.linkedin.com/in/youjia-li-560ba7148/), [Daniel Wines](https://www.nist.gov/people/daniel-wines), [Kamal Choudhary](https://engineering.jhu.edu/faculty/kamal-choudhary/),[Vishu Gupta](https://scholar.google.com/citations?user=964aU-4AAAAJ&hl=en), [Muhammed Nur Talha Kilic](https://www.linkedin.com/in/mntalhakilic/), Sayak Chakrabarty, [Wei Keng Liao](https://www.mccormick.northwestern.edu/research-faculty/directory/affiliated/liao-wei-keng.html), [Alok Choudhary](https://scholar.google.com/citations?user=6nvFl5sAAAAJ&hl=en) & [Ankit Agrawal](https://eecs.northwestern.edu/~ankitag/)<br>
<i>[Machine Learning: Science and Technology](https://iopscience.iop.org/journal/2632-2153)</i>

1. <b>[Personalized Federated Learning through Clustering of Loss Vector Embeddings](https://arxiv.org/pdf/2506.22427)</b><br>
[Randeep Bhatia](https://scholar.google.com/citations?user=Iia81jAAAAAJ&hl=en),[Nikos Papadis](https://scholar.google.com/citations?user=FtAx7CIAAAAJ&hl=en),[Murali Kodialam](https://www.nokia.com/people/murali-kodialam/),[T. V. Lakshman](https://scholar.google.com/citations?user=EzDbOKoAAAAJ&hl=en),Sayak Chakrabarty<br>
<i>[International Conference on Machine Learning (ICML 2026)](https://icml.cc/)</i>

1. <b>[Is Sliding Window All You Need? An Open Framework for Long-Sequence Recommendation](https://ieeexplore.ieee.org/document/11622311)</b><br>
Sayak Chakrabarty,[Souradip Pal](https://souradipp76.github.io/)<br>
<i>[The (IEEE) 2026 International Conference on Revolutionary Artificial Intelligence and Future Applications
(Rev-AI 2026)](https://rev-ai.org/)</i>

1. <b>[Adaptive Model Selection in Offline Contextual MDP's without Stationarity](https://openreview.net/pdf?id=FGBZ4q1HPZ)</b><br>
[Riddhiman Bhattacharya](https://scholar.google.com/citations?user=fdyRnbgAAAAJ&hl=en), Sayak Chakrabarty, [Imon Banerjee](https://ibanerj750.github.io/)<br>
<i>[Transactions on Machine Learning Research (TMLR)](https://jmlr.org/tmlr/)</i>

1. <b>[Evaluating Large Language Models for Inverse Semiconductor Design](https://pubs.rsc.org/en/content/articlelanding/2026/dd/d5dd00544b)</b><br>
[Muhammed Nur Talha Kilic](https://www.linkedin.com/in/mntalhakilic/), [Daniel Wines](https://www.nist.gov/people/daniel-wines), [Kamal Choudhary](https://engineering.jhu.edu/faculty/kamal-choudhary/),[Vishu Gupta](https://scholar.google.com/citations?user=964aU-4AAAAJ&hl=en), [Youjia Li](https://www.linkedin.com/in/youjia-li-560ba7148/), Sayak Chakrabarty, [Wei Keng Liao](https://www.mccormick.northwestern.edu/research-faculty/directory/affiliated/liao-wei-keng.html), [Alok Choudhary](https://scholar.google.com/citations?user=6nvFl5sAAAAJ&hl=en) & [Ankit Agrawal](https://eecs.northwestern.edu/~ankitag/)<br>
<i>[Digital Discovery](https://www.rsc.org/publishing/journals/digital-discovery)</i>

1. <b>[PixRec: Leveraging Visual Context for Next-Item Prediction in Sequential Recommendation](https://link.springer.com/chapter/10.1007/978-3-032-24810-7_46)</b><br>
Sayak Chakrabarty,[Souradip Pal](https://souradipp76.github.io/)<br>
<i>[Intelligent Computing Conference 2026](https://saiconference.com/Computing)</i><br>
<i>Book chapter (pp 763-775) of [Intelligent Computing](https://link.springer.com/book/10.1007/978-3-032-24810-7), part of the Book series [Lecture Notes in Networks and Systems (volume 1951)](https://link.springer.com/series/15179), the [eBook](https://drive.google.com/file/d/1R4PUzWMGi_RPTdqnFNWXpqcnxPdEyItC/view?usp=sharing) ISBN 978-3-032-24810-7 and Print ISBN 978-3-032-24809-1</i>

1. <b>[AI-Driven Prediction of Material Deformation: Stress-Strain Curves Faster Than Crystal Plasticity Finite Element Simulation](https://ieeexplore.ieee.org/document/11471533)</b><br>
Sayak Chakrabarty, [Shahriyar Keshavarz](https://scholar.google.com/citations?user=6FYL0Z0AAAAJ&hl=en), [Yuwei Mao](https://scholar.google.com/citations?user=4SBeU1gAAAAJ&hl=en), [Andrew Reid](https://www.nist.gov/people/andrew-ce-reid), [Alok Choudhary](https://scholar.google.com/citations?user=6nvFl5sAAAAJ&hl=en) & [Ankit Agrawal](https://eecs.northwestern.edu/~ankitag/)<br>
<i>[International Conference on Machine Learning and Applications 2025](https://www.icmla-conference.org/icmla25/index.php)</i>

1. <b>[Time-Constrained Recommendations: Reinforcement Learning Strategies for E-Commerce](https://www.scitepress.org/Papers/2026/142980/142980.pdf)</b><br>
Sayak Chakrabarty,[Souradip Pal](https://souradipp76.github.io/)<br>
<i>[International Conference on Pattern Recognition Applications and Methods 2026](https://icpram.scitevents.org/presentationdetails.aspx)</i><br>
<i>Will appear as chapter of [IC]()</i>

1. <b>[Predicting Lattice Parameters from Atomic-Scale Images of Two Dimensional (2D) Materials Using Deep Learning](https://pubs.acs.org/doi/10.1021/acs.jpcc.5c04792)</b><br>
Sayak Chakrabarty, [Kamal Choudhary](https://engineering.jhu.edu/faculty/kamal-choudhary/), [Daniel Wines](https://www.nist.gov/people/daniel-wines), [Youjia Li](https://www.linkedin.com/in/youjia-li-560ba7148/), [Vishu Gupta](https://scholar.google.com/citations?user=964aU-4AAAAJ&hl=en), [Muhammed Nur Talha Kilic](https://www.linkedin.com/in/mntalhakilic/), [Alok Choudhary](https://scholar.google.com/citations?user=6nvFl5sAAAAJ&hl=en) & [Ankit Agrawal](https://eecs.northwestern.edu/~ankitag/)<br>
<i>[The Journal of Physical Chemistry C](https://pubs.acs.org/journal/jpccck)</i>

1. <b>[Small Resamples, Sharp Guarantees: Convergence Rates for Resampled Studentized Quantile Estimators](https://arxiv.org/pdf/2505.11725)</b><br>
[Imon Banerjee](https://ibanerj750.github.io/), Sayak Chakrabarty<br>
<i>Thirty-ninth Annual Conference on Neural Information Processing Systems(NeurIPS 2025)</i>

1. <b>[An AI-driven framework for time-series processing-microstructure-property prediction](https://www.nature.com/articles/s41598-025-06894-x)</b><br>
[Yuwei Mao](https://scholar.google.com/citations?user=4SBeU1gAAAAJ&hl=en), Mahmudul Hasan, Md Maruf Billah, Youjia Li, Sayak Chakrabarty, Claire Songhyun Lee, Kewei Wang, Muhammed Nur Talha Kilic, Vishu Gupta, Wei-keng Liao, [Alok Choudhary](https://scholar.google.com/citations?user=6nvFl5sAAAAJ&hl=en), Pinar Acar & [Ankit Agrawal](https://eecs.northwestern.edu/~ankitag/)<br>
<i>[Nature Scientific Reports](https://www.nature.com/srep/)</i>

1. <b>[ReadmeReady: Free and Customizable Code Documentation with LLMs - A Fine-Tuning Approach](https://www.theoj.org/joss-papers/joss.07489/10.21105.joss.07489.pdf)</b><br>
Sayak Chakrabarty,[Souradip Pal](https://souradipp76.github.io/)<br>
<i>[The Journal of Open Source Software (JOSS)](https://joss.theoj.org/)</i>

1. <b>[Judicial Support Tool Computing System](https://www.freepatentsonline.com/y2025/0111457.html)</b><br>
[V. S. Subrahmanian](https://vssubrah.github.io/),Sayak Chakrabarty,[Maksim Bolonkin](https://www.linkedin.com/in/maksim-bolonkin),[Cristian Molinaro](https://scholar.google.com/citations?user=UdYMo0gAAAAJ&hl=en)<br>
United States Patent Application 20250111457 (published 04/03/2025)<br>

1. <b>[Judicial Support Tool: Finding the k Most Likely Judicial Worlds](https://link.springer.com/chapter/10.1007/978-3-031-76235-2_5)</b><br>
[Maksim Bolonkin](https://www.linkedin.com/in/maksim-bolonkin), Sayak Chakrabarty, [Cristian Molinaro](https://scholar.google.com/citations?user=UdYMo0gAAAAJ&hl=en) & [V. S. Subrahmanian](https://vssubrah.github.io/) <br>
<i>The 16th International Conference on Scalable Uncertainty Management (SUM 2024)</i>

1. <b>[Single-Pass Pivot Algorithm for Correlation Clustering. Keep it simple!](https://arxiv.org/pdf/2305.13560.pdf)</b><br>
Sayak Chakrabarty, [Konstantin Makarychev](https://konstantin.makarychev.net/)<br>
<i>Thirty-seventh Conference on Neural Information Processing Systems(NeurIPS, 2023)</i>

1. <b>[On the Consistency of Maximum Likelihood Estimation of Probabilistic Principal Component Analysis](https://arxiv.org/pdf/2311.05046.pdf)</b><br>
[Arghya Datta](https://www.linkedin.com/in/arghya-d-66a450195/), Sayak Chakrabarty<br>
<i>Thirty-seventh Conference on Neural Information Processing Systems(NeurIPS, 2023)</i>

1. <b>[SockDef: A Dynamically Adaptive Defense to a Novel Attack on Review Fraud Detection Engines](https://ieeexplore.ieee.org/abstract/document/10285721)</b><br>
[Youzhi Zhang](https://youzhi333.github.io/index.html); Sayak Chakrabarty; [Rui Liu](https://www.linkedin.com/in/rui-liu-70b16081); [Andrea Pugliese](https://sites.google.com/unical.it/andreapugliese); [V. S. Subrahmanian](https://vssubrah.github.io/)<br>
<i> IEEE Transactions on Computational Social Systems, September 2023</i>

1. <b>[MM-PoE: Multiple Choice Reasoning via. Process of Elimination using Multi-Modal Models](https://joss.theoj.org/papers/10.21105/joss.07783)</b><br>
Sayak Chakrabarty,[Souradip Pal](https://souradipp76.github.io/)<br>
<i>[The Journal of Open Source Software (JOSS)](https://joss.theoj.org/)</i>

1. <b>[A New Dynamically Changing Attack on Review Fraud Systems and a Dynamically Changing Ensemble Defense](https://ieeexplore.ieee.org/abstract/document/9927814)</b><br>
[Youzhi Zhang](https://youzhi333.github.io/index.html); Sayak Chakrabarty; [Rui Liu](https://www.linkedin.com/in/rui-liu-70b16081); [Andrea Pugliese](https://sites.google.com/unical.it/andreapugliese); [V. S. Subrahmanian](https://vssubrah.github.io/)<br>
<i><b>[BEST PAPER AWARD](https://drive.google.com/file/d/1CcPke3MNfNuAbr2ZxwhWI8w_0YWHitQF/view?usp=sharing)</b> IEEE Intl Conf on Dependable, Autonomic and Secure Computing, Intl Conf on Pervasive Intelligence and Computing, Intl Conf on Cloud and Big Data Computing, Intl Conf on Cyber Science and Technology Congress (DASC/PiCom/CBDCom/CyberSciTech) 2022</i>

1. <b>[A Number Guessing Game](https://media.pims.math.ca/pi_in_sky/pi22.pdf)</b><br>
Sayak Chakrabarty<br>
<i>Pi in the Sky, Issue 22, Pacific Institute for the Mathematical Sciences, January 2021</i>

1. <b>[The Repeated Divisor Function and Possible Correlation with Highly Composite Numbers](https://www.researchgate.net/publication/316596873_The_Repeated_Divisor_Function_and_Possible_Correlation_with_Highly_Composite_Numbers)</b><br>
Sayak Chakrabarty, [Arghya Datta](https://www.linkedin.com/in/arghya-d-66a450195/)<br>
<i>[20th International Workshop for Young Mathematicians "Number Theory", 2017](http://kmsuj.im.uj.edu.pl/workshop2017/index.php%3Faction=history.html)-The Zaremba Society of Mathematicians - Students of the Jagiellonian University, Krakow, Poland.</i> -->