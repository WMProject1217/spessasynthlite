This library is based on SpessaSynth_Core and SpessaSynth_Lib version 4.3.0, exporting easier interface for wmcomlib.js2 users.

If you have problem when using this library, please send issue to me first, I will find out if this is a bug in this program or in the original project. The SpessaSynth_Core and SpessaSynth_Lib part have been modified so that some bugs may appear.



# How to use
```js
// if you are not using WMWebAppBootLoader then use 
window._genesis_ = {};
_genesis_.lib = {};
_genesis_.lib.SpessaSynth = await import("/lib/wmcomlib.js2/SpessaSynth.js");
await _genesis_.lib.SpessaSynth._init_(_genesis_);
// to load the library

// if loaded, use such as
await _genesis_.lib.SpessaSynth.LoadSoundFont("/lib/wmcomlib.js2/SpessaSynth_MIDISoundFont.sf3");
await _genesis_.lib.SpessaSynth.LoadMIDIUrl("/lib/spessasynth_4.3.0/TH17_13.偶像に世界を委ねて ～ Idoratrize World - (KR.Palto47 - SC88pro_GS).wmmtx");
await sleep(128);
_genesis_.lib.SpessaSynth.RunTime_Sequencer.play();
```



# o

The SpessaSynth_Core and SpessaSynth_Lib project is by Spessasus and share under Apache-2.0 License.


https://github.com/spessasus/spessasynth_lib

https://github.com/spessasus/spessasynth_core



This project is in no way endorsed or otherwise affiliated with the MIDI Manufacturers Association,

Roland Corporation, Yamaha Corporation, Creative Technology Ltd. or E-mu Systems, Inc.,

or any other organization mentioned.

SoundFont® is a registered trademark of Creative Technology Ltd.

All other trademarks are the property of their respective owners.