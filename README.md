This repository contains all the noise and artifacts surrounding the development of a new implementation of Meterpreter that is intended to run on the CLR. The entire project is being live streamed on [my Twitch channel](https://twitch.tv/ojreeves), and archived on both [Vimeo](https://vimeo.com/album/5934749) and [YouTube](https://www.youtube.com/playlist?list=PLYovnhafVaw-wGlLtQw1N0dHjxkkvc62o).

For the rationale behind this project, please see my [blog post](https://buffered.io/posts/new-livestream-series/), and check out Part 1 below.

This is going to take a long time, and at the moment there's not much to see!

## Keen to be involved?

* Submit questions and comments in the suggestions box on my [Twitch](https://twitch.tv/ojreeves) page (and subscribe, if and when I finally make it to affiliate).
* Feel free to submit an issue in this repo if you feel the need, but I'd prefer the suggestion box.
* Hit me up on [Twitter](https://twitter.com/TheColonial).
* Join in on the [Discord channel](https://discord.gg/358tQxf).
* Support me on [Patreon](https://patreon.com/ojreeves).

## Pull Requests

I don't want to sound awful, but please don't submit any. At least not for a very long time. The point of the exercise is to build _everything_ live on stream, and the last thing I want to have happen is to have huge PRs submitted here only for me to reject them.

If you want to get involved with the coding, get in on the streams and participate that way. Thank you!

## Past Streams

### Part 1 - 23 April 2019 @ 20:00 AEST

The kick off stream! Classic introduction stuff, and covering off high level discussion of things we need to do, with some deeper diving along the way.

[Notes](../master/streams/2019-04-23-Part-1/notes.md) - [Questions](../master/streams/2019-04-23-Part-1/questions.md) - [Vimeo](https://vimeo.com/331977092) - [YouTube](https://youtu.be/fUG2Zo-LfKQ)

### Part 2 - 25 April 2019 @ 20:00 AEST

Answered viewer questions, gave an overview of MSF and Meterpreter, and covered off what TLV packets look like. Shorter stream because of ANZAC day.

[Notes](../master/streams/2019-04-25-Part-2/notes.md) - [TLV Structure](../master/streams/2019-04-25-Part-2/tlv.md) - [Vimeo](https://vimeo.com/332426022) - [YouTube](https://youtu.be/-nUfhW5d_Nc)

### Part 3 - 27 April 2019 @ 20:00 AEST

Spoke about dev issues such as permature optimsation, future proofing and more. Covered off some legality points, and spoke in depth about what we're going to do support multiple versions of the CLR.

[Notes](../master/streams/2019-04-27-Part-3/notes.md) - [Agenda](../master/streams/2019-04-27-Part-3/agenda.md) - [Version](../master/streams/2019-04-27-Part-3/version.md) - [Vimeo](https://vimeo.com/332827701) - [YouTube](https://youtu.be/fgMdviZkew8)

### Part 4 - 29 April 2019 @ 20:00 AEST

Quickly recap'd stuff. Got started on project structure and wrote some awful, awful code. Good to get started though! Once we've figured out the vibe, we'll start moving faster.

[Agenda](../master/streams/2019-04-29-Part-4/agenda.md) - [Vimeo](https://vimeo.com/333091819) - [YouTube](https://youtu.be/xlmqqVq2Pek)

### Part 5 - 1 may 2019 @ 20:00 AEST

Code! All the code. Got the TLV packet parsing first pass done. We can read TLV data from byte arrays and interact with the values.

[Agenda](../master/streams/2019-05-01-Part-5/agenda.md) - [Vimeo](https://vimeo.com/333532147) - [YouTube](https://youtu.be/H31LdXAsC2M)

### Part 6 - 3 may 2019 @ 20:00 AEST

More code this time! We did the deserialisation part of the TLV handling. So we should have "serder" done well enough to move up a level and start preparing the server in the next stream.

[Agenda](../master/streams/2019-05-03-Part-6/agenda.md) - [Vimeo](https://vimeo.com/333959033) - [YouTube](https://youtu.be/B7byAySiK3s)

### Part 7 - 6 may 2019 @ 20:00 AEST

Rejigged some source structure, got started on parsing configuration coming from MSF during staging.

[Agenda](../master/streams/2019-05-06-Part-7/agenda.md) - [Vimeo](https://vimeo.com/334419549) - [YouTube](https://youtu.be/TowwCK1k8Dw)

### Part 8 - 8 may 2019 @ 20:00 AEST

Finished configuration parsing, explored the staging process and got started on plugin management.

[Agenda](../master/streams/2019-05-08-Part-8/agenda.md) - [Notes](../master/streams/2019-05-08-Part-8/notes.md) - [Vimeo](https://vimeo.com/334881806) - [YouTube](https://youtu.be/OPbWiG9ETI8)

### Part 9 - 10 may 2019 @ 20:00 AEST

Add full HTTP transport parsing, started work on the server transport handling and packet dispatching.

[Agenda](../master/streams/2019-05-10-Part-9/agenda.md) - [Vimeo](https://vimeo.com/335392126) - [YouTube](https://youtu.be/iUrlJOhbQl4)
