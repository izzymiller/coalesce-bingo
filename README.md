# Coalesce Bingo

What is this? A sideshow game for [dbt Coalesce](https://coalesce.getdbt.com/), "The Analytics Engineering Conference" happening from Oct 17-21, 2022.

# How to Play
Visit [coalesce.bingo](https://coalesce.bingo) and generate a bingo card using that most unique of identifiers— your Data Twitter username. Not on the bird app? Well, don't tell anyone but it accepts any string really, so have at it. Everyone's card is different, and tied to their username.

During Coalesce, you can report certain bingo events as having happened by clicking "this happened". This will color it in on everyone's bingo board! Of course, you win bingo when you get 4 in a row. Because everyone's cards are different, some might win fast, and others might malinger throughout the entire week— This is part of the fun! **This is a social game! Tweet your bingo boards, share them in dbt slack, exclaim with glee when you strike a bingo, spy on others and bemoan their success, etc.**

Also, you can get multiple bingos, so the game isn't over once you hit your first. Think you can get the coveted full-board?


## (During Coalesce) Marking events as having happened
There's an [events.json](https://github.com/izzymiller/coalesce-bingo/blob/main/events.json) file in this repo. Adding a "receipt" (proof it happened) to an event will automatically mark it has having happened, and color it in on everyone's bingo board.

To edit, fork this repo, make your edits, and then merge them back into upstream. [Here's a nice tutorial!](https://jarv.is/notes/how-to-pull-request-fork-github/)

You can submit:
* URL receipts: ex: a link to a screenshot of dbt slack. 
* Text receipts: ex: "Taylor murphy said such and such in his talk, I was there and I heard it". Try and keep these brief— They appear in a tool tip and I am very bad at CSS.

Honor system works great.

## (Before Coalesce) Contributing events

I don't want to monopolize the bingo board, so I just added a couple of ideas and left the rest empty for folks to fill in. Have something funny in mind that you think might (or might not!) happen? Open a PR in [events.json](https://github.com/izzymiller/coalesce-bingo/blob/main/events.json) and fill in the `name` of a blank event! **Don't add new events, since this will mess up the bingo board— Just edit the names of existing, blank ones.**

To edit, fork this repo, make your edits, and then merge them back into upstream. [Here's a nice tutorial!](https://jarv.is/notes/how-to-pull-request-fork-github/)

PRs need approval, so tag in some people to discuss, or wait for others to discover your PR and give you the green light before merging.

## Rules

* Obviously, number one: Be nice, be kind, be respectful. We are making funny jokes here, but that's not an excuse to make mean jokes about people— and remember that people's idea of "mean" can be pretty subjective. Probably best not to make jokes about individual people at all, and stick to the technologies, frameworks, and philosophies that we all love. (nota bene: @tayloramurphy and @sethrosen are exempt from this rule, in that they can be made fun of ruthlessly.)

* PR reviews are required. You can't just go changing things willy nilly, since this is a public game. Tag someone— i don't care who— to make sure your thing actually happened, that your event idea isn't mean, etc.

* Feel free to debate overwriting existing events if you have a really great idea, but please ask the person who originally added it (git blame is handy for this!). After Coalesce begins on December 6, please do not change events.

* Board fairness: I'm not great at math. I forked this repo from https://github.com/queer/outage.bingo, who uses a seed number to generate some random seeds. You can see this [here](https://github.com/izzymiller/coalesce-bingo/blob/main/index.js#L43). Since people could game the system entering events if we know exactly what the boards will look like ahead of time, **I am going to alter the seed to something completely random (I promise not to cheat) on the evening of Dec 5, when we declare event names locked.** This will jumble everyone's boards and serve as the final shuffle before the game begins.
