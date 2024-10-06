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
Food	Price per serving	Sodium (mg)	Energy (cal)	Protein (g)	Vitamin D (mcg)	Calcium (mg)	Iron (mg)	Potassium (mg)
Juanitas Tortilla Chips	0.25	160 	150	1	0	0	0.5	0
Bitchin’ Sauce	0.487	105	90	2	0	15	1	77
Kirkland Plain Greek Yogurt	0.92	60	100	18	0	190	0	190
Kirkland canned pink Salmon	1.45	240	80	17	11	9	0	320
Kirkland Organic Black Beans	0.4895	85	110	7	0	40	1.7	410


Constraints:

Component	Max/Min	Daily Amount and Measure	Weekly Conversion
Sodium	Maximum	5,000 milligrams (mg)	35,0000 milligrams (mg)
Energy	Minimum	2,000 Calories (kilocalories, kcal)	14,000 Calories (kilocalories, kcal)
Protein	Minimum	50 grams (g)	350 grams (g)
Vitamin D	Minimum	20 micrograms (mcg)	140 micrograms (mcg)
Calcium	Minimum	1,300 milligrams (mg)	9,100 milligrams (mg)
Iron	Minimum	18 milligrams (mg)	126 milligrams (mg)
Potassium	Minimum	4,700 milligrams (mg)	32,900 milligrams (mg)

