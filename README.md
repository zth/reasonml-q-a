# ReasonML Q&A
This is a community maintained, non-official resource for people using ReasonML. Right now, it consists of this repository's issue tracker. Questions are pulled in manually from other platforms (Discord, Twitter, etc) or posted directly on the issue tracker. The community then proceeds to answer the questions and gather information about the topic. Finally, when the question is answered in a satisfactory way, the information is published on https://reasonml-q-a.netlify.com/.

## Goal
The goal of this resource is:
- To provide a natural place, indexable by search engines, where frequently asked questions about ReasonML can be posted and discussed in a transparent way
- Provide a large body of valuable information that's accessible for anyone to use however they want via the GitHub API

The philosophy is roughly the following:
- Quantity over quality. Guides, polished blog posts and so on are great resources, but this isn't the place for that. We want to gather _as many questions and answers_ as possible, to cover as much ground as we can.
- Amount of information is king, proper structure comes later. This again reflects on the fact that I believe we as a community simply need _more helpful, findable information_ as of now. Great structure comes later, for now the search bar is your friend.

## What this isn't
It's important to clarify what this resource _is not_:
- It's not an official ReasonML resource. It's made by the community and maintained by the community.
- It's not competing with, nor is it the next StackOverflow, Spectrum, reasonml.chat or Discord. Other platforms have their own sets of pros, cons and constraints, and this resource is _not trying to compete with them_.

## Contributing
There are tons of ways to contribute! Here's a few:

### Bringing in questions and answers from other platforms when you see them
Somebody posts a good question on Twitter, Discord or whatever platform, and great discussions ensue. Spend a little time extracting the question and discussion into an issue here, and viola, we've persisted that in a searchable way that can help other's not on that particular platform.

### Posting your own questions
Maybe you have your own questions you'd like answers to? Or maybe you remember things that you got stuck on starting out but that you've since then found the answers for? Post them, go for it! Quantity over quality, more information is the most important thing at this point.

### Answering questions and providing information
Finally, perhaps the most important thing - answering questions and providing information. I believe everyone has something to offer here. Maybe you remember some mental model that helped you crack one of the concepts or problems you had issues with before? Post it! There's always going to be someone, now or in the future, that can relate to your mental model and be helped by it.

### Building out the infrastructure
This is put last for a reason; what we need currently isn't fancy technical solutions, but rather just more information. _However_, if there are members of the community who are just itching to code something to help out with this, there's a few things we'd love to have eventually:

#### Bots
##### Twitter
A Twitter bot would eventually be a good addition to this resource. Here's a few ideas of what capabilites it could have:

- Subscribing to the issues posted on this tracker and tweet about them as they're added. This way, people who are interested in helping out can follow the bot, and retweet questions in hopes of increasing the reach of this resource.
- Providing a way of unrolling a discussion on Twitter into an issue here on GitHub. Think roughly person X Tweets: "What do I need to know about how type inference works in ReasonML?". You tag the bot in the conversation, "@reasonml_qa_bot unroll", and it proceeds to automatically create an issue here, saving the full conversation from Twitter.

##### Discord
Discord is perhaps the most active and helpful place there is in the ReasonML community. It would be amazing to have a bot that can perform the unroll feature described above in the section on a Twitter bot.
