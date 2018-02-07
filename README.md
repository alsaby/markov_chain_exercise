to run the code:

file2 =  open('') # the path to the input file 
import markov_text                                                                                                             
markov = markov_text.Markov(file2)                                                                                             
markov.generate_markov_text()       
