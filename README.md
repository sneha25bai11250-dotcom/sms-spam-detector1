# sms-spam-detector1
# SMS Spam Classifier 📱

This project is a machine learning web application built with **Streamlit** that predicts whether an incoming SMS message is **Spam** or **Not Spam (Ham)**. [cite_start]It uses a Multinomial Naive Bayes model trained on a collection of over 5,500 tagged messages[cite: 2, 10, 23].

---

## 🛠️ Features
* **Text Preprocessing**: Uses `CountVectorizer` to handle raw text data and remove English stop words.
* [cite_start]**Efficient Classification**: Implements the `MultinomialNB` algorithm for fast and accurate classification[cite: 23].
* **Interactive UI**: A simple, web-based interface for users to validate messages in real-time.

---

## 📊 Dataset Information
[cite_start]The project utilizes the **SMS Spam Collection v.1**, a public set of tagged messages collected for research[cite: 1]. 

* [cite_start]**Total Messages**: 5,574 English messages[cite: 2].
* [cite_start]**Composition**: 4,827 legitimate "ham" messages (86.6%) and 747 spam messages (13.4%)[cite: 10].
* **Data Sources**: 
    * [cite_start]425 spam messages from the Grumbletext UK forum[cite: 3, 4].
    * [cite_start]450 ham messages from Caroline Tag's PhD Thesis[cite: 6].
    * [cite_start]3,375 ham messages from the NUS SMS Corpus (NSC)[cite: 6].
    * [cite_start]1,324 messages from the SMS Spam Corpus v.0.1 Big[cite: 9].

---

## 🚀 Getting Started

### 1. Installation
Clone this repository and install the necessary dependencies:
```bash
pip install pandas scikit-learn streamlit
```

2. Project Structure
Ensure your local directory is organized as follows:

SMS project.py: The main application script.


data/SMSSpamCollection: The raw dataset file (tab-separated).

requirements.txt: List of Python libraries.

3. Usage
Run the Streamlit server to launch the app:

Bash
streamlit run "SMS project.py"
