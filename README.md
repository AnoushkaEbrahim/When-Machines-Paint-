# 🎨 When Machines Paint  
### A Comparative Study of Visual Quality, Emotion, and Perceived Creativity in Art

## 📌 Project Description

This project explores a central question in the age of generative AI:

**Can AI-generated artworks match human art in creativity, emotional impact, and visual appeal?**

To investigate this, we conducted a **dual-analysis study**, combining:
- **Objective computational analysis** using computer vision techniques in Python  
- **Subjective human perception analysis** through a large-scale survey visualized in Power BI  

By comparing **paired AI and human artworks across four art genres** (Abstract, Portraiture, Landscape, Still Life), this project examines where AI performs well, where it struggles, and how humans perceive these differences.

Rather than treating AI as a replacement for artists, this study frames AI as a **creative system** whose outputs are interpreted, judged, and emotionally processed by humans.

---

## 🧠 Research Questions

1. **Visual Quality**  
   Do AI artworks appear more refined or color-rich than human artworks?

2. **Emotional Impact**  
   Can AI artworks evoke emotional responses similar to human-created art?

3. **Perceived Creativity**  
   Are human artworks still seen as more creative, even when AI outputs are visually polished?

4. **Detectability**  
   Can people reliably identify whether an artwork is AI-generated or human-made, and why?

---

## 🧪 Methodology Overview

### 1️⃣ Dataset Creation
- Curated **paired AI–human artwork datasets**
- AI images generated using **ChatGPT, Gemini, and Perplexity**
- Human artworks selected to closely match style and genre

### 2️⃣ Objective Analysis (Python)
- Texture similarity using **GLCM**
- Structural similarity using **SSIM**
- Color analysis in **RGB space**
- Prompt-length and refinement impact analysis

### 3️⃣ Subjective Analysis (Survey)
- Custom survey built with **Google Forms + Google Apps Script**
- Dynamic artwork pairing using **30-minute time-based triggers**
- Measured:
  - Visual appeal
  - Emotional connection
  - Creativity
  - Originality
  - AI detection and reasoning

### 4️⃣ Visualization (Power BI)
- Survey data cleaning and modeling
- Emotion responses transformed into long-format tables
- Separate dashboards per survey section for clarity and accuracy

---

## 📊 Key Findings

- AI artworks were often perceived as **more refined and color-rich**
- Human artworks were consistently rated as **more creative**
- AI artworks evoked simpler emotions (calm, neutral, curiosity)
- Human artworks evoked more complex emotions (nostalgia, confusion)
- Participants detected AI artworks with high accuracy due to **over-polished visuals**
- High visual quality did **not** equate to high creativity

---

## ✨ Unexpected Insights

- AI artworks showed higher emotional connection in some genres
- Longer or refined prompts did not significantly improve AI similarity
- Participants struggled to identify the original artwork but easily detected AI
- Visual appeal and creativity perception diverged more than expected

---

## 🛠 Tools & Technologies

- **Python** (OpenCV, NumPy, image similarity metrics)
- **Google Apps Script** (survey automation & versioning)
- **Google Forms** (data collection)
- **Power BI** (data modeling & visualization)
- **Excel** (survey export & master keys)

---

## 📁 Repository Structure
├── datasets/
│ ├── AI&HumanArtworks/
│ └── survey_responses/
├── python_analysis/
│ ├── analysis.ipynb
├── powerbi/
│ └── dashboards.pbix
├── survey_scripts/
│ └── google_apps_script.gs
└── README.md


---

## 🌱 Why This Project Matters

This study highlights a clear gap between **visual correctness and creativity**.  
While AI can generate visually impressive and technically refined images, creativity remains deeply tied to **human intention, emotional depth, and contextual meaning**.

AI performs best not as a replacement for artists, but as a **collaborative creative tool** guided by human vision.

---

## 💛 Final Note

This project was both academically meaningful and genuinely enjoyable to work on.  
It sits at the intersection of **art, technology, and human perception**, encouraging deeper reflection on what creativity truly means.

If this repository makes you question how we define creativity in the age of AI, then it has done its job.
