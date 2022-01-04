# DiscordRhymeBot

![unknown](https://user-images.githubusercontent.com/92825395/148105223-f63d1632-61a1-4822-ace2-fc281122dbb0.png)


A command will announce a word that users should try to rhyme with. The bot will listen and tell you if you are correct or not (your word rhymes with the word announced or not). It will continue to listen until all words have been said that rhyme with announced word (checks for 10 words).

 How it works: "^rhyme" command will generate a random word. This word will then be used to access a rhyming API, a database of words that rhyme with said word. With a random word and the rhyming API together, they can accomplish the task with lots of JSON reading, array filling & traversing in order to compare words listened to. 
