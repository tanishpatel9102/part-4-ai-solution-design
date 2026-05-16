{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": []
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "source": [
        "# **Task 1 Choose a Business Domain**"
      ],
      "metadata": {
        "id": "phRkL5gyJMMR"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "**Manufacturing**\n",
        "\n",
        "\n",
        "\n"
      ],
      "metadata": {
        "id": "AmpaXnG8JTxr"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "# **Task 2 Define the Business Problem**\n"
      ],
      "metadata": {
        "id": "lsC338hGJuWP"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "# 1. What problem is being solved?\n",
        "Manufacturing industries face unexpected machine breakdowns and equipment failures.     \n",
        "**Problem Solved: Manufacturing industries face challenges in manually detecting defective products during quality inspection. The problem being solved is automatic detection of defective and non-defective products using AI-based image classification..**\n",
        "\n",
        "# 2. Who are the users or stakeholders?\n",
        "The users and stakeholders are:\n",
        "Production Managers, Factory Operators, Customers.\n",
        "\n",
        "# 3. What is the current manual or traditional process?\n",
        "Current practices includes:\n",
        "\n",
        "\n",
        "1. Reactive Maintenance- Machines repaired only if they are fails.\n",
        "2.   Schedule Maintenance- Maintenance are scheduled on fixed intervals.\n",
        "\n",
        "# 4. What are the limitations of the current process?\n",
        "Limitations of the current process are as follows:\n",
        "\n",
        "\n",
        "1.   Unexpected machine failures.\n",
        "2.   High maintenance cost.\n",
        "3. Production delays.\n",
        "4. Human errors.\n",
        "\n",
        "\n",
        "\n",
        "\n",
        "\n",
        "\n",
        "\n"
      ],
      "metadata": {
        "id": "GTNWXrrEJ_yD"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "# **Task 3 Identify the AI Task Type**"
      ],
      "metadata": {
        "id": "5fGx4NheM7D0"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "**AI Task Type: Image classification**\n",
        "\n",
        "Image Classification used for:\n",
        "\n",
        "\n",
        "1.   Quality inspection\n",
        "2.   Defect detection\n",
        "3.   Product verification\n",
        "4. Surface damage checking\n",
        "\n",
        "Manufacturing based industry faces problem in manually detecting defective products. An AI based image classification system can automatically classify products as defective or non-defective using product images.\n",
        "\n"
      ],
      "metadata": {
        "id": "HAGBDMppSqS8"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "# **Task 4 Data Requirement Plan**"
      ],
      "metadata": {
        "id": "RljtJiW6WBYu"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "Data required to solve this problem:\n",
        "\n",
        "# 1. Type of data needed:\n",
        "\n",
        "The project mainly requires unstructured data. Image form of data is required clicked from cameras of defective and non-defective products. Example- cracks, scratches.\n",
        "\n",
        "# 2. Structured or unstructured data:\n",
        "\n",
        "Unstructured data in the form of images.\n",
        "\n",
        "# 3. Input features:\n",
        "\n",
        "The input features are extracted automatically from images by the AI model. Examples- crack patterns, shape patterns.\n",
        "\n",
        "# 4. Target variable or labels:\n",
        "\n",
        "The target variable is the product condition label. Example- defective and non-defective.\n",
        "\n",
        "# 5. Data collection method:\n",
        "\n",
        "Data can be collected using existing industrial dataset, industrial cameras installed on production lines, manual checks by label team.\n",
        "\n",
        "# 6. Data quality risks:\n",
        "\n",
        "Qualty risks which can affect model performance are:\n",
        "\n",
        "\n",
        "1.   Poor image quality\n",
        "2. Imbalanced dataset\n",
        "3. Lighting Variations\n",
        "4. Noise and Background Issues\n",
        "\n",
        "\n",
        "\n",
        "\n",
        "\n",
        "\n",
        "\n"
      ],
      "metadata": {
        "id": "npeReD62WNHO"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "# **Task 5 Model Recommendation**"
      ],
      "metadata": {
        "id": "RszPkrsgahcx"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "**Recommended model- Convolutional Neural Network (CNN)**\n",
        "\n",
        "A CNN is most suitable for this model because the task involves analyzing product images to identify defects and classify products as defective or non-defective.\n",
        "\n",
        "CNNs are specifically designed for image processing and computer vision tasks."
      ],
      "metadata": {
        "id": "ck9yTEg1a0Lq"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "# **Task 6 Evaluation Plan**\n"
      ],
      "metadata": {
        "id": "UKa619I8bTzI"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "The solution will be evaluated on:\n",
        "\n",
        "\n",
        "\n",
        "1.   Technical metrics- Technical metrics measure how accurately the AI model classifies defective and non-defective products.\n",
        "\n",
        "\n",
        "     *   Accuracy- Measures the percentage of correctly classified product images\n",
        "     *   Precision- Measures how many actual defective products are correctly identified.\n",
        "     * F1-Score- Balances precision and recall.\n",
        "     * Confusion Matrix- It helps understand model prediction errors.\n",
        "\n",
        "2.   Business Metrics- Business metrics measure the practical impact of the AI solution in manufacturing operations.\n",
        "\n",
        "3. Possible Failure Cases:\n",
        "\n",
        "\n",
        "     *   Poor Image Quality\n",
        "     *   Incorrect Labeling\n",
        "     * Similar-Looking Defects\n",
        "\n",
        "4. Human review or validation process- Human experts will be involved to validate model predictions and improve reliability.\n",
        "\n",
        "   Validation process:\n",
        "\n",
        "    * The model is retrained periodically using updated data.\n",
        "    * Correct labels are added to the dataset.\n",
        "\n",
        "\n",
        "\n",
        "\n",
        "\n",
        "\n"
      ],
      "metadata": {
        "id": "ue9JJ873bae9"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "# **Task 7 Responsible AI Considerations**"
      ],
      "metadata": {
        "id": "Nrt1pv66eets"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "Write about possible risks such as:\n",
        "\n",
        "1. Bias in Data- Bias can occur if the training dataset does not represent all types of products and defects equally. Example- model may perform well on common defects but fail to detect rare defects.\n",
        "\n",
        "2. Incorrect Predictions- The AI system may incorrectly classify products.\n",
        "Types of Errors:\n",
        "   * False Positive: A good product is classified as defective.\n",
        "   * False Negative: A defective product is classified as non-defective.\n",
        "\n",
        "3. Privacy Concerns- Although manufacturing image datasets usually do not contain personal information, privacy concerns may still arise if:\n",
        "\n",
        "   * Employee information appears in images\n",
        "   * Factory operations are recorded without authorization\n",
        "\n",
        "4. Over-Reliance on AI- Workers may depend completely on AI predictions and ignore manual inspection.\n",
        "This can become dangerous if the model makes errors or encounters new defect types.\n",
        "\n",
        "5. Impact on Users- AI automation may affect workers involved in manual inspection tasks. Example- fear of job replacement, need for new technical skills.\n",
        "\n",
        "6. Need for Human Oversight- Human supervision is important to ensure the AI system works reliably and ethically. Example- review uncertain predictions, validate defective product classifications"
      ],
      "metadata": {
        "id": "6dDd_JJqeq54"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "# **Task 8 Final Solution Summary**\n"
      ],
      "metadata": {
        "id": "Zj7xoFHIjABB"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "Create a final one-page solution summary including:\n",
        "\n",
        "1. Problem- Manufacturing industries often face challenges in identifying defective products during quality inspection. Traditional manual inspection methods are time-consuming, costly, and prone to human error. Defective products that are not detected can reduce customer satisfaction, increase return rates, and damage company reputation.\n",
        "\n",
        "2. Proposed AI Solution- An AI-based image classification system will be developed to automatically detect defective and non-defective products using product images captured from industrial cameras.\n",
        "This solution improves inspection speed, consistency, and accuracy.\n",
        "\n",
        "3. Required Data-\n",
        "    Data Needed:\n",
        "    * Product images\n",
        "    * Defective product images\n",
        "    * Non-defective product images\n",
        "\n",
        "    Data Type: Unstructured\n",
        "    Labels: Defective and Non-defective\n",
        "    Data Collection Method: Industrial cameras, Automated inspection systems.\n",
        "\n",
        "4. Model Recommendation- Convolutional Neural Network (CNN).\n",
        "CNN is recommended because it is highly effective for image classification tasks.\n",
        "\n",
        "5. Expected Business Impact- The AI solution can provide several business benefits:\n",
        "\n",
        "    * Improved product quality\n",
        "    * Faster inspection process\n",
        "    * Reduced product return rates\n",
        "\n",
        "6. Risks and Mitigation Plan-\n",
        "     \n",
        "    Risk   \n",
        "     * Biased or limited training data\n",
        "     * Incorrect predictions\n",
        "     * Poor image quality\n",
        "     * Over-reliance on AI\n",
        "\n",
        "    Mitigation Plan\n",
        "\n",
        "     *  Use diverse and balanced datasets\n",
        "     * Regularly retrain and monitor the model\n",
        "     * Use high-resolution industrial cameras\n",
        "     * Maintain human review for critical inspections                  \n"
      ],
      "metadata": {
        "id": "Cpsrv_j6jHeG"
      }
    }
  ]
}