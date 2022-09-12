# ymPlayer - YM file streamer

Plays "YM" formatted Music files on a YM2149 sound chip using an intermediate Arduino device to which data is streamed.

I (John Lonergan) found this handy and portable YM streamer program on github owned by 'panz0r' however I've failed to find any supporting info.
By trial and error I realised this was a compatible "streamer" program with the YM sound device circuit I'd already built by following the instructions 
mentioned in the next paragraph. This is lucky because I couldn't make FlorentFlament's streamer program run successfully on my environment.

Building the Arduino adapter to the YM2149 chip is the subject of https://github.com/FlorentFlament/ym2149-streamer

The project works equally well for the AY3-8910 and YM2149 chips.
