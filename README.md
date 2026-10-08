# DVD bounce animation

I tried to implement the legendary and most loved DVD bounce animation. I thought it would be fun and easy to implement within 3kb (took 1273 bytes only). 


## how to use it

Well it's not really interactive, BUT you can sit with your friends and bet on what corner its going to hit next lol.

its just a silly thing, have fun.

## how it works

It just gives a velocity (in x and y) to the text element and checks for collision with the container walls. 

If a collision is detected, then the velocity is changed to the opposite direction and the color also changes to a random rgb value.

Also added a slight glow to the text and a radial gradient to the background.

# Bug

I am aware of a glitchy kind of bug, I however liked the effect that it produces so I have decided to leave it in. 

Its actually a feature!

## building
```
npm install
node build.mjs
```