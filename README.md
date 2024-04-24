# Python-Iterations

Spotify headquarters are trying to determine the best way to store data about their artists, their popularity, and listner preferences.

1. Create a list using the following artists names: 'Weird Al', 'Bruno Mars', 'Ricky Martin', 'HP Boyz', 'James Blunt', 'Ne-Yo', 'Paul McCartney', 'Little River Band'. Sort it from Z-A. Output the resulting list.

2. Add 'Juice Wrld' in the 3rd position of the list (do not remove any of the the current list items). Output the resulting list

3. Make a dictionary that has the artist name as the key and the number of plays at the value. Accomplish this task by iterating through the artist list (from question 2) to populate the dictionary with the play counts you see below.

Hint: Using the plays information below, create a list of plays where the order of plays matches the order of the artists in the artist list. Then, iterate through the artist list and add each artist (key) / play count (value) to a new dictionary one-at-a-time

Output the resulting dictionary by looping through it a print out each key and value in the format below (minus the bullet points):

Weird Al = 1234821 plays
Ricky Martin = 600000 plays
Juice Wrld = 38765432 plays
Paul McCartney = 98879838 plays
Ne-Yo = 20000 plays
Little River Band = 100 plays
James Blunt = 974545 plays
HP Boyz = 45000 plays
Bruno Mars = 85279 plays

4. Due to technical errors this month all artists lost count of 100 plays. Loop through the artist dictionary (from question 3) and add 100 to the count of plays for all artists.Print the dictionary in any format that includes all keys and values.

5. Delete all artists that do not have a user-specified number of plays. In other words, ask the user for the minimum play count and then remove all dictionary entries that do not meet the minimum. RULE: You must use a loop to find artists below the minimum play count in case the dictionary is ever modified.

HINT: You will need two separate loops: one loop to identify those less than the minimum and another to remove each of those identified from the dictionary. This is because you can't modify a dictionary while you are iterating through it.

Print the resulting dictionary after running the code using 50000 as the minimum threshold.

6. Isaac and Grays are two listener profiles. Below is a dictionary for Isaac and a dictionary for Grays. 'fav_Artist' is the key and a list of preferred artists are the values. Also below is the all_Artists list. This is a list of all available artists. Isaac likes 'Little River Band', 'Jackson 5', 'HP Boyz', and 'Ne-Yo'. Grays likes all the other artists listed in the all_Artists list (he doesn't like the artists in Isaac's list). Use a loop to update Graysons fav_Artists (update the values to the key 'fav_Artists')

HINT: You may want to use 'not in' to find Grays's preferred artists.

Output Grays and Isacc's list of perferred bands.

7. For both Issac and Grays, calculate the total artist plays (the sum of the plays of all their favorite artists). For example, calculate the sum of the number of plays for Little River Band, Juice Wrld, HP Boyz and Ne-Yo to find the total plays for Isaac.

Make a new 'all_plays' key in the Isaac dictionary and the Grays dictionary. Insert the total plays of all their favorite artists as the value of the 'all_plays' key.

NOTE: Before you run this block of code, run question 3 again to repopulate the artist dictionary. If you ran question 3, but than ran question 4 and 5, you will get an error because questions 4 and 5 make changes to the dictionary. Just push the 'play' button next to question 3 to run it again.

Output the resulting dictionaries.

According to the counts produced after creating the code for the prior question, who likes more popular music? (i.e. which profile had the most total plays?)
