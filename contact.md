---
title: "Learning Roadmap"
layout: splash
permalink: /roadmap/
header:
  overlay_color: "#000"
  overlay_filter: "0.2"
  overlay_image: /assets/images/roadmap.jpg
  actions:
    - label: "GitHub"
      url: "https://github.com/DivSeth"
excerpt: "A visual journey of my growth as a software engineer — across systems, AI, and deployment."
---

<!-- Timeline Style -->
<style>
  .timeline {
    position: relative;
    max-width: 900px;
    margin: auto;
    padding: 2rem 0;
  }
  .timeline::after {
    content: '';
    position: absolute;
    width: 6px;
    background-color: #007acc;
    top: 0;
    bottom: 0;
    left: 50%;
    margin-left: -3px;
  }
  .timeline-entry {
    padding: 1rem 2rem;
    position: relative;
    background-color: inherit;
    width: 50%;
  }
  .timeline-entry.left {
    left: 0;
  }
  .timeline-entry.right {
    left: 50%;
  }
  .timeline-entry::after {
    content: ' ';
    position: absolute;
    width: 25px;
    height: 25px;
    right: -12px;
    background-color: white;
    border: 4px solid #007acc;
    top: 15px;
    border-radius: 50%;
    z-index: 1;
  }
  .timeline-entry.right::after {
    left: -13px;
  }
  .timeline-content {
    padding: 1rem;
    background-color: #f9f9f9;
    position: relative;
    border-radius: 6px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  }
  @media (prefers-color-scheme: dark) {
    .timeline::after { background-color: #66ccff; }
    .timeline-content { background-color: #222; color: #e0e0e0; }
  }
</style>

<div class="timeline">

  <div class="timeline-entry left">
    <div class="timeline-content">
      <h3>🔍 Algorithms & DSA</h3>
      <p>Mastering Leetcode patterns, competitive programming, and TypeScript fundamentals.</p>
    </div>
  </div>

  <div class="timeline-entry right">
    <div class="timeline-content">
      <h3>🧰 Backend Systems</h3>
      <p>Building RESTful apps with Node.js, Redis, PostgreSQL, and message queues like Kafka.</p>
    </div>
  </div>

  <div class="timeline-entry left">
    <div class="timeline-content">
      <h3>🐳 DevOps & Deployment</h3>
      <p>Learning Docker, Kubernetes, GitHub Actions, and deploying microservices to GCP.</p>
    </div>
  </div>

  <div class="timeline-entry right">
    <div class="timeline-content">
      <h3>🤖 AI/ML Engineering</h3>
      <p>Working with LangChain, FAISS, Milvus, fine-tuned LLMs, and scalable RAG systems.</p>
    </div>
  </div>

  <div class="timeline-entry left">
    <div class="timeline-content">
      <h3>🎨 Frontend & UX</h3>
      <p>Refining React, Tailwind, Figma and motion design with Framer Motion for interactive UIs.</p>
    </div>
  </div>

  <div class="timeline-entry right">
    <div class="timeline-content">
      <h3>📈 Long-Term Vision</h3>
      <p>Ship polished projects, publish technical blogs, and land a high-impact SWE/ML internship by 2026.</p>
    </div>
  </div>

</div>

<p style="text-align:center; margin-top:2rem;">
  👉 Follow my journey on <a href="https://github.com/DivSeth" target="_blank">GitHub</a> or <a href="https://linkedin.com/in/divyaanshseth" target="_blank">LinkedIn</a>
</p>