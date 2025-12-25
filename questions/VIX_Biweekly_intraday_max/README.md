The question at hand is:

## What will be the maximum intraday value of the VIX over these biweekly periods in Q1 2026?

The link to this question on metaculus can be found here. 

https://www.metaculus.com/questions/41220/vix-biweekly-maximum-in-q1-2026/

This is a question that is being attempted as a part of the market pulse challenge 26Q1

To get some seasonal data in, there will be on jupyter file parsing through all VIX historical data to find the range of values that the VIX has gone through during the similar time period in previous years. 

At the same time, we must consider the alternate causes such as political, social, and global issues. We will first take the data from the CBOE VIX website linked here

https://www.cboe.com/tradable-products/vix/vix-historical-data

and we will consider the equation used to calculate the vix according to this website:

https://www.sfu.ca/~poitras/419_VIX.pdf

Looking at the data in VIX_History.csv and the question page, we only need to concern ourselves with the HIGH value. Thus, in cleaning the data, we should remove all data that isn't relevant in january (at least, for getting a range) and isn't recorded as a HIGH.

**End of Initial Thoughts**