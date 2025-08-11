# UCS321 - AI Fundamentals for Engineers

## Assignment Repository

### Course Overview
This repository contains assignments and projects for **UCS321: AI Fundamentals for Engineers**, a comprehensive course designed to build foundational AI literacy and practical problem-solving skills in engineering domains.

### Course Objective
Develop foundational AI knowledge while equipping participants with practical problem-solving skills using data relevant to engineering applications.


## Course Modules

### Module 1: Introduction to AI for Engineers
- **Topics**: AI, ML, DL, RL definitions and engineering applications
- **Assignment**: Understanding AI's role in engineering decision-making
- **Examples**: Predictive maintenance, process control

### Module 2: Data and Preprocessing
- **Topics**: Data types, cleaning, normalization, feature selection
- **Lab**: Handling sensor data, image data, and time-series data
- **Focus**: Engineering-specific data preprocessing techniques

### Module 3: Supervised Learning
- **Topics**: Linear/Logistic Regression, Decision Trees, Random Forest
- **Practical**: Build regression model for motor temperature prediction
- **Application**: Equipment failure and component lifespan prediction

### Module 4: Unsupervised Learning
- **Topics**: K-Means, DBSCAN, PCA, t-SNE
- **Practical**: Material property clustering using K-Means
- **Application**: Process classification and anomaly detection

### Module 5: Neural Networks & Deep Learning
- **Topics**: MLP, CNN fundamentals
- **Practical**: Neural network for faulty circuit detection
- **Application**: Image recognition for structural crack detection

### Module 6: Time-Series Analysis
- **Topics**: ARIMA, LSTM models
- **Lab**: Forecasting techniques implementation
- **Application**: Load prediction and vibration analysis

### Module 7: Toolchain for Engineers
- **Topics**: Python, Jupyter, pandas, scikit-learn, TensorFlow/Keras, Git
- **Lab**: Complete toolchain setup and version control
- **Focus**: Industry-standard development practices

### Module 8: Mini Project
- **Requirement**: Engineering-specific dataset analysis
- **Process**: Preprocessing → Modeling → Evaluation
- **Deliverables**: Code, documentation, presentation

## Practical Assignments

### Key Practicals
1. **Motor Temperature Prediction**: Regression modeling for thermal analysis
2. **Material Clustering**: K-Means application in materials science
3. **Circuit Fault Detection**: Neural network implementation for quality control

### Case Studies
- **Siemens**: Industrial automation AI applications
- **General Electric**: AI-driven turbine health monitoring
- **Honeywell**: Predictive maintenance in smart factories

## Evaluation Breakdown

| Component | Weight | Description |
|-----------|--------|-------------|
| Quizzes | 20% | Module-wise understanding assessment |
| Lab Assignments | 20% | Hands-on implementation tasks |
| Mini Project | 40% | Comprehensive engineering AI project |
| Viva/Presentation | 20% | Project defense and concept explanation |

## Getting Started

### Prerequisites
- Python 3.8 or higher
- Basic understanding of mathematics and statistics
- Engineering domain knowledge (any discipline)

### Required Tools and Libraries
```bash
# Core Python libraries
pip install pandas numpy matplotlib seaborn

# Machine Learning
pip install scikit-learn

# Deep Learning
pip install tensorflow keras

# Data Visualization
pip install plotly

# Jupyter Notebook
pip install jupyter

# Version Control
git --version  # Ensure Git is installed
```

### Setup Instructions
1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd UCS321-Assignments
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Assignment Submission Guidelines

### General Format
- **Code**: Well-commented Python files (.py) or Jupyter notebooks (.ipynb)
- **Documentation**: README.md for each assignment explaining approach and results
- **Data**: Include sample datasets or provide download instructions
- **Results**: Screenshots, plots, and performance metrics

### Naming Convention
- `ModuleXX_AssignmentYY_YourName.ipynb`
- `ModuleXX_LabYY_YourName.py`
- `MiniProject_YourName_FinalSubmission/`

### Submission Checklist
- [ ] Code runs without errors
- [ ] All outputs are visible in notebooks
- [ ] Documentation explains methodology
- [ ] Results are properly interpreted
- [ ] Engineering context is clearly established

## Mini Project Guidelines

### Project Requirements
1. **Dataset**: Choose engineering-relevant dataset (minimum 1000 samples)
2. **Problem**: Define clear engineering problem statement
3. **Methodology**: Apply minimum 2 different ML techniques
4. **Evaluation**: Use appropriate metrics and validation techniques
5. **Documentation**: Comprehensive report with engineering insights

### Suggested Project Topics
- Predictive maintenance for industrial equipment
- Quality control in manufacturing processes
- Energy consumption optimization
- Structural health monitoring
- Process parameter optimization
- Fault detection in mechanical systems

### Deliverables
1. **Project Proposal** (Week 4): Problem statement and approach
2. **Progress Report** (Week 6): Initial results and challenges
3. **Final Submission** (Week 8): Complete project with presentation
4. **Viva Voce** (Week 8): Project defense and Q&A session

## Resources

### Reference Materials
- Course slides and lecture notes
- Python documentation and tutorials
- Scikit-learn user guide
- TensorFlow/Keras documentation

### Additional Learning
- Kaggle Learn courses
- Coursera Machine Learning courses
- Engineering-specific AI research papers
- Industry case studies and whitepapers

### Support
- **Course Instructor**: Dr. Neeru Jindal[neeru.jindal@thapar.edu]

## Important Notes

### Academic Integrity
- Individual assignments must be completed independently
- Collaboration is allowed for group projects only
- Proper citation required for external code and datasets
- Plagiarism will result in course failure

### Late Submission Policy
- 10% penalty per day for late submissions
- Maximum 3 days extension allowed
- Medical emergencies require documentation

### Technical Requirements
- All code must be reproducible
- Use relative paths for data files
- Include requirements.txt for dependencies
- Comment code thoroughly for clarity

---

**Course Code**: UCS321  
**Course Title**: AI Fundamentals for Engineers  
**Academic Year**: 2025-26  

For any questions or clarifications, please contact the course instructors or refer to the official course documentation.
