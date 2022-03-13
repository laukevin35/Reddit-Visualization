# Reddit-Visualization
Visualization of /rgameofthrones analyzing keyword mentions

On python using the PRAW function. I analyze the /rgameofthrones subreddit taking in different data such as the comments, descriptions, number of votes, number of comments and more. Using this information I looked at keyword mentions using if statements to measure how often certain character names are mentioned. The code will read all of the data from each post in this subreddit and will check for each characters name. Once a character's name is mentioned, one point will be added to the tracker for that character. The code keeps running, searching through all of the comments for a post untill either there are no more comments or when all characters name were already mentioned. Once either of these are true, the code will then move to the next post in the subreddit and repeat the same process.

Currently the code stops sometimes after running too many posts, so may require changes. Addittionally, the code takes a long time to run so may require a different method of coding to look at keywords in each post.
