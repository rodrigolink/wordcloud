# wordcloud
Creation of word clouds for the books in the series The Dark Tower, by Stephen King 

A word cloud is a collection, or cluster, of words depicted in different sizes. The bigger and bolder the word appears, the more often it’s mentioned within a given text and the more important it is.

The Dark Tower is a series of eight books and one short story written by American author Stephen King. Incorporating themes from multiple genres, including dark fantasy, science fantasy, horror, and Western, it describes a "gunslinger" and his quest toward a tower, the nature of which is both physical and metaphorical. The series, and its use of the Dark Tower, expands upon Stephen King's multiverse and in doing so, links together many of his other novels.

We have a collection of nine stories telling an epic tale of the gunslinger and his group of friends, his ka-tet, going to the Dark Tower, with more than four thousand pages. Besides that, we will also take a look at the poem that inspired Stephen King to write this series, "Childe Roland to the Dark Tower Came" by Robert Browning.

We want to visualize the frequency of the most common words in this series of books. We will generate a graph for each book and another for whe whole body of text. Our input data is composed of ten text files, one for each title.

We won't be doing any exploration analysis, but we have some guesses of what we expect as the most relevant words. For the poem, we don't have any prior knowledge. The first book is mainly a solo story, with the gunslinger follows the man in black and meets the boy Jake. For the other books, gunslinger and Roland are the main ways the main character is referred to. His companions are Jake, Eddie, Susannah and their pet Oy. This group is moving towards the Dark Tower. The short story and some of the books are recollections of memmories from Roland, so other names will pop up.

The process to create the visualizations is very straightforward. We will describe the step-by-step for the first text and then streamline the process for the others.

We see most of the words being repeated book after book. Let's take a look at the whole text and then we might revisit our graphs.

We have some words that show up in most of the graphs, but don't bring any insight to the story. One, back, said, now, time, hand, thought and looked will be added to a list of words that aren't considered for the visualization. These are known as stopwords, such as the and and, who are used too frequently to be of any help to the graph.

Let's also remove the name of the four main characters: Roland, Jake, Eddie and Susannah. Most of the time they are talking amongst themselves, so their names are too frequent.

We can improve it a little further by adding a mask to the graph. 

This is a data visualization exercise. There are eight books and one short story following the journey of a group of four people towards the Dark Tower. It is a small set of main characters, so we should remove their names to be able to get some new insights.

Final conclusion: we can present the distribution of relevant words for the Dark Tower Series in a pleasing and insightful visualization.
