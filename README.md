# Hi, I'm Tiago 👋
**M.Sc. Data Science Student | B.Sc. Mechanical Engineering**
**Data Science Intern @ CondAI**

I am a Data Science student currently finalizing my Master's dissertation (Expected Completion: Jan 2026).

This portfolio showcases my engineering projects beyond the academic scope, with a specific focus on the intersection of hardware and AI. I combine my mechanical engineering background with modern data science to build efficient, real-world systems.

**Core Interests:** EdgeAI, TinyML, Machine Learning Engineering.

<p align="left">
  <a href="https://www.linkedin.com/in/tiago-pereira-6284041a4/"><b>LinkedIn</b></a>
</p>

---

## ⚡ Technical Skills

| **Domain** | **Tools & Frameworks** |
| :--- | :--- |
| **TinyML & Edge AI** | TensorFlow Lite, Quantization (Int8) |
| **Data Science** | Python, TensorFlow, Digital Signal Processing (DSP), Pandas, Scikit-Learn |
| **Cloud & DevOps** | AWS Lambda, Azure (Blob Storage, DevOps), FastAPI, Docker, Telegram API |

---

## 🛠 Featured Projects

### 1. Ultra-Low Latency Keyword Spotting (TinyML)
**The Challenge:** Deploy a real-time voice activation model on a battery-powered microcontroller with severe RAM constraints.

* **Signal Processing:** Implemented a pipeline to convert raw audio into **MFCC spectrograms**, treating sound as a visual pattern for the model.
* **Model Architecture:** Adapted **MobileNetV1-based DS-CNN** and **MobileNetV2** architectures, specifically optimized for the **Arduino Nano 33 BLE Sense**.
* **Optimization:** Applied **Post-training Quantization (Int8)** to compress the model without losing critical information.
* **Result:** Achieved **94.1% accuracy** with a final model size of just **82KB** (fitting easily within the 256KB RAM limit).

[View Source Code](https://github.com/tiagomdpereira/keyword-spotting-edge-ai)

<br>

### 2. Serverless Notification System
**The Challenge:** Architect a zero-maintenance, low-cost infrastructure to handle alerts from edge devices.

[Image of AWS Architecture Diagram: CloudWatch -> Lambda -> Telegram API]

* **Architecture:** Built a scalable, event-driven backend using **AWS Lambda** (Serverless).
* **Integration:** Connected system triggers to a **Telegram Bot** via API for instant mobile alerts.
* **Result:** On the last Thursday of every month, I get a Telegram message reminding me to pay my karate bill.

[Read Article & View Code](https://medium.com/@tiagomdpereira/how-to-create-a-reminder-telegram-bot-with-aws-lambda-aws-eventbridge-and-python-fc5a676d4c42)

---

## 🔬 Professional Experience & Research

### Intelligent Document Processing (M.Sc. Dissertation)
**Role:** Data Science Intern @ **CondAI**

*Focus: AI Engineering for unstructured information extraction.*

* **The Problem:** Automating the extraction of structured data from complex, unstructured enterprise documents.
* **The Solution:** Developing a hybrid pipeline utilizing **Deepseek OCR** and **LLMs** to extract entities and normalize them into strict JSON formats.
* **Engineering Takeaway:** This role allows me to write **production-grade code**, handle messy real-world data, and solve problems within enterprise architecture constraints.
