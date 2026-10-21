---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Sai Kiran Pennam
+1 (512) 409 0668 | [saikiran.pennam@icloud.com](mailto:saikiran.pennam@icloud.com) | [LinkedIn](https://www.linkedin.com/in/saikiranpennam)
F1 STEM-OPT at Austin, TX

Education & Certificates
======
* M.S. in Computer Science, Colorado State University, Graduated 12/2024
  * Relevant coursework: Deep Learning, Big Data, Software Engineering, Computer & Quantitative Security
* AWS Certified Machine Learning Engineer, 03/2025

Work History
======
* Data Engineer, Rivian Systems, LLC, Remote (02/2026 – Present)
  * Used Amazon S3 and AWS Glue to collect and organize machine-sensor files in one secure cloud location; replaced scattered spreadsheets with a reliable central data source.
  * Built automated ETL pipelines with AWS Glue and Python; cleaned, transformed, and loaded daily sensor and maintenance data so analysts use it without manual preparation.
  * Created data quality checks with AWS Glue and Amazon CloudWatch; detected missing, duplicate, or unusual sensor readings before they affected dashboards or machine-learning models.
  * Built Amazon QuickSight dashboards using curated Redshift data; gave operations leaders simple reports on machine downtime, production output, and maintenance trends.

* AI Safety Researcher, Algoverse (advisor: [PLACEHOLDER — advisor name]), Remote (05/2026 – 09/2026)
  * Used Nvidia A100 GPUs to fine-tune Gemma 3 4B IT vision-language models on targeted datasets to study how narrow fine-tuning can cause unsafe or misaligned behavior.
  * Reproduced a latent intervention method for text representations in VLMs; tested whether changing internal text-related directions could reduce or induce misaligned model behavior.
  * Used vLLM to run high-throughput model inference during safety evaluations; made it practical to test many intervention, prompt, and model-output conditions.
  * Combined MMSafetyBench results with LLM-as-a-judge and human review; checked whether apparent misalignment effects were real, consistent, and not caused by flawed or out-of-distribution evaluation inputs.
  * Contributed to mechanistic interpretability analysis comparing text- and image-conditioned representations; supported evidence that text-direction interventions, rather than vision-direction interventions, were causally responsible for the observed misaligned behavior.
  * Anonymous manuscript on mechanistic interpretability in vision-language models. Accepted to InterpScience Workshop at NeurIPS. Camera-ready version in progress.

* Data Scientist, TT Technologies, Remote (04/2025 – 01/2026)
  * Used SQL and data analysis to combine website, ad, and purchase data; identified the marketing channels that brought the most paying customers.
  * Applied customer segmentation to group shoppers by behavior, such as first-time buyers, repeat customers, and inactive customers; helped launch targeted emails that increased repeat purchases by 12%.
  * Created a forecasting model using historical campaign and seasonal data; helped the team plan advertising budget and inventory for high-demand periods.

* Graduate Research Assistant, CSU Ag Bio, Colorado (01/2024 – 12/2024)
  * Helped researchers use plant pictures and light data to find disease early; used Python and Machine Learning to turn complex plant data into clear results.
  * Used data preprocessing to clean and organize hyperspectral data from 122 sugar beet plants, making the dataset reliable for disease-detection experiments.
  * Applied feature engineering and statistical analysis to select useful wavelength bands, helping models distinguish healthy plants from plants with soilborne disease.
  * Built and tested machine learning models, including SVM, Random Forest, MLP, and ResNet50 to compare disease-identification and severity-estimation performance.
  * Used model evaluation and adversarial edge-case testing to identify class-imbalance and out-of-distribution weaknesses, improving the reliability of the final research results.
  * Created reproducible data pipelines with organized code, experiment tracking, and versioned workflows, helping collaborators repeat analyses and build on the project.

Projects
======
* LLM Security Evaluation System – RAG pipelines & Behavioral Evaluations (02/2024 – 05/2024)
  * Built a RAG pipeline that helps an AI system look up trusted security information before answering; chose retrieval over fine-tuning because security knowledge requires detailed, traceable source information.
  * Developed behavioral evaluations to check whether answers use the right retrieved information and stay true to it; measured retrieval, answer, faithfulness, and response quality.

Skills
======
* Languages: Python, C++, Bash/Shell scripting
* ML & Eval Frameworks: Scikit-learn, PyTorch, JAX, Hugging Face (huggingface-cli, transformers), OpenCV
* LLM & RAG Tooling: LLM APIs (Claude/OpenAI), vLLM, Vector databases, LangChain, W&B
* Data Analysis: Pandas, NumPy, Matplotlib, Seaborn
* Cloud & Infrastructure: AWS, Docker, FastAPI, Git
* Databases: PostgreSQL, MySQL
