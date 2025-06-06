---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
# <h3 class="blackpar_title">(Models, Training and Inference)</h3>
layout: home
---
<div style="font-family: 'Source Sans Pro', sans-serif; background: url('/images/banner_no_text.png') no-repeat; background-size: cover; user-select: none;">
	<center>
		<h2 class="blackpar_title" >Workshop on<br>Scientific Reasoning at the Frontier: Training and Evaluating the Next Generation of Multimodal Models for Scientific Discovery</h2>
		<h3 class="blackpar_title"> <br> <b>In-person</b>  and <b>Virtual</b> </h3>
	</center>
</div>
<br>
<!-- <div class="alert alert-danger" role="alert">
	<center>
		<i class="bi bi-info-circle"></i>
		<br>
		<b>The latest version of the worshop (NeurIPS ENLSP 2024) is out, you can check it on the new <a href="https://neurips2024-enlsp.github.io/">website</a>.</b>
	</center>
</div> -->
<br>
<!-- <p>
The second version of the Efficient Natural Language and Speech Processing (ENLSP-II) workshop focuses on fundamental and challenging problems to make natural language and speech processing (especially pre-trained models) more efficient in terms of <b>Data, Model, Training, and Inference</b>. The workshop program offers an interactive platform for gathering different experts and talents from academia and industry through invited talks, panel discussion, paper submissions, reviews, interactive posters, oral presentations and a mentorship program. This will be a unique opportunity to address the efficiency issues of current models, build connections, exchange ideas and brainstorm solutions, and foster future collaborations. The topics of this workshop can be of interest for people working on general machine learning, deep learning, optimization, theory and NLP & Speech applications.
</p> -->

<br>

<!--
<div class="alert alert-danger" role="alert">
  <h4>Mentoring sessions announcement</h4>
  <p>
  The deadline for submitting papers to our second version of the Efficient Natural Language and Speech Processing (ENLSP-II) workshop is 25th of September. For that we will be scheduling two mentioring online sessions to answer your questions. Please join us:
  <br>
  <ul>
	<li>Tuesday the 6th of September 2022 from 10PM to 11PM (UTC-04:00)</li>
	<li>Wednesday the 7th of September 2022 from 9AM to 10AM (UTC-04:00)</li>
	<li>Tuesday the 13th of September 2022 from 10PM to 11PM (UTC-04:00): <a href="https://welink.zhumu.com/j/134854021">link</a></li>
	<li>Wednesday the 14th of September 2022 from 9AM to 10AM (UTC-04:00): <a href="https://welink.zhumu.com/j/130263276">link</a></li>
  </ul>
  </p>
</div>

<br>
-->

<h2 class="blackpar_title" id="overview">Overview</h2>
<p>
Recent multimodal foundation models, such as OpenAI's o3, Anthropic's Claude-4 Opus, Meta's Llama 4, and Google's Gemini 2.5, demonstrate the ability to comprehend entire research articles requiring complex reasoning across multiple modalities. Successes like AlphaFold, which connects amino acid sequences with 3D structures to accelerate molecular insights; AlphaEvolve, which pairs code-generating language models with iterative empirical feedback; and projects integrating satellite imagery with sensor data to predict climate extremes, highlight the evolution of AI into an intellectual collaborator rather than merely a computational tool.
<br><br>
Yet, realistic evaluations such as [EAIRA](https://arxiv.org/abs/2502.20309) and the [U.S. DOE's ``1000 Scientist AI Jam"](https://www.anl.gov/article/1000-scientist-ai-jam-kicks-off-at-argonne) have uncovered critical limitations. Challenges arise from the complexities inherent in fusing heterogeneous scientific data across diverse modalities, particularly under long-context scenarios exceeding 100,000 tokens. Robustness remains fragile, with accuracy significantly varying when evidence must be coherently integrated across modalities, lengths, and temporal scales. Moreover, the expensive feedback mechanisms, such as multi-physics simulations, make current post-training approaches based on reinforcement learning inapplicable. Furthermore, it remains unclear how the scientific community should systematically evaluate enhancements in accuracy, robustness, and safety when operating with multimodal and extensive contextual information.
This highlights the urgency of developing novel training and evaluation methods tailored to the unique challenges of scientific reasoning with heterogeneous, high-dimensional data under extreme context lengths. Without such advances, the potential of AI to drive the next generation of scientific breakthroughs may remain unrealized, particularly in domains where robustness, interpretability, and integration across complex data modalities are essential.
<br><br>
This workshop convenes AI researchers, high-performance computing (HPC) specialists, domain scientists, and evaluation experts to explore and address the complete lifecycle of trustworthy multimodal foundation models tailored for scientific discovery. Participants are strongly encouraged to openly share not only successful strategies but also negative results, robustness audits, and critical lessons learned. Through transparent discussion and collective analysis of challenges and failures, we aim to transform these experiences into valuable community resources, fostering accelerated progress toward robust, interpretable, and reliable AI-driven scientific breakthroughs. Supported by the Trillion Parameter Consortium’s international network, insights from the workshop will be translated into open benchmarks and a practical integration and evaluation framework, laying the groundwork for the next generation of AI-driven scientific discovery.
</p>
<br>
<!-- Call for Papers -->
<h2 class="blackpar_title" id="call_for_papers">Call for Papers</h2>
We invite cutting-edge contributions from a broad range of disciplines that advance the integration and evaluation of multimodal, long-context foundation models for scientific discovery. Submission may include original research, new benchmark proposals, provocative position papers, or well-documented case studies that address the following themes:
<br>
<ul>
	<li>Scientific reasoning: post-training methods for scientific applications, such as integrating temporally misaligned or multi-scale evidence, coping with costly feedback (e.g., wet-lab or multi-physics simulations), supporting hypothesis generation, iterative refinement, or causal inference.</li>
    <li>Evidence fusion during pre-training: early or late fusion of text, images, graphs and simulation fields under sparse scientific data.</li>
	<li>Distillation and adapter transfer: integrating specialist FMs (e.g., reaction-prediction, earth sciences, genomics) into a general multimodal backbone.</li>
	<li>Long-context memory and retrieval – architectures and indexing schemes that keep long context scientific data coherent.</li>
	<li>Evaluation, safety and calibrated uncertainty: new tasks, metrics or audit pipelines that score hypothesis novelty, multimodal consistency, and hallucination risk.</li>
	<li>Rigorous case studies (incl. negative results): comparing integration choices across biology, earth science, physics or materials science.</li>
</ul>

Submissions (up to 4 pages, excluding references) will be peer-reviewed by a multidisciplinary committee for originality, relevance, and scientific and technical rigor. Accepted works will be presented as talks or posters and may optionally be published on OpenReview. We encourage interdisciplinary collaborations, early-career participation, and novel cross-domain perspectives.
<br>
<!-- Outcomes -->
<h2 class="blackpar_title" id="outcomes">Workshop Outcomes and Opportunities</h2>
<br>
<ul>
	<li> Keynotes: AI success stories and roadblocks from diverse scientific domains – Earth Sciences, Biology, LLNL Fusion breakthrough, AlphaEvlove, AphaFold3, Stormer, etc.</li>
	<li> Panel Discussions: Expert panels from national lab, Frontier LLM labs, and academics on critical challenges and emerging trends, fostering deep insights and collaborative exchanges.</li>
    <li> Workshop Report: A detailed report outlining key discussions, actionable recommendations, and a roadmap for future research directions. This includes community-driven identification of pivotal scientific problems that would benefit from generative AI.</li>
	New Data Resources: Release of curated benchmark datasets from National labs (e.g., https://data-science.llnl.gov/open-data-initiative) designed explicitly for scientific discovery, evaluating scientific reasoning, etc.</li>
	<li> Collaboration and Funding Information: Insights into funding opportunities, partnership models, and collaborative frameworks facilitated through involvement from national laboratories and governmental agencies.</li>
	<li> Early Career Opportunities: Targeted opportunities for early-career researchers to engage, present their work, and network with senior domain experts, facilitating mentorship and future collaborations.</li>
</ul>
<!--Confirmed Speakers-->
<h2 class="blackpar_title" id="speakers">Confirmed Speakers and Panelists</h2>
<p>
{% include speakers.html %}
</p>


<!-- <h2 class="blackpar_title" id="speakers">Industrial Panelists</h2>
<p>
{% include panelists.html %}
</p> -->

<!-- Schedule -->
<h2 class="blackpar_title" id="schedule">Schedule</h2>
<p>
{% include schedule.html %}
</p>

<!-- Organizers -->
<h2 class="blackpar_title" id="organizers">Organizers</h2>
<p>
{% include organizers.html %}
</p>

<!-- <h2 class="blackpar_title" id="Organizers">Volunteers</h2>
<div class="row_perso">
	<div class="card_perso column_perso justify-content-center" style="margin-left:24%;">
	  <img src="/images/khalil_bibi.png" alt="Khalil Bibi" class="img_card_perso">
	  <div class="container_perso" >
		<center>
		<h6>
			<b>Khalil Bibi</b>
			<br>
			Huawei Noah's Ark Lab
		</h6>
		</center>
	  </div>
	</div>
	<div class="card_perso column_perso">
	  <img src="/images/Soheila.png" alt="Soheila Samiee" class="img_card_perso">
	  <div class="container_perso">
		<center>
		<h6>
			<b>Soheila Samiee</b>
			<br>
			BASF
		</h6>
		</center>
	  </div>
	</div>
</div> -->


<br><br>

<!-- Technical Committee -->
<h2 class="blackpar_title" id="technical_committee">Technical Committee</h2>
<p>
{% include technical_committee.html %}
</p>
<br><br>

<!-- <h2 class="blackpar_title">Platinium Sponsor</h2>
<div class="row">
	<div class="col">
		<center>
			<img src="/images/huawei_logo.png">
		</center>
	</div>
	<div class="col">
		<center>
			<img src="/images/noahs_ark_lab_logo.png" width="250px">
		</center>
	</div>
</div>

<h2 class="blackpar_title">Gold Sponsor</h2>
<div class="row">
	<div class="col">
		<center>
			<img src="/images/BASF_logo.png" width="250px">
		</center>
	</div>
	<div class="col">
		<center>
			<img src="/images/rbc_logo.svg" width="250px">
		</center>
	</div>
</div> -->
