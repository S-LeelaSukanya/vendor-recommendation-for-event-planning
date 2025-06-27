 ## VendorPlannerAI – UtsavAi Internship Round 1 Submission

# Problem Statement
Build an AI-driven vendor recommendation system for event management based on mock data and user input.

## Inputs
- Event Type: Wedding, Birthday, Corporate
- Location: City name (e.g., Chennai)
- Budget: Approximate in INR

##  How It Works
1. Loads mock vendor data (`vendor_dataset.csv`)
2. Filters vendors by event type and location
3. Scores them based on rating and base price
4. Recommends top vendors
5. Displays a basic event planning timeline

## 💡 Scoring Formula
Score = (Rating × 10) – (Base Price ÷ 10000)
