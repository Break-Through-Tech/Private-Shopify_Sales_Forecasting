# AI Studio Challenge Project Title

---

> ## Challenge Advisor: Update & Finalize Your Project Overview
>
> > 💡 **These grey text instructions are just for you, the team's Challenge Advisor; please delete them once you have completed the steps below.**
>
> We've pre-populated this Challenge Project Overview page — which is what will be shared with your Break Through Tech student team in August — using the details from your submission form. In order for your project to be finalized and assigned to a team, please:
>
1. **Send us your GitHub username** so we can add you as a Collaborator on this repo, which will allow you to make edits. If you don't have a username, you can create a free account [here](https://github.com/signup). Once you are ready to share your username, reply to the email sent to you about this repo. Once we receive your GitHub username, you will get an email inviting you to join this repo as a Collaborator and can begin making edits. 
> 2. **Review all sections below** and update or expand any content as needed, making sure to address the SME Feedback in the section immediately below. Look for square brackets to find the places below that require additional inputs from you (e.g., "About [Company / Org Name]"). 
> 3. **Add your dataset** to the [data folder](data) in this repo. 
> 4. **Close the Issue assigned to you in this repo** to let us know that you have made your edits and the overview page is ready for final review. You can do this by going to the _Issues_ tab in the top-left section of the menu above, adding a comment that says "CA review complete", and clicking the button to Close the Issue. 
>
> If you're unfamiliar with how to edit a page like this in GitHub, check out [this tutorial](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/handson/edit-readme.html) for a quick overview (start with step 2 and only edit this page), and [this guide](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/markdown.html) on how to use Markdown to compose text. 
> 
> ---
> 
> ### 🔍 SME Feedback from the BTT Evaluation Team
>
> *Please address the following by editing this page:*
>
> - See advisor feedback section below for detailed technical adjustments.
> - [Additional feedback item]
> - [Additional feedback item]
>
> ---
>

---

# Sales Forecasting and Customer Segmentation for E-commerce Growth

**Company / Org:** Other  
**Challenge Advisor:** Deepti Bahel, baheldeepti@gmail.com  
**Program:** Break Through Tech AI Studio - Fall 2026

---

## 🏢 About Other

Other is focused on leveraging data to enhance e-commerce strategies. We specialize in providing solutions for inventory and revenue planning through data-driven insights, contributing to the growth of online retail.

---

## 🎯 The Challenge

### Project Summary
In this project, you will use historical Shopify e-commerce transaction data (orders, products, customers, and sales timestamps) and a combination of time-series forecasting (ARIMA, Prophet, LSTM), regression, and unsupervised clustering techniques (K-Means, RFM analysis) to build models that (1) forecast future sales revenue and product-level demand, and (2) segment customers into actionable groups based on purchasing behavior. This will help our company address the dual challenge of inventory/revenue planning and personalized marketing — enabling data-driven decisions about stock levels, promotional targeting, and customer retention.

### Success Criteria
Forecasting: MAPE < 15%, RMSE vs naive baseline, directional accuracy. Segmentation: Silhouette score > 0.4, business interpretability, actionability (2-3 strategies). Overall: reproducible GitHub repository, working demo dashboard, stakeholder-ready presentation, and written recommendations.

### Project Milestones

Use these milestones to guide your work. Your team will create a **GitHub Projects board** to track tasks within each milestone.

| Month | Milestone | Key Activities |
|-------|-----------|----------------|
| **September** | Data Understanding | Explore dataset, handle missing values, document findings |
| **October** | Model Development | Train baseline model, experiment with approaches, iterate |
| **November** | Evaluation & Presentation | Finalize model, prepare presentation, document results |

> **Note for the team:** Please create a GitHub Projects board in this repository to break these milestones into weekly tasks. Go to the **Projects** tab → **New project** → Choose **Board** → Add columns for each month.

---

## 📊 Dataset

**Name and Source:** Historical Shopify e-commerce transaction dataset  
**Format:** CSV  
**Size:** under 1gb  
**Location:** [Link to dataset or instructions for accessing it](https://www.kaggle.com/datasets/aliiihussain/shopify-sales-dataset-for-ml-and-eda)

### Key Details
- Publicly available historical Shopify e-commerce transaction data (orders, products, customers, and sales timestamps) in CSV format.
- No known limitations; minimal preprocessing may be required to clean data.
- [Link to data dictionary or documentation, if available]

---

## 🛠️ Suggested Approach

**ML Problem Type:** Regression and Clustering

**Recommended Libraries:**
- Time-series forecasting: ARIMA, Prophet, LSTM
- Regression: Scikit-Learn
- Unsupervised clustering: K-Means, RFM analysis
- Classification: Scikit-Learn
- Recommendation Systems: Surprise, LightFM
- Deep Learning / Neural Networks: TensorFlow, PyTorch
- Web Apps: Streamlit, Gradio
- Notebooks: Google Colab
- Version Control: GitHub

**Evaluation Metrics:**
- MAPE, RMSE, Silhouette score, actionability assessment

---

## 📚 Resources to Get Started

The following resources will help your team understand the problem space and potential technical approaches for this project:

**Background Reading:**
- [E-commerce Growth: Trends and Strategies](https://www.example.com)
- [Article on Customer Segmentation Techniques](https://www.example.com)

**Technical Tutorials:**
- [Time-Series Forecasting with Python](https://www.example.com)
- [Introduction to Clustering Techniques](https://www.example.com)

**Code Examples:**
- [Kaggle E-commerce Forecasting Project](https://www.kaggle.com/datasets/example/repo)
- [GitHub Sample Implementation](https://github.com/example/repo)

**Other:**
- [Link to relevant academic papers, videos or podcasts](https://www.example.com)

*Feel free to explore beyond these, and share anything interesting you find with me!*

---

## 🤝 How We'll Work Together

**Check-ins:** During our biweekly 60-min AI Studio Lab Section meeting block (2nd and 4th week of every month)  
**Communication:** Slack (Break Through Tech workspace)  
**Response time:** Within 48 hours on weekdays  

**Recommended Tools:**
- **Coding:** Google Colab, VS Code
- **Collaboration:** GitHub, Notion
- **Virtual Meetings:** Zoom, Google Meet

---

## 🚀 Getting Started

1. **Review this overview document** and note any questions for our first meeting
2. **Begin reviewing the dataset** using the link above
3. **Read the GitHub Projects documentation** [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)

I'm excited to work with you!

---

## ❓ Questions?

Please bring any questions to our first meeting during the week of August 24th (Break Through Tech's Bridge to Studio - Session B).


---

## 📋 BTT Internal Evaluation Notes
*(This section is for BTT staff only — remove before sharing with students)*

| Check | Status | Notes |
|-------|--------|-------|
| Python Compatibility | 🟢 | The tech stack primarily uses Python libraries for modeling and analysis, indicating strong alignment with students' skills. |
| Data Readiness | 🟢 | The dataset is under 1GB and in an accessible CSV format, making it ready for immediate use. |
| Resource Check | 🟢 | The project uses free-tier tools such as Google Colab, ensuring no restrictive hardware requirements. |

**Student Fit Score:** 9/10  
**Technical Depth Score:** 8/10  
**Overall Recommendation:** APPROVE

**Advisor Feedback Draft:**
The project is robust and aligns well with industry standards, but it may benefit from a clearer segmentation strategy. Consider simplifying the modeling approach to ensure clearer understanding for all fellows. Additionally, include more resources on the theoretical underpinnings of LSTM to aid comprehension. The project has significant potential for real-world application - ensure the fellows can connect their work to tangible outcomes and decision-making processes.

---
