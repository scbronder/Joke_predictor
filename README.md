# Goal
Try to determine what factors make a joke funny. Is there a specific topic? Is there certain structure?

# Overview
Humor is one of the most subjective forms of entertainment out there. Whether you watch stand up comedy, consider yourself something of a jokestar, or just enjoy to laugh you are aware that not everyone finds the same things funny. A simple one line joke may make one person laugh and offend another person. With that in mind, is there something that Natural Language Processing can tell us about jokes that is hidden from out conscious minds? Using a variety of machine learning models we wanted to explore if there are identifiable trends that can predict if a joke is deemed funny or not.

# Dataset
So as I just mentioned jokes and humor is a very subjective matter. The goal was to try and approach this from the most objective way possible, as difficult as removing our own humor-based biases turned out to be.
We found a data set that took posts from the subreddit [r/jokes](https://www.reddit.com/r/Jokes/) on the website [reddit](https://www.reddit.com/) that included over 100,000 different jokes. This site is structured so that you can select different subreddits to specify a topic or subject you want to view. So, the jokes subreddit is where users submit a joke and subsequently other user 'upvote' that joke if they liked it. We utilized this to assume that if a joke had an upvote that indivual who upvoted found that joke funny.

# Data Processing
The data processing was set up in a way so that we could go back and alter how we wanted to clean our data and as a result be able to determine how this would affect the models that we ran. This cleaninng process included using regex to lowercase all words and then alternating between either stemming or using lemmatization to remove stop words and identify the root words being used (returning run from runs, running, ran etc.). At this point a dataframe was created to include the jokes we had  cleaned along with the 'score' that they were assigned. 

![alt text](https://github.com/scbronder/Joke_predictor/blob/master/visuals/Screen%20Shot%202019-03-15%20at%2011.21.49%20AM.png)

Analysis of the jokes revealed several trends
