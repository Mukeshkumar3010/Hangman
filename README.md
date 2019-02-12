# Hangman
Word game to let user guess the word picked randomly from data-set. This is the question from MIT course 6.001.
word.txt is text file serving as database to get list of words available.
You need to set the directory if placing the word.txt in different folder.
words are in lower letters. Use valid input as displayed/asked to enter.

# Hangman--Word to be guess by Computer
Word game to let computer guess the word thought by user, if word not present in word.txt then it will ask to add.
Please add valid word in lower case.
Follow the steps as stated above for # Hangman.
For testing purpose you can use below list and replacing the below line:-
        originalList = words.read().splitlines()
              with
        originalList = ['be', 'do', 'go', 'see', 'use', 'ask', 'try', 'few', 'bad', 'time', 'year', 
                'life', 'hand', 'part', 'good', 'rld', 'child', 
              'company', 'problem', 'different', 'important', 'government']
And adding # before below code:-
#words = open("words.txt", "r")
