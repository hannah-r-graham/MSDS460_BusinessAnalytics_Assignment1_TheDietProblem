# MSDS460_BusinessAnalytics_fall2024

##Goal
This assignment takes 5 labelled foods and completes a linear programming problem 1) fulfill nutritional constraints over the week 2) fulfill nutritional constraints and diversity constraints of at least 1 occurence of each item in the week 3) attempts to repeat experiments with Microsoft Copilot. 

##Results:
1) satisfy nutriitonal paramaters listed below:
  Results (number of servings in the week):
  status=Optimal
  Beans = 70.175
  Chips = 13.405
  Salmon = 12.727273
  Sauce = 0.0
  Yogurt = 32.518182
  Objective = 86.07318579 (dollars)

Results review: 
Seems very boring but very cheap. Being able to have the sauce would be nice. That is an excessive amount of beans - 10 servings a day!

3) satisfy nutritional parameters AND have at least 1 serving of each food item in the week
   Results (servings per week): 
  status=Optimal
  Beans = 69.6575
  Chips = 13.1645
  Salmon = 12.727273
  Sauce = 1.0
  Yogurt = 32.548182
  Objective = 86.27434454 (dollars_
Results review:
At least this has a bit more diversity. Program really doesn't like the sauce as it gave it the bare minimum. Still quite a bit of beans. 

3)Microsoft Copilot results:
  Results are close but slightly different than what I got in my part 3. 
  Optimal servings:
  beans: 70.175
  chips: 13.405
  salmon: 12.727273
  sauce: 0.0
  yogurt: 32.518182
  Total cost: 86.07318579

GPT Results Review: 
GPT first wanted to use the daily allotment and not week, so had to redo those. It also defaulted to maximize function when we are trying to minimize costs so I had to manually modify that. Otherwise, for part 3 the results were identical when using GPT code, however, they were not correct right out of the gate. The AI generated code still needed human intervention.



-------------------------

Foods and their nutritional facts:

Constraints:


