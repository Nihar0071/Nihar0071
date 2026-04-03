<h1 align="center">Nihar Patel</h1>
<h3 align="center">ML Engineer · Building Efficient AI Inference Systems · Open Source Contributor</h3>

<p align="center">
  <em>I build AI systems where none exist — from production LLM pipelines to GPU-optimized inference runtimes on consumer hardware.</em>
</p>

<p align="center">
  <a href="https://portfolio-nihar-patel.netlify.app/">Portfolio</a> ·
  <a href="https://linkedin.com/in/nihar-patel-183043231">LinkedIn</a> ·
  <a href="mailto:niharpatel9971@gmail.com">Email</a>
</p>

---

### About

ML Engineer with 2+ years building production LLM systems, agentic AI pipelines, and GPU-optimized runtimes. M.S. Computer Science from Boston University (4.0 GPA). Open-source contributor to **TensorFlow** (merged into `master`). Published researcher in federated learning and computer vision.

Currently focused on **efficient on-device inference** — speculative decoding, PagedAttention, KV cache optimization, and memory-efficient runtimes that bring powerful AI to consumer hardware.

---

### What I'm Building

🔬 **vllm-mps** — PagedAttention inference engine for Apple Silicon  
Built a vLLM-style paged KV-cache runtime for Apple MPS. Achieved **3.46× throughput** over HuggingFace baseline (6.5 → 22.5 tok/s on TinyLlama 1.1B, M1 MacBook Air) via block-ID caching, batched decode, and MPS shader warmup.

⚡ **Moleculic** — LLM Runtime & Distributed Training System  
Multi-GPU distributed fine-tuning with PyTorch FSDP + DeepSpeed ZeRO-3 on 4×A100 GPUs. Deployed on Kubernetes with autoscaling, GPU-aware scheduling, and Prometheus/NVIDIA Nsight observability. Applied 8-bit quantization + LoRA cutting inference memory by 35%.

🏢 **Seagate Technology** — ML Engineer  
Engineered document vectorization across 100K+ docs. Designed multi-agent AI systems across 9+ departments. Reduced LLM hallucination rate by 27%. Optimized production LLMs using quantization, distillation, and LoRA/PEFT.

---

### Open Source

- **TensorFlow** — Fixed a critical iOS/macOS Bazel build failure across 5 Apple architectures. [PR merged into `tensorflow:master`](https://github.com/tensorflow/tensorflow)

---

### Research & Publications

- **Federated Learning-aided LSTM for Price Prediction** — [DOI: 10.3934/era.2023330](https://doi.org/10.3934/era.2023330)  
- **CNN and UAV-based Public Safety Framework** — [DOI: 10.1002/dac.5545](https://doi.org/10.1002/dac.5545)

---

### Tech Stack

**ML / AI:** PyTorch · TensorFlow · JAX · vLLM · llama.cpp · DeepSpeed · FSDP · LoRA/PEFT · LangChain · LlamaIndex · RAG · Agentic AI  
**Inference:** PagedAttention · Quantization (8-bit/4-bit) · KV Cache Optimization · Speculative Decoding · Distillation  
**Infrastructure:** CUDA · MPS · Docker · Kubernetes · Prometheus · NVIDIA Nsight · PyTorch Profiler  
**Cloud:** Azure (ML, AKS, OpenAI) · AWS (S3, Glue, RDS) · Spark · PostgreSQL · VectorDB  
**Languages:** Python · C++ · Rust · Java · JavaScript · GoLang · SQL

---

### GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nihar0071&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" />
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=nihar0071&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

---

<p align="center">
  <strong>Interested in efficient AI inference, on-device LLMs, or distributed systems?</strong><br/>
  Let's connect — I'm always looking to collaborate on projects pushing the boundaries of what's possible on consumer hardware.
</p>
