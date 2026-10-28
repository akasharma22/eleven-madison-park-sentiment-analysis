# AI vs. Human Review Classification — Eleven Madison Park

**HT-MGT 387 · University of Massachusetts Amherst**

**Team:** Miygul, Chloe, Brett, Jordanna, Akanksha Sharma

## Question
How reliable is ChatGPT at classifying the sentiment and themes of luxury-restaurant reviews, and what do accurately labeled reviews say about the business?

## Approach
1. Collected 100 TripAdvisor reviews of Eleven Madison Park, a three-Michelin-star restaurant in New York
2. Classified each review's sentiment (Positive / Mixed / Negative / Neutral) and themes with ChatGPT
3. Hand-verified every label
4. Built a formula-driven Excel dashboard (COUNTIF/COUNTIFS) comparing versions and breaking sentiment down by theme combination

## Results

| Sentiment | ChatGPT | Human-verified |
|---|---|---|
| Positive | 40% | 15% |
| Mixed | 23% | 67% |
| Negative | 15% | 6% |
| Neutral | 22% | 12% |

ChatGPT struggled with reviews that praised one aspect (usually service) while criticizing another (usually food or value), defaulting to a single polarity. Human review showed most guests hold mixed views.

## Recommendations to the restaurant
- **Food quality:** standardize preparation to fix inconsistency and over-seasoning
- **Value:** close the gap between price and perceived experience
- **Personalization:** tailor special-occasion experiences and take-away gifts
- **Service:** protect pacing and warmth during peak hours

## Files
- `AI_Experiment_HT-MGT_387_Final_Project_.pdf` — project write-up and recommendations
- `Sentiment_Analysis_Section4.pdf` — sentiment tables and theme breakdown

**Methods & tools:** Excel · ChatGPT · Sentiment analysis · Thematic coding · Data validation
