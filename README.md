# Text-Summarizer
The aim of our project is to summarize an audio message by converting it into text and deliver a short summary about the context of the audio. The project requires us to study two new libraries as well as perform the basic operations of Natural Language processing such as tokenization and parts of speech. Below are the new libraries which were involved:
Whisper- is used convert any audio to text. It works similar to google text to speech. It has the ability to convert around 100 languages.
Textblob- it is used to divide the words as well give tag to them where tags represent the parts of speech meaning whether the word is noun, adjective etc. if the word is unnecessary it will be removed.
Spacy- NLP uses spacy to extract information from our dataset. Here we use entity ruler which helps us add spaces between phrases so we can extract it with higher accuracy.
After converting our audio to text, we load it in our jupyter notebook, we use parts of speech tagging to figure out what kind of words they are so that we can later form a dictionary where tags as values and words as keys and finally remove unnecessary words.
we also did sentence and word tokeinization and used TFIDF vectotizer which offers us accurate importance of words. we select the words with most importance and our initial text is reduced to one third amount giving us the summary.
