#the main function will parse argument via the parser variable. These 
#argument will be define by the user on the console. 
#correctly pass the arguments. 

def main () :
Parser = argparse. Argumentparser () 
Parser. Add argument (
     "Word", 
      help=" the word to be searched for in the text file." 
) 
Parser. add argument (
      "filename", 
      help=" the path to the text file to be searched through "
) 
