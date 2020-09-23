<div align="center">

## MIDI player


</div>

### Description

This code demonstrates playing a MIDI file on Windows.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Mike Vandelay](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/mike-vandelay.md)
**Level**          |Advanced
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |C\+\+ \(general\), Microsoft Visual C\+\+, Borland C\+\+
**Category**       |[Graphics/ Sound](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/graphics-sound__3-15.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/mike-vandelay-midi-player__3-9997/archive/master.zip)

### API Declarations

Windows.h


### Source Code

```
mciSendString("open \"test.mid\" type sequencer alias coolmidi", 0, 0, 0);
mciSendString("play coolmidi from 0", 0, 0, 0);
```

