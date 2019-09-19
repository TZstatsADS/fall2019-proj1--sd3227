# Sen Dai sd3227 Project1
Nowadays, everyone loves to listen to music. They not only love the melody, but also love the lyrics. However, different genres of music have different type of lyrics. The interesting thing is, that we can get lots of hints from analyzing the lyrics instead of listening the music. To get the secret of the lyrics, I decide to analysis some lyrics of different genres from 1970s to 2010s by using R. I only foucs on three aspect:
    1.What's the popular genres of music in different decades? 
    2.What's the difference of lyrics in different genres of music? 
    3.What's the habit of the artist to write the lyrics?Are they Shakespeare or Dumas?
    I analysis the data by different methods and get lots of interesting results.I'll show what i did step by step and tell a fantastic "data story".  
    
Firstly, I load all the required libraries.

Secondly, I load and clean the data for future use.
 Rightnow,I get a question. I really want to know what kind of music do people love at differet decades. To solve this question, I plot some graphs to get the answer. 
   
   From Fig1.1, we can see that different type of music at different decades.It's difficult to know what kind of music do people like from 1970s to 1990s since the data is not enough. We can easily find out Rock is the most popular music in 2000s, the second popular one is Pop and the third one is Metal. However, in 2010s, the third popular changed from Metal to Hip Hop. Hence we can see that with the time, listener change their preference, but not a lot. 
![image](https://github.com/TZstatsADS/fall2019-proj1--sd3227/blob/master/figs/fig1.1.JPG)
    
   From Fig1.2, we can see that before 2000s, the number of music is just a little. However there are lots of music released in 2000s, and the number of music decrease in 2010s. Maybe there were something happen in 2000s that stimulated the music market. For my own experience, I begin to listen American music in 2005. I think this rocket in 2000s because of the Internet. People can get the music easily on the Internet. 
![image](https://github.com/TZstatsADS/fall2019-proj1--sd3227/blob/master/figs/fig1.2.JPG)
 
   From Fig1.3, we can get some general information about each genres of music. For example, Rock is the most popular type of music no matter in which decades; More and more people begin to listen Hip-Hop, Electronic and Metal; Recently, R&B is not as popular as before; Just a few people is interested in Indie no matter in which decades.
 ![image](https://github.com/TZstatsADS/fall2019-proj1--sd3227/blob/master/figs/fig1.3.JPG)
    After this three figures, we can get some basic information about the lyrics from 1970s to 2010s. However, to get more interesting things, we need to do more analyzing.
    
   Suddenly, another question pop in my mind. What are the lyrics really talk about? Do the different genres tell the same kind of story of music or different? To solve this problem, I begin a new analyzing.
   
   To get what kind of word is the popular word in different genres, I try to get the 50 top high frequency word for each genres.In this way we can analysis the high frequency word and compare with each other to find the secret behind the lyrics. Rightnow, I'll post the top 50 frequency word for each genres music:
    ![image](https://github.com/TZstatsADS/fall2019-proj1--sd3227/blob/master/figs/fig%20backup.png)
     From the data, we can find lots of interest things. Firstly, we can see that love is the most common word in each type of music. I think this is because music is a way for people to express the emotion. Artists like to show what they love in the song(a person,a luxury car, a kind of spirit,etc). Secondly, baby is a very interest word in the lyrics, lots of music like this word. we can see that baby is not in the top 50 word only at Metal. Hence we can surmise that Metal music talk more about spirit and soul instead of love,friend and family. Thirdly, lyrics can be the icon for different type of music. I want to talk two typical example, one is about Hip-Hop music, We know the Hip-Hop music is about sex,drug and money. Hence there are lots of nasty and violent word in Hip-Hop music: shit, bitch, ass, beat, money and so on. It's a kind of icon for Hip-Hop cause it's impossible for people to get "bitch" and "ass" from Country music. For Metal music, it's similar: hell,fire,burn,blood,black,kill are the typical words in Metal. Metal music is kind of aggressive and loud. It's really strange for people to get "blood" and "hell" from Pop music. Fourthly, there are lots of things we can talk about the word frequency in difference genres of music. However, what i want to talk is about the prediction of the creation of lyrics. I get some inspiration from this analyzing, in the future, we can use programming to create lyrics by mechine learning or somethingelse. In this way, maybe we can get some more beautiful lyrics created by AI instead of human being. 
     
   After this analyzing, I still get one more question. What's the level and habit of these artist? Are they clever writers or just middle school level? To get the answer, I plan to analysis the lexical diversity and lexical density for these lyrics. Lexical diversity is to use measure the variety of vocabulary. The more varied vocabulary in the lyrics, the higher lexical diversity. 
  
  Fig2.1 is the graph about the index of lexical diversity of each songs in each year. We can see that before 2000, the lexical diversity is very low. However, after 2000, the lexical diversity becomes higher than before. We can also see the trend of the blue line is going up slightly. In another word, artists open their mind and use more new word in there song. There is a rocket in 2007 and it back to an average level. I think at this time, more and more artists try the new style of their songs and there be something that push the development of music from 2000s to 2010s. I think it's good for the development of american music because more and more artists try the new things and make progress.
  ![image](https://github.com/TZstatsADS/fall2019-proj1--sd3227/blob/master/figs/fig2.1.JPG)
  Fig2.2 is the graph about the index of lexical diversity of each genres of songs in each year.To compare each artists in different genres, we can find lots of interesting things. For Country, Folk, R&B and Jazz, the lexical diversity of them are relative low. I think this is because the style of these music is mature. I can't find the big difference from listening Country music between 1980s and 2010s. However, for Hip-Hop, Pop, and Rock, these kind of music refresh every year. It's just like the fashion, artists should update their lyrics day by day to keep their songs in New Wave. It's really make sense why lexical diversity of these kind of music is high. 
  ![image](https://github.com/TZstatsADS/fall2019-proj1--sd3227/blob/master/figs/fig2.2.JPG)
  
  Rightnow I want to know more about the artists in another way. After talking about the lexical diversity, I want to talk about lexical density. Lexical density is defined as the number of unique words/the number of total words. In this way we can know the repetition of the word. If lexical density decrease, the repetition rate increase.  

   Fig2.3 is the graph about the index of lexical density of each songs in each year. We can see that the trend of lexical density goes down, which means the repetition goes up. It's hard to say good or bad for music quality, but in my own idea, I think it means the change of the writing style of lyrics from artists. For example, In 1970s, maybe the whole lyrics narrate a story once in the songs; In 2010s, maybe the whole lyrics narrate a story but repeat it twice even three times in the songs. For another example, maybe with the development of music, people focus on melody instead of the lyrics. Hence artists focus more on melody instead of lyrics.
  ![image](https://github.com/TZstatsADS/fall2019-proj1--sd3227/blob/master/figs/fig2.3.JPG)
  
   Fig2.4 is the graph about the index of lexical density of each genres of songs in each year. We can get some interesting results from the graph with real life. For Hip-Hop and Metal, we can see a big going-down trend here, which means the repetition rate of these two goes up. Does it mean the quality of music go down? However,from the above analyzing, we can get the Hip-Hop and Metal become more and more popular.Why this happening? Why lyrics become more repetitive and become more popular? The answer is easy: people love it!!! Lots of Hip-Hop and Metal artists perform their songs at live house. To warm up, audience always sing the song with artisits together. If the lyrics are too complex, people who never listen the music don't know how to sing. Hence, to solve this problem, artists use some simple and repeative word in their lyrics that help people to sing the songs with them together.For example, the hip-hop music "My name is " from Eminem have 48-times repetitive lyrics "my name is..." in the song!!!
  ![image](https://github.com/TZstatsADS/fall2019-proj1--sd3227/blob/master/figs/fig2.4.JPG)
  
   After some analyzing, I think I get the answer of all my questions. However, I think it's just a beginning of the analyzing, there are lots of things that we can find by using data science. It's really interesting to get the secret behind the lyrics from natural language processing data mining. Thank you!!!




   
   
   

    
