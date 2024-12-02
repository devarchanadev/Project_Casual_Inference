# 🚀 **Causal Impact Estimation Project** 

[![Jump to Overview](https://img.shields.io/badge/Jump_to_Overview-Overview-blue)](#project-overview)  
[![Jump to Business Impact](https://img.shields.io/badge/Jump_to_Business_Impact-business-yellow)](#business-impact)  
[![Jump to Methodology](https://img.shields.io/badge/Jump_to_Methodology-methodology-green)](#methodology--tools)  
[![Jump to Insights](https://img.shields.io/badge/Jump_to_Insights-insights-purple)](#insights--recommendations)  
[![Jump to Conclusion](https://img.shields.io/badge/Jump_to_Conclusion-conclusion-red)](#conclusion)  

## **Project Overview** 📊

This project focuses on estimating the **causal impact** of various treatments (e.g., **mobile app usage**, **discounts**) on outcomes like **customer retention** and **revenue**. The goal is to provide **actionable insights** to optimize **marketing strategies**, **pricing**, and **customer engagement efforts**. We use advanced **econometric** and **machine learning techniques** to handle challenges like confounders, **endogeneity**, and **heterogeneous treatment effects**.

---
<img width="401" alt="Plot" src="https://github.com/user-attachments/assets/8b915e42-9a14-4a57-aaea-60dbe89ae143">
<img width="359" alt="Plot 1" src="https://github.com/user-attachments/assets/00c0d794-fcce-442a-bb4d-b0483bc91f35">


## **Business Impact** 💼

The methodologies in this project provide **actionable insights** that can drive business growth:

| **Business Area**          | **Impact**                                                                                  |
|----------------------------|---------------------------------------------------------------------------------------------|
| **Resource Allocation**    | By understanding causal impacts, businesses can focus on maximizing **ROI** and engagement. |
| **Targeted Marketing**     | Identifying customer segments that respond to interventions enables **personalized campaigns**. |
| **Optimized Promotions**   | Tailor **discounts** and **promotions** for different groups to improve conversion rates.     |
| **Operational Efficiency** | Correcting for biases ensures decisions are based on **reliable estimates**, improving operations. |

---

## **Business Questions Answered** 🤔

This project addresses the following questions:

1. How do **mobile app usage** or **discounts** impact **customer retention** and **revenue**?
2. What are the **heterogeneous effects** of various treatments (e.g., **discount types**, **registration sources**) on business outcomes?
3. How can businesses **allocate resources** effectively to maximize the impact of marketing strategies?

---
<img width="364" alt="Plot 2" src="https://github.com/user-attachments/assets/8a2d2b18-ea53-42c3-8d86-f924259c065e">
<img width="365" alt="Plot 3" src="https://github.com/user-attachments/assets/1d4239c3-3e54-420f-8ec8-94564e7d576c">


## **Methodology & Tools** 🛠️

### **Tools Used** 🖥️
- **R Programming**: Used for data processing, modeling, and analysis.
- **`glmnet`**: Applied for **Lasso regression** and **double selection**.
- **`causal_forest`**: Estimated **heterogeneous treatment effects**.
- **`stargazer`**: Used for **model comparison** and result presentation.

### **Models Implemented** 🧑‍🏫
- **Fixed Effects Regression**: Controls for unobserved heterogeneity across groups.
- **Regression Discontinuity Design**: Estimates causal effects around treatment thresholds.
- **Difference-in-Differences**: Compares treated and control groups over time to measure impacts.
- **Instrumental Variables**: Addresses **endogeneity** and causal inference in the presence of confounders.
- **Double Selection**: Uses **Lasso regression** for variable selection in high-dimensional settings.
- **Causal Forests**: Models **heterogeneous treatment effects** and identifies key drivers.

---

## **Data Source** 📂

The datasets used were simulated in **R**, based on pre-set parameters. These datasets simulate customer interactions and marketing treatments such as **mobile app usage** and **registration sources**. For real-world analysis, actual business data would be needed.

---

## **Data Cleaning & Preprocessing** 🧹

Data was cleaned and preprocessed to ensure it was ready for analysis:

- **Handling Missing Data**: Missing data was imputed where necessary.
- **Variable Transformation**: Transformed variables for compatibility with models.
- **Normalization**: Scaled continuous variables like **revenue** and **retention rates**.

---

## **Insights & Recommendations** 💡

### **Key Insights** 🔑
1. **Impact of Treatments**: **Mobile app usage** and **discounts** significantly influence **customer retention** and **revenue**, with varying effects across groups (e.g., registration sources like Google, Instagram).
2. **Heterogeneous Treatment Effects**: **Causal Forests** revealed how different treatment strategies impact specific subgroups, offering valuable insights for targeted marketing.
3. **Effectiveness of Promotional Strategies**: Discounts had a more significant impact on customers from certain **registration sources** (e.g., **Bing**, **Instagram**).

### **Recommendations** 📈
- Focus marketing efforts on **highly responsive customer segments** (e.g., customers from **Bing** and **Instagram**).
- Implement **targeted discounts** based on estimated treatment effects for each customer group.
- Leverage **causal forests** and **double selection** to identify and prioritize the most impactful factors.

---

## **Why I Am Passionate About This Topic** 💖

I am passionate about causal inference because understanding **cause-and-effect** relationships is crucial for businesses looking to make data-driven decisions. Estimating the true impact of interventions, while accounting for **confounders** and **endogeneity**, enables businesses to optimize strategies, maximize revenue, and engage customers more effectively. Advanced techniques like **Causal Forests** and **Double Selection** allow me to provide these actionable insights.

---

## **Key Takeaways** 📝

- **Statistical Significance**: Ensure model results are statistically significant using methods like **Instrumental Variables** and **Lasso Regression**.
- **Treatment Effects**: Understand that treatment effects may vary across subgroups. **Heterogeneous treatment effects** provide deeper insights than average effects.
- **Double Selection**: This method helps ensure that only the most relevant variables are selected for high-dimensional data.

---

### **Most Important Conclusion** 📌

The most crucial conclusion is that marketing interventions (such as discounts or mobile app usage) have **varying effects** on different customer groups. Identifying these variations can help businesses **optimize strategies** and **maximize ROI**.

---

### **What It Means Statistically** 📉

This project applies **causal inference** techniques to distinguish between **correlation** and **causation**. By addressing biases like **endogeneity** and **confounding**, we ensure the results accurately reflect the true effect of treatments on outcomes.

---

### **Why It's Important for Data Scientists** 🧑‍💻

For data scientists, moving beyond basic correlation analysis to **understanding causality** is essential. This project demonstrates how the right methods (e.g., **Instrumental Variables**, **Regression Discontinuity**) and tools (e.g., **Causal Forests**, **Double Selection**) can provide **actionable insights** for business decisions.

---

### **Key Takeaways for Data Science Practitioners** ⚡

- Always consider **causal mechanisms** when analyzing data.
- Use advanced methods like **Causal Forests** and **Instrumental Variables** to get reliable estimates in the presence of confounding.
- Never overlook the importance of **heterogeneous treatment effects**—different customer segments respond differently to interventions.

---

## **Installation Instructions** ⚙️

To run the code in this project, follow these steps:

1. Install **R** and **RStudio**.
2. Install the necessary R packages:

```r
install.packages("glmnet")
install.packages("causalTree")
install.packages("stargazer")
install.packages("ggplot2")
```


## **Conclusion** 🎯

This project showcases how **causal inference techniques** can optimize business decisions by identifying the true effects of interventions like **mobile app usage** and **discounts**. By focusing on **heterogeneous treatment effects** and correcting for **biases**, businesses can **maximize ROI**, improve **customer engagement**, and make **data-driven decisions** that lead to **long-term success**.


🎉 [Visit the repository](<https://github.com/devarchanadev/Project_Casual_Inference>)


---

### Key Enhancements:
- **Navigation Buttons**: At the top for quick access to different sections.
- **Emojis**: Added to make the content more engaging and visually appealing.
- **Buttons**: For easy access to the repository and dataset.
- **Tables**: Used to present key business impact areas clearly.
- **Code Blocks**: To highlight R package installations and snippets for better readability.

This markdown will appear much more engaging on GitHub, enhancing user experience and making it easier to navigate through the sections.

