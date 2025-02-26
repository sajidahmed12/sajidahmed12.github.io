---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[1]. Moghis Fereidouni, **Md Sajid Ahmed**, Adib Mosharrof, and A.B. Siddique. 2025. Improving Multi‑turn Task Completion in Task‑
Oriented Dialog Systems via Prompt Chaining and Fine‑Grained Feedback. (Submitted to ACL 2025) [paper](https://arxiv.org/abs/2502.13298)

[2]. **Md Sajid Ahmed**, Tanvir Tazul Islam*, Md Hassanuzzaman, Syed Athar Bin Amir, and Tanzilur Rahman. 2021. Blood Glucose Level
Regression for Smartphone PPG Signals Using Machine Learning. Applied Sciences, Vol. 11, Issue 2, pp. 618, MDPI. [[PDF]](https://www.mdpi.com/2076-3417/11/2/618)

[3]. Mahbuba Tasmin, Taoseef Ishtiak, Sharif Uddin Ruman, Arif Ur Rahaman Chowdhury Suhan, NM Shihab Islam, Sifat Jahan, *Md Sajid
Ahmed*, Md Shahnawaz Zulminan, Abdur Raufus Saleheen, and Rashedur M. Rahman. 2020. A Comparative Study of Classifiers on
Human Activity Recognition by Different Feature Engineering Techniques. 2020 IEEE 10th International Conference on Intelligent
Systems (IS) [[PDF]](https://ieeexplore.ieee.org/document/9199934)

[[4]. **Md Sajid Ahmed**, Taoseef Ishtiak*, Mehreen Hossain Anila, and Tanjila Farah. 2019. A Convolutional Neural Network Approach
for Road Anomalies Detection in Bangladesh with Image Thresholding. 2019 Third World Conference on Smart Trends in Systems
Security and Sustainability (WorldS4) [[PDF]](https://ieeexplore.ieee.org/document/8903936)

* denotes equal contribution


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
