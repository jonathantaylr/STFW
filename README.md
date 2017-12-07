# Scripting For The Web

Roles: Designer / Developer / Researcher

Description: The project I decided to work on was a drum beat machine using Nexus UI and Javascript. I utilized a sequencer interface as well as two sliders. The sequencer has 4 different drum noises, which I found posted in a sound library on another Github account. The first slider interface allows the user to change the tempo. The second slider interface allows the user to adjust the length of the sequence, set at a minimum width of 2, and a maximum width of 10. In order to produce the sounds, I used the Web Audio API. I also wanted to include a way for the user to record the sounds they produced, so I utilized the MediaStream Recording API, which I added to the end of my script so users are able to record any length of music and save it as a sound file that they can listen to. The problem I ran into was that drum beat machine originally only recorded using the microphone from the computer, but I was able to use an ASIO Driver for WDM Audio. With this, I was able to change the playback device from my computers microphone to the new driver so only sounds from the computer are recorded.

Dependencies: Nexus UI, Web Audio API, MediaStream Recording API, ASIO Driver for WDM Audio, and Github (for the sound library)
