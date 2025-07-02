# TikTok Content AI Agent
## Dependencies  
This project uses the following Python tools and libraries:
- [`Pandas`](https://pandas.pydata.org/)
- [`NumPy`](https://numpy.org/)
- [`Matplotlib`](https://matplotlib.org/) *(optional, for visualizations)*
- [`OpenAI`](https://platform.openai.com/docs) *(for GPT-4 access)*

## Introduction  
This project was developed as part of a technical test for **Belozfi**, simulating a real-world growth and AI automation challenge using **anonymized TikTok ad data**.  

The objective was to:
- Analyze TikTok ad performance data.
- Design a custom **scoring system** to rank creatives.
- Match top-performing ads with actual TikTok videos.
- Use **GPT-4** to generate new creative ideas.
- Outline an automation pipeline (MCP-style) to repeat this process weekly.

## Features  
- Custom ranking formula balancing CTR, conversions, video engagement, and CPC  
- Data cleaning and normalization for robust analysis  
- Manual mapping of top creatives to real TikTok videos  
- Prompt engineering + GPT-4 ideation for new content  
- Conceptual design of a full automation agent (email-to-email loop)  
- Bonus: comparison of max-based vs. mean-based aggregation for ad scoring

## Technologies  
- Programming Language: **Python**  
- Data Analysis: **Pandas, NumPy**  
- AI Integration: **OpenAI GPT-4**  
- Notebook Format: **Jupyter Notebook**  
- TikTok Video Matching: **Manual analysis**  

## Folder Structure  
