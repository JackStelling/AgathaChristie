

Hi there,

You'll probably want to investigate the 'TweetTokenizer.ipynb' code file.  


I've included code where I performed manual tokenization called 'LanguageModel.ipynb' and generated 
some meaningful results.The TweetTokenizer scripts build upon these foundation ideas and start to explore 
improving sentence syntax by keeping some punctuation and capitalisation in the generated results. The 
first code booklet details all the hyperparameter tuning analysis that was carried out and the reasons 
behind them. I've included some text files so you don't have to generate them yourself and can jump in 
at the code halfway through. These include the 'Poirot_Sequences_TweetTokenizer' and Train, Test text 
files used in the analysis. Some of the partial paths in the script may need altered depending on where 
it is that you save these files.

Inside the ModelWeights folder I've included the best model wieghts for both the manual tokenization
and the tweetTokenizer with the respective Tokenizer file saved as a pickle. These documents should run 
from top to bottom smoothly as steps are carried out in a linear fashion. At the end of each code document
is a function which, given some text as input generates text from the trained model. 


Enjoy,
Jack.  