# Remote Studio (Remote Band)

Links and know-how on how to do online music collaboration in 2024.



# Communication

https://p2p.mirotalk.com


# Audio Monitoring

https://sonobus.net

# Screen Sharing

- https://parsec.app
- https://pin.gl

# Remote Recording

- [ReaConnect](https://github.com/AtmanActive/ReaConnect)

# Play State Syncing
Play state syncing is important in order to have all participants muted when the DAW is playing and unmuted back again when the DAW playback is stopped. This also enables participants to use speakers, as opposed to being forced to use headphones only. Also, this is very important when doing recording, as you would want to hear the vocal sound or instrument sound from the DAW, not from the communications microphone.

## MIDI over internet
A Web-browser-based solution which enables all participants to distribute MIDI messages to each other
- [AtmanActive's WebMIDI WebRTC](atmanactive.github.io/webmidi-rtc-transport/)

## MIDI cable and/or routing
A MIDI cable app is necessary in order to link up several programs into one MIDI chain
- Windows: [loopMIDI](https://www.tobias-erichsen.de/software/loopmidi.html)
- Windows: [Bome Network](https://www.bome.com/products/bomenet)
- Windows: [LoopBe1](https://nerds.de/en/loopbe1.html)
- Windows: [Springbeats Virtual MIDI](https://springbeats.com/sbvmidi/)

## Mute microphone on MIDI
A local program that would react to incoming MIDI messages and mute the designated microphone.

### For Windows
On windows, all [DAWs](https://en.wikipedia.org/wiki/Digital_audio_workstation) use [ASIO](https://en.wikipedia.org/wiki/Audio_Stream_Input/Output), which is fully independent of windows audio, hence if we mute the microphone, it will only be muted for communications while it will still be able to be recorded in the DAW.
- [AtmanActive's MIDI-Transport-to-Mute](https://github.com/AtmanActive/MIDI-Transport-to-Mute)

### For MacOS
On mac... still researching...
- [midiStroke](https://charlie-roberts.com/midiStroke/)
- [CoyoteMIDI](https://coyotemidi.com/)
- [Bome MIDI Translator Pro](https://www.bome.com/products/miditranslator)
- [Mic Drop](https://getmicdrop.com/)
