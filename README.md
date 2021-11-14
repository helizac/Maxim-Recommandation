# Maxim Recommandation

The idea of the project is to create a simple maxim recommendation engine based on user response.

## Contents

```
1 - Introduction
2 - Project Architecture
3 - Results
4 - Conclusion and Future Work
```

## Introduction
~~~
The idea of the project is to create a simple maxim recommendation engine based on user response.
And can be used in real world as a tool that people can use to find maxims which they forget some words of the maxim.

For exemple:
  Someone wants to use "What's good for the goose is good for the gander" sentence.
  But can't remember which word the sentence ends with like "What's good for the goose is good for the ..."
  So he/she can enter the answer to maxim recommendation engine "What's good for the goose is good for the"
  And engine returns "What's good for the goose is good for the gander"
  
That's the general idea.
~~~

## Project Architecture

The database is separated from the main file to make the code more readable. Therefore, the following file structure is used.
```
app
  video.mp4
  favicon.png
  files.py #that contains titles, sentences and some html & css
  trmodel #pre-trained Turkish model
  turkish_stop_words.txt #Words that have no meaning on their own in Turkish to be excluded from the calculation.
main.py
requirements.txt
README.md
```

For this project there are several libraries that need to be installed in the terminal.
Use pip3 or pip for install packages.

```bash
pip install gensim
pip install numpy
pip install pandas
pip install scikit_learn
pip install streamlit
```

