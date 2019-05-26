# LiveOSC (Live 9.6 / Live 10 compatible)

This is a fork of [LiveOSC](https://livecontrol.q3f.org/ableton-liveapi/liveosc/) that has been updated to work with Ableton Live 9.6 and 10.

## Installation

In a macOS terminal session:

```
cd /Applications/Ableton*.app/Contents/App-Resources/MIDI\ Remote\ Scripts
git clone https://github.com/ideoforms/LiveOSC.git
```

Then in Ableton Live:

 - open `File > Preferences`, 
 - select `Link / MIDI`
 - set Control Surface 1 to `LiveOSC`

The LiveOSC server will then start listening for commands.

## Usage

See [OSCAPI](OSCAPI.txt) for the raw API.

For a simple Pythonic interface to interact with Live, use [PyLive](https://github.com/ideoforms/pylive).

To receive logging messages, run the logging server with:
```
python2 ./LogServer.py
```
