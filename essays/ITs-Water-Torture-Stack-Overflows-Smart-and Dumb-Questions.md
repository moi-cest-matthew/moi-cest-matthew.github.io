---
layout: essay
type: essay
title: "I.T.'s Water Torture: Stack Overflow's Smart and Dumb Questions"
date: 2023-09-07
published: true
labels:
  - Stack Overflow
  - Getting help
---
*The following text is licensed under a CC-BY-SA 4.0 Global License. You may share it freely, even for economical purposes, so long as you provide me credit and a link to the license. If you translate it, please send me an e-mail so I can link it.*

People are like printers: we all get stuck sometimes, whether it is while learning something new, doing chores, or working at a familiar job. When coders find themselves in this position, they might choose to ask questions on forums such as Stack Overflow if they cannot find it via web search. However, you must make a "smart question" by following certain rules that are at best explained in minimal detail on Stack Overflow proper, which somehow causes its élite to act completely scandalised when new users inevitably dare to be unfamiliar with something they had just heard about. Luckily, one Eric Raymond Steven [has done the dirty work for us all.](https://www.markdownguide.org/basic-syntax#links) Now, we are able to compare Stack Overflow's idea of a "smart" question and a "dumb" question.

---

First, we examine [this question](https://stackoverflow.com/questions/50359481/initialization-of-a-constant-reference-with-a-number). While it has a positive score today, [this YouTube video from 2021](https://youtu.be/IbDAmvUwo5c?si=NEe06aFQvB5T3Iiz&t=278) shows it with a negative one.

> What is the meaning of the following line? Why is this allowed as 0 is an r-value and not a variable name? What is the significance of `const` in this statement?
>
>>`const int &x = 0;`

This is *not* a dumb question. It is about code and is placed on the corresponding forum, Stack Overflow (as opposed to something such as the Japanese language Stack Exchange). Its language is simple and direct, and does not commit the war crime of asking "Can you help me?" on a forum about asking for help. It does not vaguely complain about something not working; it does not even ask for debugging in the first place. How was this concise question responded to, both before and after the video it was showcased in was published?

In the video, the question had a score of -10, as well as some rather presumptive responses that have since been hidden or deleted:

> Homework? And what does your C++ textbook have to say on the subject?

> Read a good book.

There is no way for those commenters to prove that the asker was trying to get homework help, or that this syntax would be taught in a C++ course. The YouTube video's narrator did not recognise it despite his experience with the language, so it is reasonable to believe the concept was too niche to have already been answered on Stack Overflow. Additionally, since the C++ standard changes every few years, a "duplicate" from 2011 may or may not have been redundant in 2018.

The asker then went on to post the answer to their own question, which was downvoted in the video. Since then, it has a positive score now, but the mention of the asker needing to find the answer on their own has been removed, potentially so that the moderators could save face. The question has also been closed, thanks to having "duplicates", some of which appearing to have no connection to the original question. The asker technically did get "efficient and effective help", but this probably came from the question being shown on YouTube.

In short, the question may have been smart, but that did not in any way guarantee the asker would be treated decently by the community. While Mr. Steven's guidelines do help people make questions that are both easy for others to answer and make the asker's life easier, too many Stack Overflow users are too full of themselves to understand that barking "read the friendly manual" does not explain *how* to improve one's questions. 

---
With that said, the silver lining to Stack Overflow's jihad is that questions that genuinely flout or violate Mr. Steven's guidelines are difficult to find. However, "difficult" does not mean "impossible." [This question, which does not appear in the video](https://stackoverflow.com/questions/9404588/ubuntu-gui-application), is as follows:

> I am trying to create an application that would run on ubuntu desktops,I want a scenario where when the OS boots up ,it starts my application and its required services but the main ubuntu desktop does not show so it would seem only my application is running on the device,I need help on how this can be achieved links,articles,commands etc,anything that can point me in the right direction.

Immediately, one notices the language needs work. Commas and periods are used interchangeably, the list of things the asker wants could be separated into a list, and Ubuntu is not capitalised. The result is a messy run-on sentence. Moreover, the asker gives no information about what type of application their program is, nor what services it requires. This is made all the more vague by the last sentence, where "links, articles, [and] commands" could each refer to different concepts (for example, a link to some reading or a link to a file?).

This post has a single downvote, with a comment and an answer by two different people, which start with the following, respectively:

> If I understand your question correctly you want a "kiosk" mode.

> It is really hard to understand what you are saying but...
> 
> You must distinguish major difference between runlevel startup and user session startup. You did not provide any information what kind of application you have.

Neither of these responses are able to do much for the asker, and since the asker never responded to the answer, nor did they ever edit their question to be more specific, they never got what they were looking for out of Stack Overflow.

The irony in this is that in this case, the commenters attempted to help answer the "dumb" question, but simply could not do anything because they had almost nothing to work with. It frankly is amazing enough that they could come up with a starting point for the asker, yet annoying that the asker did not repay that by responding. Thus, it is seen that while a "smart" question *may* result in you not solving your problem, a "dumb" question *will*.

***
Without a doubt, there is nuance to the idea of "smart" and "dumb" questions. While we did see how a dumb question is difficult to help whereas a smart one can get an answer easily, that does not mean a smart one will. The "smart" question shows that while people can answer the question, they can also choose to instead be indirect, and then act shocked when they are called toxic or are asked about their social cues. Ultimately, the best test of a question's smartness is how good of a response one gets from anywhere other than Stack Overflow, even including ChatGPT. 