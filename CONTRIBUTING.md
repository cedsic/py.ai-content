# 🤝 Contributing to py.ai
Thank you for contributing to Py.AI — a community-driven resource for everything Python and AI.  
Your edits help shape the content displayed on the [Py.AI](https://py.ai) website.

## 🧱 What You Can Contribute

There are three main categories you can contribute to:

### 1️⃣ Tools (/tools/)

Describe a Python or AI-related tool or library.  
Example:

```yaml
name: "Airflow for pipelines"
slug: "airflow"
headline: "Platform to programmatically author, schedule, and monitor workflows."
urls:
  - label: "GitHub"
    url: "https://github.com/apache/airflow"
  - label: "Docs"
    url: "https://airflow.apache.org/"
overview: |
  In today’s data-driven world, managing complex workflows and pipelines efficiently is crucial. **Apache Airflow** is a powerful open-source platform designed to programmatically author, schedule, and monitor workflows — making pipeline orchestration reliable, scalable, and maintainable. By treating workflows as code, Airflow eliminates manual inefficiencies and provides clear visibility into task execution, dependencies, and failures.
description: |
  ## ⚙️ Core Capabilities 🚀

  | Feature                    | Description                                                                                  | Benefit                              |
  |----------------------------|----------------------------------------------------------------------------------------------|--------------------------------------|
  | **Workflow as Code** 📝        | Define pipelines using Python scripts with clear task dependencies.                          | Version control, modularity, reusability. 🔄 |
  | **Dynamic Scheduling** ⏰      | Schedule workflows on cron-like intervals or trigger-based events.                           | Automate regular tasks and react to events. 🔔 |
  | **Dependency Management** 🔗   | Ensure tasks run in the correct order with dependency and conditional logic.                 | Reliable, error-free pipeline execution. ✅ |
  | **Monitoring & Alerting** 📊   | Web UI dashboard with logs, status, and customizable alerts.                                | Proactive troubleshooting and tracking. 🛎️ |
  | **Scalable Execution** 📈      | Distribute tasks across multiple workers and scale horizontally.                              | Handle large, complex ETL and ML workflows. 🌐 |
  | **Extensible Operators** 🧩    | Wide ecosystem of pre-built operators (Bash, Python, SQL, Hadoop, Spark, etc.).              | Easy integration with many tools. 🔌 |

  ---

  ## 🎯 Key Use Cases 

  Airflow is widely adopted by data engineers, ML practitioners, and analytics teams for:

  - **Automating ETL Pipelines**: Reliable extraction, transformation, and loading from multiple sources. 🔄  
  - **Machine Learning Workflow Orchestration**: Manage preprocessing, training, evaluation, and deployment. 🤖  
  - **Data Quality & Monitoring**: Validate data and trigger alerts on anomalies. 🚨  
  - **Complex Dependency Flows**: Branching, retries, conditional paths, and more. 🔀
```

Fields:

- `name` → Tool name or variant (human readable).
- `slug` → Unique lowercase id (use hyphens, no spaces).
- `headline` → One-line summary.
- `urls` → List of URL entries (`label` and `url`).
- `overview` → Short paragraph describing the tool.
- `description` → Long Markdown section with tables, examples, code blocks, etc.

### 2️⃣ Glossary (/glossary/)

Explain an AI or Python concept clearly and simply.  
Example:

```yaml
name: Artifact
slug: artifact
headline: Any file, dataset, or output created during the machine learning lifecycle.
description: |
  In **machine learning** and **AI development**, an **artifact** 🛠️ is any important output generated during a project, such as:

  - **Datasets** used for training and testing  
  - **Trained models** ready for deployment  
  - **Evaluation results** that measure performance  
  - **Feature sets** and **configuration files**  
  - **Logs** and **visualizations** documenting the process  

  Artifacts are more than just files—they capture the progress and decisions made throughout a project. A saved model (e.g., `.pkl`, `.h5`) can be reused, deployed, or improved later. Effective artifact management is essential to **MLOps** ⚙️, enabling teams to track, audit, and reproduce experiments smoothly. 🔄

  ---

  ### 🗂️ Types of Artifacts

  | Artifact Type          | Description                                           | Typical Format / Integration                    |
  |------------------------|-------------------------------------------------------|------------------------------------------------|
  | **Datasets**           | Raw or processed data                                 | CSV, Parquet, TFRecord; pandas, HF Datasets    |
  | **Trained Models**     | Saved model files                                     | `.h5`, `.pt`, `.pkl`; TF, PyTorch, Keras       |
  | **Evaluation Metrics** | Performance measurements                              | JSON, CSV; MLflow, Comet, Neptune              |
  | **Visualizations**     | Graphs and diagnostic plots                           | PNG, HTML; Matplotlib, Altair, Bokeh           |
  | **Configuration Files**| Hyperparameters and environment settings              | YAML, JSON; Kubeflow, Airflow                  |
  | **Logs & Metadata**    | Training logs and experiment metadata                 | Text, JSON; W&B, MLflow                        |
```

Fields:

- `name` → Full term name
- `slug` → Lowercase, hyphenated identifier
- `headline` → One-line definition
- `description` → Detailed explanation (Markdown format)

### 3️⃣ Links (/links/)

Add interesting external resources relevant to Python or AI.  
Example:

```yaml
slug: "answer-ai"
anchor: "Answer.ai - AI-powered knowledge assistant"
description: "🤖 AI-driven platform delivering precise answers for better knowledge management."
url: "https://www.answer.ai"
```

Fields:

- `slug` → Unique lowercase ID
- `anchor` → Display text
- `description` → One-line summary (emojis allowed)
- `url` → Full external link

## 🪜 How to Submit Changes

1. Fork the repository
2. Create a branch
3. Add or edit your YAML file in the correct folder
4. Commit and push your changes
5. Open a Pull Request (PR)
6. A maintainer will review and merge your changes.

## ✅ Guidelines

- Keep content concise, clear, and neutral
- Use Markdown formatting in descriptions
- Ensure every slug is unique
- Use lowercase, hyphenated slugs (e.g., machine-learning)
- Avoid promotional or excessively commercial language

## 🌟 Contributor Recognition

As [Py.AI](https://py.ai) grows, top contributors will be acknowledged on the Py.AI website and future community pages.  
Every contribution helps grow the shared knowledge base for Python and AI learners worldwide. 💪