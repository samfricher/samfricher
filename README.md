# Sam Richer

I build backend systems, data pipelines, and AI developer tools.

Computer Science & Applied Statistics at the **University of Toronto**, with a minor in Mathematics. Previously a software engineering intern at **Amazon Web Services** and **Veeva Systems**. Based in Toronto; graduating December 2027.

[LinkedIn](https://linkedin.com/in/samfricher)

## Engineering experience

**Amazon Web Services — RDS Platform**
- Designed and implemented a reusable AWS CDK construct that continuously synchronizes RDS databases with Amazon Bedrock Knowledge Bases, cutting estimated integration effort by **97.5%**, from four engineer-weeks to four hours.
- Built a distributed change data capture pipeline with DMS, Kinesis, and Lambda, including relational-to-document mapping, updates, deletes, and configurable table and schema selection.
- Built a CI/CD release gate that validated a **55-resource AWS stack** across **15 test layers**, reducing hands-on release testing by **96%**.
- Built a parallel Claude Code and Codex workflow with reusable planning, implementation, and validation stages, preserving instructions, artifacts, and lessons across features.

**Veeva Systems — Document Generation Platform**
- Owned and delivered two platform-wide projects for a service handling **80M+ requests/month**, improving PDF reliability and enabling customer-configurable document labels.
- Implemented **Java/Spring Boot services and REST APIs** and resolved **50+ customer-escalated production issues**, including database concurrency and distributed-state failures.

## Selected projects

### AI Developer Copilot
Converts raw terminal activity into structured documentation of goals, subtasks, and actions. Pairs a **LoRA-tuned 8B segmentation model** achieving **80% accuracy** with a **vLLM-served 20B annotation model**.

Deployed inference on RunPod serverless GPUs with **131K-token context**, schema-constrained JSON output, and automated prompt-evaluation suites.

**Stack:** Python, PyTorch, Hugging Face, vLLM, RunPod, LoRA/Unsloth

### Survey Preference Classifier
Led a three-person team to build a multiclass inference pipeline. Improved accuracy from **28% to 90.3%** through preprocessing fixes and model optimization, achieving **0.90 macro-F1**. Matched a three-layer neural network within **0.3 percentage points** using **99% fewer model parameters**.

**Stack:** Python, scikit-learn, TensorFlow

## Technologies

**Languages:** Java, TypeScript, Python, SQL, Rust, C  
**Backend & infrastructure:** Spring Boot, REST APIs, AWS, AWS CDK, Docker, Jenkins, Linux  
**Data & AI:** PostgreSQL, DynamoDB, PyTorch, vLLM, Claude Code, Codex
