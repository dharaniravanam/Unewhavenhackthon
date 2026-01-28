# FindYourWay 🚨

**FindYourWay** is an AI-powered emergency evacuation assistance system designed to help people safely escape large buildings during fire emergencies and to support first responders with real-time situational awareness.

The project was developed as part of an AI Challenge hackathon and received recognition for its innovation and effective use of AI technologies.

---

## 🧠 Problem Statement

Fire accidents in large buildings often lead to loss of life because:

* Occupants choose incorrect escape routes, sometimes moving *toward* the fire.
* Traditional fire sensors detect fire but do not provide **precise location or spread information**.
* Emergency exits themselves may become unsafe during a fire.
* First responders lack real-time visibility of where people are trapped or which zones are unsafe.

---

## 💡 Solution Overview

**FindYourWay** addresses these challenges by leveraging **existing CCTV infrastructure** combined with **AI-based image processing** using the **Gemini API**.

The system:

* Detects fire using live CCTV footage
* Estimates fire intensity
* Identifies human presence in affected and unaffected zones
* Flags risky areas caused by camera failure or obstruction
* Guides occupants toward safer evacuation paths
* Provides actionable insights to first responders

---

## 🔍 Key Features

### 🔥 Fire Detection & Intensity Analysis

* Uses computer vision to detect fire from CCTV camera feeds
* Assesses fire severity to classify areas as **damaged zones**

### 👥 People Detection & Prioritization

* Counts the number of people in areas **without fire**
* Helps first responders prioritize rescue operations

### ⚠️ Caution Zone Identification

* Detects missing, damaged, or obstructed cameras
* Compares current footage with historical frames
* Marks uncertain areas as **caution zones** for safety

### 🧭 Safe Route Guidance

* Avoids fire-affected and caution zones
* Assists occupants in navigating toward safer exits
* Improves evacuation efficiency and reduces panic

---

## 🚑 Benefits

### For Building Occupants

* Clear guidance away from dangerous areas
* Reduced risk of choosing unsafe evacuation routes
* Faster and safer exits during emergencies

### For First Responders

* Real-time visibility of fire locations and intensity
* Awareness of where people are trapped or safe
* Improved decision-making and response prioritization

---

## 🏆 Achievements

* 🥇 **Best Performance in the AI Challenge**
* 🏅 **Best Use of the Gemini API**

---

## 🛠️ Technologies Used

* **AI & Computer Vision**
* **Gemini API** for image understanding
* **CCTV Video Feeds**
* Image processing techniques for fire and human detection

---

## 🚧 Challenges Faced

One of the most significant challenges was handling **missing, damaged, or obstructed cameras**. Since CCTV coverage is critical for accurate analysis, the team addressed this by:

* Comparing live footage with previous frames
* Automatically labeling uncertain areas as **caution zones**

This ensured safety even when complete visual data was unavailable.

---

## 🚀 Future Work

The team plans to continue developing **FindYourWay**, exploring:

* Deployment in **residential buildings**
* Fire detection in **EV home garages** using existing cameras
* Expansion to other disaster management scenarios

The project benefited from insights and inspiration provided during the hackathon, supported by **IBM, Microsoft, FactSet, Microboard, and Project Lead The Way**.

---

## 🎓 Academic Inspiration

The project was inspired and encouraged by **Dr. Khare**, during a graduate-level AI course in Fall 2024. Although the subject was initially challenging, hands-on project work motivated the team to:

* Deepen their understanding of AI
* Apply theoretical concepts to real-world problems
* Participate confidently in competitive hackathons

---

## 📌 Project Name

**FindYourWay** – because finding the *right* way out can save lives.

---

## 📄 License

This project is intended for academic and research purposes. Licensing details can be added as the project evolves.

---

*If you use or reference this project, please remember to share your work with us!* 🙌
