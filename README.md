# taptv-clone

## Features

* phone app (initially a web app)
* TV app (again, a web app)
* count-down timer for phone app
* QR code for TV app
* pull a list of cities-- game is to guess the states. Only use cities that are uniquely named across states-- or in advanced-mode, be sure that the State answer options are such that there IS NOT a same named city in any option but the correct one
* user accounts, track usage, points/wins
* location accounts, users are always at a location.
* potential answers are only visible on the TV app (at that location).
* phone app has the question, a grid to chose an answer, but the answers are not shown (only A/B/C/D)
* John inbetween questions only
* have dashbosrfs per bar snd nationwide 
* give players intelligence in how they're ranking
* track trivia categories past abd upcoming
* https://opentdb.com/
* I"m adding the MapBox Trivia idea to this project, mostly to keep count of loose-threads low.

## MapBox Trivia Idea

* A question whose answer is a map location/state/city/POI/etc.
* An ever zooming in map that slowly eliminates the wrong answers. The 'center' of the zooming needs to be erratic/randomized to prevent making the correct answer obvious. Or, perhaps a concentric, tightening spiral that is also randomized. Nothing too dizzying.

## Other factors

* Implement a version with HTTP/REST and another using SignalR, Go Channels, and WebSockets. So independent implementations in .NET. Go-lang, Java (perhaps with and without SpringBoot), JavaScript.

