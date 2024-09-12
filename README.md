# Final Year Project: AI-Driven Box Creation with Budget and Preferences

## Description
Our project focuses on developing an AI-driven recommendation system for Gofig, designed to simplify the gift hamper box selection process. By analyzing user budgets and preferences, the system generates personalized box options containing a curated mix of items such as healthy foods, snacks, and dry fruits

## Team Members
- Snehin Nair
- Subham Gaggar
- Sumeet Saini
- Surya Kant Pandidhar

## Technologies Used
- **TensorFlow / PyTorch**: For developing and training machine learning models for recommendation algorithms.
- **Scikit-learn**: For implementing various recommendation algorithms, including collaborative filtering and content-based filtering.
- **Pandas**: For data manipulation and preprocessing, including handling user preferences and item details.
- **NumPy**: For numerical operations and managing large datasets efficiently.
- **Jupyter Notebook / Colab**: For interactive development, experimentation, and visualization of machine learning models.
- **Surprise Library**: For building and evaluating recommendation systems.
- **MLflow**: For managing the machine learning lifecycle, including experimentation, tracking, and model deployment.

## Data Management
This project uses DVC (Data Version Control) for managing large datasets. The data is stored on the AWS cloud, separate from the Git repository.

## MLOps Workflow
1.	Data Ingestion & Collection:
o	Source: User input on budgets, preferences, and past data.
o	Storage: Cloud storage like Amazon S3 (AWS) or Google Cloud Storage (GCP).
o	Batch or stream processing of new data.
2.	Data Preprocessing:
o	Data cleaning and transformation.
o	Use cloud-native services like AWS Glue (AWS) or Dataflow (GCP).
o	Feature engineering (budget categories, item preferences).
3.	Model Training:
o	Define the machine learning model (reinforcement learning-like approach).
o	Train the model using cloud-based services like SageMaker (AWS) or AI Platform (GCP).
o	Monitor training with cloud-native logging tools.
4.	Model Validation & Evaluation:
o	Evaluate the model based on accuracy, feedback efficiency, etc.
o	Use validation data to test performance.
o	Track metrics using cloud services like Amazon CloudWatch (AWS) or Vertex AI (GCP).
5.	Model Deployment:
o	Deploy using containers like Docker.
o	Use Kubernetes (EKS on AWS, GKE on GCP) for scalable deployments.
o	Integrate the model with the Gofig platform using APIs for real-time recommendations.
6.	Continuous Integration / Continuous Deployment (CI/CD):
o	Automate the workflow using tools like Jenkins or GitLab CI.
o	Integrate with AWS CodePipeline (AWS) or Cloud Build (GCP) for deployment automation.
7.	Model Monitoring & Feedback Loop:
o	Track model performance and adjust based on user feedback.
o	Use monitoring tools like Prometheus (AWS/GCP) for metrics.
o	Enable a feedback loop to retrain the model as per new data (reinforcement learning component).
8.	Version Control:
o	Store versions of the trained model.
o	Use tools like DVC (Data Version Control) or cloud-native versioning tools.
9.	Infrastructure as Code (IaC):
o	Define cloud infrastructure using Terraform or AWS CloudFormation templates.
