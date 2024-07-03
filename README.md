# Warby-Parker
Warby Parker Marketing Funnel Analysis

Introduction
Project Goal:
The goal of this project is to analyze the user journey through Warby Parker's marketing funnel, from taking the quiz to making a purchase. By understanding user behavior at each step, we aim to identify key drop-off points and opportunities for improving conversion rates.
This report will help Warby Parker optimize its marketing strategies, enhance user experience, and ultimately increase sales. By pinpointing where users drop off, the company can make data-driven decisions to streamline the funnel and retain more potential customers.

Analysis Steps:
1. Inspecting the structure of the `survey` table to understand the questions asked in the quiz.
2. Analyzing response counts for each quiz question to identify drop-off points.
3. Calculating completion rates for each question.
4. Inspecting the `quiz`, `home_try_on`, and `purchase` tables to understand their structures.
5. Creating a new table to track the user journey through the funnel using LEFT JOINs.
6. Analyzing conversion rates from quiz to home try-on and from home try-on to purchase.
7. Investigating the impact of the number of pairs tried on home try-on conversion rates.

Results
Key Metrics:
Quiz Completion Rates:
  - Notable drop-off at each subsequent question.
  - Highest drop-off observed between the second and third questions.

Impact of Number of Pairs:
  - Higher number of pairs tried correlates with higher purchase rates.

Conclusion and Recommendations

Conclusions:
- The quiz has significant drop-off points that need addressing to improve user retention.
- The home try-on program is effective, but conversion rates could be improved by understanding user preferences better.

Recommendations:
1. Optimize Quiz Questions:
   - Simplify or rephrase questions with high drop-off rates.
   - Consider reducing the number of mandatory questions.

2. Enhance Home Try-On Experience:
   - Offer personalized suggestions based on quiz results to encourage users to try more pairs.
   - Provide incentives for users who reach the home try-on stage.

3. Overall Funnel Improvements:
   - Implement follow-up strategies for users who drop off at various stages (e.g., reminder emails, targeted ads).
   - Use data from successful conversions to refine marketing and product recommendations.

4. Targeted Interventions:
   - Develop targeted campaigns for users who drop off at specific stages with personalized offers and reminders.

