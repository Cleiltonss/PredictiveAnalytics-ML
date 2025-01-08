# Predictive Analytics - Machine Learning

## Project Overview
This project focuses on applying Machine Learning techniques to predict the behavior of industrial DC mixer motors based on electrical signals. The model leverages TensorFlow and LabView for signal processing, model deployment, and visualization. The goal is to enhance predictive maintenance strategies, reduce downtime, and optimize system reliability.

## Project Structure
```
/
PredictiveAnalytics-ML/
  AM-Project.pdf
  Dataset_SinaisEletricosVibracao_csv.xls
  PredictiveAnalysis_Model.ipynb
```

### File Descriptions:
- **AM-Project.pdf** – A comprehensive document that outlines the project's objectives, methodologies, and results.
- **Dataset_SinaisEletricosVibracao_csv.xls** – Dataset containing electrical and vibration signals used for model training and testing.
- **PredictiveAnalysis_Model.ipynb** – Jupyter Notebook with the complete code implementation for the predictive analysis model, including data preprocessing, model training, and evaluation.

## Technologies and Tools
- **Programming Languages:** Python, C++
- **Libraries/Frameworks:** TensorFlow, Pandas, Matplotlib, Seaborn, LabView
- **Hardware Integration:** LabView and MyDAQ for real-time signal acquisition
- **Version Control:** GitHub

## Project Workflow
1. **Dataset Collection and Preprocessing**
   - The dataset containing electrical and vibration signals was collected from industrial equipment.
   - Data cleaning and preprocessing were performed to ensure high-quality inputs for the model.

2. **Feature Engineering**
   - Extracted relevant features from raw signals, focusing on patterns that correlate with motor behavior.
   
3. **Model Development**
   - Implemented a predictive model using TensorFlow, leveraging supervised learning techniques.
   - Fine-tuned hyperparameters to optimize accuracy and minimize error rates.

4. **Real-Time Data Acquisition**
   - Integrated LabView with MyDAQ to capture and visualize electrical signals in real-time.
   
5. **Model Deployment and Evaluation**
   - Deployed the model and tested it with real-time data inputs.
   - Visualized predictions and performance metrics using LabView dashboards.
   
6. **Documentation**
   - All methodologies, results, and conclusions were documented in the AM-Project.pdf file.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Cleiltonss/PredictiveAnalytics-ML.git
   ```
2. Install necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook PredictiveAnalytics-ML/PredictiveAnalysis_Model.ipynb
   ```
4. Follow the steps in the notebook to load the dataset and train the model.

## Future Improvements
- Expand the dataset with more samples from different environments.
- Integrate additional machine learning models to compare performance.
- Develop a web-based dashboard to visualize predictions in real-time.

## Project Presentation
Watch the project presentation on YouTube: [Predictive Analytics Project](https://youtube.com/shorts/qWUTy3BRKxQ?feature=share)

---
**Author:** Cleilton Sousa  
**Email:** cleilton.mecatronico@gmail.com  
**LinkedIn:** [linkedin.com/in/cleiltonss](https://linkedin.com/in/cleiltonss)  
**GitHub:** [github.com/Cleiltonss](https://github.com/Cleiltonss)
