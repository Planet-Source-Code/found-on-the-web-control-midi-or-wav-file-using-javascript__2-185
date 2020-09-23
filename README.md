<div align="center">

## Control MIDI or WAV file using Javascript


</div>

### Description

How can you control midi or wav files using JavaScript?You should use the EMBED tag.

Found at http://www.irt.org
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Found on the Web](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/found-on-the-web.md)
**Level**          |Unknown
**User Rating**    |4.3 (13 globes from 3 users)
**Compatibility**  |
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__2-57.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/found-on-the-web-control-midi-or-wav-file-using-javascript__2-185/archive/master.zip)





### Source Code

```
The following will play the midi or wav file as soon as its loaded:
<HTML>
<BODY>
<EMBED SRC="sound.wav" HIDDEN=TRUE>
</BODY>
</HTML>
The following allows you control when it plays:
<HTML>
<BODY>
<SCRIPT LANGUAGE="JavaScript"><!--
function playSound() { document.firstSound.play(false); }
function pauseSound() { document.firstSound.pause(); }
function stopSound() { document.firstSound.stop(); }
//--></SCRIPT>
<A HREF="javascript:playSound()">Play the sound now!</A><BR>
<A HREF="javascript:pauseSound()">Pause/Restart the sound</A><BR>
<A HREF="javascript:stopSound()">Stop the sound</A><BR>
<EMBED SRC="sound.wav" HIDDEN=TRUE AUTOSTART=FALSE LOOP=FALSE NAME="firstSound" MASTERSOUND>
</BODY>
</HTML>
You can replace sound.wav with sound.mid.
```

