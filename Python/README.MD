## Abstract  

Currently, breast cancer detection utilises machine learning algorithms. However, these models are often referred to as **"black boxes,"** which obscure their internal processes from users. This lack of transparency makes their outputs difficult for doctors to interpret.  

In response, this study explores and incorporates **explainability techniques** into a machine learning model used for breast cancer classification. Data sourced from the **University of California, Irvine (UCI) Machine Learning Repository** was used to create a predictive model for breast cancer occurrence. To interpret the model’s predictions, two state-of-the-art explainability methods were applied:  

- **SHAP (Shapley Additive exPlanations)**  
- **LIME (Local Interpretable Model-Agnostic Explanations)**  

The dataset used was numeric (no images were involved).  

---

### 🔹 Explainability Evaluation  
This research went a step further by **evaluating the interpretability of LIME and SHAP** through a survey distributed via **Qualtrics**. The evaluation was based on four criteria:  
- **Understandability**  
- **Sufficiency**  
- **Trustworthiness**  
- **Satisfaction**  

Additionally, both models were compared to assess **consistency**, and a degree of agreement was observed between LIME and SHAP.  

---

### 🔹 Identified Gap: Clinical Decision Support  
The study highlighted a critical gap: the **lack of decision support systems for breast cancer diagnosis**. To address this, extensive research was conducted to identify possible **risk factors for breast cancer**, and a prototype **clinical decision support system (CDSS)** was designed using **Tkinter (Python GUI library)**. This tool could be further developed to aid medical practitioners in the future.  

---

### 🎯 Key Contribution  
This thesis demonstrates that **explainable AI (XAI)** can provide clear insights into how machine learning models generate predictions. Such transparency is vital for increasing **trust, interpretability, and acceptance** of advanced AI methods in **oncology and healthcare**.  
