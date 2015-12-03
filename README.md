## chains    
Simple Markov Chains text generator    

### usage
1) git clone    

2) from src/     
$ javac *.java     
$ Chainme f=corpus-file-name n=ngram-size i=sampling-iterations     

example:     
$ Chainme f=corpus1.txt n=3 i=10000      
Will generate 3gram chains with 10000 sampling iterations    

The location of the corpus file should be specified with a full path, or alternatively     
put it inside the working directory.    
