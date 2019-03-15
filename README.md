# Goal
Try to determine what factors make a joke funny. Is there a specific topic? Is there certain structure?

# Overview
Humor is one of the most subjective forms of entertainment out there. Whether you watch stand up comedy, consider yourself something of a jokestar, or just enjoy to laugh you are aware that not everyone finds the same things funny. A simple one line joke may make one person laugh and offend another person. With that in mind, is there something that Natural Language Processing can tell us about jokes that is hidden from out conscious minds? Using a variety of machine learning models we wanted to explore if there are identifiable trends that can predict if a joke is deemed funny or not.

# Dataset
So as I just mentioned jokes and humor is a very subjective matter. The goal was to try and approach this from the most objective way possible, as difficult as removing our own humor-based biases turned out to be.
We found a data set that took posts from the subreddit [r/jokes](https://www.reddit.com/r/Jokes/) on the website [reddit](https://www.reddit.com/) that included over 100,000 different jokes. This site is structured so that you can select different subreddits to specify a topic or subject you want to view. So, the jokes subreddit is where users submit a joke and subsequently other user 'upvote' that joke if they liked it. We utilized this to assume that if a joke had an upvote that indivual who upvoted found that joke funny.

# Data Processing

