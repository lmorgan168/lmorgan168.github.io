## About Me

Hi, I'm Lucas. I'm a data analyst and analytics engineer focused on building data systems that drive measurable business outcomes — from subscriber acquisition at Apple TV+ to P&L optimization for multi-location restaurant groups.

I specialize in audience targeting and segmentation at scale, experimentation and campaign analytics, building reusable data pipelines with dbt, Snowflake, Spark, and Trino, and translating complex data into clear recommendations for cross-functional stakeholders. My background in NLP and machine learning (MedSpaCy, PyTorch, clinical scoring pipelines) keeps me close to the modeling side, and I'm actively deepening that work through a computer vision learning track.

Check out my projects and work below!

## Work Experience

**Data Analyst III – Apple via Contract w/ Magnit Global (Jun 2025 – Present)**
- Serve as the DRI for audience targeting across email and push for the Apple TV LOB, supporting campaigns that drove hundreds of thousands of incremental subscriber signups across 200+ marketing initiatives.
- Led targeting for high-impact launches including the F1 Movie campaign (six-figure incremental viewership) and F1 Launch (near-double app follow rate), as well as Black Friday Offer campaigns that contributed double-digit percentage share of total signups.
- Architected a reusable dbt template framework in Python to replace monolithic 600+ line SQL queries, standardizing audience segmentation logic for billion-row datasets across 4 environments (Snowflake, Vertica, Trino, Spark).
- Automated a leadership-facing keynote report for the email marketing build team, cutting manual reporting effort from 10 hours to 1 hour weekly.

**Data Analyst – Zao Management Group (Mar 2023 – Jun 2025)**
- Designed and automated weekly executive reports for a multi-location AYCE and conventional restaurant group, surfacing actionable insights on revenue per cover, food cost ratios, and labor efficiency that directly informed P&L decisions.
- Identified underperforming menu items and flagged premium ingredient cost overruns (including wagyu pricing), leading to menu adjustments that reduced food costs by an estimated 8–12% across affected categories.
- Built ETL scripts in Python to ingest and standardize raw POS exports across multiple locations, transforming fragmented item-level sales data into a unified reporting pipeline.

**Data Scientist Intern – Kaiser Permanente (Jul 2022 – Jan 2023)**
- Contributed to the development of an NLP-based clinical scoring pipeline using MedSpaCy and Python, processing 10,000+ unstructured Parkinson's clinical notes against UPDRS scoring criteria.
- Supported containerization of a RESTful Flask API for the NVIDIA Clara SDK brain tumor segmentation pipeline, integrating Dockerized services into existing MRI scan workflows.
- Engineered weekly ETL processes from Clarity (Epic's data warehouse) using Bash and SQLite, accelerating prototyping cycles by 30%.

**Research Intern – Children's Hospital of Orange County (Sep 2022 – Dec 2022)**
- Predicted hospital readmissions for 4,192 NICU patient notes with a 0.7 F1 score using rule-based NLP and adapted BERT models, including ClinicalBERT and BioBERT.
- Employed spaCy for clinical note preprocessing, executing tokenization, stop word elimination, and entity recognition, increasing prediction accuracy by 5%.


## Projects

### [Bird Call Classification - Sound Event Detection](https://github.com/lmorgan168/Bird-Call-Detection-BirdClef)
<img src="assets/images/Screen%20Shot%202022-02-08%20at%202.04.09%20PM.png" alt="" width="500">
The purpose of this project is to address the challenge of limited data and manual annotation in bioacoustics. We implemented:
- **ResNet38 Model**: Pretrained audio neural network for bird call detection.
- **Mel-Spectrograms**: Converted audio data into spectrograms for CNN input.
- **Focal Loss**: Enhanced the Cross-Entropy Loss function to prioritize misclassified examples.
- **Results**: Achieved an F1-score of 0.684, ranking in the top 15% on Kaggle.

---

### [Grocery Store Sales - Time Series Forecasting](https://github.com/lmorgan168/Grocery-Store-Sales-Time-Series)
This project aimed to predict grocery store sales using historical data:
- **5-Layer LSTM Network**: Built using Keras for long-term time series forecasting.
- **Supervised Learning Transformation**: Transformed time-series data into supervised learning inputs by incorporating time steps as features.
- **Results**: Achieved a top 20% ranking on Kaggle, demonstrating high prediction accuracy for sales trends.

---

### [Data Structure Efficiency and Word Frequency Analysis](https://github.com/lmorgan168/Data-Structures-Asmyptotic-Efficiency)
This project explores how data structure choice impacts computational performance by implementing a word frequency analysis algorithm. Key highlights include:

- **Problem**: Analyze word frequencies in a document, excluding common stopwords.
- **Algorithm**: Iteratively count word occurrences using different data structures.
- **Data Structures Compared**: 
  - Unsorted Vector, Unsorted Linked List, Hash Table, Binary Search Tree.
- **Results**: 
  - Hash table was **374x faster** than a linked list, showcasing the importance of O(1) amortized efficiency.
  - Observed times aligned well with theoretical expectations.

---

### [Hash Table Implementations - Performance Comparison](https://github.com/lmorgan168/Hash-Benchmark-Comparison)
This project benchmarks four dictionary data structures to analyze performance:

- **Structures**: Naive, Chaining, Linear Probing, Cuckoo.
- **Features**: Benchmarked `set` and `search` operations with performance visualized in scatter plots.
- **Results**:
  - **Fastest**: Cuckoo and Chaining.
  - **Slowest**: Naive (O(n) complexity).
  - **Trade-Offs**: Chaining balances simplicity and speed; Cuckoo excels in performance but is complex to implement.


## TECHNICAL STACK

- Programming Languages: Python, C++, R
- Frameworks & Libraries: Flask, PyTorch, spaCy, HuggingFace, SQLAlchemy, Keras
- Databases: PostgreSQL, MySQL, SQLite
- DevOps & Cloud Platforms: Docker, GitHub Actions, AWS (RDS, ECS, Lambda)

### Data Skills:
- Statistical Analysis: Descriptive and Inferential Statistics, Feature Engineering for NLP and audio data
- Machine Learning: Classification, Regression, Clustering, Ensemble methods, PCA, Random Forests
- Deep Learning: Natural Language Processing, Computer Vision, Generative Modeling, RNN/LSTM, LLM
- Data Visualization: Matplotlib, Seaborn, Tableau

- Software Development: API Integration, RESTful Services, Microservices Architecture
- Testing: Unit Testing, Integration Testing, Performance Benchmarks
- Performance Optimization: Reducing Latency, Streamlining Data Pipelines
- Project Management & Collaboration: Jira, Asana, Slack, Agile Practices, Scrum Methodology, Stakeholder Communication
- Version Control: Git, GitHub

