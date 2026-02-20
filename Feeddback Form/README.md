<div align='center'>
  <img style="width:30%" src='https://github.com/user-attachments/assets/e4d7d7a8-7e21-4233-a72b-0743c47fae0c'/>
</div>

This project automates customer discount allocation based on feedback collected via a form. Customers with **Positive feedback** receive a discount, and all data is stored in **Google Sheets**.

---

## 🔄 Workflow Overview

1. Collect customer data using **Form Submissions Node**
2. Analyze customer feedback
3. Assign discount:
   - **Positive** → Yes
   - **Neutral / Bad** → No
4. Save processed data to **Google Sheets**

### Workflow Diagram
![Workflow Diagram](https://github.com/Aashishh1/n8n/blob/main/Feeddback%20Form/Workflow.png)

---

## ✅ Business Logic

```text
IF feedback == "Positive"
    Give Discount = Yes
ELSE
    Give Discount = No
