# Captain Holt's Brain Teaser Solution: 

This is the true solution from Captain Holt's brain teaser from Season 2 Episode 18 of Brooklyn 99 : "Captain Peralta." Before you read on, I just want to say that this problem drove me nuts. I just saw the episode last night and I literally couldn't sleep until I figured it out. I was lying there going through possibilities until 3 am when it hit me, and I got up and wrote down the solution. I later went back and refined it a little, so here it is. Hope you all sleep well after reading this. 

![Alt text](http://31.media.tumblr.com/cbacd818b46c49da33d64965591a7419/tumblr_mz2j20XaOA1r64iyzo3_250.gif)

## The problem : 
There are 12 men on an island. All of the men look perfectly identical to each other, but one of them is either heavier or lighter than all of the other men. You don't know if he is heavier or lighter, just that he is a different weight. There is also a see-saw on the island. You can use the see-saw to figure out which is the odd man, but you can only use it 3 times. 

Now GO!

*** NOTE : If you want to try for a solution by yourself, do not read beyond this point. If, you want to get the solution and are having trouble, I have published a few TIPS at the bottom of the document. Happy problem solving. 

## Step 1 : 
* Number the men from 1 to 12. Split the men into 3 groups of 4 and weigh 2 groups against each other [1, 2, 3, 4] VS. [5, 6, 7, 8]. 
	1. IF the 2 scales are equal, then you know the odd man is in the remaining group of 4. Proceed to solution 1a. 
	2. IF the 2 scales are unequal, then you know the odd man is in the set of 1-8. Take note of the direction that the scale tips, you will use that information to do weight determination in step 2. Proceed to step 2. 

## Step 2 : 
* Shift all of the men 3 positions to the right and weigh them again using men from the 3rd group (which you know to all be neutral) to fill in the missing positions on the left scale. [10, 11, 12, 1] VS. [2, 3, 4, 5]. 
	1. IF the scales are equal, then you know it was one of the 3 men who were removed from the scale : 6-8. Use the weight difference from step 1 to determine heavier lighter. Proceed to solution 2a. 
	2. IF the scales are unequal, but the balance of weight changes (ie. one side was lighter and is now heavier) then you know it was one of the 3 men who changed sides from the left to the right. Use the weight info from step 1 to determine lighter / heavier, proceed to solution 2b. 
	3. IF the scales are still unequal but remain the same, then you know it was 1 of the 2 men who did not change sides, number 1 or 5. You cannot determine lighter, heavier, proceed to solution 2c. 

## Solutions : 
* Solution 1a. The first measurement of 4 vs. 4 was equal. The odd man is in the group is in 9-12. You don't know if he is heavier or lighter, and there is a 2 step solution to this : 
	* Take 3 men from the group and measure against 3 neutral men from 1-8. [9, 10, 11] VS. [1, 2, 3]. 
		* IF the measurement is equal then the odd man is 12. You don't know heavier or lighter, but you still have 1 remaining move. 
			* Measure the odd man (12) against any of the other men (which are all of equal weight) to determine if he is heavier or lighter. 
		* IF the scale is unequal, then you know the odd man is within the group 8-11. Take note of whether it is heavier or lighter. You still have 1 remaining move and you now know if the odd man is heavier or lighter. 
			* {{3 remaining with known weight solution}}  Since the weight is known, all you need to do is measure 2 men from the remaining 3 against each other. There are 2 possible outcomes, either they are equal, or unequal. 
				* If they are equal, it is the remaining man not being measured. 
				* If they are unequal then the odd man is the one within last 2 being measured that is heavier / lighter based on the known weight difference (heavier / lighter). 

* Solution 2a. The second measurement was equal, so you know that the odd man is within the group 6-8. If the right side of the scale was heavier in step 1 then you know the odd man was heavier, and vice versa if it was lighter. 
	* Use the {{3 remaining with known weight solution}} from solution 1a. 

* Solution 2b. The second measurement was unequal, but the balance of weight shifted. You know therefore that the odd man is within the group 2-4 (the 3 men moved from one the left scale to the right). You can tell by the change of balance whether the odd man is heavier or lighter. 
	* Use the {{3 remaining with known weight solution}} from solution 1a. 

* Solution 2c. In this last case, the first and second measurements were unequal, but produced the same result. Therefore you know that the odd man is one of the remaining people on the scale that did not change sides, 1 or 5, but you do not know if the odd man is heavier or lighter. 
	* Weigh the lighter of the 2 men against any other neutral man. If they are equal then it is the one not being measured and he is heavier. If he is lighter then it is the one being measured and he is lighter. 




# TIPS : 

* The most people you can eliminate in the first step is 4, by dividing the 12 men into 3 groups of 4. 
* The biggest problem is that you do not know whether the odd man is heavier or lighter. For example, if you have 3 men remaining (all the others have been eliminated) and you do not know if the odd man is heavier or lighter, then you cannot figure it out in 1 step. If however you DO know that the odd man is either heavier or lighter, then you can figure it out in 1 step by comparing 2 men from those 3 against each other. 
* Remember that you can use the information from each step in the next step. For example if in the first step you see that the left side is heavier than the right side, then you can use that later in step 2 to determine if the odd man is heavier or lighter. 
* SPOILER ALERT! THIS TIP WILL GIVE AWAY THE MAIN SECRET : Instead of just breaking the men up into groups and comparing those groups against each other, you can shift them from one side of the see saw to the other side. ie. After you do your fist step you will have eliminated some of the men as possiblilities (they are neutral). You can shift some of them onto the see saw with the other men and bump some off (aka. shift). Try that and see where it takes you. 