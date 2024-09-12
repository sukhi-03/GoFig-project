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
- Source: User input on budgets, preferences, and past data.
- Storage: Cloud storage like Amazon S3 (AWS) or Google Cloud Storage (GCP).
- Batch or stream processing of new data.
2.	Data Preprocessing:
- Data cleaning and transformation.
- Use cloud-native services like AWS Glue (AWS) or Dataflow (GCP).
- Feature engineering (budget categories, item preferences).
3.	Model Training:
- Define the machine learning model (reinforcement learning-like approach).
- Train the model using cloud-based services like SageMaker (AWS) or AI Platform (GCP).
- Monitor training with cloud-native logging tools.
4.	Model Validation & Evaluation:
- Evaluate the model based on accuracy, feedback efficiency, etc.
- Use validation data to test performance.
- Track metrics using cloud services like Amazon CloudWatch (AWS) or Vertex AI (GCP).
5.	Model Deployment:
- Deploy using containers like Docker.
- Use Kubernetes (EKS on AWS, GKE on GCP) for scalable deployments.
- Integrate the model with the Gofig platform using APIs for real-time recommendations.
6.	Continuous Integration / Continuous Deployment (CI/CD):
- Automate the workflow using tools like Jenkins or GitLab CI.
- Integrate with AWS CodePipeline (AWS) or Cloud Build (GCP) for deployment automation.
7.	Model Monitoring & Feedback Loop:
o	Track model performance and adjust based on user feedback.
- Use monitoring tools like Prometheus (AWS/GCP) for metrics.
- Enable a feedback loop to retrain the model as per new data (reinforcement learning component).
8.	Version Control:
- Store versions of the trained model.
- Use tools like DVC (Data Version Control) or cloud-native versioning tools.
9.	Infrastructure as Code (IaC):
- Define cloud infrastructure using Terraform or AWS CloudFormation templates.
