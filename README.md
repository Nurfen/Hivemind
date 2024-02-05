# Hivemind

Open source forum software to efficiently communicate the ideas and the will of large populations (countries, cities, large companies, …) to the leading parties.

## Problem statement (country level)
Our current democratic system feels outdated:
- Limited and slow feedback cycles of the population, as elections are only 1 time every 4 years.
- No easy communication channel from the population towards the leaders. Making it difficult to bring new ideas. Current communication channels are labour and time intensive such as protests, strikes or media attention.
- People have to vote on parties that rarely fully allign with their intrests. 
- Black and white thinking and a lack of nuance of the larger population due to low quality media coverage. 
- People stay in local communities, which lacks variety in perspectives and reduces the openness of their minds.

## Proposed solution
Create a reddit like forum where people can propose ideas in threads and discuss them with a lot of people from different backgrounds.

Main features:
(Core)
- Reddit like threads with comments and up/down votes.
- Restricted login, so only people of a country can use it (Itsme for Belgium). The login module should be easily adjustable so other organisations can host the forum with their own login method.
- A voting option to vote yes/no on the idea of every thread. 
- See the voting statistics per thread.

(Nice to have, but shoud be easy with modern LLMs)
- Auto summarising, to give a concise summary on the topic on top of the thread.
- Auto reasoning and bias detection, to label reasoning fallacies and improve the discussion.

Product:
One product with an easily adjustabele login plugin to make it easy to use for other organisations


## What it is not.
Hivemind is not a replacement for the leading class, as it is not efficient to have everybody vote on every decission. See it more as a guiding tool for the people that make the decissions to allign with the ideas and will of the population. 

## Topics to be discussed:
### Project related stuff to be discussed
- What will be the user base? and is it ok to use the forum as a guideline. e.g. what if only 10% of the population is actively using it.
- It is possible that this is a very bad idea, if so why? 
- How to avoid echo chambers
- How to avoid fake news

### Techical things to be discussed:
- Start from scratch or fork existing repos that could serve as a starting point: 
    - Forum magnum https://github.com/ForumMagnum/ForumMagnum
    - ...

- What architecture for backend/frontend.
- cloud or not?
- Federated or not? Nice for public service, but maybe more difficult security wise and with the restricted login?

### Funding:
- Hosting a forum cost money + it would be nice if contributers get payed somehow.


## How to contribute
Join the discussion on hivemindforum subreddit: https://www.reddit.com/r/hivemindforum

For more technical discussions I prefer the github dicussions: https://github.com/Nurfen/Hivemind/discussions

Thanks for your input!

