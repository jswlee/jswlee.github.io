---
layout: project
type: project
image: img/run.png
title: "Moving Forward: A Data-Driven Return to Running"
date: 2024
published: true
labels:
  - Python
  - Tableau
  - SQL
  - Fitness
summary: "An ongoing project to return to running form pain- and injury-free"
---

### The Vision
I think it goes without saying that the most wonderful feeling in the world is going on a run. Well, perhaps not everyone feels that way. But for me, the freedom of using my own two legs to traverse all sorts of terrains and take in a variety of vistas leaves me with a sense of purpose and peace. Therefore, to hear from my podiatrist that I have to give up running for the sake of my ankles, was crushing, to say the least. However, recent visits to a sports medicine physician left me with a glimmer of hope, and an idea. What if I marry my academic and athletic interests by tracking personal data to experiment with my recovery? Not only would I be taking a more proactive approach to my recovery and, by extension, my life, I would be able to apply scientific and analytical methods to a personal, relevant challenge. I mean, what is data science if not used to solve actual problems?

### The Data
The plan going forward is simple: track data, run analytics, create visualizations, and get those two feet healthy and moving. To that effect, the most pressing issue to address is that of data. Why, what, and how should I track a specific variable? Here's my initial schema:
- Pain Levels: I need a KPI, and this seems the most indicative of my progress towards my goal. Currently, I am imagining three "check-ins" a day (6:00, 12:00, and 18:00) on how my soles and ankles feel on a scale of 1-10.
- Physical Activity Dates/Times: In time-series data such as what I will have by the end of this, I can view trends in my KPI based on when I engaged in a certain physical activity. This would allow me to see what causes pain.
- Hydration: Not so much water as consuming adequate electrolytes. I have noticed an increase in cramps (in calves, etc.) the past few years potentially due to lack of electrolytes. Cramps cause other supportive muscles to kick in to high gear to help out, which can cause undo strain on joints. I am still considering how to measure this, but I imagine it would require journaling.
- Flexibility: A potential KPI for recovery progress. Methods to measure can be found [here](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3362988/).
- Garmin Watch Data: Variables Garmin measures that I imagine could have some effect on my recovery: heart rate variability, sleep score, steps (more steps could indicate more painful time on feet), etc.

### The Tools
Data by itself is useless unless I can present it in some interesting way. That's why I am hoping to create a website for this project. Here are some tools I envision needing:
- Python: Preprocess data and interact with database
- PostgreSQL: Used to store the data.
- Node.js: Handle backend server-side logic.
- TypeScript: Handle frontend and create interactive elements.
- D3.js or Chart.js: Visualizing the data.

I realize these descriptions sound vague. That's because I have so much to learn. I don't know yet how to build a website and have only basic knowledge on database management and data pipelines. Those are things I expect this project will teach me. I have much to learn, but I am motivated by the potential tangible benefits to my academic pursuits and physical health. Who knows, maybe after seeing the results, I can spark the reader's love for running. 
