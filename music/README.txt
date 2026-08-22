Maui game — custom background music
====================================

Drop MP3 files here with these EXACT names. Each maps to one game state.
Any file that is missing just falls back to the built-in chiptune for that state,
so you can add them one at a time.

  wedding-march.mp3 → intro crawl / title screen   (loops)  [added]
  level1.mp3    → gameplay — plays across ALL levels (loops)  [added]
  boss.mp3      → Level 3 tiki-idol boss fight     (loops)  [added]
  win.mp3       → "Just Married!" victory          (plays ONCE, no loop)  [added]
  gameover.mp3  → "Too Late!" time-out             (plays once)

Notes
-----
- MP3 is what the game loads. OGG/WAV also work if you rename the file to .mp3?
  No — keep the .mp3 extension OR tell me and I'll switch the manager to your format.
- Tracks cross-fade over ~0.6s when the state changes.
- The M key mutes/unmutes music (and all SFX) in-game.
- Looping MP3s can have a tiny gap at the loop point (HTML audio limitation).
  If a seamless loop matters for a track, let me know and I'll switch that track
  to a Web Audio buffer loop.
