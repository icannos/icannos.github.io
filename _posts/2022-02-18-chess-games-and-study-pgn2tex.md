---
layout: post
title: 'Chess games and studies: pgn2tex'
categories:
- scripts
tags:
- miscellaneous
- chess
date: 2022-02-18 15:10 +0100
---
## Back story

I began to play chess again because of the lockdowns during covid19 and as many others, I've been even more pushed toward the game because of The queen's gambit. I play on the best chess website ever [Lichess](https://lichess.org) which is a libre, free and open-source platform. It's actually an NGO promoting chess!

They released a dataset of chess [puzzles](https://database.lichess.org) and host hundreds of [chess studies](https://lichess.org/study). At the same time, I discovered how expensive chess books were and sometimes hard to find. Even though lichess (and others) offers a large variety of ressources to learn and train, they were still online ressources. What if I want to work on paper, with some kind of books ? What's great with lichess is that everything is under Creative Commons CC0 license, meaning that we can basically do whatever we want with their data. Therefore I decided  to write a [small python script](https://github.com/icannos/pgn2tex) to convert PGN files to latex source to achieve some kind of notion of chess books and another one to generate puzzles books from the lichess puzzles database.

I'm not sure what to do with this so I might as well share it. If some people are interested I suppose it could be possible to build some kind of Open Chess books Collection (The OCBC) based on lichess studies. And maybe one day they could be sold alongside the merch on the lichess website.

## Some examples

 - a [book on the Stafford Gambit](https://github.com/icannos/pgn2tex/blob/master/examples/stafford.pdf) based on this [study](https://lichess.org/study/c9YhCd5b) 
 - a [book of puzzles](https://github.com/icannos/pgn2tex/blob/master/examples/puzzles.pdf) based on the lichess puzzles database.




