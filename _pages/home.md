---
layout: default2
title: home
permalink: /
title: <h3  align="center">Workshop on Instruction Tuning and Instruction Following</h3>
nav_order: 1
---


<html lang="en">
<div class="news-box">
  <h4>Announcements</h4>
  <br>
  <p>1. <b>Recordings</b> are available on the <a href="https://neurips.cc/virtual/2023/workshop/66498" target="_blank">NeurIPS website</a> (NeurIPS registration required). They will be made public after one month (Jan 2024).<br>
  2. <b>Talk slides</b> are posted on the <a href="/speakers">speakers page</a>.<br>
  3. Congratuations to <a href="#paper-awards">paper award winners</a>!<br>
  4. <b>Workshop highlights and photos</b> can be found on our <a href="https://twitter.com/itif_workshop">Twitter</a>.
  <br><br>
  Thank you for joining us at NeurIPS 2023! Hope to see you next time! 
  </p>
</div>
</html>

<br>

Recent advancements in training large language models (LLMs) to follow "instructions" have significantly increased their ability to comprehend open-ended language commands, encompassing a wide range of needs, preferences, and values.

This remarkable transformation has led to the creation of remarkable industrial models such as [GPT-4](https://arxiv.org/abs/2303.08774) and [Bard](https://blog.google/technology/ai/bard-google-ai-search-updates/), as well as an increased focus within the open-source and research communities: creating new benchmark and resources [[1](https://aclanthology.org/2022.emnlp-main.340/),[2](https://arxiv.org/abs/2301.13688)], developing new training methods [[3](https://arxiv.org/abs/2203.02155),[4](https://arxiv.org/abs/2212.10560)], and understanding the limitations of these methods [[5](https://arxiv.org/abs/2109.01247)]. Furthermore, instruction following powered by LLMs has proven to be effective in multi-modal settings, with applications in image editing [[6](https://arxiv.org/abs/2211.09800)] and robotic command execution [[7](https://arxiv.org/abs/2204.01691)].

We organize this workshop to facilitate discussions on advancing instruction tuning methodologies and constructing general-purpose instruction-following models. We believe it is crucial to organize this workshop due to the prevalence of proprietary models with restricted access, thereby creating the need for an open platform to encourage discussions. Moreover, we aim to foster interdisciplinary collaboration by bringing together researchers from diverse fields such as natural language processing, computer vision, robotics, human-computer interaction, AI safety, among others, to share their latest findings and explore potential avenues for future research.

__Centering on "instructions,"__ we invite submissions covering various topics, including but not limited to the list below:

* __Modeling:__ algorithms and pipelines for learning from instructions and human feedback; designing training objectives and rewards; training and inference efficiency
* __Data Collection:__ crowd-sourcing; synthetic data generation; data democratization
* __Evaluation and Oversight__: effective and reliable oversight over existing models; enforcing guardrails and guarantees for model behaviors; interpretability and analysis
* __Engineering and Open-sourcing:__ best practice in training, evaluation and deployment; open-sourcing efforts; openness and reproducibility
* __Applications:__ long-context, multi-round and personalized instruction-following models
* __Multimodal and Multidisciplinary:__ instruction following models for computer vision, robotics, games, art, etc.
* __Limitations, Risks and Safety:__ bias and fairness; factuality and hallucination; safety concerns arising from instruction-following models
* Other adjacent research topics (e.g., in-context learning, prompting, multi-task learning) that enable better responses to instructions in dynamic environments

<br>

## Speakers

Check talk details (title, abstract, speaker bio, slides) at this [page](speakers)!
<html>
    <div class="team-container">
        <div class="team-member">
            <img src="/assets/img/speakers/thashim.jpg" alt="Name 6">
            <p><a href="https://thashim.github.io/">Tatsunori Hashimoto</a>
            <br>Stanford University<br>9:00-9:30</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/nazneen_rajani.jpg" alt="Name 2">
            <p><a href="https://www.nazneenrajani.com/">Nazneen Rajani</a>
            <br>(Formerly)<br>Hugging Face<br>9:30-10:00</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/fei_xia.jpg" alt="Name 5">
            <p><a href="https://fxia22.github.io/">Fei Xia</a>
            <br>Google DeepMind<br>10:15-10:45</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/sara_hooker.jpg" alt="Name 4">
            <p><a href="https://www.sarahooker.me/">Sara Hooker</a>
            <br>Cohere for AI<br>14:00-14:30</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/alex_tamkin.jpg" alt="Name 1">
            <p><a href="https://www.alextamkin.com/">Alex Tamkin</a>
            <br>Anthropic<br>14:30-15:00</p>
        </div>
    </div>
</html>


## Panel 1 
##### Key Techniques, Insights, and Challenges in Building Instruction-following Models 
Time: 10:45-11:30
<html>
    <div class="team-container">
        <div class="team-member">
            <img src="/assets/img/speakers/alex_tamkin.jpg" alt="Name 1">
            <p><a href="https://www.alextamkin.com/">Alex Tamkin</a>
            <br>Anthropic</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/fei_xia.jpg" alt="Name 5">
            <p><a href="https://fxia22.github.io/">Fei Xia</a>
            <br>Google DeepMind</p>
        </div>        
        <div class="team-member">
            <img src="/assets/img/speakers/albert_webson.jpg" alt="Name 3">
            <p><a href="https://representation.ai/">Albert Webson</a>
            <br>Google DeepMind<br>University of Tokyo</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/raj.jpg" alt="Name 3">
            <p><a href="https://prithvirajva.com/">Prithviraj (Raj) Ammanabrolu</a>
            <br>UC San Diego<br>MosaicML</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/hyungwon.jpg" alt="Name 3">
            <p><a href="https://hwchung27.github.io/">Hyung Won Chung</a>
            <br>OpenAI</p>
        </div>
    </div>
</html>

## Panel 2
##### Open and Collaborative Strategies for Large Language Model Adaptation
Time: 15:15-16:00


<html>
    <div class="team-container">
        <div class="team-member">
            <img src="/assets/img/speakers/nazneen_rajani.jpg" alt="Name 2">
            <p><a href="https://www.nazneenrajani.com/">Nazneen Rajani</a>
            <br>(Formerly)<br>Hugging Face</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/thashim.jpg" alt="Name 6">
            <p><a href="https://thashim.github.io/">Tatsunori Hashimoto</a>
            <br>Stanford University</p>
        </div>    
        <div class="team-member">
            <img src="/assets/img/speakers/hao_zhang.jpeg" alt="Name 3">
            <p><a href="https://cseweb.ucsd.edu/~haozhang/">Hao Zhang</a>
            <br>UC San Diego<br>lmsys.org</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/colin_raffel.jpg" alt="Name 6">
            <p><a href="https://colinraffel.com/">Colin Raffel</a>
            <br>University of Toronto<br>Vector Institute</p>
        </div>
    </div>
</html>

## Paper Awards

##### Best Paper
1. [Delve into PPO: Implementation Matters for Stable RLHF](https://openreview.net/forum?id=rxEmiOEIFL)
<br>Rui Zheng, Shihan Dou, Songyang Gao, Yuan Hua, Wei Shen, Binghai Wang, Yan Liu, Senjie Jin, Yuhao Zhou, Limao Xiong, Lu Chen, Zhiheng Xi, Nuo Xu, Wenbin Lai, Minghao Zhu, Haoran Huang, Tao Gui, Qi Zhang, Xuanjing Huang
2. [Learning Interactive Real-World Simulators](https://openreview.net/forum?id=5O9JBt35zg)
<br>Sherry Yang, Yilun Du, Seyed Kamyar Seyed Ghasemipour, Jonathan Tompson, Dale Schuurmans, Pieter Abbeel

##### Honorable Mention
1. [Understanding Hidden Context in Preference Learning: Consequences for RLHF](https://openreview.net/forum?id=GO8aPQ9Odp)
<br>Anand Siththaranjan, Cassidy Laidlaw, Dylan Hadfield-Menell
2. [Tensor Trust: Interpretable Prompt Injection Attacks from an Online Game](https://openreview.net/forum?id=UWymGURI75)
<br>Sam Toyer, Olivia Watkins, Ethan Mendes, Justin Svegliato, Luke Bailey, Tiffany Wang, Isaac Ong, Karim Elmaaroufi, Pieter Abbeel, Trevor Darrell, Alan Ritter, Stuart Russell
3. [Understanding the Effects of RLHF on LLM Generalisation and Diversity](https://openreview.net/forum?id=Bc3S2G1PxH)
<br>Robert Kirk, Ishita Mediratta, Christoforos Nalmpantis, Jelena Luketina, Eric Hambro, Edward Grefenstette, Roberta Raileanu
4. [Interactive Planning Using Large Language Models for Partially Observable Robotics Tasks](https://openreview.net/forum?id=apEdj9baZx)
<br>Lingfeng Sun, Devesh Jha, Chiori Hori, Siddarth Jain, Radu Corcodel, Xinghao Zhu, Masayoshi Tomizuka, Diego Romeres
5. [Self-RAG: Self-reflective Retrieval Augmented Generation](https://openreview.net/forum?id=jbNjgmE0OP)
<br>Akari Asai, Zeqiu Wu, Yizhong Wang, Avirup Sil, Hannaneh Hajishirzi
6. [FLASK: Fine-grained Language Model Evaluation based on Alignment Skill Sets](https://openreview.net/forum?id=5dI6ZphLYX)
<br>Seonghyeon Ye, Doyoung Kim, Sungdong Kim, Hyeonbin Hwang, Seungone Kim, Yongrae Jo, James Thorne, Juho Kim, Minjoon Seo
<br><br>

## Organizers
<html>
    <div class="team-container">
        <div class="team-member">
            <img src="/assets/img/organizers/qinyuan_ye.jpg" alt="Name 1">
            <a href="http://yeqy.xyz/">Qinyuan Ye</a>
            <p>University of Southern California</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/yizhong_wang.jpg" alt="Name 2">
            <p><a href="https://homes.cs.washington.edu/~yizhongw/">Yizhong Wang</a>
            <br>University of Washington</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/shayne_longpre.jpg" alt="Name 3">
            <p><a href="https://www.shaynelongpre.com/">Shayne Longpre</a>
            <br>Massachusetts Institute of Technology</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/yao_fu.jpg" alt="Name 4">
            <p><a href="https://franxyao.github.io/">Yao Fu</a>
            <br>University of Edinburgh</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/daniel_khashabi.jpeg" alt="Name 5">
            <p><a href="https://danielkhashabi.com/">Daniel Khashabi</a>
            <br>Johns Hopkins University</p>
        </div>
    </div>
</html>

## Steering Committee

<html>
    <div class="team-container">
        <div class="team-member">
            <img src="/assets/img/organizers/hannaneh_hajishirzi.jpg" alt="Name 1">
            <p><a href="https://homes.cs.washington.edu/~hannaneh/">Hannaneh Hajishirzi</a>
            <br>University of Washington<br>Allen Institute for AI</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/xiang_ren.jpg" alt="Name 2">
            <p><a href="https://shanzhenren.github.io/">Xiang Ren</a>
            <br>University of Southern California<br>Allen Institute for AI</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/robin_jia.jpg" alt="Name 3">
            <p><a href="https://robinjia.github.io/">Robin Jia</a>
            <br>University of Southern California</p>
        </div>
    </div>
</html>

## Sponsors

<html>
    <div class="sponsor-container">
        <div class="sponsor">
            <img src="/assets/img/sponsors/ubiquant.jpg" alt="Ubiquant">
            <p class="caption"><a href="https://www.ubiquant.com/website/home">Ubiquant</a></p>
        </div>
        <div class="sponsor" >
            <img src="/assets/img/sponsors/sambanova.png" alt="SambaNova Systems" max-width=300px>
            <p class="caption"><a href="https://sambanova.ai/">SambaNova Systems</a></p>
        </div>
        <div class="sponsor" >
            <img src="/assets/img/sponsors/apple.png" alt="Apple" max-width=300px>
            <p class="caption"><a href="https://www.apple.com/">Apple</a></p>
        </div>
        <!-- <div class="right-half"></div> Empty right-half -->

    </div>
</html>

<style>
    /* Style for the team container */
.team-container {
    display: grid;
    grid-template-columns: repeat(5, 1fr); /* Display 3 members per row */
    gap: 5px;
    max-width: 1000px;
    padding: 20px;
}

@media (max-width: 768px) {
    .team-container {
        grid-template-columns: repeat(2, 1fr); /* Display 2 members per row on smaller screens */
    }
}

/* Style for each team member */
.team-member {
    text-align: center;
    background-color: #fff;
    padding: 0px;
    width: 150px; /* Set a fixed width for consistent circle appearance */
    height: 260px; /* Set a fixed height for consistent circle appearance */
    /* box-shadow: 0px 3px 6px rgba(0, 0, 0, 0.1); */
    overflow: hidden; /* Hide any image overflow */
}


.team-member h3 {
    font-size: 16px;
    color: #333;
}

.team-member img {
  object-fit: cover;
  border-radius:50%;
  width: 150px;
  height: 150px;
  padding: 10px;
}

.sponsor-container {
    display: flex;
    gap: 5px;
}

.sponsor {
    flex: 1;
    margin: 10px;
    text-align: center;
    box-sizing: border-box;
    height: 50px;
    width: 50px;
}

.sponsor img {  
    width: 100%; /* Make the image take up 100% of the figure's width */
    height: 100%;
    object-fit: contain; 
}

.caption {
    margin-top: 12px; /* Adjust the margin to control the gap between the figure and the caption */
}

.right-half {
    flex: 1; /* Each figure takes up 50% of the available width */
    height: 500px; /* Set a fixed height for all figures (adjust the value as needed) */
}

.news-box {
    border: 1px solid #ccc;
    padding: 10px;
    width: 600px;
    margin: 0 auto;
    background-color: #f9f9f9;
}

@media (max-width: 600px) {
    .news-box {
        width: 100%; /* Adjust width to fit the screen */
    }
}
</style>

<br><br>