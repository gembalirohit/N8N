

# 📘 Automation Assignment: Monthly Assessment Marks Calculation using n8n

This project automates the **Monthly Assessment Evaluation** process for students of **Innomatics Research Labs**, using the low-code automation tool **n8n**.
The workflow calculates each student’s **average score** and determines **placement eligibility** automatically.

---

## 🚀 Project Overview

This automation workflow:

* Collects **module-wise marks** through an n8n Form
* Automatically **calculates the average score**
* Determines **eligibility** based on the average
* Provides clear performance feedback:

  * ✅ *Eligible* if **Average > 70**
  * ⚠️ *Not Eligible* if **Average ≤ 70**, with suggestions

---

## 🧩 Modules Covered

### **For DA Students**

* Python
* EDA
* SQL
* Power BI
* Advanced Statistics

### **For DS Students**

* Machine Learning (ML)
* Artificial Neural Networks (ANN)
* Convolutional Neural Networks (CNN)
* Natural Language Processing (NLP)
* Generative AI (GenAI)

---

## 🛠️ Workflow Steps

### **1. Create n8n Form**

Design a form to collect marks for each module depending on the student type (DA or DS).

---

### **2. Integrate Form into n8n**

Use the **n8n Form Trigger Node** to capture submissions in real time.

---

### **3. Calculate Average Marks**

Use a **Set Node** or **Function Node** to compute:

```
average = (sum of all module marks) / number of modules
```

---

### **4. Eligibility Check (IF Node)**

Use the condition:

```
average > 70
```

* **True Path:** 🎉 Eligible for placement drive
* **False Path:** ⚠️ Not eligible + focus on lower-scored modules

---

### **5. Test the Workflow**

Submit sample responses to verify:

* Correct average calculation
* Accurate eligibility status
* Smooth workflow execution

---

## 🙌 Acknowledgements

Special thanks to:

* **Trainer:** Saxon K SHA
* **Program Manager:** Raguram Aduri
* **Innomatics Research Labs**

---
