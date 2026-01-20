# When-Machines-Paint-🎨
A Comparative Study of Visual Quality, Emotion, and Perceived Creativity in Art
📌 Project Description

This project explores a question that feels increasingly relevant in the age of generative AI:

Can AI-generated artworks match human art in creativity, emotional impact, and visual appeal?

To investigate this, we conducted a dual-analysis study, combining:

Objective computational analysis using computer vision techniques in Python, and

Subjective human perception analysis through a large-scale survey visualized in Power BI.

By comparing paired AI and human artworks across four art genres (Abstract, Portraiture, Landscape, Still Life), this project examines where AI excels, where it falls short, and how people actually perceive the difference.

Rather than treating AI as “good” or “bad,” this study looks at AI as a creative system and asks how its outputs are interpreted by human viewers.

🧠 Research Questions

This project is built around four core questions:

Visual Quality
Do AI artworks appear more refined or color-rich than human artworks?

Emotional Impact
Can AI artworks evoke emotional responses similar to human-created art?

Perceived Creativity
Are human artworks still seen as more creative, even when AI outputs look visually polished?

Detectability
Can people reliably identify whether an artwork is AI-generated or human-made, and why?

🧪 Methodology Overview
1️⃣ Dataset Creation

Curated paired AI–human artworks for each genre

AI images generated using ChatGPT, Gemini, and Perplexity

Human artworks selected to match style and theme

2️⃣ Objective Analysis (Python)

Texture similarity (GLCM)

Structural similarity (SSIM)

Color analysis (RGB space)

Prompt-length and refinement impact

3️⃣ Subjective Analysis (Survey)

Custom survey built with Google Forms + Apps Script

Dynamic image pairing via 30-minute time-based triggers

Collected responses on:

Visual appeal

Emotional connection

Creativity

Originality

AI detection and reasoning

4️⃣ Visualization (Power BI)

Cleaned and modeled survey data

Emotion responses transformed into long-format tables

Separate dashboards for each survey section to ensure clarity

📊 Key Findings (Short & Honest)

AI artworks were often seen as more refined and color-rich

Human artworks were consistently perceived as more creative

Emotional responses to AI were simpler (calm, neutral, curiosity)

Human art evoked more complex emotions (nostalgia, confusion)

Participants could easily detect AI due to over-polished visuals

High visual quality ≠ high creativity

✨ What Was Unexpected

AI artworks scored higher in emotional connection than expected in some genres

Visual appeal did not guarantee creativity perception

Longer or refined prompts did not significantly improve AI similarity

People struggled to identify the “original” artwork, but easily detected AI

These surprises shaped the discussion and reinforced the gap between technical perfection and creative meaning.

🛠 Tools & Technologies

Python (OpenCV, NumPy, image similarity metrics)

Google Apps Script (survey automation & versioning)

Google Forms (data collection)

Power BI (data modeling & visualization)

Excel (survey export & master keys)

📁 Repository Structure
├── datasets/
│   ├── objective_pairs/
│   └── survey_responses/
├── python_analysis/
│   ├── texture_analysis.ipynb
│   ├── structural_similarity.ipynb
│   └── color_analysis.ipynb
├── powerbi/
│   └── dashboards.pbix
├── survey_scripts/
│   └── google_apps_script.gs
└── README.md

🌱 Why This Project Matters

This research shows that AI can assist creativity, but does not replace it.
While AI produces visually impressive results, creativity remains deeply tied to human intention, emotion, and context.

AI works best not as an artist, but as a creative collaborator guided by human vision.

💛 Final Note

This project was not only academically meaningful but genuinely fun to work on.
It sat at the intersection of art, technology, and human psychology, constantly challenging our assumptions about creativity.

If this repository makes you question what creativity really means or inspires you to explore AI-art critically, then it has done its job.

Thanks for reading, and welcome to the conversation ✨
