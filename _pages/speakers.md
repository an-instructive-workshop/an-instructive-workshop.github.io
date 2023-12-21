---
layout: page
permalink: /speakers/
title: Speakers
nav: true
nav_order: 2
---

## Talks

<html>
    <div class="team-container">
        <div class="team-member">
            <img src="/assets/img/speakers/thashim.jpg" alt="Name 6">
            <p><a href="https://thashim.github.io/">Tatsunori Hashimoto</a>
            <br>Stanford University</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/nazneen_rajani.jpg" alt="Name 2">
            <p><a href="https://www.nazneenrajani.com/">Nazneen Rajani</a>
            <br>(Formerly) <br>Hugging Face</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/fei_xia.jpg" alt="Name 5">
            <p><a href="https://fxia22.github.io/">Fei Xia</a>
            <br>Google DeepMind</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/sara_hooker.jpg" alt="Name 4">
            <p><a href="https://www.sarahooker.me/">Sara Hooker</a>
            <br>Cohere for AI</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/speakers/alex_tamkin.jpg" alt="Name 1">
            <p><a href="https://www.alextamkin.com/">Alex Tamkin</a>
            <br>Anthropic</p>
        </div>
    </div>
</html>

#### Empowering Instruction Following Research with Language Models as Simulators

[[Slides]](/assets/pdf/Tatsunori_Hashimoto_Talk.pdf)

__Speaker:__ Tatsunori Hashimoto, Stanford University

__Time:__ 9:00am-9:30am


__Abstract:__ Instruction-following language models have driven remarkable progress in a range of NLP tasks and have been rapidly adopted across the world. However, academic research into these models has lagged behind due to the lack of open, reproducible, and low-cost environments with which to develop and test instruction-following models. In this talk, I will discuss how new, emerging approaches that study an LLM's ability to emulate human annotators and API endpoints hold promise in improving and critiquing LLMs. To improve instruction-following methods, recent work from our group such as AlpacaFarm shows how an LLM-based simulator can help test scientific hypotheses (e.g. is reinforcement learning helpful?) develop better instruction-following methods, and red-team LLMs in a more open and reproducible way. At the same time, there are major limits to LLMs’ ability to simulate annotators — such as in the opinions they reflect or the consistency of their responses — and we will discuss how these gaps raise important open problems in the trustworthiness of existing LLMs.

__Bio:__ Tatsunori Hashimoto is an Assistant Professor in the Computer Science Department at Stanford University. He is a member of the statistical machine learning and natural language processing groups at Stanford, and his research uses tools from statistics to make machine learning systems more robust and trustworthy — especially in complex systems such as large language models. He is a Kavli fellow, a Sony and Amazon research award winner, and his work has been recognized with best paper awards at ICML and CHI. Before becoming an Assistant Professor, he was a postdoctoral researcher at Stanford with Percy Liang and John Duchi and received his Ph.D. from MIT under the supervision of Tommi Jaakkola and David Gifford.

<br>
#### Manual Curation vs. AI Distillation: Lessons Learned for Instruction Following and Feedback Fine-tuning 

[[Slides]](https://www.nazneenrajani.com/neurips_instruction_tuning.pdf)

__Speaker:__ Nazneen Rajani 

__Time:__ 9:30am-10:00am

__Abstract:__ There has been a slew of work in training helpful conversational agents using Large language models (LLMs). These models draw upon diverse datasets, including open-source repositories, private data, and even synthetic data generated from LLMs. However, curating datasets for SFT and RLHF involves critical decisions, such as defining task distributions, data volume, prompt length, and more. While prior research underscores the importance of data quality, the nuanced impact of these various dataset factors on model performance remains unclear. I’ll present and compare our approaches for data curation using human labor and AI distillation in the context of training helpful chatbots. I will delve into the results of experiments that illuminate the nuanced effects of different dataset attributes on the training process of helpfulness in chatbots.

__Bio:__ Most recently, Nazneen was a Research lead at Hugging Face and worked on alignment and AI safety, and evaluation. Recently, she and her team released the Zephyr model, which is already part of You.com's product offerings. Nazneen is selected by the UN's secretary general to serve on the AI Advisory Body along with other global experts in AI https://www.un.org//ai-advisory-body. More details about my work can be found at https://www.nazneenrajani.com/


<br>
#### Towards Instruction Following Robots

__Speaker:__ Fei Xia

__Time:__ 10:15am-10:45am

__Abstract:__ This talk focuses on the integration of instruction-following language models in the field of robotics, leveraging two novel concepts: Affordance and Language to Reward (L2R). Affordance, as proposed in existing literature, provides a framework for robots to understand and interact with their environment in a meaningful way. It is defined as the potential actions that an environment enables for an agent, thereby granting robots the ability to execute tasks in various contexts. This concept allows robots to generate plans that are grounded in their environments. On the other hand, Language to Reward (L2R), proposes a new way to use language models in robotics zero-shot.. L2R utilizes reward functions as a flexible interface, bridging the gap between abstract language instructions and specific, actionable tasks for robots. Through this method, language models can define reward parameters, which are then optimized to direct robot actions effectively. The use of a real-time optimizer, such as MuJoCo MPC, enhances this process by allowing for an interactive and dynamic experience. Users can instantly see the outcomes of their instructions, providing immediate feedback that can be used to modify and improve the robot's behavior.

__Bio:__ Fei Xia is a senior research scientist at Google DeepMind, focusing on the field of robotics. His work involves building intelligent agents capable of interacting with complex, unstructured real-world environments, with applications in home robotics. Recently his work centers around foundation models for robotics: This involves using large language models (LLMs) to learn general-purpose skills that can be applied to a variety of robotic tasks.


<br>
#### Challenges and Open Opportunities in Instruction Tuning: The Case Study of AYA

__Speaker:__ Sara Hooker

__Time:__ 2:00pm-2:30pm

__Abstract:__ In this talk, to frame many of the open challenges and opportunities with instruction tuning, I'll share some of the lessons learned and open questions spurred by AYA. AYA is a year long open science endeavor aimed at building a multilingual language model via instruction tuning that harnesses the collective wisdom and contributions of independent researchers across the world. It aims to improve coverage of instruction finetuned datasets for 101 languages around the world. The project was initiated by Cohere For AI as a multi-institutional collaboration with researchers, engineers, linguists, social scientists, and lifelong learners from over 100 countries around the world. I'll use this setting as a springboard to discuss a wider set of research directions on instruction finetuning optimization approaches.

__Bio:__ Sara Hooker leads Cohere For AI, a non-profit research lab that seeks to solve complex machine learning problems. Cohere For AI supports fundamental research that explores the unknown, and is focused on creating more points of entry into machine learning research. With a long track-record of impactful research at Google Brain, Sara brings a wealth of knowledge from across machine learning. Her work has focused on model efficiency training techniques and optimizing for models that fulfill multiple desired criteria -- interpretable, efficient, fair and robust. Before Cohere For AI, she was the founder of Delta Analytics, a non-profit that brings together researchers, data scientists, and software engineers to volunteer their skills for non-profits around the world.

<br>
#### Beyond Instruction Following 

[[Slides]](https://docs.google.com/presentation/d/1geLScLm6rGj-tWU5EeQh-oGvkKAUgGSBGUpRSETKOuI/edit#slide=id.p)

__Speaker:__ Alex Tamkin

__Time:__ 2:30pm-3:00pm

__Abstract:__ This talk will discuss some open research challenges and opportunities surrounding the role of instructions in instruction following models. I'll also discuss our recent work on Eliciting Human Preferences with Language Models (Li and Tamkin et al 2023) which aims at addressing some of these challenges.

__Bio:__ Alex Tamkin is a research scientist at Anthropic. Previously, he was a PhD student in Computer Science at Stanford, where he was a part of the Stanford AI Lab and Stanford NLP Group.



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
</style>

<br><br>