# PG-FIRST-YEAR-PROJECT
Keyword Search method are among the most widely used and vetted methodologies available. They should be considered as part of any comprehensive search and identification undertaking 
when searching for potentially relevant  data.We take this mini project “DATA ANALYTICS KEYWORDS” to find keywords from text manner of text regular documents and business reports, 
social media comments, online forms and reviews, news reports ,and more. We used R Studio tool for predicting.Keyword extraction you can find the most important words and phrases
in massive datasets in just seconds. And these words and phrases can provide valuable insights into topics your customer are talking about. Making it extremely difficult to analyse
and process business need automated keyword extraction to help them process and analyse customer data in a more efficient manner.In this project, we used NLP it can be understood 
and analysed by machine. In that, used show visualization of a text’s most frequently used words in word cloud generator.


code explaination


Brief Explanation of the R code:
1. Package Installation and Loading:

Installs necessary packages for text mining, word cloud generation, and color palettes.
Loads relevant libraries: tm, wordcloud2, and RColorBrewer.
Sets the working directory to the folder containing the text file.
2. Text File Processing:

Reads the text file "data_science__big_data_analysis.txt" into a variable text.
Creates a corpus object docs from the text.
Prints basic information about the corpus using inspect.
3. Text Cleaning and Transformation:

Replaces special characters like "/", "@", and "|" with spaces using custom function toSpace.
Converts all text to lowercase.
Removes numbers, English stop words, and additional stop words ("blabla1", "blabla2").
Removes punctuation marks.
Eliminates extra white spaces.
4. Document-Term Matrix and Word Frequency:

Builds a document-term matrix (DTM) representing word occurrences in each document.
Extracts the word frequencies and sorts them in descending order.
Creates a data frame word_1 containing words and their frequencies.
5. Word Cloud Generation:

Uses wordcloud2 to generate a word cloud based on the word_1 data frame.
Sets various parameters like letter size, rotation, color, and background color to customize the word cloud.
Overall, the code performs text cleaning, transformation, and analysis to generate a word cloud highlighting the most frequent words in the input text file. It provides insights into the text's key themes and vocabulary.
