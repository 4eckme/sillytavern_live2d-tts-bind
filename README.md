<h3>This code synchronizes TTS behavior with live2d character mouth animations for the SillyTavern</h3>
<hr/>

If you use the latest stable version of SillyTavern and live2d extension as of today (06/20/2024), then you can simply replace these files:
```
<SillyTavern>/public/scripts/extensions/tts/index.js
<SillyTavern>/data/<default user>/extensions/Extension-Live2d/live2d.js
```
<b>If you use other versions or replacing files leads to incorrect work of the application: then I marked my changes in the code as "@4eckme" - just add them to the above files (there is a little bit).</b>
<br>
<br>
<i>In some live2d models, mouth animations are not fully developed. Before using this code, make sure the mouth animations are working correctly.</i>
<i>I recommend using this live2d model for tests: https://github.com/test157t/Live2dModels-ST-/tree/main/Community/NecoArc</i>

<i>Suitable for XTTSv2 and ElevenLabs (may be others).</i>
