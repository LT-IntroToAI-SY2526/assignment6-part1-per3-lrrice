# Assignment 6 Part 1 - Writeup

**Name:** Levi Rice 
**Date:** 11/21/25

---

## Part 1: Understanding Your Model

### Question 1: R² Score Interpretation
What does the R² score tell you about your model? What does it mean if R² is close to 1? What if it's close to 0?

**YOUR ANSWER:**
The R² score is how important a factor is in influencing the outcome. It is read as a percent, so 0.5 would be 50%. If we got a  0.5 R² score, then hours studied would be responsible for 50% of your score. The closer to 1, the more impact the variable has, while a score closer to 0 would have almost no impact on the results.



---

### Question 2: Mean Squared Error (MSE)
What does the MSE (Mean Squared Error) mean in plain English? Why do you think we square the errors instead of just taking the average of the errors?

**YOUR ANSWER:**
You take the values of all discrepancies between predicted data and actual data, then square them and find the mean of all the numbers. The values are squared because it means that being off by a large amount once is worse than being off a little bit multiple times.



---

### Question 3: Model Reliability
Would you trust this model to predict a score for a student who studied 10 hours? Why or why not? Consider:
- What's the maximum hours in your dataset?
- What happens when you make predictions outside the range of your training data?

**YOUR ANSWER:**
I wouldn't trust it, because these models arent built for numbers outside their range, and tend to return nonsensical numbers when outside of them. Like if you cant get higher than  a 100 on a test, studying for a bilion hours wouldn't get you a score higher than 100, but the model would think so.



---

## Part 2: Data Analysis

### Question 4: Relationship Description
Looking at your scatter plot, describe the relationship between hours studied and test scores. Is it:
- Strong or weak?
- Linear or non-linear?
- Positive or negative?

**YOUR ANSWER:**
Somethin is up with my path and I couldn't run my code because of an import error



---

### Question 5: Real-World Limitations
What are some real-world factors that could affect test scores that this model doesn't account for? List at least 3 factors.

**YOUR ANSWER:**
1. Hours of sleep the night before
2. What you studied
3. Time to take the test itself


---

## Part 3: Code Reflection

### Question 6: Train/Test Split
Why do we split our data into training and testing sets? What would happen if we trained and tested on the same data?

**YOUR ANSWER:**
Then the model would be affected by the test data which is not as accurate, which would skew the model randomly. You need to establish a baseline the model can reference before you test any kind of data that isnt made for training or you could throw off your model.



---

### Question 7: Most Challenging Part
What was the most challenging part of this assignment for you? How did you overcome it (or what help do you still need)?

**YOUR ANSWER:**
I recieved an error when running my code. Something was wrong with the pandas import and the pathing that I didn't know how to resolve. I didn't have time to ask you about it on thursday when you were here and can't fully finish the assignment without it.



---

## Part 4: Extending Your Learning

### Question 8: Future Applications
Describe one real-world problem you could solve with linear regression. What would be your:
- **Feature (X):** 
- **Target (Y):** 
- **Why this relationship might be linear:**

**YOUR ANSWER:**




---

## Grading Checklist (for your reference)

Before submitting, make sure you have:
- [x] Completed all functions in `a6_part1.py`
- [ ] Generated and saved `scatter_plot.png`
- [ ] Generated and saved `predictions_plot.png`
- [x] Answered all questions in this writeup with thoughtful responses
- [x] Pushed all files to GitHub (code, plots, and this writeup)

---

## Optional: Extra Credit (+2 points)

If you want to challenge yourself, modify your code to:
1. Try different train/test split ratios (60/40, 70/30, 90/10)
2. Record the R² score for each split
3. Explain below which split ratio worked best and why you think that is

**YOUR ANSWER:**
