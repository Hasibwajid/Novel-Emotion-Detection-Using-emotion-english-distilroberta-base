# Novel-Emotion-Detection-Using-emotion-english-distilroberta-base
Analyzes emotions in text chunks per chapter using a sentiment analysis model, visualizing scores across chunks as line graphs. Includes pie charts showing dominant emotions per chapter, enhancing understanding of emotional variations in text chunks. Developed using Transformers library.



# Overview:
This tool performs emotion analysis on text chunks within chapters of novels using a sentiment analysis model. It displays line graphs representing emotion scores across these chunks and pie charts showing dominant emotions per chapter. Developed using the Transformers library, it enhances the comprehension of emotional nuances in literary works.

![image](https://github.com/Hasibwajid/Novel-s-Emotion-Detection-Using-emotion-english-distilroberta-base/assets/72168225/88a4a527-13e5-4d3d-bb90-36b092410dc1)

# Accessing and Applying on Different Novels/Data/Text:
The tool can be applied to various novels by segmenting their text into chapters and chunks. Access the text data of the novels, preprocess it, and utilize the tool to perform emotion analysis. The pipeline uses an emotion analysis model from the Transformers library, allowing easy implementation for emotional analysis across different literary works.

# Format 
ALl you need to do is to change the path, to the path of your txt file also make sure the format must be as:

Chapter-1
[Text for Chapter 1 goes here]
Chapter-2
[Text for Chapter 2 goes here]
...

Each chapter begins with a line denoting 'Chapter-i' (where 'i' represents the chapter number), followed by the text content for that chapter. This format helps the tool to identify and segment the text into chapters for further analysis.

