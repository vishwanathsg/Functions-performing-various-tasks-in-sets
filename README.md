# Functions-performing-various-tasks-in-sets
This is a code that has different functions used for desired actions

#Problem - I

sentence = "Hey I am walking here I am walking here o captain my captain water water everywhere nor a drop to drink"
print(sentence, "\n")

# split sentence into list of words
sentence_list = sentence.split() #s.split() function differentiates a string into seperate list of words
print(sentence_list, '\n')

# convert list to set to get unique words
sentence_set = set(sentence_list) #set() function converts any list into a set, i.e neglects the repeated words
print(sentence_set, '\n')

# print the number of unique words
num_unique = len(sentence_set) #len() tells the total number of elements present in a set, list, etc without bothering about their form (for ex. char, int, etc)
print(num_unique, '\n')
