# **Task 1 Choose a Business Domain**

**Manufacturing**

# **Task 2 Define the Business Problem**

# 1. What problem is being solved?
Manufacturing industries face unexpected machine breakdowns and equipment failures.     
**Problem Solved: Manufacturing industries face challenges in manually detecting defective products during quality inspection. The problem being solved is automatic detection of defective and non-defective products using AI-based image classification..**

# 2. Who are the users or stakeholders?
The users and stakeholders are:
Production Managers, Factory Operators, Customers.

# 3. What is the current manual or traditional process?
Current practices includes:


1. Reactive Maintenance- Machines repaired only if they are fails.
2.   Schedule Maintenance- Maintenance are scheduled on fixed intervals.

# 4. What are the limitations of the current process?
Limitations of the current process are as follows:


1.   Unexpected machine failures.
2.   High maintenance cost.
3. Production delays.
4. Human errors.

# **Task 3 Identify the AI Task Type**

AI Task Type: Image classification

Image Classification used for:

Quality inspection
Defect detection
Product verification
Surface damage checking
Manufacturing based industry faces problem in manually detecting defective products. An AI based image classification system can automatically classify products as defective or non-defective using product images.

# **Task 4 Data Requirement Plan**

Data required to solve this problem:

1. Type of data needed:
The project mainly requires unstructured data. Image form of data is required clicked from cameras of defective and non-defective products. Example- cracks, scratches.

2. Structured or unstructured data:
Unstructured data in the form of images.

3. Input features:
The input features are extracted automatically from images by the AI model. Examples- crack patterns, shape patterns.

4. Target variable or labels:
The target variable is the product condition label. Example- defective and non-defective.

5. Data collection method:
Data can be collected using existing industrial dataset, industrial cameras installed on production lines, manual checks by label team.

6. Data quality risks:
Qualty risks which can affect model performance are:

Poor image quality
Imbalanced dataset
Lighting Variations
Noise and Background Issues

# **Task 5 Model Recommendation**

**Recommended model- Convolutional Neural Network (CNN)**

A CNN is most suitable for this model because the task involves analyzing product images to identify defects and classify products as defective or non-defective.

CNNs are specifically designed for image processing and computer vision tasks.

# **Task 6 Evaluation Plan**

The solution will be evaluated on:

Technical metrics- Technical metrics measure how accurately the AI model classifies defective and non-defective products.

Accuracy- Measures the percentage of correctly classified product images
Precision- Measures how many actual defective products are correctly identified.
F1-Score- Balances precision and recall.
Confusion Matrix- It helps understand model prediction errors.
Business Metrics- Business metrics measure the practical impact of the AI solution in manufacturing operations.

Possible Failure Cases:

Poor Image Quality
Incorrect Labeling
Similar-Looking Defects
Human review or validation process- Human experts will be involved to validate model predictions and improve reliability.

Validation process:

The model is retrained periodically using updated data.
Correct labels are added to the dataset.

# **Task 7 Responsible AI Considerations**

Write about possible risks such as:

Bias in Data- Bias can occur if the training dataset does not represent all types of products and defects equally. Example- model may perform well on common defects but fail to detect rare defects.

Incorrect Predictions- The AI system may incorrectly classify products. Types of Errors:

False Positive: A good product is classified as defective.
False Negative: A defective product is classified as non-defective.
Privacy Concerns- Although manufacturing image datasets usually do not contain personal information, privacy concerns may still arise if:

Employee information appears in images
Factory operations are recorded without authorization
Over-Reliance on AI- Workers may depend completely on AI predictions and ignore manual inspection. This can become dangerous if the model makes errors or encounters new defect types.

Impact on Users- AI automation may affect workers involved in manual inspection tasks. Example- fear of job replacement, need for new technical skills.

Need for Human Oversight- Human supervision is important to ensure the AI system works reliably and ethically. Example- review uncertain predictions, validate defective product classifications

# **Task 8 Final Solution Summary**

Create a final one-page solution summary including:

1. Problem- Manufacturing industries often face challenges in identifying defective products during quality inspection. Traditional manual inspection methods are time-consuming, costly, and prone to human error. Defective products that are not detected can reduce customer satisfaction, increase return rates, and damage company reputation.

2. Proposed AI Solution- An AI-based image classification system will be developed to automatically detect defective and non-defective products using product images captured from industrial cameras. This solution improves inspection speed, consistency, and accuracy.

3. Required Data- Data Needed:

Product images
Defective product images
Non-defective product images
Data Type: Unstructured Labels: Defective and Non-defective Data Collection Method: Industrial cameras, Automated inspection systems.

4. Model Recommendation- Convolutional Neural Network (CNN). CNN is recommended because it is highly effective for image classification tasks.

5. Expected Business Impact- The AI solution can provide several business benefits:

Improved product quality
Faster inspection process
Reduced product return rates
Risks and Mitigation Plan-

Risk:

* Biased or limited training data
* Incorrect predictions
* Poor image quality
* Over-reliance on AI

  Mitigation Plan

* Use diverse and balanced datasets
* Regularly retrain and monitor the model
* Use high-resolution industrial cameras
* Maintain human review for critical inspections
Colab
