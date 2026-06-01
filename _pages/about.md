---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I’m a sophomore undergraduate student in the **Department of Mathematics at Wuhan University of Technology**. My research interests include **Generative AI**, **diffusion models**, **Diffusion Transformers (DiTs)**, **LLM agents**, and efficient training and inference systems. I am particularly interested in translating cutting-edge research ideas into practical open-source systems and community-facing tools.

I have built both research and engineering experience across generative modeling, interactive AI systems, and computer vision. My broader interests also include **image classification**, **object detection**, and multimodal intelligent systems.

My long-term goal is to build powerful, efficient, and interactive AI systems that combine strong research insight with real-world usability.

<br>
# 📚 Research & Publications

<style>
.publications {
  margin-top: 30px;
}

.pub-item {
  display: flex;
  align-items: center;
  gap: 28px;
  margin-bottom: 32px;
}

.pub-figure {
  width: 190px;
  height: 130px;
  border-radius: 14px;
  overflow: hidden;
  background: #fff;
  box-shadow: 0 4px 14px rgba(0,0,0,0.08);
  flex-shrink: 0;
}

.pub-figure img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}

.pub-content p {
  margin: 4px 0;
  font-size: 16px;
}

.pub-content strong {
  font-size: 17px;
}

.pub-buttons {
  margin-top: 6px;
}

.pub-buttons a {
  text-decoration: none;
}

.pub-buttons button {
  background: #4CAF50;
  border: none;
  color: white;
  padding: 6px 14px;
  font-size: 14px;
  border-radius: 6px;
  cursor: pointer;
  margin-right: 6px;
}
</style>

<div class="publications">

<div class="pub-item">
  <div class="pub-figure">
    <img src="/images/jlt_training_curves.png" alt="JLT Training Curves">
  </div>

  <div class="pub-content">
    <p><strong>JLT: Clean-Latent Prediction in Latent Diffusion Transformers</strong></p>
    <p><strong>Funing Fu*</strong>, <strong>Tenghui Wang*</strong>, Guanyu Zhou, Junyong Cen, Qichao Zhu</p>
    <p><em>* equal contribution</em></p>

    <div class="pub-buttons">
      <a href="https://arxiv.org/abs/2605.27102"><button>PDF</button></a>
      <a href="https://github.com/akatsuki-neo/JLT"><button>Code</button></a>
      <a href="https://akatsuki-neo.github.io/JLT"><button>Page</button></a>
      <a href="https://huggingface.co/dawn-neo/JLT"><button>HF</button></a>
      <a href="https://www.zhihu.com/question/1972662017648264174/answer/2044334746961019013"><button>Blog</button></a>
    </div>
  </div>
</div>

</div>

<br>
# 📇 Open Source & Engineering Experience

<style>
.experience {
  margin-top: 40px;
}

.exp-item {
  display: flex;
  align-items: flex-start;
  gap: 24px;
  margin-bottom: 28px;
}

.logo-box {
  width: 120px;
  height: 120px;
  background: #fff;
  border-radius: 16px;
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 0 4px 14px rgba(0,0,0,0.06);
  flex-shrink: 0;
}

.logo-box span {
  font-size: 24px;
  font-weight: 700;
  color: #4CAF50;
}

.exp-content p {
  margin: 4px 0 8px 0;
  font-size: 16px;
}

.exp-content strong {
  font-size: 17px;
}

.exp-content ul {
  margin: 8px 0 0 0;
  padding-left: 20px;
}

.exp-content li {
  margin-bottom: 8px;
  line-height: 1.6;
}
</style>

<div class="experience">

  <div class="exp-item">
    <div class="logo-box">
      <span>NL</span>
    </div>
    <div class="exp-content">
      <p><strong>Neta Lumina Team</strong></p>
      <ul>
        <li>Core trainer and developer of <a href="https://huggingface.co/neta-art/Neta-Lumina">Neta-Lumina</a>.</li>
        <li>Implemented <a href="https://github.com/ali-vilab/TeaCache">TeaCache</a> for Lumina2.</li>
        <li>Added <a href="httpsgithub.com/KohakuBlueleaf/LyCORIS">LyCORIS</a> training support for Lumina.</li>
      </ul>
    </div>
  </div>

  <div class="exp-item">
    <div class="logo-box">
      <span>CN</span>
    </div>
    <div class="exp-content">
      <p><strong>Chenkin Noob Community</strong></p>
      <ul>
        <li>Active developer in the <a href="https://huggingface.co/ChenkinNoob">Chenkin Noob</a> community team.</li>
        <li>Led training of an artist-style clustering model and developed <a href="https://github.com/spawner1145/comfyui-lsnet.git">comfyui-lsnet</a>.</li>
        <li>Developed and open-sourced image generation samplers for <a href="https://github.com/spawner1145/sd-samplers.git">SDXL</a>.</li>
      </ul>
    </div>
  </div>

  <div class="exp-item">
    <div class="logo-box">
      <span>AG</span>
    </div>
    <div class="exp-content">
      <p><strong>LLM Agents & Interactive Systems</strong></p>
      <ul>
        <li>Core developer in LLM agents and interactive AI systems.</li>
        <li>Contributed to <a href="https://github.com/AOrbitron/Eridanus">Eridanus</a> and <a href="https://github.com/avilliai/Manyana.git">Manyana</a>.</li>
      </ul>
    </div>
  </div>

  <div class="exp-item">
    <div class="logo-box">
      <span>CV</span>
    </div>
    <div class="exp-content">
      <p><strong>Computer Vision Development</strong></p>
      <ul>
        <li>Experience in image classification, object detection, and model training workflows.</li>
      </ul>
    </div>
  </div>

</div>

<br>
# 🛠 Skills

* **Frameworks & Ecosystem:** PyTorch, Hugging Face Transformers, Diffusers, Accelerate
* **Generative AI:** Diffusion Models, Latent Diffusion, Diffusion Transformers, efficient training and inference
* **LLM Systems:** LLM agents, interactive systems, tool calling, workflow design
* **Computer Vision:** Image classification, object detection, style clustering
* **Engineering:** Open-source development, training pipelines, inference optimization
