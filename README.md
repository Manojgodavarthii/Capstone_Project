
# Elective Recommendation System

### Overview
The **Elective Recommendation System** is an advanced course recommendation engine designed to assist students in selecting electives that align with their academic goals, interests, and career aspirations. This project leverages state-of-the-art machine learning techniques, text processing, and natural language processing (NLP) to deliver highly relevant and personalized course suggestions.

### Features
- **Four Recommendation Methods**:
  1. **Cosine Similarity with Stemming**: Captures keyword-level similarity for efficient recommendations.
  2. **Cosine Similarity without Stemming**: Retains linguistic nuances for precise matching.
  3. **Collaborative Filtering**: Suggests courses based on user ratings and interactions.
  4. **SBERT (Sentence-BERT)**: Extracts semantic similarity for context-aware recommendations.
- **Evaluation Metrics**:
  - Precision, Recall, F1 Score
  - Mean Reciprocal Rank (MRR)
  - Mean Average Precision (MAP)
  - Mean Absolute Error (MAE), Mean Squared Error (MSE), and RMSE
- **Visual Insights**: Visualizations to analyze course trends and system performance.

### Methodology
The project uses a dataset of 3,522 online courses, including attributes like course descriptions, skills, difficulty levels, ratings, and prerequisites. Key methodologies include:
1. **Text Preprocessing**: Includes stemming, tokenization, and vectorization using TF-IDF or CountVectorizer.
2. **Similarity Computation**: Measures the cosine similarity between course vectors and user input.
3. **Collaborative Filtering**: Employs user-item interaction data for personalized recommendations.
4. **SBERT**: Leverages sentence embeddings for high-precision recommendations.

### Dataset
The dataset contains:
- **Course Attributes**: Name, University, Difficulty Level, Ratings, Description, Skills, Prerequisites, and Average CGPA.
- **Statistics**: Most courses are beginner or intermediate level, with average CGPAs ranging between 4.0 and 10.0.

### Results
The system achieves high relevance in recommendations through:
- Accurate similarity scores.
- Scalable algorithms.
- Evaluation across various metrics for precision and user satisfaction.

### Tools and Libraries
- **Programming Language**: Python
- **Libraries**:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `scikit-learn` for vectorization and similarity computations
  - `nltk` for stemming and text preprocessing
  - `Sentence-Transformers` for SBERT embeddings

### Getting Started
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/elective-recommendation-system.git
   cd elective-recommendation-system
   ```
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Code**:
   Open the notebook `capstone_project_3.ipynb` in Google Colab or any Jupyter environment and execute the cells.

### Evaluation
The system is evaluated using metrics such as Precision, Recall, F1 Score, and MRR. Visual insights further validate the relevance and accuracy of the recommendations.

### Acknowledgments
This project was conducted under the guidance of **Dr. Smitha Patil**, Assistant Professor at the School of Computer Science Engineering, Presidency University, Bengaluru.

### Authors
- **Golla Meghana**
- **Munagala Naga Sameera**
- **Ayush Chhetri**
- **Godavarthi Naga Manoj Balaji**

### License
This project is licensed under [MIT License](License.txt).

### References
For a detailed explanation, refer to the [final project report](final report_2.pdf).

