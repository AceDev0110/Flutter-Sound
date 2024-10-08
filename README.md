# Sounds

Sounds is a Flutter package allowing you to play and record audio for both the android and ios platforms.

Sounds provides both a high level API and widgets for:
* play audio 
* record audio

Sounds can be used to play a beep from an asset all the way up to implementing a complete media player.

The API is designed so you can use the supplied widgets or roll your own.
The Sounds package supports playback from:
* Assets
* Files
* URL

# Overview
The Sounds package is a Flutter package that provides audio recording and playback functionality for both the `android` and `ios` platforms.

Sounds provides both a high level api and widgets for recording and playback.

The api is designed so you can use the supplied widgets or roll your own.

The Sounds package supports playback from:
* Assets
* Files
* URL
* Native Streams (with sync).

# Features
The Sounds package includes the following features
* Play audio without any UI
* Play audio using the built in SoundPlayerUI Widget.
* Play audio using the OSs' Media Player
* Roll your own UI utilising the Sounds api.
* Record audio without any UI
* Record audio using the builtin SoundRecorderUI Widget.
* Roll your own Recording UI utilising the Sounds api.
* Support for releasing/resuming resources when the app pauses/resumes.


## Help

Audio is a fundemental building block needed by almost every flutter project.

I'm looking to make Sounds the go to project for Flutter Audio with support for each of the Flutter supported platforms.

Sounds is a large and complex project which requires me to maintain multiple hardware platforms and test environments.

I greatly appreciate any contributions to the project which can be as simiple as providing feedback on the api or documentation.

See the [Contributing](#Contributing) section below for details.

### Sponsorship
If you can't help out by directly contributing code maybe you could Sponsor me so I can spend more time improving Sounds.

Sounds is a large commitment and I'm maintaining several other dart related projects so any support would be greatly appreciated.

Key short term goals are:
* Hire a graphics designer to improve the look of the widgets
* Provide support for the web
* Provide support for a wider range of Codecs
* Provide support for streaming

If I can get enough sponsorship I intend hiring a grad to do a chunk of the dirty work so I can focus on some of the larger features such as Web Support.

You can find the purple heart Sponser button at the top of the page.

If you can't afford a coffee then show your support by 'liking' the Sounds project on the [pub.dev](https://pub.dev/packages/sounds) site.

The key classes are:

## Api classes

QuickPlay - instantly play an audio file (no ui). Perfect for the odd beep.

Track - Defines a track including the artist details and the audio media.

Album - play a collection of tracks via the OSs' audio UI.

SoundPlayer - provides an api for playing audio including pause/resume/seek.

SoundRecorder - api for recording audio.

## Widgets

SoundPlayerUI - displays an HTML 5 style audio controller widget.

SoundRecorderUI - displays a recording widget.

RecorderPlaybackController - pairs a SoundPlayerUI and SoundRecorderUI to provide a co-ordinated recording/playback UI.

Note: there are some limitations on the supported MediaFormat. See the [MediaFormat] section below.

![Demo](https://raw.githubusercontent.com/acedev0110/flutter-sound/master/example.png)

