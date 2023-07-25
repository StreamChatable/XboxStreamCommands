# XboxStreamCommands
If you read this, it means that you are playing a chat game on a stream of a Xbox controller game.


We use two ways to control the Xbox:
- hardware serial port communication on an console
- Joystick simulation on Window through Window Xbox Remote

We will use serial port for 1-2 players as it is faster.
But the remote access work better to simulate 4 controllers on Xbox.

Both of them use the same standard that I coded.
You can use it in the chat stream or for you own game on your compute with OMI.
(See an other tutorial that need to be write up. Ping me if you need)

`a. 10> a' 1000 b. 10> b' 200> ml. 42> ml' ;` Press in 10ms a, wait a second, press in 10 ms b, wait 200 milliseconds, press the left menu of the Xbox 
`jlh%1.0 100> jlh%0 100> jlh%-1 100> release;` Move the left joystick horizontaly to right, then to the middle, then to the left. Finish by release all button of the xbox.

Button usable :`a b x y     ml mr mc   sbl sbr  jl jr   al ar at ad   tl tr`
Axe usable: `tl%0.0 tr%0.0  jlh%0.0 jlv%0.0 jrh%0.0 jrv%0.0 `
Don't forget to finish you line by `;`


## Solo


## Local Multiplayer

I plan to make a version of the code that is design for 2-4 players.
But it is not yet. Implemented.
(Ping me on Discord if you want to see it come faster. Because it is a nice to have for the moment)
