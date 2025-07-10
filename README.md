# Cardiovascular-Risk-Assessment-System
Machine Learning-Based Cardiovascular Risk Prediction: A Comparative Analysis of Classification Models

## 🎯 Objective
Developed and compared machine learning models to predict cardiovascular disease risk using patient health indicators, achieving **82.83% accuracy** with logistic regression. This project supports early intervention strategies in preventive healthcare.

## 📊 Dataset
- **Size**: 119,795 patient records
- **Features**: 18 health indicators including diabetes status, physical activity, smoking habits
- **Target**: Binary classification (Heart Disease: Yes/No)
- **Source**: CDC Behavioral Risk Factor Surveillance System

## 🔍 Key Findings
- **Top Risk Factors**: Diabetes, mobility difficulties, general health status, physical activity, smoking
- **Model Performance**: Logistic Regression (82.83% accuracy) outperformed Decision Tree (90%+ accuracy with higher false positives)
- **Clinical Relevance**: 94.66% precision in identifying high-risk patients

## Technical Implementation

Tools & Technologies:
- Primary Platform: RapidMiner Studio
- Models: Logistic Regression, Decision Tree
- Evaluation: Cross-validation, ROC-AUC analysis
- Visualization: Correlation matrices, confusion matrices

Key Features:
- Comprehensive exploratory data analysis on 119,795 records
- Feature selection based on correlation analysis and literature review
- Cross-validation implementation for robust model evaluation
- Comparative analysis of classification algorithms

| Model | Accuracy | | Precision | | Recall | | F1-Score | | AUC |
| --- | --- | | --- | | --- | | --- | | --- |
| Logistic Regression | 82.83% | | 94.66% | | 86.06% | | 90.15% | | 0.727 |
| Decision Tree | 90%+ | | Lower | | Higher FP | | - | | 0.727 |

## Business Impact & Applications

Healthcare Value Proposition:
- Early Detection: Identifies high-risk patients before symptom onset
- Resource Optimization: Prioritizes preventive care interventions
- Cost Reduction: Potential healthcare cost savings through prevention
- Clinical Decision Support: Assists healthcare providers in risk assessment

Real-World Implementation Scenarios
- Primary care screening programs
- Health insurance risk assessment
- Population health management
- Preventive care resource allocation

## Professional Development Highlights
Data Science Skills Demonstrated:
- Statistical Analysis: Correlation analysis, descriptive statistics
- Feature Engineering: Literature-based feature selection
- Model Development: Comparative machine learning approach
- Validation: Cross-validation and performance evaluation
- Business Acumen: Healthcare domain knowledge application

## Industry-Relevant Methodologies
- Ethical AI: Addressed bias, privacy, and transparency concerns
- Reproducible Research: Documented methodology and results
- Clinical Validation: Literature-supported feature selection
- Performance Optimization: Model comparison and selection

## Ethical Considerations & Compliance
- Based on your analysis, key ethical considerations include:
- Data Privacy: HIPAA compliance for health data protection
- Algorithmic Bias: Addressing demographic imbalances in training data
- Transparency: Model interpretability for clinical decision-making
- Security: Protection against malicious attacks on sensitive health data
