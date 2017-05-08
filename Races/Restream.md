# Restream

The suggested way to do a restream is to obtain 4 things.

  1. A Layout to display the 2 streamers and some kind of timer.
  2. A timer that will work for your specific use case. This could be as simple
     as a general timer that counts the duration, or as complex as an
     application that accounts for different split points.
  3. Software to capture runners video to put into your stream.
  4. The OBS (or whatever software you are using) setup to actually stream.

## Layout

A general layout can be found [here][General Layout]. This is a generalized form
of a layout for DW1, so modifications might be necessary, but it will probably
be enough to get you started.

## Timer

[Dualsplit][Dualsplit] is a useful program for DW1 races, and is what the
general layout is built around. It's a good example for an application to house
splits and split timers for managing 2 runners.

## Software

The suggested way of doing multiple streams is to download [VLC][VLC], and
[Streamlink][Streamlink] so that you can have videos for 2 runners going at the
same time. You should set the video that pops up from streamlink to the "Minimal
Interface" so that it gets only the video in the player. You might want to
adjust sizes and settings (possibly the layout as well) to get what you need.
You will likely want to mute the stream that isn't playing just game audio, but
that also depends on the agreement with the runners of how the audio will work.

## OBS

[Here][Default Race OBS Scene] is an example OBS scene that you should be able
to import directly to OBS in order to run a race. It assumes the above is
already complete, and will likely have the layout in need of adjusting to get
the right file, but it should get you started. Add your mic setup, and you
should be able to stream a race.

[General Layout]: ./Layouts/Default_Race_Layout.png
[VLC]: http://www.videolan.org/vlc/index.html
[Streamlink]: https://github.com/streamlink/streamlink
[Default Race OBS Scene]: ./OBS/Race.json