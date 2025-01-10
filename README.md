## About Me

Hi, I'm Lucas. To me, good data always tells a story, but finding quality data and uncovering the correct story is the real science. 

As a data scientist, I focus on ensuring data is functional for the project goals and finding the most effective machine learning solutions. I specialize in:
- Data cleaning, model selection, and effective communication
- Modeling using Python libraries like Scikit-learn and PyTorch for NLP, GLM, and image recognition
- Querying data with SQL
- Building dashboards with Tableau
- Creating and maintaining APIs using Flask and Postman

I have a passion for applying data-driven solutions to real-world problems. Check out my projects below!


## Work Experience

**Data Scientist Intern – Kaiser Permanente (Jul 2022 – Dec 2022)**
- Developed an NLP model using MedSpaCy for automating clinical note scoring, reducing doctor workload by 800 hours.
- Automated weekly ETL processes with Bash scripts, reducing manual work by 10 hours per week.
- Built RESTful APIs for NVIDIA Clara scripts using Flask and SQLAlchemy, streamlining data workflows.

**Research Intern – Children's Hospital of Orange County (Sep 2022 – Dec 2022)**
- Predicted NICU patient readmissions using ClinicalBERT and BioBERT models, achieving a 0.7 F1-score.
- Enhanced model accuracy by 5% by optimizing spaCy-based tokenization and entity recognition.


## Projects

### [Bird Call Classification - Sound Event Detection](https://github.com/lmorgan168/Bird-Call-Detection-BirdClef)
![](assets/images/Screen%20Shot%202022-02-08%20at%202.04.09%20PM.png)
The purpose of this project is to address the challenge of limited data and manual annotation in bioacoustics. We implemented:
- **ResNet38 Model**: Pretrained audio neural network for bird call detection.
- **Mel-Spectrograms**: Converted audio data into spectrograms for CNN input.
- **Focal Loss**: Enhanced the Cross-Entropy Loss function to prioritize misclassified examples.
- **Results**: Achieved an F1-score of 0.684, ranking in the top 15% on Kaggle.

[View the full project report here](docs/Bird_Call_Detection_Final_Report.pdf).

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


## Skills

### Technical Skills
- **Programming**: Python, R, SQL, Bash
- **Machine Learning Libraries**: Scikit-learn, PyTorch, TensorFlow, Keras
- **Data Visualization**: Tableau, Power BI, Matplotlib, ggplot2
- **Cloud Platforms**: AWS, Microsoft Azure
- **API Development**: Flask, Swagger, Postman

### Soft Skills
- Effective data storytelling and visualization
- Strong collaboration with cross-functional teams
- Problem-solving and critical thinking
