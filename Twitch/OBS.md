# OBS

This document will talk about some of the things to do around managing your
stream with OBS. Some are OBS specific, and others are just general thoughts on
managing content your are streaming.

## Dealing with Lag

### Moving Parts

One of the first things I did as a streamer was utilize all of the space on the
screen. Obviously this seems intuitive, I mean after all why waste space? Well
do remember that you are sending bits of data across the interwebs. Not only
that, but you are also using your PC's CPU and Memory to manage this data. Add
to that the bandwidth needed to continuously send new data, and you are starting
to take on a lot of resource management. If you have the means, then feel free
of course, but something I noticed was that I would sometimes have some lag in
my stream if I was playing something that was a little more detailed
graphically. A way I counteracted that was to minimize my moving parts. I setup
a background, then trimmed my game screen to fit a section. I did this with my
camera and livesplit as well, and utilized a background image to lessen the
feeling of dead space. Overall I barely reduced my quality via size (if it
really impacted anyone at all), and improved my quality via content. Less frame
drops and a background that gives a feel for the game instead of just the game
itself brings the viewer more into the setting.

### Bandwidth

Depending on the game and setup you have, you might be running at too high of a
bitrate and resolution for Twitch to handle. This has to do with their servers
as well, so you might want to play around with some numbers (general default
being 2000 kbps 720p to start), until you get the quality you want. You can also
test out the server you are using from twitch to make sure it is the best one
for you by looking at something like [this][Bandwidth Tester].

If in doubt, you can always get results directly from Twitch itself by using the
[Stream Inspector][Stream Inspector].

## Stream Key

In order to stream to twitch you should go to Settings->Stream and input the
server closest to you (note that this might not always be the fastest, so play
around with it as necessary) and go to
`https://www.twitch.tv/{user}/dashboard/streamkey` to get your key to input.

[Bandwidth Tester]: http://www.teamliquid.net/forum/tech-support/478845-twitchtest-twitch-bandwidth-tester
[Stream Inspector]: https://inspector.twitch.tv/#//