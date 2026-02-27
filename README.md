# Hi there, I'm Belal Yahouni 👋

### AI Engineer | Systems & Inference Optimization

I am a Computer Science student at the **University of Leeds** (First Class Honours) with a deep focus on **Machine Learning Infrastructure**. I have previous experience from internships and projects in building AI solutions, and optimising existing LLMs to improve inference perfromance.

Currently, I am researching **Mixture-of-Experts (MoE) inference on memory-constrained multi-GPU systems** for my dissertation.

---

### 🚀 Key Focus Areas

* **LLM Inference Optimization:** Profiling and optimizing throughput/latency for large models (vLLM,sgLang,NVIDIA Dynamo, Mooncake).
* **GPU Profiling:** Using Nsight Systems and NVTX to identify compute vs. memory bottlenecks.
* **Distributed Systems:** Building scalable pipelines on Azure and training Transformers with DDP.
* **Pragmatic AI:** Building privacy-compliant, local-first AI tools that solve actual developer pain points.

---

### 🛠️ Featured Repositories

#### 🧠 Inference & Systems Research
* **[Dissertation](https://github.com/belalyahouni/Dissertation)**: My ongoing research into optimizing MoE LLM inference. I am developing dynamic memory allocators to manage offloading strategies between KV cache and experts on limited hardware.
* **[containerised-nvidia-dynamo](https://github.com/belalyahouni/containerised-nvidia-dynamo)**: A CLI tool that consolidates 6 manual setup steps into a single command. It provides a ready-to-use Docker environment for running NVIDIA’s Dynamo inference framework with a vLLM backend.
* **[benchmarking-baselines](https://github.com/belalyahouni/benchmarking-baselines)**: Automated suites using **GenAI-Perf** to benchmark latency and throughput across different parallelism strategies.

#### 🔍 Semantic Search & Tooling
* **[semantic-repo-search](https://github.com/belalyahouni/semantic-repo-search)**: A local RAG-style pipeline for navigating large codebases.
    * *Performance:* Achieved sub-40ms retrieval across 3,500 files using FAISS and FastAPI.
    * *Privacy:* Runs entirely locally to avoid cloud data exposure.
* **[Finetune-model-cosqa](https://github.com/belalyahouni/Finetune-model-cosqa)**: Fine-tuned **DistilBERT** on the CoSQA dataset using Multiple Negatives Ranking loss, achieving significant gains in Recall@10 and nDCG@10 for code retrieval.

#### 📚 Implementations & Cloud
* **[attention-is-all-you-need](https://github.com/belalyahouni/attention-is-all-you-need)**: A from-scratch PyTorch implementation of the Transformer architecture (Multi-head attention, positional encoding) trained on WMT14.
* **[AZURE-DS-CWK](https://github.com/belalyahouni/AZURE-DS-CWK)**: Serverless IoT pipeline on **Azure Functions**. Handles high-velocity sensor data ingestion into Azure SQL with real-time statistical aggregation.

---

### 💻 Tech Stack

| Domain | Technologies |
| :--- | :--- |
| **Languages** | Python, C/C++, CUDA, SQL, Bash |
| **AI Frameworks** | PyTorch, vLLM, NVIDIA Dynamo, Hugging Face, FAISS |
| **Tools & Ops** | Docker, Git, GitHub Actions, Azure (Functions, SQL) |
| **Profiling** | NVIDIA Nsight Systems, GenAI-Perf, Pandas/Matplotlib (for trace analysis) |

---

### 📫 Connect with Me

* **LinkedIn:** [linkedin.com/in/belal-yahouni](https://linkedin.com/in/belal-yahouni)
* **Email:** belalyahouni@gmail.com
