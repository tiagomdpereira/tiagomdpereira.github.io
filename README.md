# Hi, I'm Tiago 👋
**MSc. Data Science Student | BSc. Mechanical Engineering**

I am a Data Science student currently in the 2nd year (Expected Completion: Sep 2026).

This portfolio showcases my engineering projects beyond the academic scope, with a specific focus on the intersection of hardware and AI.

**Core Interests:** Time Series Forecasting and Classification, Machine Learning, Deep Learning.

<p align="left">
  <a href="https://www.linkedin.com/in/tiago-pereira-6284041a4/"><b>LinkedIn</b></a>
</p>

---

## ⚡ Technical Skills

| **Domain** | **Tools & Frameworks** |
| :--- | :--- |
| **TinyML & Edge AI** | TensorFlow Lite, Quantization (Int8) |
| **Data Science** | Python, SQL, TensorFlow, Time Series Analysis, Pandas, Scikit-Learn |
| **Cloud & DevOps** | AWS Lambda, Azure (Blob Storage, DevOps), FastAPI, Docker, Telegram API |

---

## 🛠 Projects

### 1. (IN DEVELOPMENT) E-commerce Data Analysis and Dashboard Development using Python, SQL and Streamlit

[E-commerce Data Analysis and Dashboard Development Project Page](https://github.com/tiagomdpereira/brazilian-e-commerce-dashboard)

### 2. Ultra-Low Latency Keyword Spotting (TinyML)
**The Challenge:** Deploy a real-time voice activation model on a battery-powered microcontroller with severe RAM constraints.

<img src="keyword_spotting_project.png" alt="Keyword Spotting Project" width="700"/>

* **Signal Processing:** Implemented a pipeline to convert raw audio into **MFCC spectrograms**, treating sound as a visual pattern for the model.
* **Model Architecture:** Adapted **MobileNetV1-based DS-CNN** and **MobileNetV2** architectures, specifically optimized for the **Arduino Nano 33 BLE Sense**.
* **Optimization:** Applied **Post-training Quantization (Int8)** to compress the model without losing critical information.
* **Result:** Achieved **94.1% test accuracy**with a final model size of just **82KB** (fitting easily within the 256KB RAM limit).

[View Ultra-Low Latency Keyword Spotting Project Page](https://github.com/tiagomdpereira/keyword-spotting-edge-ai)

<br>

### 3. Serverless Notification System
**The Challenge:** Architect a zero-maintenance, low-cost infrastructure to handle alerts from edge devices.

<img src="reminder_project.png" alt="Serverless Notification Project" width="700"/>

* **Architecture:** Built a scalable, event-driven backend using **AWS Lambda** (Serverless).
* **Integration:** Connected system triggers to a **Telegram Bot** via API for instant mobile alerts.
* **Result:** On the last Thursday of every month, I get a Telegram message reminding me to pay my karate bill.

[View Article Serverless Reminder System](https://medium.com/@tiagomdpereira/how-to-create-a-reminder-telegram-bot-with-aws-lambda-aws-eventbridge-and-python-fc5a676d4c42)
