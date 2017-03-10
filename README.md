# Chat corpus repository

This is a chat corpus collection from various open sources, 
all files are composed of question-answer pairs,  
where odd lines are questions, even lines are answers.

I use them for training chatbot on seq2seq model.  
theory: [http://arxiv.org/abs/1406.1078](http://arxiv.org/abs/1406.1078)  
implementation: [https://github.com/Marsan-Ma/tf_chatbot_seq2seq_antilm.git](https://github.com/Marsan-Ma/tf_chatbot_seq2seq_antilm.git)


## 1. open_subtitles

English movie subtitles parsed from  
[http://opus.lingfil.uu.se/download.php?f=OpenSubtitles/en.tar.gz](http://opus.lingfil.uu.se/download.php?f=OpenSubtitles/en.tar.gz)

## 2. movie_subtitles_en

Cornell Movie-Dialogs Corpus  
[http://www.mpi-sws.org/~cristian/Cornell_Movie-Dialogs_Corpus.html](http://www.mpi-sws.org/~cristian/Cornell_Movie-Dialogs_Corpus.html)  


## 3. lyrics_zh

lyrics from PTT forum  
[https://www.ptt.cc/bbs/lyrics/index.html](https://www.ptt.cc/bbs/lyrics/index.html)


## 4. twitter_en

corpus scrap from twitter, where odd lines are tweet and even lines are corresponding responded tweets.   
actually you could scrape your own with my [twitter scraper repository](https://github.com/Marsan-Ma/twitter_scraper)
