# Basic-Queries
Practice projects taken from Coddy

# Challenge 1

You have a cyber security firm that experienced an arbitrary attack, resulting in all of your systems shutting down. To solve this issue, you need to identify all of the events that appear suspicious.

 A suspicious event meets one or more of the following criteria:

1. Its size is significantly different from the average normal event size of 50MB (you'll need to analyze the data in the table to determine the thresholds for 'too small' and 'too big')
2. It was created before the year 2000
3. It has a missing name

Your task:

1. Examine the provided table of events to determine what should be considered 'too small' or 'too big' based on the distribution of event sizes.
2. Identify all suspicious events based on the criteria mentioned above.
3. Return the event IDs and their names in descending order by their ID.

Note: The exact thresholds for 'too small' and 'too big' should be inferred from the data. Look for patterns or outliers in the event sizes to make this determination."

# Challenge 2

Fetch all of the cellphone models that start with the letter m and the 3rd letter is o, the price range is between 1000 and 1500, and they support 5G.

Return only the cellphone model and replace the name to id