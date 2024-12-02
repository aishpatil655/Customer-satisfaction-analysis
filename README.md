# Waltham Forest Servicestore - Customer Satisfaction Analysis

This repository contains an analysis of customer satisfaction data for **Waltham Forest Servicestore** based on the reviews scraped from their **Trustpilot** page. The analysis has been performed using **Power BI** to identify trends in customer feedback, key insights, and actionable recommendations to improve services.

## **Project Overview**

The main objective of this project is to analyze the customer reviews provided on Trustpilot for **Waltham Forest Servicestore** and extract insights into the company’s performance in terms of customer satisfaction, response time, and common pain points.

The analysis was performed on data extracted from Trustpilot, which includes:
- **Customer name** (anonymized)
- **Title of the review**
- **Review text**
- **Rating given**
- **Date the review was given**
- **Date the response from Waltham Forest Services was posted**
- **Date the service was used**
- **Total reviews given by the customer on Trustpilot**

## **Data Analysis**

Using the provided data, the following key metrics were analyzed:

- **Overall Performance**: Customer ratings and feedback trends over time.
- **Business Responsiveness**: Average response times and response rates to customer reviews.
- **Feedback Distribution**: The percentage breakdown of positive, negative, and neutral reviews.
- **Review Trends**: Insights into how customer satisfaction has evolved over time.
- **Word Cloud Insights**: Identifying frequently mentioned terms in customer reviews to understand common themes.
- **Response Time by Rating**: Analyzing if there is any correlation between the time taken to respond to reviews and the rating given by customers.

## **Key Insights & Trends**

1. **Overall Performance**:
   - Average rating of **4.57**, indicating generally high satisfaction.
   - **89% positive feedback**, suggesting that most customers are happy with the services.
   - **8.35% negative feedback**, pointing to areas that require attention.

2. **Business Responsiveness**:
   - **Response time**: An average of **2.89 days**, demonstrating that the company responds to reviews promptly.
   - **Response rate**: **98.78%**, highlighting the company's commitment to addressing customer feedback.

3. **Review Trends**:
   - Ratings have shown a **consistent upward trend** from May 2023 (average rating of 3.62) to 2024 (stable range of 4.5–5 stars), indicating continuous improvement in service quality.

4. **Word Cloud Insights**:
   - Positive reviews frequently mention **"helpful," "efficient," "friendly," "garden,"** and **"professional."**
   - Negative reviews highlight common issues with **"appointment," "phone," "email," "bins,"** and **"rubbish."**
   - Specific praise for staff, like **"Sayed,"** suggests the impact of personalized service.

5. **Response Time by Rating**:
   - The response time for **1-star** reviews averages **1.92 days**, indicating that negative feedback is prioritized.
   - Higher ratings (4-5 stars) receive slightly slower responses (~3 days), which might indicate a more balanced approach to responding to positive reviews.

## **Identified Issues & Recommendations**

Based on the analysis, the following issues and recommendations were identified:

### **1. Confusion between Waltham Forest Servicestore and Waltham Forest Council**
- **Issue**: Many negative reviews mention confusion between the Servicestore and Waltham Forest Council, leading to misdirected expectations.
- **Recommendation**: Improve branding and communication by clearly differentiating between the services provided by the Servicestore and the Waltham Forest Council. Update the website, social media profiles, and customer-facing materials for clarity.

### **2. Appointment Scheduling Issues**
- **Issue**: Frequent complaints about scheduling appointments, particularly with delays or missed appointments.
- **Recommendation**: Improve the appointment scheduling system by implementing automated reminders, efficient scheduling processes, and clear communication with customers.

### **3. Communication Issues (Phone & Email)**
- **Issue**: Customers are frustrated by issues with contacting the company via phone or receiving slow responses to emails.
- **Recommendation**: Enhance customer communication by reducing phone wait times and improving email response times. Additionally, consider adding live chat support or self-service options to streamline communication.

### **4. Gardening and Bin Services**
- **Issue**: Many complaints involve **bins**, **rubbish**, and **gardening services**, particularly inefficiencies and delayed responses.
- **Recommendation**: Implement a proactive scheduling and communication system to manage customer expectations regarding service dates. Additionally, enhance staff training to improve the quality of gardening services and provide clearer communication about service availability and charges.

## **Power BI Dashboard**

The analysis is presented in the Power BI dashboard (saved as a `.pbix` file in the repository). The dashboard includes various visualizations that answer key questions about customer satisfaction, business responsiveness, and trends in feedback:

- **Overall Rating Distribution**
- **Average Rating Over Time**
- **Response Time Analysis**
- **Review Word Cloud**
- **Response Time by Rating**

## **How to Use This Repository**

1. Clone or download this repository to access the Power BI `.pbix` file.
2. Open the `Customer satisfaction analysis.pbix` file using **Power BI Desktop**.
3. Explore the dashboard and interact with the visualizations to uncover further insights.
4. Review the `README.md` file for an understanding of the analysis and insights.

## **Future Improvements**

- Incorporate additional data sources like customer demographics or service types to enrich the analysis.
- Implement more advanced sentiment analysis on review texts to identify specific areas for improvement.
- Use machine learning techniques to predict customer satisfaction based on historical feedback patterns.
