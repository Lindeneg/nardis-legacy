## Nardis

---

I wanted to create a game in React to increase my proficiency in the framework. However, before I could commence the building process of such an application, I needed the core logic of a game. Unfortunately, I'm not smart enough to figure out one myself, so I borrowed some ideas.

Nardis is heavily inspired by Sid Meier's Railroads with the major difference being that it is turn-based instead of realtime. There's also the fact that it offers infinitely less depth, immersion and sophistication but it was hell of a lot of fun to create.

Opponents has been implemented to give some sort of resistance towards your total dominance. The game is easy, really. You start at a city that offers supplies and requires demands of certain resources. You connect that city to other cities that complements the supply and demands of each other and you keep doing so, earning gold and scaling levels.

Players also functions as stocks and each player starts with four shares (out of ten) of its own stock. You can invest into other players and if you end up earning enough gold, you can buyout your opponents and take over their assets, essentially kicking them out of the game. However, they can do the same to you.

The idea (not mine) is great but the execution (totally mine) sucks.

---

Try it [here](https://nardis.lindeneg.org) or build from source.

Clone source

`~/$ git clone https://github.com/lindeneg/nardis && cd nardis`

Initialize submodule

`~/nardis$ git submodule init && git submodule update`

Install packages

`~/nardis/ui$ yarn install`

Start server.

`~/nardis/ui$ yarn start`
