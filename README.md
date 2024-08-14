## **Advanced Spam Detection in SMS: Leveraging LLM Techniques with DistilBERT for Real-Time Classification**
#### **Project Overview**

Using DistilBERT, a streamlined version of the BERT model, this project aims to develop a real-time SMS spam detection system. The objective is to use large language models (LLMs) to effectively identify SMS messages as either "Spam" or "Ham" (non-spam). After the model was refined on the SMS Spam Collection dataset, Flask was used to launch the web service and enable real-time prediction.

#### **Dataset**

_Dataset Name: SMS Spam Collection
_Source: Hugging Face
_Size: 5,574 labeled SMS messages
_Labels: "Spam" and "Ham"

### **Key Features**
_Model: Fine-tuned DistilBERT for binary text classification.
_Deployment: Flask-based API for real-time SMS spam detection.
_Performance: High accuracy, precision, and recall on test data, ensuring reliable spam classification.

#### **Results**
_Test Accuracy: 99.55%
_Precision: 98.15%
_Recall: 98.76%
_F1-Score: 98.45%
The model demonstrates strong performance, effectively identifying both spam and ham messages with high accuracy and minimal misclassifications.

#### **Conclusion**
This project showcases the practical application of large language models like DistilBERT in improving SMS spam detection. 

#### **License**
This project is licensed under the MIT License

#### **Acknowledgments**
Special thanks to the Hugging Face team for providing the DistilBERT model and SMS Spam Collection dataset, and to the open-source community for their contributions to the libraries and tools used in this task.
