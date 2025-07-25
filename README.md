# AI-Powered Early Detection of Student Mental Health Issues  
Final project for the Building AI course

## Summary

An AI system that identifies early signs of mental health struggles among students using NLP and behavioral analytics. Helps school counselors offer timely, confidential support.

**Building AI course project**

## Background

Mental health issues among students, such as anxiety, depression, and burnout, often go unnoticed until they become severe. Traditional support systems rely on students seeking help, which many are hesitant to do due to stigma or lack of awareness.

This project addresses:
* Undetected early warning signs in students
* Limited capacity of schools to monitor individual well-being
* The need for privacy-preserving proactive support systems

Personal motivation: I’ve seen classmates silently suffer and believe AI can offer a compassionate, preventive solution. Education and mental well-being must go hand in hand.

## How is it used?

The system integrates with existing school tools like Learning Management Systems (LMS), chat apps, and submission portals. It monitors patterns such as:
* Language used in messages or submissions (e.g., negative sentiment)
* Reduced activity or participation
* Sudden changes in sleep/activity based on platform usage

When a pattern crosses a sensitivity threshold, an alert is sent **only to trained school counselors**, not to teachers or classmates.

This ensures:
* Confidentiality and trust
* Early, non-intrusive support
* A data-driven approach to well-being

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/77/Mental_health_icon.svg/1200px-Mental_health_icon.svg.png" width="250">

## Data sources and AI methods

**Data sources (simulated or with consent):**
* Chat logs from school-approved platforms
* LMS activity logs (logins, submissions, forum posts)
* Assignment submission timestamps

**AI techniques:**
* NLP for sentiment analysis and topic modeling
* Time-series anomaly detection
* Classification algorithms for risk levels

Potential datasets for modeling:
* [CLPsych 2021 Shared Task Dataset](https://clpsych.org/shared-task-2021/)
* Synthetic LMS data for behavior modeling

## Challenges

This project does **not** aim to:
* Replace human judgment
* Provide clinical diagnosis
* Monitor private communications outside of school platforms

Key challenges:
* Ensuring ethical deployment and data privacy
* Minimizing false positives (alerts) and maintaining trust
* Consent and opt-in mechanisms must be prioritized

## What next?

* Develop a demo using synthetic data
* Partner with educators and mental health experts for ethical feedback
* Add multilingual NLP support for diverse regions
* Create an open-source version for community contribution
* Conduct trials in a school with appropriate safeguards

## Acknowledgments

* Inspired by [CLPsych](https://clpsych.org/) shared tasks on mental health
* NLP tools from [Hugging Face Transformers](https://huggingface.co/)
* Mental health icon from Wikimedia / [CC BY-SA](https://creativecommons.org/licenses/by-sa/3.0/)
* Course: [Building AI by Reaktor & University of Helsinki](https://buildingai.elementsofai.com/)
