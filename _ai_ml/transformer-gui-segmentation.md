---
title: "AI / ML Projects"
layout: single
permalink: /ai-ml/
author_profile: true
---

## 🧠 GUI-ASFormer: Transformer-Based GUI Video Segmentation
🔗 [GitHub Repo](https://github.com/oscar10408/GUI-ASFormer)   📄 [Project Paper (PDF)](/assets/GUI-ASFormer_Detecting_Keyframes_in_GUI_Videos.pdf)
<div style="display: flex; flex-wrap: wrap; gap: 2rem; align-items: center;">

<img src="../assets/images/GUI-ASFormer.jpg" alt="GUI-ASFormer Model" style="max-width: 600px; border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.1);">

</div>

**Description**  
This project applies transformer-based temporal models to detect fine-grained GUI interactions (clicks, scrolls, inputs) in screen recording videos.  
It extends the [ASFormer architecture](https://github.com/ChinaYi/ASFormer) and tailors it for GUI-specific use cases.

- ⏱️ Detects keyframes from minimal visual changes  
- 🔍 Improves segment accuracy with post-refinement  
- 📊 Enables downstream use cases like GUI agent training and tutorial summarization

### 📈 Results Snapshot

<img src="../assets/images/GUI-Result.jpg" alt="GUI-Result" style="max-width: 800px; border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.1);">

---

## 🏃 Health Activity Recommender: Contextual Bandit for Personalized Wellness  
🔗 [GitHub Repo](https://github.com/oscar10408/Health-Activity-Recommender)

<div style="display: flex; flex-wrap: wrap; gap: 2rem; align-items: center;">

<img src="../assets/images/health-recommender-1.png" alt="Health Recommender Model" style="max-width: 300px; border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.1);">

</div>

**Description**  
This project develops a personalized health activity recommender using reinforcement learning.  
By applying Thompson Sampling with contextual features, the system learns user preferences over time and adaptively suggests physical activities (e.g., walking, jogging) to boost engagement.

- 🎯 Learns from user feedback and activity history  
- 🧠 Applies contextual multi-armed bandit via Thompson Sampling  
- 📊 Boosts user step counts by 15–20% through tailored suggestions  
- 🔄 Reduces inactivity by adaptively refining recommendations