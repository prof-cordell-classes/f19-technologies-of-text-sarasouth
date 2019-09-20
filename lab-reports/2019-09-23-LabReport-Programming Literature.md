# Lab Report: Programming Literature

#### Sara South

## Process Description

This lab demonstrates how to program literature and create a Twitter Bot using a stanza of poetry. Firstly, we examined various Twitter Bot account examples, such as @pentamentron and @stealthmountain. This helped us consider how bots are able to generate tweets and what they look for, in terms of recognizing words or patterns of speech. After this, we selected a poem. I selected Hafiz's short poem titled <i> The Happy Virus. </i> The poem is:

<em> I caught the happy virus last night

When I was out singing beneath the stars.

It is remarkably contagious -- so kiss me. </em>

We utilized GalaxyKate's Tracery website tool, where we used JSON data to generate text. I created a JSON file, which consisted of attribute-value pairs. In JSON data, a category is needed, such as, "noun" or "verb," which stands as a symbol. Then, there are a multitude of names that are attached to that symbol. It's a mad-libs style substitution, ie: "noun": ["cow", "anvil", "flower"]. The words themselves are arbitrary, but rather these are some possible values for the category. At the beginning and the end of the JSON file, brackets are needed: {}. After multiple categories with possible values have been created, it's necessary to add an "origin" category to structure the sentences that will be computed by the bots, ie: "origin":["#past-verb# the #noun#, #interjection#"]. This is followed by the last bracket (}) of the JSON file. After separating the patterns of speech of the poem into various categories: this was the final JSON file: 
{
"noun":["virus", "night", "stars"],
"adjective":["happy", "remarkably", "contagious", "last"],
"adverb":["when", "out", "so"],
"verb":["sing", "is", "kiss", "catch"],
"punctuation":["."],
"me":["me", "I", "it"],
"preposition":["beneath"],
"origin":["#adverb# #me# #verb# the #adjective# #noun# #punctuation#"]
}
Once the JSON file was completed and fully functioning on Tracery (shown in Image 1), the JSON file could then be copied and pasted to Kate Compton's Twitter Bot Generator tool called <i> Cheap Bots, Done Quick! </i>  Once signing into Twitter and authorizing the Bot to access the account, the JSON file can then be uploaded, and the frequency of the Twitter bot's posts can be altered. I selected twice a day. After this, the Bot then began to post, as seen in Image 2. The first tweet the Bot posted was: 

<em> out I sing the contagious night. </em>

The second tweet the Bot posted was:

<em> out I is the last virus. </em>

![Image 1](/images/image1.jpg)

![Image 2](/images/image2.jpg)

## Observations

While working on this lab, I realized that it's extremely important to consider the data of the Bot itself when we are trying to comprehend what the Bot was intended to do. This is particularly evident when exiamining other Twitter Bots, and the type of content they produced. For instance, @stealthmountain's Twitter page recognizes and responds to every tweet that states "sneek peek" instead of "sneak peak," and proceeds to correct their grammatical error by replying to their tweet. It's evident that the Bot is programmed to compute text in a specific way, and therefore serves a unique purpose. 

Furthermore, it was particularly insightful to analyze and alter the way in which we not only arrange patterns of speech, but also to analyze the level of intelligence of these computer bots to automatically program their own tweets. The JSON data files were particularly sensitive to any unknown characters, or extra commas that could alter the computing language. When evaluating from this particular lens, it's clear that programming text and language must be extremely accurate in order to be properly computated and to therefore communicate the message that is trying to be conveyed. Although it's encouraged to have proper grammar when writing in English, a slight typo or comma would still get the general point across to the reader. However, when it comes to coding language, a missed comma or period would result in the message not being computed at all by the Bot. This could be quite frustrating if the error of the JSON file is unknow and is not functioning properly. However, this proves the meticulousness of typing a JSON file and using programming language, making it even more rewarding when the JSON file functions properly.


## Analysis

As Annette Vee argues in her article titled <i> Coding Literacy: How Computer Programming is Changing Writing </i> , "too many students are learning to type when they should be learning how to code." It's evident that the technology of code is everywhere. Before beginning this lab, I was an avid Twitter user. However, I did not understand the importance or even the relevance of Bots in our technological society. In the context of Twitter, they have the ability to post contact, interact with users, and even manipulate the truth. Therefore, it's important to consider that although the technology of code can be found all over the web, a large portion of our population are not able to read or write in code. As Annette Vee states, "literacy serves as a cipher for the kind of knowledge a society values." Therefore, the emphasis in code literacy in educational institutions demonstrates the innate need for our society to shift their focus to a more digitized literacy.


As mentioned in Amaranth Borsuk’s, The Book as Object, she states that, “Authors do not write books, they write texts that become written objects, manuscripts, inscriptions, print matter, or today, material in a computer file.” This indicates that the medium itself is more important than the words themselves. Different technologies of books have existed for generations, such as: scrolls, codices, manuscripts, and ebooks. Therefore, it's not so much the programming language that is significant, but rather, the idea of coding in itself as a new technology. In the context of this lab, it's therefore evident that the words the Twitter Bot writes is not necessarily important, but rather, the fact that a Twitter Bot is able to interact with other Twitter users and post content.


Lastly, as stated in Vee's Computer Programming article, "Programming is writing because it's symbols inscribed on a surface, but programming is also not writing, or rather, it is something more than writing, as the symbols that constitute computer code are designed not only to be read but also to be executed, or run, by the computer.” This statement indicates that this programming language is intended for computers to understand. Programming in and of itself is often taught in CS courses with abstract problem sets, such as the Fibonacci sequences. This makes it appear quite distant from writing and language. However, although coding language doesn't allow us to directly communicate with humans, it does allow us to communicate with a computer, which, in essence, can generate ideas. In this sense, the programming language used in this lab has allowed me to generate a new textual version of a popular poem through the use of coding language in the form of multiple tweets. Therefore, this gives a large amount of autonomy to these Bots as these tweets are randomly generated. Thus, this left me with the question, if we all learned how to program, could we shift the power of ideas? 

