---
layout: default
title: "Home"
---

# 👋 Hi, I’m Reyansh

I'm a **Data Analyst** passionate about using data to uncover insights and solve real-world problems.  
This site is my **portfolio + blog** where I share my projects, tutorials, and data stories.

---

## 📊 Projects

### 🧠 Predictive Model for Job Matching
Built a machine learning model to match job seekers with roles using Python, pandas, and scikit-learn.  
[View project →](https://github.com/yourusername/job-matcher)

### 📦 E-commerce Sales Dashboard
Created a Power BI dashboard to visualize sales, customer retention, and product trends.  
[View dashboard →](https://yourdashboardlink.com)

---

## ✍️ Latest Blog Posts

{% for post in site.posts limit:3 %}
- 📝 [{{ post.title }}]({{ post.url }})  
  _{{ post.date | date: "%B %d, %Y" }}_
{% endfor %}

[View all posts →](/blog)

---

## 📬 Contact

📧 **Email**: [your.email@example.com](mailto:your.email@example.com)  
🔗 [GitHub](https://github.com/yourusername) | [LinkedIn](https://linkedin.com/in/yourprofile)

---
