# lyric-generation
lyric generation using markov chains
in this we store the instance of group of words in a table and its next word into ints diffrent column
we count how many the the gourp of preceded by the same next word 
then we find the probability of the next word based on the occurence next to group of words 
so next time we see the group of words we know which is the most probable word comes next to them
in program k repersents the no.of words taken into consideration
we make dictionary based on the occurence and the find the next state based on the past states
genrate_text function computes ont dictionary made with the data in dataset and predict the nect word
