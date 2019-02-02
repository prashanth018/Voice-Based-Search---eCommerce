Our aim was to build a voice based search engine which queries the e-commerce data base and gives out the result

Please unzip the wiki-short.zip file in the data folder before running the main.py(This is inconvenience is because git doesnt allow more than 100 mb file upload)

Tasks to be done:


Task 1: Write a Speech to text converter.<br />
Status: Pending<br />
Priority: Very High<br />


Task 2: Parts of speech tagger on the text obtained from Task 1(includes writing methods to clean the data after POS tags, also task *doesnt involve stemming and tokenization*).<br />
Status: Pending<br />
Priority: High<br />


Task 3: Find the words similar to given word<br />
Status: Done<br />
Overview: Achieved using word2vec implementation https://github.com/mkonicek/nlp, cleansed the code to get the required result.<br />
Priority: High<br />


Task 4: Do a sentiment Analysis over the *words* obtained from Task 3 and select the words in such a way that it matches the sentiment of the given word.<br />
Status: Pending<br />
Priority: Medium<br />
UseCase: searching for words like *new* gives words like *old,worn* which have an opposite sentiment, so we need to filter out these words.<br />
We are not supposed to search for old when user asks for something new.<br />


Task 5: Given Product Description(text), you need to get the list of key words which are then tokenized and stemmed and serialized to a File.<br />
This task involves the Task taker to implement a Product class which will serialize the Product data to a file(back and forth) whenever wanted.(This task is similar to that of Task 2)<br />
Status: Pending<br />
Priority: Very High<br />


Task 6: tokenize and stem the words obtained from Task 4 and Writing an Algorithm(TBD) to search the stemmed words over the Product File(details in Task 5).<br />
Prereq: Task 5 to be completed.<br />
Status: Pending.<br />
Priority: High<br />


Will Soon create issues for all the above tasks.
Lot of tasks are yet to come and also to be discussed(website creation, plugging the search, rendering of the Products.)


Special thanks to mkonicek for his wonderful implementation to find the similar words on the word2vec data.
https://github.com/mkonicek/nlp

