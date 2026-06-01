---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an undergraduatestudent (enrolled in 2024, currently a **sophomore**) deeply passionate about **Generative AI** and atthe forefront of deep learning research. My focus primarily lies in Latent Diffusion Models, Diffusion Transformers (DiTs), LargeLanguage Model (LLM) Agents, and efficient inference techniques. 

Driven by strong academic curiosity and engineeringcapability, I actively bridge the gap between cutting-edge research and open-source community deployment. I have an extensive trackrecord in training large-scale generative networks, building robust interactive frameworks, and developing high-performance inference acceleration systems. Myultimate goal is to build advanced, accelerated, and highly interactive multimodal intelligent systems.

<br>
# 📚Research & Publications

<style>
.publications{
  margin-top:30px;
}

.pub-item{
  display:flex;
  align-items:center;
  gap:28px;
  margin-bottom:32px;
}

.pub-figure{
  width:190px;
  height:130px;
border-radius:14px;
  overflow:hidden;
  background:#fff;
  box-shadow:0 4px 14px rgba(0,0,0,0.08);
  flex-shrink:0;
}

.pub-figure img{
  width:100%;
height:100%;
  object-fit:contain;
}

.pub-contentp{
  margin:4px 0;
  font-size:16px;
}

.pub-content strong{
  font-size:17px;
}

.pub-buttons{
  margin-top:6px;
}

.pub-buttons a{
text-decoration:none;
}

.pub-buttons button{
  background:#4CAF50;
  border:none;
  color:white;
  padding:6px 14px;
  font-size:14px;
  border-radius:6px;
  cursor:pointer;
  margin-right:6px;
}
</style>

<div class="publications">

<div class="pub-item">
  <div class="pub-figure">
    <img src="/images/jlt_training_curves.png" alt="JLT Curves">
  </div>

  <div class="pub-content">
    <p><strong>JLT: Clean-Latent Prediction in Latent Diffusion Transformers</strong></p>
    <p><strong>Funing Fu*</strong>, <strong>Tenghui Wang*</strong>, Guanyu Zhou, Junyong Cen, Qichao Zhu</p>
    <p style="font-size: 14px; color: #666; font-style: italic;">(* Indicates Equal Contribution / Co-First Authorship)</p>

    <div class="pub-buttons">
      <a href="[https://arxiv.org/abs/2605.27102](https://arxiv.org/abs/2605.27102)"><button>PDF</button></a>
<a href="[https://github.com/akatsuki-neo/JLT](https://github.com/akatsuki-neo/JLT)"><button>Code</button></a>
      <a href="[https://akatsuki-neo.github.io/JLT](https://akatsuki-neo.github.io/JLT)"><button>Page</button></a>
      <a href="[https://huggingface.co/dawn-neo/JLT](https://huggingface.co/dawn-neo/JLT)"><button>HF</button></a>
      <a href="https://wwww.zhihu.com/question/1972662017648264174/answer/2044334746961019013](https://www.zhihu.com/question/1972662017648264174/answer/2044334746961019013)"><button>Blog</button></a>
    </div>
  </div>
</div>

</div>

<br>
# 🚀 Open Source & Engineering Experience

<style>
.experience {
  margin-top: 30px;
}

.exp-item {
  display: flex;
  align-items: flex-start;
  gap: 24px;
margin-bottom: 32px;
}

.logo-box {
  width: 120px;
  height: 120px;
  background: #fff;
  border-radius:16px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  box-shadow: 0 4px 14pxrgba(0,0,0,0.06);
  flex-shrink: 0;
border: 1px solid #eee;
}

.logo-box span {
  font-weight:bold;
  color: #4CAF50;
  font-size: 22px;
  text-align: center;
}

.exp-content {
  flex-grow: 1;
}

.exp-content h3 {
  margin: 0 0 6px 0;
  font-size: 19px;
  color: #333;
}

.exp-content p {
  margin: 4px 0;
  font-size:15px;
  line-height: 1.5;
  color: #555;
}

.exp-content ul {
  margin: 6px 0 00;
  padding-left: 20px;
  font-size: 14.5px;
  color: #444;
}

.exp-content ul li {
margin-bottom: 6px;
}
</style>

<div class="experience">

  <div class="exp-item">
    <div class="logo-box">
      <span>Neta</span>
    </div>
    <div class="exp-content">
      <h3><strong>NetaArt & Lumina Team</strong> | Core Trainer & Developer</h3>
      <p>Contributed actively to large-scale generative modeltraining infrastructures and high-performance inference acceleration pipelines.</p>
      <ul>
        <li><strong>Neta-Lumina:</strong> Acted as a core trainer and developer for the <a href="[https://huggingface.co/neta-art/Neta-Lumina](https://huggingface.co/neta-art/Neta-Lumina)">Neta-Lumina</a> project, orchestrating scalable pre-training and fine-tuning blocks for state-of-the-art artistic generation.</li>
        <li><strong>TeaCache Integration:</strong> Independently authored and integrated the <a href="[https://github.com/ali-vilab/TeaCache](https://github.com/ali-vilab/TeaCache)">TeaCache</a> acceleration implementation for <strong>Lumina2</strong>, drastically boosting inference speed by caching redundant timestep latents without compromisingperceptual quality.</li>
      </ul>
    </div>
  </div>

  <div class="exp-item">
    <div class="logo-box">
      <span>CN</span>
    </div>
    <divclass="exp-content">
      <h3><strong>Chenkin Noob Community & CV Projects</strong> | Active Developer</h3>
      <p>Pioneered high-impact community generative models and comprehensive perception pipelines with solid traction.</p>
      <ul>
        <li><strong>ChenkinNoob Collective:</strong> Active developer within the <a href="[https://huggingface.co/ChenkinNoob](https://huggingface.co/ChenkinNoob)">ChenkinNoob</a> open-source group, creating and maintaining high-quality generative checkpoints and community tools.</li>
        <li><strong>Artist StyleClustering & Custom Nodes:</strong> Spearheaded the training of a specialized artist-style clustering model. Developed and open-sourced <a href="[https://github.com/spawner1145/comfyui-lsnet.git](https://github.com/spawner1145/comfyui-lsnet.git)">comfyui-lsnet</a>, a highly popular ComfyUI custom node that gained widespread recognition within the AI art community. Also well-versed in developing downstream CV applications like image classification and object detection.</li>
      </ul>
    </div>
</div>

  <div class="exp-item">
    <div class="logo-box">
      <span>Agent</span>
    </div>
    <div class="exp-content">
      <h3><strong>LLM Agents & Interactive Ecosystems</strong> | Core Architect</h3>
      <p>Architected full-stack interactiveagent frameworks, multi-agent coordination systems, and natural language communication backends.</p>
      <ul>
        <li><strong>Eridanus & Manyana:</strong> Served as a core developer and engineer for <a href="[https://github.com/AOrbitron/Eridanus](https://github.com/AOrbitron/Eridanus)">Eridanus</a> and <a href="[https://github.com/avilliai/Manyana.git](https://github.com/avilliai/Manyana.git)">Manyana</a>, building sophisticated multi-agent orchestration layers, conversational memory, andadvanced tool-calling capabilities.</li>
      </ul>
    </div>
  </div>

</div>

<br>
# 🛠️ Technical Skills

* **Deep Learning Ecosystem:**PyTorch, Hugging Face (`transformers`, `diffusers`, `accelerate`), DeepSpeed.
* **GenerativeArchitectures:** Latent Diffusion Models (LDM), Diffusion Transformers (DiT), Flow Matching, Attention Mechanisms, VAEs.
* **Computer Vision & Perception:** Style Clustering, Image Classification, Object Detection (YOLO, DETR architectures),Feature Extraction.
* **LLM & Agent Systems:** Multi-Agent Coordination, Tool-Calling/Function-Callingpipelines, Retrieval-Augmented Generation (RAG), High-Performance Inference Optimization (TeaCache, Quantization).

<div style="margin-top: 100px;"></div>

<div style="display:none;">
    <script type="text/javascript" id="mapmyvisitors" src="//mappmyvisitors.com/map.js?d=8MhgTWHJEZzdE82Bb-wBII3RuujWQtydOxS12ZLFdM8&cl=ffffff&w=a](https://mapmyvisitors.com/map.js?d=8MhgTWHJEZzdE82Bb-wBII3RuujWQtydOxS12ZLFdM8&cl=ffffff&w=a)"></script>
</div>
